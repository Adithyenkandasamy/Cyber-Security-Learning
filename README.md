# 🛡️ Cybersecurity & Ethical Hacking Roadmap (Developer Edition)

> **Goal:** Become a highly skilled Application Security Engineer / Penetration Tester / Red Teamer while staying a strong software developer.

## Rules
- Practice only on systems you own or are explicitly authorized to test.
- Build, break (in labs), fix, document, repeat.

---

# Phase 0 – Computer Science Foundations (2–3 Weeks)

## Operating Systems
- Processes & Threads
- Memory (Stack/Heap)
- Virtual Memory
- System Calls
- File Systems
- Permissions
- Boot Process

### Labs
- Inspect `/proc`
- Use `strace`, `lsof`, `ps`
- Build a tiny shell in Python

### Master
- Linux CLI
- Bash
- Vim
- SSH
- Cron

---

# Phase 1 – Networking (4 Weeks)

## Learn
- OSI Model
- TCP/IP
- ARP
- ICMP
- DNS
- DHCP
- HTTP/HTTPS
- TLS
- Routing
- NAT
- VPN

## Tools
- Wireshark
- tcpdump
- nmap
- netcat
- socat

### Projects
- TCP Chat Server
- Port Scanner
- Packet Sniffer
- DNS Lookup Tool

Checkpoint:
- Explain every TCP handshake packet.
- Read a packet capture without help.

---

# Phase 2 – Programming for Security

## Python
- sockets
- threading
- asyncio
- requests
- scapy
- hashlib
- cryptography

## C Basics
- pointers
- memory
- structs
- malloc/free
- buffer overflows (theory & labs)

Projects
- Hash Cracker
- Directory Brute Forcer
- Web Crawler
- Log Analyzer

---

# Phase 3 – Linux Internals

Study:
- ELF
- Permissions
- SUID
- Capabilities
- PAM
- systemd
- Namespaces
- cgroups

Labs
- Create users
- Configure SSH
- Harden a Linux VM
- Audit logs

---

# Phase 4 – Web Development Security (8 Weeks)

Understand:
- HTTP
- Cookies
- Sessions
- JWT
- OAuth2
- CORS
- REST
- GraphQL
- WebSockets

## OWASP Top 10

### Injection
- SQL Injection
- NoSQL Injection
- Command Injection
- LDAP Injection

### Authentication
- Broken Authentication
- Session Fixation
- JWT Attacks

### Access Control
- IDOR
- Privilege Escalation
- Mass Assignment

### Client-side
- XSS
- CSRF
- Clickjacking

### Server-side
- SSRF
- XXE
- SSTI
- File Upload

### Labs
- DVWA
- Juice Shop
- WebGoat
- PortSwigger Web Security Academy

Projects
- Build a vulnerable FastAPI app.
- Exploit it in a lab.
- Patch every vulnerability.

---

# Phase 5 – API Security

Study
- REST
- GraphQL
- Rate Limiting
- API Gateway
- JWT
- OAuth

Practice
- Burp Suite
- Postman

Attack Labs
- Broken JWT
- IDOR
- Parameter Pollution
- Missing Authorization
- BOLA

---

# Phase 6 – Pentesting Workflow

1. Recon
2. Enumeration
3. Vulnerability Analysis
4. Exploitation
5. Post Exploitation
6. Reporting

Tools
- nmap
- ffuf
- gobuster
- nikto
- Burp Suite
- Metasploit

---

# Phase 7 – Windows & Active Directory

Learn
- NTLM
- Kerberos
- LDAP
- Group Policy

Tools
- BloodHound
- Impacket
- Evil-WinRM

Labs
- Attack an AD lab.
- Escalate privileges.
- Defend it.

---

# Phase 8 – Cloud Security

AWS
- IAM
- EC2
- S3
- Lambda

Azure
- Identity
- RBAC

Practice
- Detect misconfigurations.
- Harden cloud resources.

---

# Phase 9 – Containers & Kubernetes

Docker
- Images
- Networks
- Secrets

Kubernetes
- Pods
- RBAC
- Network Policies

---

# Phase 10 – Reverse Engineering

Tools
- Ghidra
- x64dbg
- radare2

Learn
- x86 Assembly
- ELF
- PE
- Malware Basics

---

# Phase 11 – Cryptography

Study
- AES
- RSA
- ECC
- SHA
- HMAC
- TLS

Implement
- File Encryption Tool
- Secure Password Manager

---

# Phase 12 – Bug Bounty

Platforms
- HackerOne
- Bugcrowd
- Intigriti

Methodology
- Recon
- Enumeration
- Validation
- Responsible Disclosure

---

# Essential Projects

- Port Scanner
- Vulnerability Scanner
- Password Manager
- Network Scanner
- Web Vulnerability Scanner
- Secure Chat App
- Malware Sandbox (isolated VM)
- FastAPI Security Testing Lab
- Log Monitoring Dashboard
- SIEM Mini Project

---

# Reading List

## Beginner
- Linux Basics for Hackers
- Black Hat Python

## Intermediate
- Web Application Hacker's Handbook
- Real-World Bug Hunting

## Advanced
- Practical Malware Analysis
- The Art of Exploitation

---

# Practice Platforms

## Beginner
- OverTheWire Bandit
- PicoCTF

## Intermediate
- TryHackMe

## Advanced
- Hack The Box
- PortSwigger Academy

---

# Certifications (Optional)

1. Security+
2. eJPT
3. PNPT
4. OSCP
5. CRTO
6. OSEP

---

> Build. Break (Legally). Fix. Document. Repeat.