
# Debian 13 Cyber Setup

**Professional first-time setup script for Debian 13 (Trixie)** optimized for **Cybersecurity Beginners** using **KDE Plasma**.

This script configures a clean, secure, and productive Debian environment with all essential tools and modern software.

---

## Features

- Proper Debian repositories (`main + contrib + non-free + non-free-firmware`)
- Full system update & upgrade
- Essential development and productivity tools
- Nala (better `apt` frontend)
- btop + neofetch
- VLC Media Player, LibreOffice, Firefox ESR
- **ZapZap** — Modern WhatsApp Desktop Client (via Flatpak)
- Firmware packages for better hardware support
- KDE Plasma integration
- Detailed logging and error handling

---

## Installation Methods

### Method 1: Git Clone (Recommended)

```bash
# Clone the repository
git clone https://github.com/muhammadtalha1322/debian13-fresh-setup.git

# Navigate to the directory
cd debian13-fresh-setup

# Make the script executable
chmod +x update_deb.sh

# Run the setup script
sudo ./update_deb.sh
```

### Method 2: Direct Download (Quick)

```bash
# Download the script directly
wget https://raw.githubusercontent.com/muhammadtalha1322/debian13-fresh-setup/main/update_deb.sh

# Make it executable
chmod +x update_deb.sh

# Run the script
sudo ./update_deb.sh
```

---

## What Gets Installed

- **System Tools**: `curl`, `wget`, `git`, `git-lfs`, `build-essential`, `nala`
- **Development**: Python 3 + pip + venv + python3-dev
- **Productivity**: VLC, LibreOffice, Firefox ESR
- **Utilities**: btop, neofetch, gzip, unzip, p7zip-full
- **Communication**: ZapZap (WhatsApp Desktop)
- **Flatpak + Flathub**
- **Firmware**: `firmware-linux` + `firmware-linux-nonfree`

---

## Author

**Muhammad Talha**  
GitHub: [@muhammadtalha1322](https://github.com/muhammadtalha1322)

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contributing

Feel free to open issues or submit pull requests to improve the script.

---

**Made for the Cybersecurity Community**  
If this script helped you, please consider starring the repository 
