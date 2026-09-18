# 🔵 TLS / SSL Traffic Analysis

## 1. Overview

TLS (Transport Layer Security) is used to protect network communication by providing encryption and authentication.

SSL is the predecessor to TLS and is considered obsolete compared with modern TLS versions.

---

## 2. Lab Objective

The objective of this part of the lab was to understand how TLS/SSL affects the visibility of network traffic during a MITM scenario.

---

## 3. Traffic Analysis

During the practical lab, encrypted network traffic was analyzed to understand what information can and cannot normally be observed when communication is protected by TLS.

---

## 4. Observations

The analysis demonstrated the difference between protected and unprotected network communication.

When TLS is properly used, the contents of the application communication are encrypted rather than being transmitted as readable application data.

---

## 5. Security Perspective

Encryption is an important defense against network interception because it helps protect the confidentiality and integrity of communication.

However, certificate validation and proper TLS configuration are also important when investigating potential MITM activity.

---

## 6. Evidence

The screenshots in this folder document the TLS/SSL traffic analysis performed during the lab.

---

## 7. Key Takeaways

* TLS protects network communication through encryption.
* Modern systems should use TLS rather than obsolete SSL protocols.
* Encrypted traffic changes what a network observer can directly inspect.
* Certificate-related anomalies can be relevant when investigating MITM attacks.
