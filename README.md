<div align="center">

# 📸 ScreenshotHub Releases

### Ultra-Fast, Beautiful Screen Capture & Step Guide Suite for Desktop
**macOS • Windows • Linux**

[![Latest Release](https://img.shields.io/github/v/release/iamtashanto/screenshothub-releases?color=3b82f6&label=Latest%20Version&style=for-the-badge)](https://github.com/iamtashanto/screenshothub-releases/releases/latest)
[![Platform Support](https://img.shields.io/badge/Platform-macOS%20%7C%20Windows%20%7C%20Linux-blueviolet?style=for-the-badge)](https://github.com/iamtashanto/screenshothub-releases/releases)
[![Website](https://img.shields.io/badge/Official%20Website-ss.tashanto.com-06b6d4?style=for-the-badge)](https://ss.tashanto.com)
[![License](https://img.shields.io/badge/License-MIT-emerald?style=for-the-badge)](https://github.com/iamtashanto/screenshothub-releases)

<p align="center">
  <a href="https://ss.tashanto.com"><b>Official Website</b></a> •
  <a href="#-quick-install-terminal-commands"><b>Quick Install</b></a> •
  <a href="#-direct-downloads"><b>Direct Downloads</b></a> •
  <a href="#-key-features"><b>Features</b></a> •
  <a href="#-macos-setup-guide"><b>macOS Setup</b></a>
</p>

---

</div>

## ⚡ Quick Install (Terminal Commands)

Install ScreenshotHub in seconds with a single terminal command:

### 🍎 macOS (Apple Silicon & Intel)
Automatically detects your architecture (M1/M2/M3/M4 or Intel), downloads, installs to `/Applications`, and clears Gatekeeper quarantine:
```bash
curl -fsSL https://ss.tashanto.com/install.sh | bash
```

### 🪟 Windows (PowerShell)
Downloads the latest installer and runs the setup wizard:
```powershell
irm https://ss.tashanto.com/install.ps1 | iex
```

### 🐧 Linux (Ubuntu / Debian / Mint)
Downloads the official `.deb` package and installs via `dpkg`:
```bash
curl -fsSL https://ss.tashanto.com/install-linux.sh | bash
```

---

## 📦 Direct Downloads

Download the standalone installer or portable binary directly for your operating system:

| Platform | Architecture / Format | Direct Download Link |
| :--- | :--- | :--- |
| **🍎 macOS (Apple Silicon)** | M1 / M2 / M3 / M4 (`.dmg`) | [📥 Download ScreenshotHub Apple Silicon](https://github.com/iamtashanto/screenshothub-releases/releases/latest/download/ScreenshotHub-1.0.4-arm64.dmg) |
| **🍎 macOS (Intel)** | x86_64 64-bit (`.dmg`) | [📥 Download ScreenshotHub Intel DMG](https://github.com/iamtashanto/screenshothub-releases/releases/latest/download/ScreenshotHub-1.0.4.dmg) |
| **🪟 Windows (x64)** | Setup Installer (`.exe`) | [📥 Download Windows Installer](https://github.com/iamtashanto/screenshothub-releases/releases/latest/download/ScreenshotHub-Setup-1.0.4.exe) |
| **🪟 Windows (Portable)** | Standalone Portable (`.zip`) | [📥 Download Windows Portable ZIP](https://github.com/iamtashanto/screenshothub-releases/releases/latest/download/ScreenshotHub-1.0.4-win.zip) |
| **🐧 Linux (Debian / Ubuntu)** | Debian Package (`.deb`) | [📥 Download Linux .deb](https://github.com/iamtashanto/screenshothub-releases/releases/latest/download/screenshothub_1.0.4_amd64.deb) |
| **🐧 Linux (Universal)** | Standalone AppImage (`.AppImage`) | [📥 Download Linux AppImage](https://github.com/iamtashanto/screenshothub-releases/releases/latest/download/ScreenshotHub-1.0.4.AppImage) |

> 💡 *Looking for older versions or checksums? Browse all builds on our [GitHub Releases Page](https://github.com/iamtashanto/screenshothub-releases/releases).*

---

## ✨ Key Features

- 🚀 **Ultra-Low Resource Footprint**: Optimized with modern hardware acceleration, background memory trimming, and zero telemetry.
- 🎯 **Multi-Monitor & Window Snapping**: Capture full screens, selected display areas, or specific application windows instantly.
- 🎨 **Rich Annotation Suite**: Built-in arrows, numbered step badges, blur/pixelate tool for sensitive data, shapes, text, and highlighter.
- 📋 **Step-by-Step SOP Guide Creator**: Build sequential visual walkthroughs and developer documentation in minutes.
- ⌨️ **Global Background Hotkeys**:
  - `⌥ / Alt + Shift + 1`: Snipping tool (Interactive drag region)
  - `⌥ / Alt + Shift + 2`: Capture Active Window
  - `⌥ / Alt + Shift + 3`: Capture Entire Screen
  - `⌥ / Alt + Shift + 5`: Delayed Timer Capture
- ☁️ **Instant Cloud Sync & Share**: Generate secure, short public links in one click via [ss.tashanto.com](https://ss.tashanto.com).

---

## 🍏 macOS Setup Guide (First Launch)

Because ScreenshotHub is distributed independently without the Mac App Store sandbox limitations:

1. **Gatekeeper Notice**:
   If macOS displays *"ScreenshotHub cannot be opened because Apple cannot check it for malicious software"*:
   - Open **System Settings** → **Privacy & Security**.
   - Scroll down to the Security section and click **"Open Anyway"**.
   - *Alternatively, run `xattr -cr /Applications/ScreenshotHub.app` in your Terminal.*

2. **Screen Recording Permission**:
   - macOS requires explicit permission for screenshot tools.
   - Go to **System Settings** → **Privacy & Security** → **Screen Recording**.
   - Toggle **ON** for **ScreenshotHub**.

---

## 🌐 Official Links

- 🌍 **Website**: [https://ss.tashanto.com](https://ss.tashanto.com)
- 📦 **Releases Repository**: [iamtashanto/screenshothub-releases](https://github.com/iamtashanto/screenshothub-releases)
- 👨‍💻 **Author**: [Md Tanvir Ahamed Shanto (@iamtashanto)](https://github.com/iamtashanto)

---

<div align="center">
  <sub>Built with ❤️ by <a href="https://github.com/iamtashanto">Tanvir Ahamed Shanto</a>. All rights reserved.</sub>
</div>
