# Steel-Mountain-THM-Writeup
TryHackMe Steel Mountain Write-Up – Windows Exploitation &amp; Privilege Escalation

## 📌 Overview
This repository contains my write-up for the Steel Mountain room on TryHackMe.
The goal was to gain initial access to a Windows machine and escalate privileges
to SYSTEM.

## 🎯 Objectives
- Enumerate open services
- Exploit a vulnerable web service
- Gain a shell
- Perform privilege escalation
- Capture user and root flags

### 🔍 Nmap Scan
An initial network scan was performed to identify open ports and services running on the target machine.
The `-sV` flag was used to detect service versions, which helps in identifying potential vulnerabilities.

```bash
nmap -sV <TARGET_IP>
```
![Nmap Scan](https://github.com/phanidhar2829/Steel-Mountain-THM-Writeup/blob/8ea7da0483463697b4ffa8b992665372d1447dce/scrshots/nmap.png)

```Q1. Who is the employee of the month?
(Hint: Reverse the image)
```

