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
- Detailed logging with error handling

---

## Installation Methods

### Method 1: Git Clone (Recommended)

```bash
# Clone the repository
git clone https://github.com/muhammadtalha1322/debian13-fresh-setup.git

# Go into the directory
cd debian13-fresh-setup

# Make script executable
chmod +x update_deb.sh

# Run the setup script
sudo ./update_deb.sh
