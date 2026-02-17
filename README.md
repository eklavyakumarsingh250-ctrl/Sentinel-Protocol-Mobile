 🛡️ Sentinel Protocol: Mobile-Native Security Layer
> **Institutional-grade smart contract auditing, optimized for mobile devices.**

![License](https://img.shields.io/badge/License-MIT-green.svg)
![Platform](https://img.shields.io/badge/Platform-Termux%20%7C%20Linux-blue.svg)
![Status](https://img.shields.io/badge/Status-Beta-orange.svg)

**Sentinel** is a lightweight, mobile-first security tool designed to detect **Honeypots**, **Rug Pulls**, and **Malicious Opcodes** on the BNB Chain. Unlike traditional auditors that require heavy desktop environments, Sentinel runs natively on **Termux**, allowing traders and developers to audit contracts *on the fly* from their phones.

---

## ⚡ Key Features
* **🕵️‍♂️ Honeypot Detection:** Simulates buy/sell transactions to check for trapped liquidity.
* **📱 Mobile-Native:** Optimized for Termux (Android) with low resource consumption.
* **🚨 Opcode Scanner:** Scans bytecode for malicious functions (e.g., `transfer` disable).
* **📉 Liquidity Analysis:** Checks LP lock status and top holder distribution.

---

## 🚀 Installation (Termux / Linux)

No complex setup required. Just copy-paste these commands:

```bash
# 1. Update & Install Dependencies
pkg update && pkg upgrade -y
pkg install python git -y

# 2. Clone the Repository
git clone [https://github.com/eklavyakumarsingh250-ctrl/Sentinel-Protocol-Mobile.git](https://github.com/eklavyakumarsingh250-ctrl/Sentinel-Protocol-Mobile.git)
cd Sentinel-Protocol-Mobile

# 3. Install Python Libraries
pip install -r requirements.txt

# 4. Run Sentinel
python sentinel_lite.py
