# SQL Injection Attack on DVWA (Web Exploitation Lab)

## 🧠 Overview
This project demonstrates a SQL injection attack on a vulnerable web application (DVWA).

The objective was to manipulate input fields to bypass intended query logic and retrieve unauthorized data from the database.

This showcases practical web exploitation skills including input testing, logic manipulation, and data extraction.

---

## ⚙️ Lab Environment

- Attacker: Kali Linux
- Target: Metasploitable (DVWA)
- Platform: VirtualBox
- Application: DVWA (Damn Vulnerable Web App)

---

## 🔎 Reconnaissance

The target application was accessed via browser:

http://192.168.56.103

DVWA was located and accessed through the web interface.

---

## 🧪 Initial Testing (Normal Input)

A normal query was tested:

```bash
User ID: 1
