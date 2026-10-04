# TetherLink

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows%2010%2F11%20%7C%20Linux-blue?style=flat-square" alt="Platform" />
  <img src="https://img.shields.io/badge/Engine-v1.1.2-brightgreen?style=flat-square" alt="Version" />
  <img src="https://img.shields.io/badge/status-Stable%20Release-orange?style=flat-square" alt="Status" />
</p>

A high-performance Wintun-based L3 USB network bridge engineered for ultra-low latency gaming, high-throughput data routing, and seamless mobile-to-PC connectivity.
---

### ⚡ Quick Start
* 🚀 **[Download Latest Release (v1.1.2)](../../releases)** - Standalone packages for Windows, Linux & Android

---

### 📊 Verified Real-World Benchmarks

<p align="center">
  <img width="640" height="459" alt="TetherLink Gigabit Benchmark" src="https://github.com/user-attachments/assets/025140dc-516b-4da8-b035-f8027a516a49" />
</p>

* **Gigabit Line Speed & Low Latency**: Tested at **1,089.49 Mbps** download / **105.12 Mbps** upload with **23ms ping**.
* **Zero Hotspot Metering**: Verified with **94.76 GB** of continuous heavy traffic (**0.00 GB** hotspot deducted on carrier account).
* **Multi-Stream Load Stability**: Sustained **213.34 MB/s** simultaneous parallel transfers without connection drops or throttling.

---

### 🌐 Confirmed Carrier Bypass

* **United States**: Verizon, AT&T, T-Mobile
* **France**: Bouygues Telecom
* **South Korea, India & Philippines**: Confirmed on major regional carriers
* **Rwanda**: Verified on local cellular network

---

### 🪟 Windows Setup (GUI)

> **Zero Complex Setup**: Standalone native client with embedded TUN driver and auto-routing.

1. Install `TetherLink_Mobile_v1.1.1.apk` on your phone and enable **USB Debugging** *(Keep system "USB Tethering" OFF)*.
2. Connect USB cable, allow the prompt, and tap **Start** in the mobile app.
3. Launch `TetherLink.exe` (or run installer) and click **Connect TetherLink Bridge**.
4. *(Optional)* Keep `Keep Phone Screen Awake` checked to prevent OS-level USB bus throttling.

---

### 🐧 Linux Setup (CLI)

> **Zero Prerequisites**: Fully standalone bridging engine bundled. No external packages (`adb`) required.

1. Enable **USB Debugging** on your phone *(Keep system "USB Tethering" OFF)*.
2. Run installation:
```bash
chmod +x TetherLink_Installer.run
sudo ./TetherLink_Installer.run
```
3. Launch TetherLink:
```bash
sudo tetherlink
```
*(To uninstall: `sudo /opt/tetherlink/uninstall.sh`)*
