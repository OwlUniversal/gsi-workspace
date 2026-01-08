# 🌸 Sakura GSI Lab

Welcome to my personal GSI repository. This project hosts manually maintained Generic System Images for ARM64 devices. 

Every image here is built with manual source-level interventions. I aim to provide only confirmed bootable images; however, I am not responsible for device-specific incompatibilities.

## 📥 Downloads
All flashable images are available in the **[Releases](https://github.com/OwlUniversal/gsi-workspace/releases)** section. 

## 🚀 Quick Start
1. Reboot to **fastboot** (or **fastbootd**, depending on your phone).
2. Flash the system image: `fastboot flash system system.img`
3. Wipe Data (Mandatory for first boot): `fastboot -w`
4. Reboot and enjoy: `fastboot reboot`

## 🤝 Acknowledgments
- **[RisingOS Revived](https://github.com/RisingOS-Revived-devices) / [LineageOS](https://github.com/LineageOS) / [PHH](https://github.com/phhusson)** for the foundation.
- **[Cromite](https://github.com/uazo/cromite)** for the secure browser engine.
- **[legacy.launcher](https://github.com/hxehex)** for technical insights, kernel tweaks, and testing images.

## ⚖️ Disclaimer
Your warranty is now void. I am not responsible for bricked devices, dead SD cards, or thermonuclear war. Please ensure you have a backup of your data before flashing! 
