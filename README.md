<p align="center">
  <img src="https://raw.githubusercontent.com/raind4sher/delphi-linux/refs/heads/main/logo.png"width="500" />
</p>

# Delphi Linux
> A lightweight, performance-oriented Linux distribution tailored for the Lenovo Ideapad series.

[![Build Status](https://img.shields.io/badge/System-Stable-success?style=flat-square)](#)
[![Kernel](https://img.shields.io/badge/Kernel-6.x-blue?style=flat-square)](#)
[![Package Manager](https://img.shields.io/badge/Manager-Delman-informational?style=flat-square)](#)

---

## 🟢 Overview
Delphi Linux is a custom-engineered x86_64 distribution designed for efficiency and aesthetic minimalism. Built upon a streamlined Linux kernel and a custom `initramfs` from scratch, it provides a high-performance environment with a proprietary package management system.

## 🚀 Key Features
- **Optimized Boot:** Minimalist init process for near-instantaneous time-to-shell.
- **Delman (Delphi Manager):** A decentralized, GitHub-backed package management system.
- **Enhanced UI:** Optimized TTY environment featuring the Lunar ASCII framework and ANSI color-coded telemetry.
- **Hardware Synergy:** Specifically configured for Lenovo Ideapad Slim 3i compatibility.

## 📦 Package Management
Delphi utilizes **Delman**, a source-to-binary manager. It fetches pre-compiled static binaries directly from this repository's automated build system.

### Delman Usage
```bash
delman install <package_name>
