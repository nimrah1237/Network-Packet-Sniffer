# Network Packet Sniffer

## 📌 Overview
This project is a **professional Network Packet Sniffer** developed using **Python** and **Scapy**.  
It captures live network traffic such as **TCP, UDP, ARP, ICMP, DNS**, and other non-IP packets,  
and automatically saves them into a `.pcapng` file for later analysis in **Wireshark**.

This was completed as part of my **CodeAlpha Internship**.

---

## ✨ Features
- Real-time packet capture for multiple protocols.
- Shows captured packets instantly in the command line.
- Automatically saves packets to `.pcapng` format.
- Compatible with Wireshark for deep packet analysis.
- Organized folder structure for professional reporting.

---

## 📂 Folder Structure                                                                                                                                                                                                      
NetworkSniffer_Report/
│
├── docs/ # Project documentation & analysis report
├── pcaps/ # Captured packet files (.pcapng)
├── screenshots/ # Screenshots of packet analysis
└── scripts/ # Python scripts for packet capturing
---

## 🛠 Requirements
- Python 3.x
- Scapy
- Wireshark

Install Scapy:
```bash
pip install scapy

---
▶️ Usage
1.Open a terminal in the scripts folder.

2.Run the sniffer:python network_sniffer.py
3.Press Ctrl + C to stop capturing.

4.The .pcapng file will be saved automatically in the pcaps folder.

5.Open the file in Wireshark to analyze.

🧑‍💻 Author
Nimrah
Internship Project at CodeAlpha
Date: 9 August 2025
