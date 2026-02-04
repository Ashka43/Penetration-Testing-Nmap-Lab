# Penetration Testing Methodology

## 1. Lab Setup
Two virtual machines were configured using VirtualBox:
- Kali Linux as the attacker
- Metasploitable2 as the vulnerable target

## 2. Network Verification
IP addresses were identified to confirm both machines were on the same network.

## 3. Host Discovery
Nmap was used to verify that the target system was reachable.

## 4. Port Scanning
A full port scan was conducted to identify all open ports.

## 5. Service Enumeration
Service and version detection was performed to identify outdated or vulnerable software.

## 6. OS Detection
Operating system fingerprinting was conducted using Nmap.

## 7. Vulnerability Scanning
Nmap NSE scripts were used to identify known vulnerabilities and insecure configurations.
