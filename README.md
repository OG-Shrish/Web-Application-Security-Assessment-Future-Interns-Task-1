# Web Application Security Assessment

A hands-on security assessment of a deliberately vulnerable web application using industry-standard penetration-testing tools and manual testing techniques.

## Overview

This project evaluates common web application vulnerabilities through automated scanning and manual security testing.

The assessment focuses on identifying vulnerabilities, understanding their security impact, mapping findings to OWASP categories, and documenting remediation strategies.

## Objectives

* Identify common web application vulnerabilities
* Perform automated vulnerability scanning
* Perform manual security testing
* Analyze vulnerability impact
* Map vulnerabilities to OWASP categories
* Document remediation recommendations

## Tools Used

* Kali Linux
* OWASP ZAP
* Burp Suite Community Edition
* DVWA
* Firefox

## Vulnerabilities Tested

### SQL Injection

Tested application inputs for SQL injection vulnerabilities and analyzed the resulting security impact.

### Cross-Site Scripting

Tested user-controlled input for reflected XSS vulnerabilities.

### Cross-Site Request Forgery

Evaluated application requests for CSRF protection weaknesses.

## Methodology

```text
Reconnaissance
      |
      v
Automated Scanning
      |
      v
Manual Testing
      |
      v
Vulnerability Verification
      |
      v
Impact Analysis
      |
      v
OWASP Mapping
      |
      v
Remediation Recommendations
```

## Testing Approach

### Automated Testing

OWASP ZAP was used to identify potential vulnerabilities and generate security findings.

### Manual Testing

Burp Suite was used to intercept and modify HTTP requests and verify vulnerabilities manually.

## OWASP Mapping

| Vulnerability | OWASP Category              |
| ------------- | --------------------------- |
| SQL Injection | A03 – Injection             |
| XSS           | A03 – Injection             |
| CSRF          | A01 – Broken Access Control |

## Key Findings

The assessment demonstrates the importance of:

* Input validation
* Output encoding
* Secure authentication
* CSRF protection
* Proper access control
* Security testing throughout development

## Report

A detailed security assessment report containing screenshots, findings, impact analysis, and remediation recommendations is included in this repository.

## Disclaimer

All testing was performed in an intentionally vulnerable and controlled environment for educational purposes.

Do not perform security testing against systems without explicit authorization.

## Author

**Shrish Ahankari**

Cybersecurity Intern – Future Interns
