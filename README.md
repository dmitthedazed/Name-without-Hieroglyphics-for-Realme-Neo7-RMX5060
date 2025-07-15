# Name Without Hieroglyphics for Neo7-CN

A Magisk module that removes Chinese characters (hieroglyphics) from device names throughout the system for the realme Neo7 CN variant. Also compatible with KernelSU.

## 📱 Device Compatibility

- **Device**: realme Neo7 (Chinese variant)
- **Model**: RMX5060
- **Requirements**: Magisk v20.4+ or KernelSU with root access
- **Android Version**: Compatible with Android versions supported by realme Neo7

## 🎯 What This Module Does

This module modifies system properties to replace Chinese characters in device names with clean English equivalents:

- **Market Name**: Changed to "realme Neo7" (without Chinese characters)
- **Bluetooth Name**: Set to "realme Neo7" 
- **Hotspot/Tethering Name**: Set to "Neo7"
- **Device Display Name**: Unified as "realme Neo7"

## 🔧 Installation

### Prerequisites
- Rooted device with Magisk v20.4+ or KernelSU
- realme Neo7 CN variant (RMX5060)

### Steps
1. Download the latest release from the [Releases](../../releases) page
2. Open Magisk Manager or KernelSU Manager
3. Go to "Modules" section
4. Tap "Install from storage"
5. Select the downloaded ZIP file
6. Reboot your device

## 📋 Modified Properties

The module modifies the following system properties:

```properties
ro.vendor.oplus.market.enname=realme Neo7
ro.vendor.oplus.market.name=realme Neo7
bluetooth_name=realme Neo7
device_tether_name=Neo7
```

## 🗂️ Module Structure

```
Name-Without-Hieroglyphics-for-Neo7-CN/
├── module.prop              # Module metadata and information
├── system.prop              # System properties to be modified
├── META-INF/
│   └── com/
│       └── google/
│           └── android/
│               ├── update-binary    # Installation script
│               └── updater-script   # Magisk identifier
└── README.md                # This file
```

## ⚠️ Important Notes

- **Backup**: Always create a full system backup before installing any Magisk module
- **Device Specific**: This module is specifically designed for realme Neo7 CN variant (RMX5060)
- **Compatibility**: May not work correctly on other devices or variants. Compatible with both Magisk and KernelSU
- **Updates**: System updates may require reinstallation of the module

## 🔄 Uninstallation

1. Open Magisk Manager or KernelSU Manager
2. Go to "Modules" section
3. Find "Name Without Hieroglyphics (for Neo7 CN)"
4. Tap the trash icon to remove
5. Reboot your device

## 🐛 Troubleshooting

### Module Not Working
- Ensure you're using realme Neo7 CN variant (RMX5060)
- Check that Magisk version is v20.4+ or KernelSU is properly installed
- Verify the module is enabled in Magisk Manager or KernelSU Manager
- Try reinstalling the module

### Bootloop or System Issues
- Boot into recovery mode
- Remove the module by deleting `/data/adb/modules/namewithouthieroglyphs/`
- Reboot the device

## 📱 Before & After

### Before (with Chinese characters)
- Device shows Chinese characters in system information
- Bluetooth name contains hieroglyphics
- Confusing device identification

### After (clean English names)
- Clean "realme Neo7" display name
- English-only bluetooth identification
- Simplified device naming throughout system

## 🤝 Contributing

Feel free to contribute to this project by:
- Reporting bugs or issues
- Suggesting improvements
- Testing on different firmware versions
- Submitting pull requests

## 📄 License

This project is open source. Feel free to modify and distribute according to your needs.

## 👤 Author

- **dmitthedazed** - Original creator and maintainer

## 🙏 Acknowledgments

- Magisk team for the excellent framework
- KernelSU team for the alternative root solution
- realme community for testing and feedback
- Contributors who helped improve the module

---

**⚠️ Disclaimer**: This module modifies system properties. Use at your own risk. The author is not responsible for any damage to your device.

