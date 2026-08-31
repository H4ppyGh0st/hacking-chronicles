# Security Research Portfolio

Welcome to my Security Research Portfolio.

This repository is a collection of my work in **cybersecurity, vulnerability research, web application security, and penetration testing**. It documents vulnerabilities I have discovered, security assessments I have performed, proof-of-concepts, technical research, and lessons learned throughout my work as an independent security researcher.

My main focus is understanding how vulnerabilities arise, how they can be identified and reproduced, their potential impact, and how they can be properly mitigated.

---

## About Me

I am a software developer with a focus on **cybersecurity and security research**, particularly in web applications and software security.

My research involves analyzing applications and open-source software to identify security weaknesses, understand their root causes, develop controlled proof-of-concepts, and document the findings following responsible disclosure practices.

I am particularly interested in vulnerabilities involving **access control, authentication, client-side security, server-side vulnerabilities, and application logic**.

---

## Areas of Research

My research and security assessments cover areas including:

* Web Application Security
* API Security
* Vulnerability Research
* Broken Access Control
* IDOR / BOLA
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Server-Side Request Forgery (SSRF)
* Server-Side Template Injection (SSTI)
* SQL Injection
* File Upload Vulnerabilities
* Authentication & Authorization
* Business Logic Vulnerabilities
* Security Misconfigurations
* Client-Side and Server-Side Security

---

## CVE Research

This section contains vulnerabilities discovered during my security research.

Each vulnerability is documented with technical details such as:

* Vulnerability description
* Affected software and versions
* CWE classification
* Severity and impact
* Root cause analysis
* Proof-of-concept
* Technical reproduction steps
* Disclosure timeline
* Remediation recommendations

### Published Research

| CVE            | Product | Vulnerability                           | Severity |
| -------------- | ------- | --------------------------------------- | -------- |
| CVE-2026-11944 | openSIS | Authenticated Path Traversal            | Medium   |
| CVE-2026-8406  | openSIS | Insecure Direct Object Reference (IDOR) | High     |
| CVE-2026-1213  | Askbot  | Insecure Direct Object Reference (IDOR) | Medium   |


> Additional CVEs and research will be added as they are publicly disclosed.

---

## Penetration Testing

This repository also contains technical case studies based on penetration testing and security assessments performed in authorized environments.

The case studies focus on the methodology used to identify vulnerabilities rather than exposing confidential client information.

Testing areas include:

* Reconnaissance
* Attack Surface Mapping
* Authentication Testing
* Authorization Testing
* Input Validation
* API Security
* Business Logic
* File Upload Testing
* Client-Side Security
* Server-Side Security
* Vulnerability Validation
* Exploitation
* Impact Analysis
* Security Reporting

All sensitive information such as credentials, tokens, internal addresses, personal information, and confidential client data is excluded or sanitized.

---

## Proof of Concepts

Where appropriate, research findings include controlled proof-of-concepts designed to demonstrate the vulnerability and its impact.

PoCs are intended for **educational and security research purposes** and should only be executed against systems where testing is explicitly authorized.

---

## Security Research and Writeups

In addition to CVE research, this repository contains technical writeups covering different vulnerabilities, attack techniques, methodologies, and lessons learned during security research.

The objective is not only to document the final vulnerability, but also to explain the **reasoning and methodology behind the discovery process**.

---

## Tools and Technologies

Some of the tools and technologies used throughout my research include:

### Security Tools

* Burp Suite
* Nmap
* Nuclei
* Nikto
* WPScan
* Gobuster
* Metasploit
* Wireshark
* OWASP ZAP
* Kali Linux

### Programming and Scripting

* Python
* JavaScript
* PHP
* Java
* SQL

### Technologies

* Django
* REST APIs
* PostgreSQL
* Linux
* Git / GitHub

---

## Research Approach

My general approach to security research can be summarized as:

```text
Reconnaissance
      ↓
Attack Surface Mapping
      ↓
Identify Potential Attack Vectors
      ↓
Manual Testing
      ↓
Vulnerability Validation
      ↓
Root Cause Analysis
      ↓
Proof of Concept
      ↓
Impact Assessment
      ↓
Responsible Disclosure
      ↓
Technical Documentation
```

I prioritize **understanding the underlying cause of a vulnerability** rather than relying exclusively on automated scanners.

---

## Repository Structure

```text
security-research/
│
├── CVEs/
│   ├── CVE-XXXX-XXXXX/
│   │   ├── README.md
│   │   ├── poc/
│   │   └── screenshots/
│   │
│   └── ...
│
├── Pentesting/
│   ├── web-applications/
│
│
└── Writeups/
    ├── CTF/

```

---

## Responsible Disclosure

All vulnerability research documented in this repository is performed for **authorized security testing, research, and educational purposes**.

Sensitive information, credentials, private infrastructure details, and confidential client information are intentionally excluded from public documentation.

Where applicable, vulnerabilities are disclosed responsibly to the affected vendors or maintainers before public disclosure.

---

## Contact

For security research, collaboration, or other professional inquiries, feel free to contact me through my GitHub profile.

---

> **Research. Discover. Understand. Secure.**
