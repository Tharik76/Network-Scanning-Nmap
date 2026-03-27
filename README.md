# 🛡️ Network Scanning & Information Gathering using Nmap

## 📌 Overview
This project demonstrates how to perform network scanning using Nmap in Kali Linux to discover live hosts, open ports, services, and vulnerabilities.

## 🎯 Objective
To understand the reconnaissance phase of cybersecurity attacks and how attackers gather information before launching an attack.

## 🛠 Tools Used
- Kali Linux
- Nmap

## 🌐 Network Details
- IP Address: 10.88.92.45
- Network Range: 10.88.92.0/24

## 🔍 Steps Performed

### 1. Host Discovery
nmap -sn 10.88.92.0/24

Discovered active devices in the network.

### 2. Port Scanning

nmap 10.88.92.192

Identified open ports.

### 3. Service Detection

nmap -sV 10.88.92.192

Detected running services and versions.

### 4. OS Detection

sudo nmap -O 10.88.92.192

Identified the operating system.

### 5. Full Scan

sudo nmap -A 10.88.92.192

Performed aggressive scanning including scripts and version detection.

### 6. Vulnerability Scan

sudo nmap --script vuln 10.88.92.192

Checked for possible vulnerabilities.

## 📊 Results
- Found 3 active devices in the network
- Identified open ports such as HTTP, SSH (based on scan)
- Detected services and versions
- Performed vulnerability assessment

## 🎓 Learning Outcomes
- Network mapping
- TCP/IP fundamentals
- Port scanning techniques
- Reconnaissance in cybersecurity

  ## 🔎 Key Observations
- Found 3 active devices in network
- Target device had open ports like 80 (HTTP)
- Service detection revealed web server running

  ## 🛡️ SOC Analyst Perspective
If an attacker performs scanning:
- Multiple connection attempts will appear in logs
- IDS/IPS systems can detect abnormal scanning activity
- Alerts may be triggered for port scanning behavior

  ## ✅ Conclusion
This project helped me understand how attackers perform reconnaissance and how security teams can detect scanning activity in real-world environments.

## ⚠️ Disclaimer
This project was conducted in a safe and authorized lab environment for educational purposes only.

## 👨‍💻 Author
Mohamed Tharik
