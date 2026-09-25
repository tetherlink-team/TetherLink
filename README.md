# TetherLink

Direct Hardware-Level USB Packet Pipeline for Ultra-Low Latency Carrier Limit Bypass.

TetherLink transforms your Android smartphone into a high-performance raw packet processing interface for Windows PC and Linux. Engineered from the ground up to eliminate bufferbloat, bypass carrier hotspot throttling, and deliver native gigabit-grade throughput without proxy overhead.

---

### 📥 Download & Official Links
* **Windows Client:** [Download TetherLink Setup v1.1.0 (.exe)](https://github.com/tetherlink-team/TetherLink/releases)
* **Linux CLI (Standalone):** [Download TetherLink CLI v1.0.0 (.run)](https://github.com/tetherlink-team/TetherLink/releases)
#### 🐧 Linux Quick Start
```bash
chmod +x tetherlink-linux-v1.0.0.run
sudo ./tetherlink-linux-v1.0.0.run
```
> To uninstall and flush routes: `sudo tetherlink-uninstall`
---

### Key Capabilities
* **Kernel-Level Packet Exchange**: Direct Layer-3 network translation delivering zero-latency packet transmission for competitive gaming.
* **Full UDP & Direct NAT Support**: Native compatibility with Steam downloads, Discord voice servers, and multiplayer matchmakers without traffic drops.
* **Carrier Throttling Bypass**: Seamlessly handles high-throughput traffic at the hardware transport layer without triggering mobile hotspot detection buckets.
* **Zero Thermal Throttling**: Low-power USB transport keeps your smartphone cool and charging, avoiding the battery degradation common with Wi-Fi proxies.
* **Zero-Fragmentation Protocol**: Intelligent dynamic packet optimization prevents transmission stalls during peak bandwidth utilization.
* **Zero Configuration**: Plug-and-play setup without requiring complex routing configurations.
* **Doze-Mode Bypass**: Integrated screen-awake control in the desktop client to prevent Android from cutting USB bus throughput during sleep.
* **Clean Process Lifecycle**: Automatic teardown hooks guarantee mobile background services terminate immediately when the PC client closes, ensuring zero battery drain.
  
### 🚀 Real-World Gaming Benchmark
![TetherLink Steam Download Benchmark - 127.6 Mbps Sustained Peak](https://github.com/user-attachments/assets/ef241c5f-88dc-494f-b2b3-9bfea5260dfd)

* **Test Environment**: Cellular LTE+ (4G LTE-A) connection via standard USB cable (no Wi-Fi).
* **Sustained Throughput**: Maintained **121.6+ Mbps** (Peak: **127.6 Mbps**) without packet drops, completely saturating the local carrier band.
* **5G / High-Bandwidth Ready**: C-native zero-copy pipeline capable of scaling seamlessly to 5G multi-hundred Mbps line rates.
* **Zero Thermal Throttling**: Low-power hardware transport keeps the phone completely cool and charging throughout the entire 20GB+ download session.

### Requirements

* **PC:** 
  * Windows 10 / 11 (64-bit)
  * Linux (x86_64, systemd-based distributions)
* **Mobile:** Android 8.0+ with USB Debugging enabled
* **Hardware:** Standard USB data cable

