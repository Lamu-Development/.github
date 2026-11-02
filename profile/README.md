# Lamu Development

Welcome to the **Lamu Development** organization. This space is dedicated to developing, optimizing, and building custom Android ROMs for the **Motorola Moto G05 / Moto G15 / Moto G15 Power** family (codenames: `lamu` / `lamul`).

---

## 📱 Supported Devices

<p align="center">
  <img src="https://cdn.r0rt1z2.com/assets/lamu-family.png" alt="Motorola moto g05 / g15 / g15 power" title="moto g05, g15 and g15 power" width="800" />
</p>

| Model | Codename | SoC | Shipped Android | Models |
| :--- | :--- | :--- | :--- | :--- |
| **Moto G05** | `lamul` | MediaTek Helio G81 Extreme (MT6769) | Android 15 | XT2523-2, XT2523-3, XT2523-4, XT2523-5, XT2523-9, XT2523-11 |
| **Moto G15** | `lamu` | MediaTek Helio G81 Extreme (MT6769) | Android 15 | XT2521-2, XT2521-3, XT2521-4 |
| **Moto G15 Power** | `lamu` | MediaTek Helio G81 Extreme (MT6769) | Android 15 | XT2521-5 |

---

## 🎯 Our Objectives

- **Clean Organization**: Centralize all device trees, kernel modules, vendor blobs, manifests, and patches in a unified workspace without cluttering personal profiles.
- **Custom ROM Support**: Port, adapt, and build aftermarket Android distributions (LineageOS, AlphaDroid, and other AOSP-based projects) for `lamu` and `lamul`.
- **Patches & Improvements**: Maintain curated patches, device overlays, and build scripts tailored specifically for the hardware.
- **Upstream Sync**: Keep clean forks synchronized with upstream sources while isolating custom modifications.

---

## 📂 Repositories

| Repository | Purpose | Origin |
| :--- | :--- | :--- |
| **[android_device_motorola_lamu](https://github.com/Lamu-Development/android_device_motorola_lamu)** | Device tree configuration & HAL setup | Forked from `LineageOS` |
| **[android_device_motorola_mt6768-common](https://github.com/Lamu-Development/android_device_motorola_mt6768-common)** | Motorola MT6768 common device tree | Forked from `LineageOS` |
| **[proprietary_vendor_motorola_lamu](https://github.com/Lamu-Development/proprietary_vendor_motorola_lamu)** | Proprietary vendor blobs & prebuilts | Forked from `TheMuppets` |
| **[proprietary_vendor_motorola_mt6768-common](https://github.com/Lamu-Development/proprietary_vendor_motorola_mt6768-common)** | Motorola MT6768 common vendor blobs | Forked from `TheMuppets` |
| **[android_device_motorola_lamu-kernels](https://github.com/Lamu-Development/android_device_motorola_lamu-kernels)** | Prebuilt kernel binaries | Forked from `LineageOS` |
| **[android_kernel_motorola_lamu-modules](https://github.com/Lamu-Development/android_kernel_motorola_lamu-modules)** | Device kernel modules | Forked from `LineageOS` |
| **[android_kernel_motorola_lamu-mediatek_modules](https://github.com/Lamu-Development/android_kernel_motorola_lamu-mediatek_modules)** | MediaTek platform kernel modules | Forked from `LineageOS` |
| **[android_kernel_motorola_lamu_manifest](https://github.com/Lamu-Development/android_kernel_motorola_lamu_manifest)** | Kernel manifest configurations | Forked from `LineageOS` |
| **[resources](https://github.com/Lamu-Development/resources)** | Custom ROM manifests, patches, overlays & scripts | Lamu Development |

---

## 🤝 Credits & Acknowledgements

Our device trees and sources build directly upon the work of the open-source community:

- **[The LineageOS Project](https://github.com/LineageOS)** — for providing the base device tree, kernel sources, and ongoing maintenance.
- **[TheMuppets](https://github.com/TheMuppets)** — for extracting and maintaining proprietary vendor blobs.
- **Motorola Mobility LLC & MediaTek** — for stock firmware and GPL kernel releases.
- All contributors and developers in the Android custom ROM community.
