# SOC Network Security Lab

This project demonstrates basic cybersecurity analysis using Nmap and Wireshark to analyze a local network.

---

## Tools Used
- Nmap
- Wireshark

---

## Steps Performed

1. Performed network scan:
   nmap -sS -sV 192.168.100.1

2. Identified open ports and services

3. Captured live traffic using Wireshark

4. Analyzed TCP packets and connection behavior

---


## Findings

- Detected multiple open ports:
  - Port 21 (FTP) → Potential security risk if not secured
  - Port 22 (SSH) → Possible brute force target
  - Port 80 (HTTP) → Unencrypted communication

- HTTP service showed redirection behavior
  → Indicates possible insecure configuration

- Wireshark analysis revealed abnormal TCP behavior:
  - RST, ACK packets detected
  - Frequent connection drops

  → This may indicate firewall filtering or failed connections

---

## Recommendations

- Disable or secure FTP service
- Use SSH key authentication
- Replace HTTP with HTTPS
- Monitor unusual TCP traffic
- Apply firewall rules

---

## Status

Completed beginner SOC project
