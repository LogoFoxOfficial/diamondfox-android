# DiamondFox Android

DiamondFox is an Android utility for supported Samsung Galaxy S23 Ultra firmware builds.

This repository contains no source code. It is used for project information, releases and documentation.

[Download latest APK](https://github.com/LogoFoxOfficial/diamondfox-android/releases/latest)

## Current status

The current release line is **DiamondFox 2**.

DiamondFox provides temporary, boot-scoped root on supported firmware while keeping the bootloader locked and Verified Boot intact. Root access, `dfrootd`, Zygisk and Vector are lost after a normal reboot and must be established again.

The initial root bootstrap currently requires DiamondFox Bridge / shell access. Once `dfrootd` is active, normal root operations no longer depend on Wireless Debugging for that boot.

### Firmware support

| Firmware | Status | Root profile |
| --- | --- | --- |
| **ZZI8** | ✅ Supported | Zephyr r2 / F168 |
| **ZZHL** | ✅ Supported | Zephyr |
| **FZG1** | ⚠️ Legacy support | Fennec |
| **FZH3** | ❌ Deprecated | Fennec |
| **GZI8** | 🧪 Research / not supported | Gecko |

Compatibility is firmware-specific. A profile must match the exact supported device, firmware and kernel before DiamondFox will attempt root.

## Features

- Device and firmware detection
- Temporary kernel root
- Private boot-scoped `dfrootd` root service
- Standard Android `su` support with per-app permissions
- Systemless module management
- DiamondFox Zygisk-compatible provider
- RAM-only Vector 2.2 runtime
- Legacy Xposed and modern libxposed compatibility
- Native Xposed module and scope management
- Samsung diagnostics, firmware inspection and system tools
- Crash/reset forensics and support-report export
- Built-in update checking and APK signature verification

## Important

DiamondFox is still **pre-release software**. Alpha builds may contain unexpected bugs, crashes or compatibility issues.

No boot image or real Android system partition is persistently modified by the normal DiamondFox root flow.

Issues, compatibility reports and logs can be posted in the DiamondFox XDA thread:

https://xdaforums.com/t/root-sm-s918b-diamondfox-ram-only-kernel-root-on-locked-bootloader-with-standard-android-su.4802243/

## Releases

Prebuilt APKs are available from the repository's **Releases** section.
