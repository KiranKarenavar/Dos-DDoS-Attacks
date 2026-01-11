# 🚨 DoS & DDoS Attacks Lab – Cybersecurity Module 10

## 📌 Project Overview
This repository contains my **Cybersecurity Module 10 Lab Project** focused on **Denial of Service (DoS)** and **Distributed Denial of Service (DDoS)** attacks.  
The lab combines theoretical understanding with hands-on practice in a **controlled and ethical lab environment**.

The project covers attack concepts, types, tools, detection techniques, mitigation strategies, and traffic analysis.

---

## 🎯 Learning Objectives
- Understand DoS and DDoS attack concepts  
- Differentiate between DoS and DDoS attacks  
- Learn about botnets and their role in DDoS  
- Study various types of DoS/DDoS attacks  
- Gain hands-on exposure to attack tools  
- Understand detection and mitigation techniques  

---

## 🔐 DoS vs DDoS
| Feature | DoS | DDoS |
|------|----|----|
| Attack Source | Single system | Multiple systems |
| Power | Low to Moderate | Very High |
| Detection | Easier | Difficult |
| Example | Single attacker | Botnet-based |

---

## 🤖 Botnets
A **botnet** is a network of compromised devices controlled by an attacker (botmaster). These infected systems are commonly used to launch **large-scale DDoS attacks**, spam campaigns, and malware distribution.

**Key Characteristics:**
- Large-scale and globally distributed  
- Stealthy operation  
- Controlled using Command & Control (C2) servers  
- Frequently used in DDoS attacks  

**Example:** Mirai Botnet (IoT-based)

---

## ⚔️ Types of DoS/DDoS Attacks

### 1️⃣ Volumetric Attacks
- Flood target bandwidth with massive traffic  
- Measured in **bits per second (bps)**  

**Examples:**
- UDP Flood  
- ICMP Flood  
- Ping of Death  
- Smurf Attack  
- DNS Amplification  

---

### 2️⃣ Protocol Attacks
- Target **OSI Layer 3 & 4**  
- Measured in **packets per second (pps)**  

**Examples:**
- SYN Flood  
- ACK Flood  
- SYN-ACK Flood  
- Fragmentation Attacks  

---

### 3️⃣ Application Layer Attacks
- Target **OSI Layer 7**  
- Measured in **requests per second (rps)**  
- Mimic legitimate traffic  

**Examples:**
- HTTP GET/POST Flood  
- Slowloris Attack  
- UDP Application Flood  
- DDoS Extortion Attacks  

---

## 🛠️ All-in-One Tools Used (Lab Study)

> ⚠️ All tools were used strictly in a controlled lab environment for educational purposes.

1. **GoldenEye** – HTTP Flooding Tool  
2. **Slowloris** – Low bandwidth application-layer attack  
3. **Raven-Storm** – Multi-purpose DoS framework  
4. **Metasploit (Auxiliary SYN Flood)**  
5. **OWASP HTTP POST Tool**  
6. **XOIC** – Packet flooding tool  
7. **TorsHammer** – Tor-based slow POST attack  
8. **THC-SSL-DoS** – SSL exhaustion attack tool  
9. **HTTP DoS Tool (GUI-based)**  
10. **HOIC (High Orbit Ion Cannon)**  
11. **LOIC (Low Orbit Ion Cannon)**  
12. **Hping3** – Packet crafting and flooding  

---

### 🕵️ DoS/DDoS Detection Techniques

1. Traffic Volume Analysis
2. Rate-based Detection (RPS, PPS)
3. Behavioral Analysis
4. Signature-based Detection
5. Anomaly-based Detection
6. Source-based Detection
7. Protocol Analysis
8. Flow-based Detection
9. Entropy-based Detection
10. Machine Learning-based Detection

### Detection Tools:
1. Snort / Suricata
2. Wireshark
3. SIEM Solutions
4. Cloud-based Anti-DDoS Services

---

## 📊 Network Traffic Analysis

Network traffic was captured and analyzed using Wireshark.
Abnormal spikes in packets and requests were observed during attack simulations, confirming the impact of DoS/DDoS traffic.

---
## 👤 Author
**Kiran Karenavar**  
Cybersecurity / Ethical Hacking Student  

---

### ⚠️ Ethical Disclaimer

This project is conducted strictly for educational purposes.
All experiments were performed in a controlled lab environment.
Unauthorized DoS/DDoS attacks on real-world systems are illegal and unethical.

---

