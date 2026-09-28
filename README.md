# TetherLink

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows%2010%2F11%20%7C%20Linux-blue?style=flat-square" alt="Platform" />
  <img src="https://img.shields.io/badge/Engine-v1.1.0-brightgreen?style=flat-square" alt="Version" />
  <img src="https://img.shields.io/badge/Status-Stable%20Release-orange?style=flat-square" alt="Status" />
</p>

High-speed, zero-leak USB tethering engine designed to bypass mobile carrier hotspot throttling and reduce latency for gaming and heavy workloads.

---

### ⚡ Quick Start
* 🚀 **[Download Latest Release (v1.1.0)](../../releases)** — Standalone binaries for Windows & Linux

---

### 📊 Verified Real-World Benchmarks

<p align="center">
  <img width="640" height="459" alt="TetherLink Gigabit Benchmark" src="https://github.com/user-attachments/assets/025140dc-516b-4da8-b035-f8027a516a49" />
</p>

* **Gigabit Line Speed & Low Latency**: Tested at **1,089.49 Mbps** download / **105.12 Mbps** upload with **23ms ping**.
* **Zero Hotspot Metering**: Verified with **94.76 GB** of continuous heavy traffic (**0.00 GB** hotspot deducted on carrier account).
* **Multi-Stream Load Stability**: Sustained **213.34 MB/s** simultaneous parallel transfers without connection drops or throttling.

---

### 🪟 Windows Setup (GUI)

> **Zero Complex Setup**: Standalone native client with embedded TUN driver and auto-routing.

1. Enable **USB Debugging** on your phone *(Keep system "USB Tethering" OFF)*.
2. Connect USB cable, allow the prompt, and tap **Start** in the Android app.
3. Launch `TetherLink.exe` and click **Connect TetherLink**.
4. *(Optional)* Keep `Keep Phone Screen Awake` checked to prevent OS-level USB bus throttling.

---

### 🐧 Linux Setup (CLI)

> **Zero Prerequisites**: Fully standalone bridging engine bundled. No external packages (`adb`) required.

1. Enable **USB Debugging** on your phone *(Keep system "USB Tethering" OFF)*.
2. Run installation:
   ```bash
   chmod +x TetherLink_Installer.run
   sudo ./TetherLink_Installer.run



---

 <img width="1338" height="409" alt="debian-linux-cli" src="https://github.com/user-attachments/assets/ab94ba6d-a073-4ea0-98ea-757b1342b9d4" />
<img width="640" height="258" alt="parallel-downloads-213mb" src="https://github.com/user-attachments/assets/a07acfe8-569a-442c-bc51-ff4cdbdedc42" />
<img width="586" height="254" alt="att-usage-95gb" src="https://github.com/user-attachments/assets/c92d9baa-8aff-4eb1-9c4a-c98600141f1f" />

