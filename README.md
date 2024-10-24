# Hackintosh EFI for Lenovo Legion 5 15ARH05

This repository contains the EFI configuration for running macOS on the Lenovo Legion 5 15ARH05 laptop.

## Specifications

- **Model:** Lenovo Legion 5 15ARH05
- **Processor:** AMD Ryzen™ 5 4600H with Radeon™ Graphics
- **RAM:** 16.0 GiB
- **Graphics:** NV167 / AMD Radeon™ Graphics

## Features

- Fully functional macOS installation
- Support for audio, Wi-Fi, and GPU acceleration
- Pre-configured EFI folder for easy setup

## Installation Instructions

1. **Backup Your Data:**
   Before proceeding, ensure you have backed up all important data.

2. **Create a macOS Bootable USB:**
   - Use a macOS installer (downloaded from the App Store) to create a bootable USB drive.

3. **Replace the EFI Folder:**
   - Mount the EFI partition of your USB drive.
   - Replace the existing `EFI` folder with the one from this repository.

4. **Boot from USB:**
   - Reboot your laptop and enter the BIOS settings.
   - Change the boot order to prioritize the USB drive.
   - Save changes and exit the BIOS.

5. **Install macOS:**
   - Follow the on-screen instructions to install macOS on your desired partition.

6. **Post-Installation:**
   - After installation, boot into macOS and repeat the process to mount the EFI partition of your macOS drive.
   - Copy the `EFI` folder from this repository to the EFI partition.

## Troubleshooting

- If you encounter issues during boot, double-check the BIOS settings, ensuring that Secure Boot is disabled and the proper SATA mode is selected.
- Refer to Hackintosh forums and communities for additional support.

## Contributing

Feel free to contribute by submitting issues or pull requests. Your feedback and suggestions are welcome!

## License

This project is licensed under the MIT License. See the LICENSE file for more information.

## Disclaimer

This guide is intended for educational purposes only. Running macOS on non-Apple hardware may violate Apple's End User License Agreement (EULA).
