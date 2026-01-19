📌 Project Overview

This project focuses on performing a basic security assessment of a vulnerable web application using industry-standard tools. The goal is to identify common vulnerabilities, analyze their impact, and suggest appropriate remediation techniques based on OWASP Top 10 guidelines.

🎯 Objectives

Understand common web vulnerabilities
Perform automated and manual security testing
Identify and document security flaws
Map vulnerabilities to OWASP Top 10
Suggest remediation techniques

🛠 Tools Used

Kali Linux
OWASP ZAP
Burp Suite Community
DVWA (Damn Vulnerable Web Application)
Firefox Browser

🔍 Vulnerabilities Tested

SQL Injection
Cross-Site Scripting (XSS)
Cross-Site Request Forgery (CSRF)

⚙️ Methodology
Automated Testing
Conducted automated vulnerability scans using OWASP ZAP.
Identified security issues and generated reports.
Manual Testing
Intercepted HTTP requests using Burp Suite.
Tested input fields with crafted payloads.
Verified vulnerabilities manually.

🧪 Sample Payloads
SQL Injection
' OR '1'='1

XSS
<script>alert('XSS')</script>

📊 OWASP Top 10 Mapping
Vulnerability	OWASP Category
SQL Injection	A03 – Injection
XSS	A07 – Cross-Site Scripting
CSRF	A05 – Security Misconfiguration

🧠 Key Learnings

Real-world vulnerabilities can be easily exploited if not handled correctly.
Input validation and sanitization are critical.
Automated tools help, but manual testing is essential.

📄 Report

The complete report with screenshots, findings, and remediation steps is included in the repository.

👤 Author

Shrish
Cyber Security Intern – Future Interns
