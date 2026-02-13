# 🛡️ TryHackMe Ethical Hacking Lab – FakeBank

## 📌 Project Overview

This lab was completed on TryHackMe as part of my ethical hacking training.

The scenario involved a fictional banking website where a customer’s account had a negative balance due to an unauthorized threat actor.

My objective was to investigate the web application, discover hidden directories, and identify how the manipulation occurred.

## 🖼️ Screenshots

### Dirb Scan Output
![Dirb Scan](Picture1.jpg)

---

## 🎯 Objective

- Perform web enumeration
- Identify hidden directories
- Discover vulnerable endpoints
- Understand how the balance manipulation occurred

---

## 🛠️ Tools Used

- Kali Linux Terminal
- Dirb (Web Content Scanner)
- Command Line Interface (CLI)

---

## 🔍 Enumeration Process

I began by scanning the target website using **Dirb**, a web content brute-forcing tool.

Target URL:

http://fakebank.thm

Command used:

dirb http://fakebank.thm

Dirb performed directory brute forcing and returned hidden paths within the web application.

---

## 🚨 Discovery

During the scan, Dirb identified a hidden endpoint:

http://fakebank.thm/bank-transfer

This endpoint allowed manipulation of the bank transfer functionality.

By accessing this hidden page, I was able to analyze how the balance was altered and reverse the negative amount.

---

## 🧠 Skills Demonstrated

- Web Enumeration
- Directory Brute Forcing
- Command Line Usage
- Web Application Investigation
- Understanding Web Vulnerabilities

---

## 🔐 Key Takeaway

This lab strengthened my understanding of how attackers discover hidden web directories and exploit insecure endpoints.

It reinforced the importance of:
- Proper access controls
- Securing hidden directories
- Preventing unauthorized transaction manipulation
