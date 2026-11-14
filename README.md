# vendor_gms

GApps for AOSP

### How to use?

1. Clone this repo to `vendor/gms`

2. Inherit it from `lineage_RM6785.mk` in device tree:

```
# Inherit gms
$(call inherit-product-if-exists, vendor/gms/common/common-vendor.mk)
```
