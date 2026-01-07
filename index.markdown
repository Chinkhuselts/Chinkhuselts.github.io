---
layout: default
title: Chinkhuselts Cybersecurity Portfolio
---

# Welcome

I am a Cybersecurity enthusiast specializing in **Network Defense** and **Threat Analysis**. I build Security Simulation Environment to simulate real-world attacks and engineer defense strategies using industry-standard tools like Snort, Splunk/ELK, and Wireshark.

[📄 **Download My Resume**](./Resume.pdf){: .btn}

---

## 🛡️ Featured Projects

### 1. Snort NIDS: Enterprise-Grade Intrusion Detection
**Tech Stack:** Snort 2.9, Ubuntu 22.04, Nmap, VirtualBox

I designed and deployed a Network Intrusion Detection System (NIDS) to monitor live traffic and identify malicious patterns.
* **Defense:** Engineered custom rules that successfully detected 100% of simulated TCP SYN scans and ICMP floods.
* **Optimization:** Tuned configuration to reduce false positives by filtering known safe traffic.
* **Outcome:** Created a functional detection lab capable of logging and alerting on real-time threats.

*[View Project Repository](https://github.com/Chinkhuselts/snort2-nids-project)*

---

### 2. Network Traffic Forensics: Man-in-the-Middle Attack Analysis
**Tech Stack:** Wireshark, Arpspoof, SSH, Linux

Simulated and analyzed a Man-in-the-Middle (MitM) attack to understand ARP poisoning mechanics.
* **Attack:** Used `arpspoof` to intercept traffic between a victim and the gateway.
* **Analysis:** Captured packets with Wireshark to reconstruct the attack chain and identify compromised credentials.
* **Remote Management:** Managed the attack infrastructure securely via SSH tunneling.

*[View Project Repository](https://github.com/Chinkhuselts/wireshark-mitm-analysis)*

---

### 3. ELK & Snort SIEM Integration
**Tech Stack:** Elasticsearch, Logstash, Kibana, Snort

Built a mini-SIEM (Security Information and Event Management) pipeline to visualize network alerts.
* **Integration:** Piped Snort logs into the ELK stack for real-time indexing.
* **Visualization:** Created a Kibana dashboard to visualize attack frequency and geo-location of attackers.

*[View Project Repository](https://github.com/Chinkhuselts/elk-snort-siem-setup)*

---

### 4. Malware Analysis: WannaCry Ransomware
**Tech Stack:** CAPEv2 Sandbox, Windows 10 Guest

Conducted dynamic analysis of the WarCry ransomware in a hardened sandbox environment.
* **Sandboxing:** Configured CAPEv2 with a hardened Windows 10 VM to prevent VM-detection evasion.
* **Forensics:** Extracted IOCs (Indicators of Compromise) including C2 IP addresses and file hashes.

*[View Project Repository](https://github.com/Chinkhuselts/CAPEv2-Analysis)*

---

## 📫 Contact
* **Email:** husele1000@gmail.com
* **GitHub:** [github.com/Chinkhuselts](https://github.com/Chinkhuselts)
