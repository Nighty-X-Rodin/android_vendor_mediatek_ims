### 1. Clone into your ROM source tree

Clone this repository into `vendor/mediatek/ims`:

```bash
git clone https://github.com/Nighty-X-Rodin/android_vendor_mediatek_ims.git -b lineage-24.0 vendor/mediatek/ims
```

### 2. Inherit in Device Product Makefile

In your device tree makefile (e.g., `device/xiaomi/rodin/device.mk` or `lineage_rodin.mk`):

```makefile
# MediaTek IMS
$(call inherit-product, vendor/mediatek/ims/ims.mk)
```


## 👤 Maintainer & Credits

- **Base Tree & References**: [Klozz](https://github.com/xiaomi-rodin-mtk6899)
- **Original Mediatek IMS Package**: [Aryan Sinha (techyminati)](https://github.com/techyminati)
