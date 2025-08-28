<div align="center">

# ✨ Nyaa~ Magical SMB Explorer 🐾

### NETWORKING-SAMBA-TUI-EXPLORER-SAVER

**Explore Samba shares across your LAN using adorable magic and terminal spells! 💖**

</div>

<p align="center">
  <a href="https://github.com/LINUX-OASIS/NETWORKING-SAMBA-TUI-EXPLORER-SAVER/blob/main/LICENSE"><img src="https://img.shields.io/github/license/LINUX-OASIS/NETWORKING-SAMBA-TUI-EXPLORER-SAVER?style=for-the-badge" alt="License"></a>
  <a href="https://github.com/LINUX-OASIS/NETWORKING-SAMBA-TUI-EXPLORER-SAVER/issues"><img src="https://img.shields.io/github/issues/LINUX-OASIS/NETWORKING-SAMBA-TUI-EXPLORER-SAVER?style=for-the-badge&color=A370F0" alt="Issues"></a>
  <a href="https://github.com/LINUX-OASIS/NETWORKING-SAMBA-TUI-EXPLORER-SAVER/pulls"><img src="https://img.shields.io/github/issues-pr/LINUX-OASIS/NETWORKING-SAMBA-TUI-EXPLORER-SAVER?style=for-the-badge&color=21B5A3" alt="Pull Requests"></a>
  <a href="https://github.com/LINUX-OASIS/NETWORKING-SAMBA-TUI-EXPLORER-SAVER/stargazers"><img src="https://img.shields.io/github/stars/LINUX-OASIS/NETWORKING-SAMBA-TUI-EXPLORER-SAVER?style=for-the-badge&color=FFDF00" alt="Stars"></a>
  <br>
  <img src="https://img.shields.io/badge/tech-Bash%20%7C%20nmap%20%7C%20smbclient-C71585?style=for-the-badge&logo=gnubash" alt="Tech Stack">
  <img src="https://img.shields.io/github/last-commit/LINUX-OASIS/NETWORKING-SAMBA-TUI-EXPLORER-SAVER?style=for-the-badge" alt="Last Commit">
</p>

---

This script casts a wide magic net to find all SMB hosts for you, senpai! It provides a friendly Text-based User Interface (TUI) to discover, list, and manage Samba hosts on your local network.

<!-- Add a GIF of the script in action here! -->
<!-- ![Demo GIF](path/to/your/demo.gif) -->

## ✨ Features

*   **🐾 Magical TUI:** A cute and easy-to-use `whiptail` interface.
*   **🧙 Automatic Discovery:** Scans your local network ranges to find all active Samba hosts.
*   **📂 Share Listing:** Select a host to view all of its available Samba shares.
*   **💾 Host Saver:** Save a discovered host's IP and hostname to your `/etc/hosts` file for easy access.
*   **🗑️ Host Deleter:** Easily remove previously saved hosts from your `/etc/hosts` file.
*   **🔮 Auto-Dependency Check:** The script checks for required tools and will offer to install them for you!

## 🖥️ Compatibility

This script is designed to run on Debian-based Linux distributions that use the `apt` package manager. It has been tested on:

*   **Debian**
*   **Ubuntu** & its derivatives (Kubuntu, Xubuntu, etc.)
*   **Linux Mint**
*   ...and other Debian derivatives!

## 🔧 Dependencies

The script relies on a few key command-line tools to work its magic.

*   `whiptail` (for the TUI)
*   `nmap` (for network scanning)
*   `smbclient` & `nmblookup` (for Samba communication)
*   `nbtscan` (for NetBIOS name scanning)

Don't worry, senpai! If any of these are missing, the script will detect them and ask for your permission to install them automatically using `sudo apt install`.

## 🚀 Getting Started

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/LINUX-OASIS/NETWORKING-SAMBA-TUI-EXPLORER-SAVER.git
    cd NETWORKING-SAMBA-TUI-EXPLORER-SAVER
    ```

2.  **Make the script executable:**
    ```bash
    chmod +x custom-NETWORKING-SAMBA-SCANNER-SAVER.sh
    ```

3.  **Run the script with sudo:**
    (Sudo is required for network scanning and modifying `/etc/hosts`)
    ```bash
    sudo ./custom-NETWORKING-SAMBA-SCANNER-SAVER.sh
    ```

## 🧙‍♂️ Maintainer

This project is lovingly maintained by:

*   [**LINUX-OASIS**](https://github.com/LINUX-OASIS)

## 🌐 Links

*   [**Issues**](https://github.com/LINUX-OASIS/NETWORKING-SAMBA-TUI-EXPLORER-SAVER/issues)
*   [**Pull Requests**](https://github.com/LINUX-OASIS/NETWORKING-SAMBA-TUI-EXPLORER-SAVER/pulls)
*   [**Releases**](https://github.com/LINUX-OASIS/NETWORKING-SAMBA-TUI-EXPLORER-SAVER/releases)
*   [**Wiki**](https://github.com/LINUX-OASIS/NETWORKING-SAMBA-TUI-EXPLORER-SAVER/wiki)

## 💬 Contributing

Pull requests, issues, and suggestions are warmly welcomed! For major changes, please open an issue first to discuss what you would like to change.

Please see **CONTRIBUTING.md** for guidelines.

## 📜 License

This project is licensed under the **GNU General Public License v3.0**.

See the LICENSE file for details.
