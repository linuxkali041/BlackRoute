# ⚡ BlackRoute VPN 
> **The Ultimate Privacy Shield for Windows** - Powered by Xray-core

<p align="center">
  <img src="https://img.shields.io/badge/Version-3.6.0%20Latest-success?style=for-the-badge&logo=windows" alt="Version 3.6.0">
  <img src="https://img.shields.io/badge/Platform-Windows%2010%2F11-blue?style=for-the-badge&logo=microsoft" alt="Platform">
  <img src="https://img.shields.io/badge/.NET-8.0-purple?style=for-the-badge&logo=dotnet" alt=".NET 8">
  <img src="https://img.shields.io/badge/License-Private-red?style=for-the-badge" alt="License">
</p>

---

## 📖 Overview

**BlackRoute** (internal codename *ZenithVPN*) is a cutting-edge, privacy-first VPN client designed for Windows. It combines the raw power of **Xray-core** (V2Ray/VLESS/VMess/Trojan) with a stunning, modern **WPF** interface featuring glassmorphism, smooth animations, and a premium dark theme.

Unlike standard VPN clients, BlackRoute offers granular control over your connection, advanced routing capabilities, and a suite of diagnostic tools to ensure your privacy is never compromised.

---

## ✨ Features (v3.6.0)

### 🎨 **Premium UI Experience**
- **AMOLED Dark Mode**: Fully optimized for modern displays with deep blacks and vibrant accents.
- **Glassmorphism**: Elegant transparency and blur effects.
- **Smooth Animations**: Fluid transitions and interactive elements.
- **Custom Window Chrome**: Borderless, shadow-enhanced window design.

### 🚀 **Next-Gen Connectivity**
- **Multi-Protocol Support**: VLESS, VMess, Trojan, Shadowsocks, SOCKS, HTTP.
- **Mux Turbo Stream**: Multiplexing technology to boost performance on high-latency networks.
- **Smart Routing (Split Tunneling)**:
  - **Domain Rules**: Bypass or proxy specific domains.
  - **App Mode**: Select specific applications to bypass the VPN.
- **Quic & UDP Optimization**: Accelerated transport for gaming and streaming.

### 🛡️ **Advanced Security Suite**
- **DNS Hijack Detector**: Verifies your DNS integrity against trusted DoH providers.
- **Privacy Leak Check**: Helper tool to detect WebRTC, DNS, and IPv6 leaks.
- **MTU Prober**: Automatically discovers optimal packet size for your network path.
- **Kill Switch**: System-level firewall rule management to prevent data leaks.
- **Secure DNS**: Built-in support for Cloudflare, Google, Quad9, AdGuard, and custom DoH.

### 📊 **Real-Time Monitoring**
- **Live Speed Test**: Integrated download, upload, and ping testing.
- **Connection Stats**: Beautiful dashboard for IP, location, and data usage.
- **Visual Logs**: Color-coded, real-time Xray core logs for debugging.

---

## 🛠️ Installation

### Prerequisites
- **OS**: Windows 10 or Windows 11 (64-bit).
- **Runtime**: [.NET 8.0 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0).
- **Core**: The application requires `xray.exe`, `geoip.dat`, and `geosite.dat` in the `Core/` directory.

### Quick Start
1. **Download** the latest release.
2. **Extract** the archive to a folder of your choice.
3. **Run** `BlackRoute.exe` (Run as Administrator recommended for full feature set).
4. **Import** a server config (Clipboard or File).
5. **Connect** and enjoy secure browsing.

---

## 📝 Roadmap

- [x] **v3.5.0**: Core stability, initial UI overhaul.
- [x] **v3.6.0**: Premium UI polish, Speed Test, Split Tunneling V2.
---

## 📜 Credits

- **Core Engine**: [Project X](https://github.com/XTLS/Xray-core)
- **UI Framework**: WPF (.NET 8)
- **Icons**: Fluent System Icons
- **Developed by**: [INFECTDx](https://t.me/INFECTDx).

---

> **Disclaimer**: This tool is intended for personal privacy protection and network research. Please use responsibly and in accordance with your local laws.
