# Opencore EFI for Hackintosh on ASUS ROG Z390-H / AMD RX 580 GPU
This repository is exclusively designed for ASUS ROG Z390-H i7-9700K RX580 to run BigSure/Catalina with no hassle
Everything is working on BigSur/Catalina with OpenCore
- You need to generate your own UUID/Serial
- The opencore EFI works with Big Sur, including WIFI/Bluetooth.

## Specs

- NZXT H500 Mid-Tower
- ASUS ROG Strix Z390-H
- Intel Core i7-9700K 8-Core
- Radeon Shapphie Pulse RX 580
- CORSAIR Vengeance RGB PRO 16GB (2 x 8GB)
- Samsung 970 EVO PLUS NVMe M.2 SSD 500GB
- Seagate 2TB
- Cooler Master Elite v3 600w
- Corsair H115i
- TP-link Archer T6E

## What works

- **Wifi & Bluetooth**
- **dGPU** Hardware Accelaration  (Final Cut Pro X, VideoProc, Compressor tested)
- **AirDrop, Handoff** 
- **SideCar** 
- **iMessage**
- **All Rear USB3.1 USB2.0 Type-C/Type-A Ports** (few USB2.0 ports disabled) 
- **Onboard HD Audio**
- **USB 3.1 Gen2** (may require a USB3.1 Gen2 to PCIe Card, i.g. ASM1142 chip-based)
- **H264/H265 HW Encode/Decode Supported**

### Credits

* **OpenCore Bootloader** from [OpenCore Respository](https://github.com/acidanthera/OpenCorePkg)
* **The best Installation guide I followed** from [OpenCore Vanilla Desktop Guide](https://khronokernel-2.gitbook.io/opencore-vanilla-desktop-guide/)