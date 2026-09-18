# 🕵️ MITM Lab — Network Deception

## 📌 Overview

This project documents my hands-on investigation of **Man-in-the-Middle (MITM)** attack techniques in a controlled cybersecurity lab environment.

The lab focused on analyzing how network communication can be intercepted or manipulated and how defenders can identify suspicious network activity.

---

## 🎯 Topics Covered

* ARP Spoofing
* DNS Spoofing
* TLS/SSL Traffic Analysis
* Network Traffic Analysis
* MITM Detection
* Defensive Measures

---

## 🔴 ARP Spoofing

ARP Spoofing is a technique that can manipulate the relationship between IP addresses and MAC addresses on a local network.

During the lab, I analyzed network traffic and examined Ethernet and ARP-related communication.

### Evidence

📁 [View ARP Spoofing Evidence](./ARP-Spoofing)

---

## 🟠 DNS Spoofing

DNS Spoofing involves manipulating DNS responses to redirect a domain name toward an unintended destination.

During the lab, I analyzed DNS requests and responses to understand how suspicious DNS behavior can be investigated.

### Evidence

📁 [View DNS Spoofing Evidence](./DNS-Spoofing)

---

## 🔵 TLS / SSL Analysis

TLS provides encryption and authentication mechanisms that help protect network communication.

During the lab, I analyzed TLS/SSL-related traffic and explored the visibility of encrypted network communication.

### Evidence

📁 [View TLS/SSL Evidence](./TLS-SSL)

---

## 🔍 Detection Perspective

Potential indicators of MITM activity can include:

* Unexpected ARP behavior
* Changes in IP-to-MAC relationships
* Suspicious DNS responses
* Unusual network traffic
* TLS or certificate anomalies

Network traffic analysis can help security analysts investigate these indicators.

---

## 🛡️ Defensive Measures

Some defensive measures include:

* Using HTTPS and secure protocols
* Validating TLS certificates
* Monitoring ARP behavior
* Monitoring DNS traffic
* Network segmentation
* Investigating unusual network activity

---

## 📚 What I Learned

Through this lab, I strengthened my understanding of:

* Man-in-the-Middle attacks
* ARP Spoofing
* DNS Spoofing
* TLS/SSL
* Network traffic analysis
* Attack indicators
* Basic defensive techniques

---

## 🧪 Lab Environment

The practical exercises were performed in a controlled **TryHackMe learning environment** for educational purposes.

---

## ⚠️ Disclaimer

This project is intended for educational purposes only.

All practical activities were performed within a controlled lab environment. No unauthorized systems or real-world networks were targeted.

