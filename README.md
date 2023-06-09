# Acer-Swift-3-SF314-54-2018-MacOS
Use this OpenCore EFI to run MacOS on Acer Swift 3 SF314-54 (2018) 

**Now supporting MacOS Ventura 13.3 - 23 April 2023 **
 <img src="macOS-ventura-13.3.1.webp"/>
## Configuration

| Specifications | Detail                                                  |
| ------------------- | ------------------------------------------- |
| Computer model      | Acer Swift 3 SF314-54 (2018)      |
| Processor           | Intel Core i5-8250U     |
| Memory              | 8GB/20GB  DDR4 2400MHz              |
| Hard Disk           | Only tested with SATA SSD    |
| Integrated Graphics | Intel UHD Graphics 620                     |
| Monitor             |  FHD 1920x1080 (14 inch) |
| Sound Card          | Realtek ALC256 (layout-id:13)           |
| Wireless Card       | Swapped with a DW1820A                     |
| SD Card Reader      | Realtek                 |


## Current Status

- **Fingerprint sensor** is not working
- **Built-in DMIC** is not working
- Everything else works well
- Brightness keys now using new .kext and working 100% with normal brightness keys **F3** and **F4**
- Install **Captin.dmg** to have a Caps Lock indicator on screen
- Install **ComboJack** to assist with Headphones / Headset
- **Apple Watch** unlock is not consitant but seems to be a generic problem on hackintoshes
- **2.4 GHz Wifi interference** with Bluetooth (mostly Bluetooth audio) also seems to be a common problem
## Download
链接：https://cloud.189.cn/t/EBr2MfqI3uEn（访问码：hah3）
## Install
- First. flash MacOS dmg file to greater than or equal to 16g of usb disk by [Etcher](https://github.com/balena-io/etcher)
- Second. disable secure boot and enbale VTX from BIOS
- Third. reboot computer from usb and enter windows 11 pe
- Fourth. replace EFI of opencore with this project EFI
- Last. reboot compoter and enter MacOS install
