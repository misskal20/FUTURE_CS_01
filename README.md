Vulnerability Assessment Report – testphp.vulnweb.com Web Application

📌 Overview

This repository contains the deliverables for Cyber Security Task 1 (2026) under the Future Interns Cyber Security Internship Program.

The objective of this task was to perform a read-only vulnerability assessment of a public-facing web application and present the findings in a structured and professional security report.

The assessment was conducted ethically using passive techniques only. No exploitation or harmful actions were performed against the target system. The focus was on identifying common security misconfigurations, missing security controls, and information disclosure issues.

🌐 Target Information

Website Tested: testphp.vulnweb.com
Application Type: Public-facing demo web application
Assessment Type: Passive Vulnerability Assessment (Read-Only Scope)
Assessment Date: February 2026

🎯 Assessment Scope

✔ In-Scope

Publicly accessible web pages

Passive vulnerability scanning

HTTP header analysis

Security header verification

Login page security review

Network exposure analysis (port scanning)

Server information disclosure checks


❌ Out-of-Scope

Authentication bypass attempts

Exploitation of identified vulnerabilities

Brute-force attacks

Denial-of-Service (DoS) testing

Any intrusive or service-disrupting actions


🛠️ Tools Used

The following tools were used during the assessment:

Nmap – Network and port exposure analysis

OWASP ZAP (Passive Scan) – Identification of security misconfigurations without active exploitation

Browser Developer Tools – HTTP header and client-side security inspection

Canva – Professional formatting and preparation of the final PDF report


🔎 Summary of Key Findings

During the assessment, several security weaknesses were identified, including:

Sensitive information disclosure on the login page

Missing Content Security Policy (CSP)

Missing Anti-CSRF protection

Missing security headers (X-Frame-Options, X-Content-Type-Options)

Server version and technology disclosure

Unencrypted HTTP communication

The overall risk level of the application was classified as Medium, based on the combined impact of the identified issues.


📄 Deliverable

The complete Vulnerability Assessment Report is available in this repository as a professionally designed PDF document.


⚠ Disclaimer

This assessment was conducted strictly using passive, read-only techniques.
No exploitation, denial-of-service testing, or unauthorized access attempts were performed.

This project was completed for educational purposes as part of the Cyber Security Internship Program at Future Interns.# FUTURE_CS_01
