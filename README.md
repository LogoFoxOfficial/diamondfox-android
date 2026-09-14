# DiamondFox Android

DiamondFox is an Android utility for supported Samsung Galaxy S23 Ultra firmware builds.

This repository contains no source code. It is currently used for project information, releases and documentation.

## Current status

DiamondFox can currently perform temporary root on supported firmware.

### Supported firmware

- **ZZHL:** fully supported and verified with the Android app
- **FZG1, FZH3:** are available, but it's not yet verified if these exploits work right now.

Root access is temporary and is lost after a reboot.

## Current features

- Device and firmware detection
- Compatible root profile selection
- Temporary root execution
- Root status reporting

At the moment, DiamondFox does not provide additional root management features.

## Planned

Planned features include:

- DiamondFox Root Backend
- Per-app root access with allow/deny prompts
- Persistent root permission policies
- `su` compatibility for third-party root apps
- Automatic continuation of a pending root operation after a required reboot
- Additional device diagnostics and research utilities

## Notes

DiamondFox is currently focused on the Galaxy S23 Ultra and firmware-specific root support.

Development is ongoing and compatibility may change between firmware builds.
