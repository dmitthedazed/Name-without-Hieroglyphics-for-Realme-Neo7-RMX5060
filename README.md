# Name without Hieroglyphics for Realme Neo7 (RMX5060)

A Magisk module that fixes hieroglyphics (Chinese characters) in system properties for the Realme Neo7 CN variant (RMX5060).

## Features

- Replaces Chinese characters with proper English names
- Fixes Bluetooth device name
- Fixes tethering name
- Fixes market names

## Installation

1. Download the latest release ZIP from [Releases](https://github.com/dmitthedazed/Name-without-Hieroglyphics-for-Realme-Neo7-RMX5060/releases)
2. Open Magisk Manager
3. Tap on "Modules"
4. Tap "Install from storage"
5. Select the downloaded ZIP file
6. Reboot your device

## What it fixes

The module modifies the following properties:

- `ro.vendor.oplus.market.enname` → realme Neo7
- `ro.vendor.oplus.market.name` → realme Neo7
- `bluetooth_name` → realme Neo7
- `device_tether_name` → Neo7

## Automatic Updates

This module supports automatic updates through Magisk Manager. The module will check for updates automatically, and you'll be notified when a new version is available.

## Building from Source

The module is automatically built and released via GitHub Actions whenever changes are pushed to the main branch. Each release increments the version by 0.1.

## Compatibility

- **Device:** Realme Neo7 (RMX5060) - Chinese variant
- **Android Version:** Compatible with all Android versions supported by Magisk
- **Magisk Version:** 20.4+

## Changelog

See [Releases](https://github.com/dmitthedazed/Name-without-Hieroglyphics-for-Realme-Neo7-RMX5060/releases) for version history and changes.

## License

This project is provided as-is for the Realme Neo7 community.

## Credits

- Created by dmitthedazed
- Thanks to the Magisk development team