# Week 7 — VAPT Web Application Security Testing with Burp Suite

## Overview

This project documents a practical Web Application Vulnerability Assessment and Penetration Testing (VAPT) exercise performed in an authorized DVWA/local lab environment.

The assessment demonstrates reconnaissance, HTTP interception, manual vulnerability testing, endpoint discovery, evidence collection, and professional security reporting.

## Objectives

* Understand the role of an interception proxy in web application testing.
* Configure Burp Suite and a browser for HTTP/HTTPS interception.
* Perform reconnaissance and map the application's attack surface.
* Identify input points, parameters, cookies, authentication flows, and endpoints.
* Validate common web vulnerabilities using controlled test cases.
* Use Burp Repeater and Intruder for request analysis.
* Perform endpoint discovery using Burp, Gobuster, or Dirsearch.
* Document findings, impact, root cause, and remediation.

## Tools Used

* Burp Suite Community Edition
* DVWA (Damn Vulnerable Web Application)
* OWASP ZAP
* Gobuster / Dirsearch
* Web browser

## Assessment Methodology

1. Configure Burp Suite and the dedicated browser proxy.
2. Capture and inspect HTTP/HTTPS requests and responses.
3. Perform reconnaissance and map the application using Burp Target/Site Map.
4. Analyze authentication and session behavior.
5. Conduct controlled manual vulnerability testing with Burp Repeater.
6. Use Intruder for small, controlled request variations.
7. Discover and validate application endpoints.
8. Perform supporting validation with OWASP ZAP.
9. Document findings with reproducible evidence and remediation guidance.

## Vulnerabilities Assessed

* SQL Injection
* Stored Cross-Site Scripting (XSS)
* Reflected Cross-Site Scripting (XSS)
* Parameter Tampering
* Authentication and Session Analysis
* Endpoint Exposure

## Key Findings

The report documents SQL Injection, Stored XSS, and Reflected XSS in the intentionally vulnerable lab. Other assessment areas include parameter tampering, authentication/session analysis, and endpoint discovery.

## Remediation

* Use parameterized queries and prepared statements.
* Apply context-aware output encoding.
* Use safe templates and DOM APIs.
* Enforce server-side authorization and business-rule validation.
* Protect sessions and cookies with appropriate security attributes.
* Remove unused endpoints and enforce access controls.
* Retest after remediation.

## Repository Structure

* `README.md` — Project overview, objectives, methodology, and tools.
* `Week_7_VAPT_Report.pdf` — Detailed assessment report.
* `screenshots/` — Actual screenshots captured during authorized lab testing.

## Learning Outcomes

* Practical understanding of HTTP interception.
* Familiarity with Burp Suite Proxy, HTTP History, Target, Repeater, and Intruder.
* Experience with manual web vulnerability validation.
* Understanding of endpoint discovery and scanner verification.
* Evidence-based security reporting and remediation planning.

## Scope and Disclaimer

This exercise is for educational purposes and was restricted to an intentionally vulnerable, authorized laboratory environment. Testing public or third-party systems requires explicit permission.

## Author

Harsh Dankhra
