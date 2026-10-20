# Loophole Desktop

This repository hosts release builds for Loophole Desktop. Source code is not kept here.

## Installation

Download the file for your platform from the [Releases](../../releases) page.

| Platform | Architecture | File |
|----------|--------------|------|
| Windows | x64 | `loophole-desktop-win-x64.exe` |
| macOS | Apple Silicon (arm64) | `loophole-desktop-mac-arm64.dmg` |
| macOS | Intel (x64) | `loophole-desktop-mac-x64.dmg` |
| Linux (Debian/Ubuntu) | amd64 | `loophole-desktop-linux-amd64.deb` |
| Linux (Debian/Ubuntu) | arm64 | `loophole-desktop-linux-arm64.deb` |
| Linux (Fedora/RHEL) | x86_64 | `loophole-desktop-linux-x86_64.rpm` |
| Linux (Fedora/RHEL) | aarch64 | `loophole-desktop-linux-aarch64.rpm` |
| Linux (AppImage) | x86_64 | `loophole-desktop-linux-x86_64.AppImage` |
| Linux (AppImage) | arm64 | `loophole-desktop-linux-arm64.AppImage` |

### Windows

Run the `.exe` and follow the installer.

### macOS

Open the `.dmg` and drag Loophole into your Applications folder.

### Linux

**Debian / Ubuntu**

```bash
sudo dpkg -i loophole-desktop-linux-amd64.deb
```

**Fedora / RHEL**

```bash
sudo rpm -i loophole-desktop-linux-x86_64.rpm
```

**AppImage**

```bash
chmod +x loophole-desktop-linux-x86_64.AppImage
./loophole-desktop-linux-x86_64.AppImage
```

## Updates

To update, download the newest release and install it over your current version.
