# The BeX Downgrader

- The original script was created by LukeZGD https://github.com/LukeZGD
- This script is based off https://github.com/LukeZGD/Legacy-iOS-Kit by LukeZGD

## Features
- Quick downgrading to older version with powdersn0w

## Supported devices
- [Identify your device here](https://ipsw.me/device-finder)
- **iPhone 5C and iPad mini 3 devices are NOT supported by OTA downgrades**
- See the list below for powdersn0w downgrading.

- Restoring with powdersn0w is supported on the following devices:
    - iPhone 4 GSM - targets iOS 4.3 to 7.1.1 - the only one tested by me, so if you have devices listed below please let me know if this tool works for this phones.
    - iPhone 4 CDMA - targets iOS 5.0 to 7.1.1
    - iPhone 4S, 5, 5C, iPad 2 Rev A, iPad 4, iPod touch 5 - targets iOS 5.0 to 9.3.5
    - iPad 1 - targets iOS 4.3.1 to 5.1
    - iPod touch 3 - targets iOS 4.3 to 5.1
    - Using powdersn0w requires iOS 7.1.x blobs for your device
        - For iPhone 5 and 5C, both 7.0.x and 7.1.x blobs can be used
        - For iPad 4, only 7.0.x blobs can be used
        - For iPad 1 and iPod touch 3, 5.1.1 blobs are used instead

## Supported OS versions/distros

#### Supported architectures: x86_64, arm64, armhf

- **macOS** 10.13 and newer (10.15 and newer recommended)
- **Linux** not supported for now

## Tools and other stuff used
- curl
- bspatch
- [powdersn0w_pub](https://github.com/dora2-iOS/powdersn0w_pub) - dora2ios; [LukeZGD fork](https://github.com/LukeZGD/powdersn0w_pub)
    - [Most of the exploit ramdisks used are from kok3shidoll's repo](https://github.com/kok3shidoll/untitled)
    - [5C 7.0.x exploit ramdisk is from Ralph0045's iloader repo](https://github.com/Ralph0045/iloader)
    - [iPad 1 exploit ramdisk is from Ralph0045's iBoot-5-Stuff repo](https://github.com/Ralph0045/iBoot-5-Stuff)
- [ipwndfu](https://github.com/LukeZGD/ipwndfu) - axi0mX, Linus Henze, synackuk; LukeZGD fork
- [ipwnder_lite](https://github.com/dora2-iOS/ipwnder_lite/tree/7265a06d184e433989db640d5e83ea58d5862609) - dora2ios (used on macOS)
- [iPwnder32](https://github.com/dora2-iOS/iPwnder32/tree/243ea5c6d1bd15f8bdd0b3a1ff4a7729bc14bac4) - dora2ios (old version with libusb used on Linux)
- [gaster](https://github.com/0x7ff/gaster/) - 0x7ff
- [daibutsuCFW](https://github.com/dora2-iOS/daibutsuCFW) - dora2ios; [LukeZGD fork](https://github.com/LukeZGD/daibutsuCFW)
- [daibutsu](https://github.com/kok3shidoll/daibutsu) - dora/kok3shidoll, Clarity
- [libimobiledevice](https://github.com/libimobiledevice/libimobiledevice) - libimobiledevice
- [libirecovery](https://github.com/libimobiledevice/libirecovery) - libimobiledevice
- [libideviceactivation](https://github.com/libimobiledevice/libideviceactivation) - libimobiledevice
- [tsschecker](https://github.com/tihmstar/tsschecker) - tihmstar; [1Conan fork](https://github.com/1Conan/tsschecker) v413
- [iBoot32Patcher](https://github.com/dora2-iOS/iBoot32Patcher/) - dora2ios fork
- If i missed any while deleting please dm me on twitter (i mean X) @iNostalgia
