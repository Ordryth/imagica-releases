<div align="center">

<img src="assets/logo.png" alt="Imagica Desktop Logo" width="120" style="border-radius: 20px;" />

# Imagica Desktop

**High-Performance Local AI Creative Studio with RapidRAW Lumetri Suite**

[![Release](https://img.shields.io/github/v/release/Ordryth/imagica-releases?color=blue&label=version)](https://github.com/Ordryth/imagica-releases/releases/latest)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-brightgreen)](https://github.com/Ordryth/imagica-releases/releases/latest)
[![License](https://img.shields.io/badge/license-Apache%202.0-orange)](LICENSE)
[![Local Inference](https://img.shields.io/badge/inference-100%25%20Local%20%26%20Private-purple)]()

[**Download Latest Release**](https://github.com/Ordryth/imagica-releases/releases/latest) • [**Website**](https://imagica.co.in) • [**Documentation**](https://imagica.co.in/docs)

</div>

---

## 🚀 Overview

**Imagica Desktop** is a modern, privacy-focused desktop application for AI-powered digital art and creative image generation. Powered by Tauri and Rust, it provides maximum hardware efficiency, instant startup times, and minimal memory overhead.

All AI models and inference engines run **100% locally** on your device with hardware acceleration (CUDA, Apple Metal, DirectML). Your prompts, creative assets, and generated images never leave your machine.

---

## 📥 Downloads (v0.1.7)

Download the pre-compiled installer for your operating system:

| Platform | Architecture | Package | Direct Download Link |
| :--- | :--- | :--- | :--- |
| 🪟 **Windows** | x64 (64-bit) | Setup (.exe) | [**Download Windows (.exe)**](https://github.com/Ordryth/imagica-releases/releases/download/v0.1.7/Imagica.Desktop_0.1.7_x64-setup.exe) |
| 🪟 **Windows** | x64 (Enterprise) | MSI (.msi) | [**Download Windows (.msi)**](https://github.com/Ordryth/imagica-releases/releases/download/v0.1.7/Imagica.Desktop_0.1.7_x64_en-US.msi) |
| 🍏 **macOS** | Apple Silicon (M1–M4) | DMG (.dmg) | [**Download macOS Apple Silicon (.dmg)**](https://github.com/Ordryth/imagica-releases/releases/download/v0.1.7/Imagica.Desktop_0.1.7_aarch64.dmg) |
| 🍏 **macOS** | Intel (x64) | DMG (.dmg) | [**Download macOS Intel (.dmg)**](https://github.com/Ordryth/imagica-releases/releases/download/v0.1.7/Imagica.Desktop_0.1.7_x64.dmg) |
| 🐧 **Linux** | Universal | AppImage | [**Download Linux (.AppImage)**](https://github.com/Ordryth/imagica-releases/releases/download/v0.1.7/Imagica.Desktop_0.1.7_amd64.AppImage) |
| 🐧 **Linux** | Debian / Ubuntu | DEB (.deb) | [**Download Debian/Ubuntu (.deb)**](https://github.com/Ordryth/imagica-releases/releases/download/v0.1.7/Imagica.Desktop_0.1.7_amd64.deb) |

---

## ✨ Features

- **⚡ Native Hardware Acceleration:** Direct integration with NVIDIA CUDA, Apple Metal (MPS), and Microsoft DirectML for lightning-fast local generation.
- **🎨 RapidRAW Lumetri Suite:** Professional color grading engine featuring tone curves, exposure adjustment, selective color shifts, and cinematic presets.
- **🖼️ Infinite Imagine Canvas:** Node-based creative workspace for effortless image generation, inpainting, outpainting, and multi-layer compositing.
- **🤗 Hugging Face Hub Integration:** Seamlessly browse, download, and manage your favorite open-weights models and LoRAs locally.
- **🔒 Zero Data Telemetry:** 100% offline-ready. No accounts required, no hidden tracking, and no external API dependencies.

---

## 🛠️ Installation Instructions

### Windows
1. Download `Imagica.Desktop_0.1.7_x64-setup.exe`.
2. Double-click the installer and follow the setup wizard.
3. Launch **Imagica Desktop** from your Start menu or Desktop shortcut.

### macOS (Apple Silicon M1/M2/M3/M4 & Intel)
1. Download `Imagica.Desktop_0.1.7_aarch64.dmg` (for Apple Silicon) or `Imagica.Desktop_0.1.7_x64.dmg` (for Intel).
2. Open the disk image and drag **Imagica Desktop** into your **Applications** folder.
3. If macOS shows *"Imagica Desktop is damaged and can't be opened"*, open **Terminal** and run:
   ```bash
   xattr -cr "/Applications/Imagica Desktop.app"
   ```
   *(Or go to **System Settings** > **Privacy & Security** and click **Open Anyway**).*

### Linux (One-Line Universal Installer)
Run in terminal (supports Ubuntu, Debian, Fedora, Arch, and more):
```bash
curl -fsSL https://imagica.co.in/install.sh | bash
```

Or run manual packages:
#### AppImage:
```bash
chmod +x Imagica.Desktop_0.1.7_amd64.AppImage
./Imagica.Desktop_0.1.7_amd64.AppImage
```

#### Ubuntu / Debian:
```bash
sudo dpkg -i Imagica.Desktop_0.1.7_amd64.deb
```

---

## 📋 System Requirements

| Specification | Minimum | Recommended |
| :--- | :--- | :--- |
| **OS** | Windows 10 (64-bit), macOS 12+, Ubuntu 20.04+ | Windows 11, macOS 14+, modern Linux |
| **CPU** | Quad-core x86_64 or Apple Silicon M1 | 8-core CPU or Apple M2/M3/M4 |
| **RAM** | 8 GB | 16 GB or more |
| **Storage** | 2 GB free space | 10 GB+ SSD free space (for models) |
| **GPU** | DirectX 12 / Metal / Vulkan capable | NVIDIA RTX 3060+ (8GB+ VRAM) or Apple Silicon |

---

## 📄 License

This project is distributed under the [Apache License 2.0](LICENSE).
