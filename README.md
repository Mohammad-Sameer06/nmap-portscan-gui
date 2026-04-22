# Network Port Scanner GUI 🛡️

A high-performance, multi-threaded TCP port scanner featuring a professional graphical user interface. This project was developed to apply core network reconnaissance and security principles gained during my Cybersecurity Virtual Internship with the Vodafone Idea Foundation and Edunet Foundation.

## 📋 Overview

Understanding open ports and services is a fundamental step in network security auditing. This tool provides a clean, professional interface to identify active services on a target host efficiently. By integrating multi-threading, it allows for rapid scanning that mimics real-world security tools while remaining lightweight and dependency-free.

## ✨ Features

- **Multi-threaded Engine:** Supports up to 500 concurrent threads for near-instantaneous results across wide port ranges.
- **Service Mapping:** Automatically identifies and labels common services (SSH, FTP, HTTP, MySQL, RDP, etc.).
- **Professional UI:** A clean, minimal Tkinter interface featuring a real-time progress bar and elapsed-time tracking.
- **Session Management:** Ability to gracefully stop a running scan and export results to a `.txt` file for further analysis.
- **Cross-platform:** Fully compatible with Windows, macOS, and Linux environments.

## 🛠️ Technical Stack

- **Language:** Python 3.7+
- **GUI Framework:** Tkinter (Standard Library)
- **Networking:** Socket programming
- **Concurrency:** Threading module

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or newer.
- Tkinter (usually bundled with Python; on Linux, install via `sudo apt-get install python3-tk`).

### Installation

```bash
git clone https://github.com/techtrainer20/nmap_portscan_gui.git
cd nmap_portscan_gui
```

### Usage

```bash
python portscanergui.py
```

1. Enter the Target IP or Hostname.
2. Define the Start and End port range.
3. Click Start Scan to begin the reconnaissance process.

## 🛡️ Internship Context

This project serves as a practical implementation of the concepts explored during my March–April 2026 Cybersecurity Internship. It focuses on:

- Network layer communication and TCP handshakes.
- Identifying potential attack vectors through open ports.
- Automating security tasks to improve response times.

## ⚖️ License & Disclaimer

This project is released under the MIT License.

**Warning:** This tool is intended for educational purposes and authorized security testing only. Unauthorized scanning of networks is illegal and unethical. Use responsibly.

---

Developed by Mohammad Sameer  
2nd Year B.Tech Student in Computer Science & Engineering
