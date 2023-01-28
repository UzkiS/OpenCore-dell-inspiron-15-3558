# OpenCore-dell-inspiron-15-3558

<p align="center">
    <a href="https://www.apple.com/macos/">
        <img src="https://img.shields.io/badge/macOS-BigSur_v11.7.3-ff69b4.svg"/>
    </a>
    <a href="https://github.com/acidanthera/OpenCorePkg">
        <img src="https://img.shields.io/badge/OpenCore-0.8.8-brightgreen.svg"/>
    </a>
</p>


Dell inspiron 15 3558‘s OpenCore for MacOS BigSur
(Because macos12+ does not support fakepciid, internal usb2.0 hub will be lost, so it only supports BigSur)

## Device infomation
- Wireless card: Intel 3168

## Before installation

### star this project >w<

### Edit config.plist

**At first, please complete the 'PlatformInfo' use [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS).**

- PlatformInfo>Generic>MLB
- PlatformInfo>Generic>ROM
- PlatformInfo>Generic>SystemSerialNumber
- PlatformInfo>Generic>SystemUUID

### BIOS Settings

- VTd -> Disabled
