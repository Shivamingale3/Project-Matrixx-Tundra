
![Logo](https://camo.githubusercontent.com/b223a3321709c53792ac80d54218fd5227fb64e8258e84a786d09143e6f52996/68747470733a2f2f692e706f7374696d672e63632f4c684659647a31332f42616e6e65722d4c6f676f2d4865616465722e706e67)


# Project-Matrixx-Tundra

### Project Matrixx Unofficial Custom ROM for Motorola Edge 30 Fusion (tundra)


# Acknowledgements

 - ## [Project Matrixx](https://github.com/ProjectMatrixx)
 - [Device Trees](https://github.com/raghavt20/android_device_motorola_tundra) || [-by : raghavt20](https://github.com/raghavt20)
 - [Lineage OS stuff](https://github.com/orgs/LineageOS/repositories) 
 - [Lord Luke : for Guidance](https://t.me/Beetle84) 


## About Project Matrixx
Welcome to Project Matrixx!

- Project Matrixx is a custom ROM based on crDroid Android
- Added few extra features and borrowed UI from RisingOS
- Currently source is Android 14

More info : [Project Matrixx](https://github.com/ProjectMatrixx)


## Features

- Initial build A14
- Moto Cam included
- Everything works

## Bugs

- None spotted yet
- If found please report to me on telegram.
## Installation

1. Install device drivers & latest platform-tools & add them to path
2. Backup data
3. Unlock Bootloader [Tutorial](https://motorola-global-portal.custhelp.com/app/standalone/bootloader/unlock-your-device-a)
4. Download the ROM from below.
5. Extract the ROM and open terminal in that extracted Folder.
6. Reboot into bootloader, connect the device and enter the following commands:  

        fastboot -w
        fastboot flash boot boot.img
        fastboot flash vendor_boot vendor_boot.img
        fastboot flash dtbo dtbo.img
        fastboot flash vbmeta vbmeta.img
        fastboot flash vbmeta_system vbmeta_system.img
        fastboot reboot fastboot
         
7. The device will now reboot into fastbootd now enter these commands:

        fastboot flash super super_empty.img
        fastboot flash system system.img
        fastboot flash system_ext system_ext.img
        fastboot flash product product.img
        fastboot flash vendor vendor.img
        fastboot reboot
        
8. The device will now reboot into system now setup the device to be able to use it.
## 🔗 Links

- ### [Project Matrixx ROM - tundra](https://sourceforge.net/projects/shivam-ingale-s-tundra/files/Project-Matrixx/Matrixx-v10.1.2-Unofficial-tundra-Gapps-20231226.zip/download)
- [Device Drivers](https://gsmusbdrivers.com/download/motorola-mobile-drivers-64-bit/)
- [Platform-tools](https://developer.android.com/tools/releases/platform-tools)
- [Stock ROM - Choose by Channel](https://mirrors.lolinet.com/firmware/motorola/tundra/official/)
- [Device Support Group](https://t.me/motoedge30fusion)
- [Device Updates Group](https://t.me/Edge30FusionUpdates)
- Feedback or Report to Me : [Telegram](https://t.me/Shivamingale)

## Screenshots

[Matrixx Folder](https://photos.app.goo.gl/dhqH44zbzGxhGVbJ7)


# [Download Link : Here](https://sourceforge.net/projects/shivam-ingale-s-tundra/files/Project-Matrixx/Matrixx-v10.1.2-Unofficial-tundra-Gapps-20231226.zip/download)

