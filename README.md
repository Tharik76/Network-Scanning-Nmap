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

## ⚠️ Disclaimer
This project was conducted in a safe and authorized lab environment for educational purposes only.

## 👨‍💻 Author
Mohamed Tharik
