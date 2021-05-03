A proof-of-concept Bed Bath and Beyond functioning coupon generator.

---

Hosted at:

  https://simewu.github.io/coupon-gen-bedbathandbeyond

The fully-featured version is stored in the following application, containing a expiration date selector, coupon percentage off selector, and dollars-off selector.

  https://old.smilebasicsource.com/page?pid=1210

---

**How does it work?**

BBB coupons are in the following format: `AAA BBBBB CCCCCCC YYDDD`.

- **A** : Coupon code
  - 101 : Traditional 20% off a single item
  - 129 : 20% off entire purchase
  - 729 : 20% off entire purchase
  - 981 : Custom percentage off (see **C**)
- **B** : Coupon code identifier information
- **C** : Optional data value (may vary in length)
  - 010000000 : 1% off
  - 990000000 : 99% off
- **YY** : Two-digit year (18 : 2018)
- **DDD** : Day of the year (between 1 and 365)

Barcodes are generated in Code 128.