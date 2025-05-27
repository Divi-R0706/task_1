# task_1
# 🔍 Local Network Port Scanning with Nmap
This project demonstrates how to perform basic network reconnaissance using **Nmap** to scan your **local network** for open ports and services. The goal is to understand network exposure and identify potential vulnerabilities.
## 📌 Objective
- Discover devices on your local network
- Identify open ports and running services
- Learn about common vulnerabilities and security risks
----------
## 🧰 Tools Used
- [Nmap](https://nmap.org/) – Network scanning and discovery tool
- [Wireshark](https://www.wireshark.org/) *(optional)* – For packet analysis
-----------
## 🖥️ Environment
- OS: Kali Linux (or any Linux distro)
- Interface: `eth0`
- IP Address: `192.168.40.129`
- Subnet: `255.255.255.0` → CIDR: `/24`
------------
## 🧭 Steps Followed
### 1. ✅ Installed Nmap
sudo apt update && sudo apt install nmap
-------
Found My Local IP and Subnet
ifconfig
IP: 192.168.40.129
Subnet: 255.255.255.0 → Network: 192.168.40.0/24
🚀 Ran TCP SYN Scan on Local Network
sudo nmap -sS 192.168.40.0/24


