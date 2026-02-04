# Penetration Testing Lab Using Nmap

## 📌 Overview
This project demonstrates a penetration testing and vulnerability assessment lab conducted in a controlled environment. The objective was to simulate attacker reconnaissance techniques and analyze security weaknesses using Nmap.

The lab follows a real-world penetration testing workflow, focusing on network discovery, service enumeration, OS detection, and vulnerability identification.

---

## 🛠 Tools & Technologies
- Kali Linux (Attacker Machine)
- Metasploitable2 (Vulnerable Target)
- Nmap
- VirtualBox
- Host Operating System: Windows

---

## 🧪 Lab Environment Setup
- Two virtual machines configured on the same virtual network
- Kali Linux used for scanning and enumeration
- Metasploitable2 used as an intentionally vulnerable system

---

## 🔍 Methodology
The following steps were performed during the penetration testing process:
1. Network connectivity verification
2. Host discovery
3. Full port scanning
4. Service and version detection
5. Operating system detection
6. Aggressive scanning
7. Vulnerability scanning using Nmap NSE scripts

---

## 📊 Key Findings
- Multiple open ports increasing attack surface
- Outdated and vulnerable services
- Insecure configurations such as open FTP and exposed SMB services
- High-risk services identified for potential exploitation
