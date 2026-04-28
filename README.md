# Penetration Test Engagement – Internal Lab Environment

##  Engagement Overview
This repository contains a **sanitized summary and supporting deliverables** from a penetration testing assessment conducted on a Linux-based web application server within a controlled internal lab environment.

The objective of the engagement was to identify security vulnerabilities, validate their impact through controlled exploitation, and assess the overall security posture of the system.

---

##  Scope
- Target: Linux Web Application Server  
- Target IP: 172.20.10.3  
- Network: Internal Lab Network (172.20.10.0/24)  
- Applications: WordPress, phpMyAdmin  

---

##  Methodology
The assessment followed industry-recognized practices aligned with:
- **PTES (Penetration Testing Execution Standard)**  
- **OWASP Testing Guide**

Phases included:
- Reconnaissance  
- Scanning & Enumeration  
- Vulnerability Analysis  
- Exploitation  
- Post-Exploitation  
- Data Validation & Reporting  

---

##  Tools & Technologies
- arp-scan  
- Nmap  
- FTP  
- SMBClient  
- DirBuster  
- WPScan  
- Hydra  
- ExploitDB (searchsploit)  
- Metasploit Framework (msfconsole)  
- Meterpreter  
- phpMyAdmin  
- Web Browser  
- Linux CLI Tools  
- Kali Linux  

---

##  Key Findings
- Misconfigured FTP service allowing unauthorized access  
- SMB share exposure with insufficient access control  
- Weak authentication enabling brute-force attacks  
- Exposure of administrative web interfaces  
- Insecure file upload leading to Remote Code Execution (RCE)  
- Exploitable vulnerabilities resulting in full system compromise  
- Privilege escalation to root-level access  
- Unauthorized database access via phpMyAdmin  
- Lack of security logging and monitoring mechanisms  

---

##  Risk Summary
| Severity | Count |
|----------|------|
| Critical | 4    |
| High     | 2    |
| Medium   | 2    |
| Low      | 1    |

---


##  Ethics & Disclosure
All testing activities were conducted in a **controlled and authorized lab environment**.  
Sensitive details have been sanitized prior to public sharing.

---


##  Author
**Fawaz Abdul Azeez**  
Cybersecurity Student
