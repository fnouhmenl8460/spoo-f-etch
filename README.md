# spoo-f-etch

**spoo-f-etch** is an automated system info spoofing tool for Neofetch. Run its installer script once, and it will configure Neofetch to display fully spoofed system information — distro, hostname, kernel, uptime, packages, CPU, GPU, and more — without any further input.

---

## Features

- Fully automatic installation and configuration  
- Spoofs all key Neofetch system info fields with predefined fake values  
- Backs up existing Neofetch config automatically  
- No Python or manual edits required  
- Designed to work on **most Linux distributions**  
- Simple one-command setup  

---

## Requirements

- Linux with Bash shell  
- `sudo` privileges  
- Internet connection for installing Neofetch and dependencies  

---

## Supported Distributions

The installer script attempts to detect your Linux distribution’s package manager and use it to install Neofetch if missing. Supported package managers include:

- `apt` (Debian, Ubuntu, Mint, Pop!_OS, etc.)  
- `dnf` (Fedora, RHEL, CentOS)  
- `yum` (Older Fedora, RHEL, CentOS)  
- `pacman` (Arch, Manjaro)  
- `zypper` (openSUSE)  
- `apk` (Alpine Linux)  

If your distro or package manager is not detected, the script will prompt you to install Neofetch manually.

---

## Installation

```bash
git clone https://github.com/fnouhmenl846/spoo-f-etch
cd spoo-f-etch
chmod +x installer.sh
./installer.sh
