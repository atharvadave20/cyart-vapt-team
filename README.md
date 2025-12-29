# PTES-Based Vulnerability Assessment & Penetration Testing (VAPT)

## 📌 Project Overview
This repository documents a complete Vulnerability Assessment and Penetration Testing (VAPT) engagement conducted in a controlled lab environment using the Penetration Testing Execution Standard (PTES).

The objective of this project was to identify vulnerabilities, validate exploitability, assess risk, and demonstrate the impact of security weaknesses through controlled exploitation.

---

## 🎯 Target Information
- **Target System:** Metasploitable2
- **IP Address:** 192.168.227.129
- **Operating System:** Ubuntu 8.04 (Hardy Heron)
- **Application Tested:** Damn Vulnerable Web Application (DVWA)
- **Environment:** Internal Lab

---

## 🛠 Tools & Technologies
- Nmap
- OpenVAS
- Metasploit Framework
- sqlmap
- Kali Linux

---

## 🧪 Methodology (PTES)
The engagement followed the Penetration Testing Execution Standard (PTES):

1. Pre-Engagement Interactions
2. Intelligence Gathering
3. Threat Modeling
4. Vulnerability Analysis
5. Exploitation
6. Post-Exploitation
7. Reporting
8. Remediation

---

## 🔍 Key Findings Summary
- SQL Injection vulnerability in DVWA allowing database extraction
- Weak password hashing (MD5) leading to credential compromise
- Remote command execution via vulnerable distcc service
- Privilege escalation through misconfigured SUID binary
- Full system compromise with root-level access achieved

---

## 📂 Repository Structure
Week-2/
├── 01-Planning/
├── 02-Reconnaissance/
├── 03-Vulnerability-Assessment/
├── 04-Exploitation/
├── 05-Post-Exploitation/
├── 06-Reporting/


---

## 📄 Reporting
- Detailed vulnerability findings are documented in the OpenVAS report
- Exploitation and post-exploitation steps are included in respective directories
- A complete PTES-aligned VAPT report is available in the Reporting section

---

## ⚠️ Disclaimer
This project was conducted strictly in a controlled lab environment for educational purposes. No unauthorized testing was performed on production systems.

---

## 👤 Author
**Atharva Dave**  
Cybersecurity / VAPT Enthusiast

