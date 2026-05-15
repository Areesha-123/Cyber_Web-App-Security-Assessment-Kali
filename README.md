 Web Application Security Assessment - Kali Linux

 📝 Project Overview
This repository contains a structured cybersecurity assessment report of a publicly accessible web target (**University of the Punjab**). The assessment was conducted using specialized security tools within **Kali Linux** to identify potential vulnerabilities, service exposures, and configuration weaknesses.
**Objective:** To demonstrate the practical application of penetration testing phases and provide actionable remediation strategies to enhance security posture.

🛠️Tools & Technologies Used
The assessment utilized a variety of tools across different phases of the penetration testing lifecycle:
* **Reconnaissance:** `Whois`, `nslookup`, `DNSenum`
* **Scanning & Enumeration:** `Nmap`, `SSLScan`, `WhatWeb`, `Wafw00f`
* **Web Analysis:** `Gobuster`, `WPScan`, `Skipfish`
* **Exploitation Research:** `Metasploit Framework`

## 🛡️ Assessment Methodology
The project followed a standard industry methodology:
1.  **Passive Reconnaissance:** Information gathering without direct interaction.
2.  **Active Scanning:** Direct interrogation of the target to find open ports and services.
3.  **Web Analysis:** Identifying hidden directories and CMS-specific vulnerabilities.
4.  **Risk Verification:** Assessing the impact of findings (No active exploitation was performed).
5.  **Remediation:** Developing security best practices based on findings.

## 📊 Key Findings & Risk Assessment
| Tool | Risk Level | Finding |
| :--- | :--- | :--- |
| **Nmap** | Medium | Detected 4 open ports and active services. |
| **SSLScan** | Medium | Identified weak SSL/TLS ciphers and outdated protocols. |
| **Gobuster** | Medium | Discovered sensitive directories such as `/admin` and `/uploads`. |
| **Skipfish** | Med-High | Identified potential XSS and Information Disclosure issues. |
| **WhatWeb** | Low | Fingerprinted tech stack: Apache and PHP 7.4.3. |

## 🚀 Remediation Recommendations
To mitigate the identified risks, the following actions are recommended:
* Disable weak/legacy SSL/TLS ciphers and enforce strict encryption.
* Close unnecessary open ports and services to reduce the attack surface.
* Harden DNS configurations to minimize public infrastructure exposure.
* Secure sensitive directories (e.g., `/admin`) with strong multi-factor authentication.
* Maintain a regular schedule for patching and security audits.

## ⚖️ Ethical Disclaimer
This project was conducted strictly for **educational purposes** on a legally authorized target. All activities adhered to ethical hacking principles and responsible disclosure guidelines. No unauthorized access or damage was caused.

 👤 Author
* **Areesha Raheel**
* **Date:** January 19, 2026
