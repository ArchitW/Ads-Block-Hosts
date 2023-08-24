💀 Ads-Block-Hosts 💀

# AdBlocker using Hosts File

## Overview

This project provides a simple way to block advertisements across various platforms (Mac, Windows, Linux, and Android) by leveraging the hosts file. The hosts file is used to map hostnames to IP addresses and can be manipulated to redirect ad-serving domains to a non-existent IP, effectively blocking ads.

## How It Works

The script in this repository automates the process of editing the hosts file to include entries that redirect known ad-serving domains to a local IP address (typically 127.0.0.1 || 0.0.0.0). This prevents your device from loading ads from these domains.

## Supported Platforms

- Mac
- Windows
- Linux
- Android

## Usage

1. Clone or download this repository to your local machine.
2. Navigate to the appropriate directory for your platform:
   - For Mac, Windows, and Linux: `scripts` [WIP]
   - For Android: `android-scripts`[WIP]
3. Run the corresponding script:
   - For Mac: `sudo ./block_ads_mac.sh` [WIP] 
   - For Windows: Run `block_ads_windows.bat` as Administrator [WIP]
   - For Linux: `sudo ./block_ads_linux.sh` [WIP] 
   - For Android: Follow instructions in `android-scripts/README.md` [WIP]
4. Follow the prompts to update the hosts file.
5. Reboot your device or restart networking services for the changes to take effect.

**Note:** The scripts modify system files, so use them with caution. Make sure to back up your hosts file before running the scripts.

## Contribution

Contributions are welcome! If you have improvements or additional scripts for other platforms, feel free to fork this repository and submit a pull request.

## Disclaimer

Blocking ads using the hosts file can impact the functionality of certain websites and services. Use this script responsibly and be aware of potential side effects. The maintainers of this repository are not responsible for any adverse effects on your system.

## License

This project is licensed under the [MIT License](LICENSE).

---

**Disclaimer:** This project is provided for educational and informational purposes only. Use it at your own risk. The maintainers are not responsible for any damages or consequences caused by the use of this project.

