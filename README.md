# TetherLink

<p align="center">
  <a href="https://tetherlink-team.github.io/TetherLink/"><img src="https://img.shields.io/badge/Website-Official%20Site-00FF66?style=flat-square&logo=googlechrome&logoColor=black" alt="Official Website" /></a>
  <img src="https://img.shields.io/badge/Platform-windows%2010%2F11%20%7C%20Linux-blue?style=flat-square" alt="Platform" />
  <img src="https://img.shields.io/badge/Mobile-Android%208%2B%20(No%20Root)-brightgreen?style=flat-square" alt="Mobile" />
  <img src="https://img.shields.io/badge/Engine-v1.1.3-blueviolet?style=flat-square" alt="Version" />
  <img src="https://img.shields.io/badge/status-Stable%20Release-orange?style=flat-square" alt="status" />
</p>

A high-performance Wintun-based L3 USB tethering bridge engineered for unthrottled PC connectivity, zero hotspot quota deduction, and ultra-low latency routing.

---

### ⚡ Quick Start
* 🌐 **[Official Website & Documentation](https://tetherlink-team.github.io/TetherLink/)** - Features, detailed guides & community
* 🚀 **[Download Latest Release (v1.1.4)](../../releases)** - Standalone packages for Windows, Linux & Android

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
4. (Optional) In the desktop client, keep **"Keep Phone Screen Awake (Prevents Throttling)"** checked to prevent OS-level USB bus sleep.

---

### 🐧 Linux Setup (CLI)

> **Zero Prerequisites**: Fully standalone bridging engine bundled. No external packages (`adb`) required.

1. Install TetherLink_Mobile_v1.1.1.apk on your phone and enable USB Debugging (Keep system "USB Tethering" OFF).
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

---

### 💡 Troubleshooting & Device Tips

* **OnePlus / Oppo / Realme (OxygenOS / ColorOS):**
  If throughput fluctuates or drops to kb/s, OnePlus aggressively throttles background network sockets.
  * Go to `Settings` → `Battery` → `Battery Optimization` (or `App Battery Management`).
  * Find **TetherLink** and set it to **"Don't optimize"** (Allow background activity).

* **Carrier 5G Tower Stability (T-Mobile / Verizon):**
  If speeds fluctuate wildly in low-band 5G areas (n71/n5), temporarily switching the phone's network mode to **"LTE/4G only"** can lock in stable latency and prevent carrier tower hopping.
