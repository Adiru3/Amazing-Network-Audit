# ANA - Amazing Network Audit

![Version](https://img.shields.io/badge/version-1.1-blue.svg)
![.NET Framework](https://img.shields.io/badge/.NET%20Framework-4.0-green.svg)
![License](https://img.shields.io/badge/license-MIT-orange.svg)

**ANA (Amazing Network Audit)** is a comprehensive, single-file C# network diagnostic tool that performs deep OSI model layer analysis from Layer 1 (Physical) to Layer 7 (Application). 

**NEW in v1.1**: Now features a dedicated **Packet Analysis Mode** (similar to Wireshark/Etherape) for real-time traffic monitoring!

---

## 🌟 Features

### Core Functionality

#### **Packet Analysis Mode (Wireshark-lite)** 🔍
- **Real-time Sniffing**: Capture TCP/UDP/ICMP packets using Raw Sockets.
- **Filter Builder**: Easy-to-use constructor to filter by Protocol (TCP, UDP) or IP address.
- **Dark Grid UI**: High-contrast, readable packet list with dark styling.
- **Details**: View Time, Source, Destination, Protocol, and Length of every packet.

#### **Automatic Administrator Elevation** 🔐
- **Auto-requests administrator privileges** on startup via UAC prompt
- Ensures full access to low-level network APIs and Raw Sockets.

#### **OSI Model Layer Auditing**
- **L1-L2**: Adapter status, Link speed, Wi-Fi deep scanning (Signal/Quality/Channels).
- **L3-L4**: Routing logic, Gateway ping, MTU fragmentation check, TCP retransmission stats.
- **L7**: DNS latency check (Google, Cloudflare, Quad9), Web Port (80/443) checks.

### User Interface

#### **Modern Dark UI** 🎨
- **Cyberpunk Theme**: Neon accents on dark backgrounds (no blinding white screens).
- **Dual Modes**: Switch between **Audit** (Health Check) and **Analysis** (Packet Sniffer) tabs.
- **Multilingual**: Instant switching between **English**, **Russian**, **Ukrainian**, and **Turkish**.

#### **Rich Reporting**
- Generates self-contained HTML reports with beautiful CSS animations.
- Reports are saved locally and accessible via the **History** sidebar.

---

## 🚀 Usage

### 1. Run Audit
- Click **RUN AUDIT** to perform a health check.
- View the generated HTML report for issues and optimization tips.

### 2. Run Packet Analysis
- Switch to the **ANALYSIS** tab.
- Select your Network Interface from the dropdown.
- Click **START** to begin sniffing.
- Use **Filters** to narrow down traffic (e.g., "TCP" or "192.168.1.1").

---

## 🔗 Connect with me
[![YouTube](https://img.shields.io/badge/YouTube-@adiruaim-FF0000?style=for-the-badge&logo=youtube)](https://www.youtube.com/@adiruaim)
[![TikTok](https://img.shields.io/badge/TikTok-@adiruhs-000000?style=for-the-badge&logo=tiktok)](https://www.tiktok.com/@adiruhs)

### 💰 Legacy Crypto
* **BTC:** `bc1qflvetccw7vu59mq074hnvf03j02sjjf9t5dphl`
* **ETH:** `0xf35Afdf42C8bf1C3bF08862f573c2358461e697f`
* **Solana:** `5r2H3R2wXmA1JimpCypmoWLh8eGmdZA6VWjuit3AuBkq`
* **USDT (TRC20):** `TNgFjGzbGxztHDcSHx9DEPmQLxj2dWzozC`
* **USDT (TON):** `UQC5fsX4zON_FgW4I6iVrxVDtsVwrcOmqbjsYA4TrQh3aOvj`

### 🌍 Support Links
[![Donatello](https://img.shields.io/badge/Support-Donatello-orange?style=for-the-badge)](https://donatello.to/Adiru3)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-Support-blue?style=for-the-badge&logo=kofi)](https://ko-fi.com/adiru)

[![Steam](https://img.shields.io/badge/Steam-Trade-blue?style=for-the-badge&logo=steam)](https://steamcommunity.com/tradeoffer/new/?partner=1124211419&token=2utLCl48)
