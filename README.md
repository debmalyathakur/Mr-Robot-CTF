# TryHackMe – Mr Robot CTF

## Room Overview

**Platform:** TryHackMe  
**Room:** Mr Robot CTF  
**Category:** Capture The Flag (CTF)  
**Difficulty:** Medium  
**Focus Areas:** Web Application Security, Enumeration, Linux, Privilege Escalation

### About the Room

The Mr Robot CTF room on TryHackMe is a practical cybersecurity lab inspired by the Mr. Robot series. The objective is to identify security weaknesses, gain initial access, discover credentials, and escalate privileges to obtain all three flags.

I completed this lab by following a structured penetration testing approach, starting with web application reconnaissance and enumeration, followed by initial access, credential discovery, Linux enumeration, and privilege escalation.

This exercise helped me understand how multiple security weaknesses can be connected to compromise a target system.

### Prerequisites

Before attempting this room, having a basic understanding of the following topics is recommended:

- Basic Linux commands and terminal navigation.
- Networking fundamentals (TCP/IP, ports, and services).
- HTTP/HTTPS and web application fundamentals.
- Basic web directory and file enumeration.
- WordPress fundamentals and web application security.
- Linux users, groups, permissions, and file ownership.
- Basic understanding of password hashes and encoding.
- Introduction to Linux privilege escalation.
- Basic familiarity with penetration testing tools.

### Tools & Technologies Used

- **Nmap** – Network and service enumeration.
- **DirBuster** – Web directory and file discovery.
- **Burp Suite** – Web application inspection.
- **Netcat** – Network connection and listener management.
- **Linux Terminal** – System enumeration and analysis.
- **CrackStation** – Password hash analysis.

### Assessment Overview

My assessment covered the following stages:

1. **Initial Reconnaissance:** Examined the target's exposed web services and gathered initial information.
2. **Web Enumeration:** Investigated accessible directories, files, and application resources.
3. **Initial Access:** Identified an opportunity to gain access through the web application.
4. **Credential Discovery:** Examined accessible files and identified authentication-related information.
5. **User-Level Access:** Obtained access to another user account and continued system enumeration.
6. **Privilege Escalation:** Investigated system permissions and identified a potential privilege-escalation misconfiguration.
7. **Final Objective:** Successfully obtained all three flags and completed the CTF.

*Note: This section provides a high-level overview. The detailed walkthrough, screenshots, commands, and practical findings are documented separately.*

### Key Learning Outcomes

Through this practical exercise, I improved my understanding of:

- Structured web application reconnaissance.
- Identifying exposed directories and resources.
- Understanding common WordPress security weaknesses.
- Credential discovery and password hash analysis.
- Linux privilege and permission enumeration.
- Identifying potentially vulnerable SUID binaries.
- Understanding the relationship between initial access and privilege escalation.
- Following a structured penetration testing methodology.

### Lab Completion

**Status:** Successfully Completed

**Flags:** 3/3 Captured

This lab provided valuable hands-on experience in web application assessment, Linux enumeration, and privilege escalation.

### Author

**Debmalya Thakur**  
Cybersecurity Enthusiast | Aspiring VAPT & Application Security Professional

- LinkedIn: [Connect with me](https://www.linkedin.com/in/debmalya-thakur-9b240417b/)
- GitHub: [My Security Portfolio](https://debmalyathakur.github.io/portfolio)

---

*Disclaimer: This write-up is intended strictly for educational purposes. All testing was performed within the authorized TryHackMe lab environment.*
