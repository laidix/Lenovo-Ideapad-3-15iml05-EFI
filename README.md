# EFI for Hackintosh on Lenovo Ideapad 3 15iml05

[![macOS](https://img.shields.io/badge/macOS-26.4-brightgreen?style=for-the-badge&logo=apple&logoColor=white)](https://www.apple.com/macos/)
[![OpenCore](https://img.shields.io/badge/OpenCore-1.0.7-blue?style=for-the-badge&logo=opencore&logoColor=white)](https://github.com/acidanthera/OpenCorePkg)
[![Download](https://img.shields.io/badge/Download-Latest%20EFI-orange?style=for-the-badge&logo=github&logoColor=white)](https://github.com/laidix/Lenovo-Ideapad-3-15iml05-EFI/releases/latest)

## Fully working EFI.
It should work, if you get issues, just do report it in issues and I will fix it.

## Native WiFi Patching Config Part is also there! Just need to uncomment it in DeviceProperties tab.

<p align="center">
  <img src="Pictures/Laptop.webp" alt="Laptop" width="600">
</p>

## Specifications

| Component | Model | Status |
|---|---|---|
| CPU | Intel Core i5-10210U | Up to macOS Tahoe 26 |
| iGPU | Intel Integrated Graphics(630) | Up to macOS Tahoe 26 |
| Audio | Realtek Audio | Up to macOS Tahoe 26 |
| Wi-Fi | Intel Wi-Fi 6E AX210 | Up to macOS Tahoe 26 |
| Bluetooth | Intel Bluetooth | Up to macOS Tahoe 26 |
| Storage | NVMe SSD | Up to macOS Tahoe 26 |

## What Works
- Everything except:
  
## What Doesn't Work

- Native WiFi support(!!SINCE SEQUOIA!!)
- Sound(!!ONLY IF YOU ARE ON MACOS TAHOE, PATCHING REQUIRED!!)

## BIOS Settings

- Disable Secure Boot
- Disable Fast Boot

## Screenshots
<p align="center">
  <img src="Pictures/AboutThisMac.png" alt="About This Mac" width="800">
</p>
<p align="center">
  <img src="Pictures/Settings.png" alt="Settings" width="800">
</p>
<p align="center">
  <img src="Pictures/Tahoe.png" alt="Tahoe" width="800">
</p>

## Credits
- Hackintosh community for finding and helping to fix my errors which were not leading to boot, and also for Mmio Whitelists.
