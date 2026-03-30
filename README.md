SOC Network Traffic Analysis Lab

 Objective

This project demonstrates basic SOC skills by analyzing network traffic and detecting potential reconnaissance activity.

⸻

 Tools Used
	•	Nmap
	•	Wireshark

⸻

 Steps

1. Network Scan
2. nmap -sS -sV 192.168.100.1
3. 2. Packet Capture

Captured network traffic using Wireshark.

3. Analysis

Analyzed packets to identify protocols and suspicious patterns.

⸻

 Findings
	•	Open ports detected (HTTP, HTTPS)
	•	TCP SYN packets observed
	•	DNS and ARP traffic identified

⸻

 Detection

The observed traffic indicates port scanning activity, which is part of the reconnaissance phase of a cyber attack.

⸻

 Recommendations
	•	Close unused ports
	•	Use firewall
	•	Monitor network traffic

⸻

 Screenshots
Nmap :
https://github.com/blueabeer/soc-network-project/blob/main/fg2.png
https://github.com/blueabeer/soc-network-project/blob/main/fg3.png
https://github.com/blueabeer/soc-network-project/blob/main/fg4.png
https://github.com/blueabeer/soc-network-project/blob/main/fg5.png

wireshark :
https://github.com/blueabeer/soc-network-project/blob/main/fg1.png


This behavior is a strong indicator of reconnaissance activity.
⸻

SYN Packets
This shows SYN scan activity.



Skills
- Network Scanning
- Packet Analysis
- Basic Threat Detection
⸻

Conclusion

This project shows how basic network monitoring can help detect early-stage cyber attacks.


