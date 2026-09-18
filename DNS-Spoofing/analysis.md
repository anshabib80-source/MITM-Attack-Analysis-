# 🟠 DNS Spoofing Analysis

## 1. Overview

DNS (Domain Name System) translates domain names into IP addresses.

DNS Spoofing is a technique where an attacker attempts to provide a false DNS response so that a domain resolves to an unintended destination.

---

## 2. Lab Objective

The objective of this part of the lab was to understand how DNS communication can be manipulated in a MITM scenario and how DNS traffic can be analyzed.

---

## 3. Traffic Analysis

During the lab, DNS requests and responses were inspected to understand the communication between the client and DNS infrastructure.

The analysis focused on identifying the relationship between:

* DNS queries
* DNS responses
* Requested domain names
* Returned IP addresses

---

## 4. Observations

During the practical analysis, I examined DNS traffic and observed how DNS responses can affect the destination associated with a requested domain.

---

## 5. Security Perspective

Unexpected DNS responses or unexpected changes in DNS resolution can be indicators of suspicious network activity.

A security analyst can investigate DNS traffic to identify abnormal responses and potential redirection.

---
## 6. Evidence

### Evidence 1 — DNS Response Filter

The following screenshot shows the use of the `dns.flags.response==1 && dns.qry.name==` filter during the traffic analysis.

![Ethernet Source Filter](./DNS-Response Filter)

## 7. Key Takeaways

* DNS translates domain names into IP addresses.
* DNS communication can be abused in MITM scenarios.
* DNS traffic can provide useful indicators during network investigations.
* Monitoring DNS behavior can help identify suspicious activity.
