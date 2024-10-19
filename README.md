# EvolutionX for the Xiaomi 12T
### Ever wanted to get out of the boundaries set by the laggy and buggy HyperOS but also have a Pixel phone for cheap? Wait no more, because EvolutionX has arrived for the Xiaomi 12T 'plato'
Thanks to [The Xiaomi Mediatek Devs](https://github.com/xiaomi-mediatek-devs) this is possible. For this project I used the following parts to compile this build:

Required files   | Source
-------:|:-------------------------
Hardware     | [android_hardware_xiaomi](https://github.com/xiaomi-mediatek-devs/android_hardware_xiaomi) <br /> [android_hardware_mediatek](https://github.com/xiaomi-mediatek-devs/android_hardware-mediatek)
Device Trees | [android_device_xiaomi_plato](https://github.com/Yufukuai/android_device_xiaomi_plato) (fork of plato's device tree) <br /> [android_device_xiaomi_mt6895-common](https://github.com/xiaomi-mediatek-devs/android_vendor_xiaomi_mt6895-common) <br /> [android_device_mediatek_sepolicy_vndr](https://github.com/xiaomi-mediatek-devs/android_device_mediatek_sepolicy_vndr)
Vendor Trees     | [android_vendor_xiaomi_mt6895-common](https://github.com/xiaomi-mediatek-devs/android_vendor_xiaomi_mt6895-common) <br /> Vendor tree for the device itself was extracted using extract-files.sh (from device trees)
Kernel Dependencies  | [android_kernel_xiaomi_mt6895](https://github.com/xiaomi-mediatek-devs/android_kernel_xiaomi_mt6895)

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Octa-core CPU with 4x Arm Cortex-A78 up to 2.85GHz
Chipset | Mediatek Dimensity 8100
GPU     | Mali-G610 MC6
Memory  | 8 GB RAM (LPDDR5 6400Mbps)
Shipped Android Version | 12
Storage | 128/256 GB (UFS 3.1)
Battery | Li-Po 5000 mAh, non-removable
Display | 1220 x 2712 pixels, 6.67 inches, 60/120hz

![Xiaomi 12T](https://i02.appmifile.com/898_operator_sg/26/08/2022/fc94660da1d6dd006f7589327bb72813.png)
