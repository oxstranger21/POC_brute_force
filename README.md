# Web Application Vulnerability Assessment
Authentication Bypass (Brute Force) & Cross-Site Scripting (XSS)

This repository contains Proof of Concept (POC) documentation for common web application security vulnerabilities identified during authorized penetration testing.

**📌 Overview**

The assessment focuses on identifying weaknesses in authentication mechanisms and input validation that may allow attackers to gain unauthorized access or execute malicious scripts.

## 🚨 Vulnerabilities Identified
**🔐 Authentication Bypass via Brute Force**

Login functionality allows unlimited attempts.

Username and password can be guessed using wordlists.

No rate limiting, CAPTCHA, or account lockout implemented.

**Impact:**

Account Takeover

Unauthorized Access

Data Breach

## ⚠️ Cross-Site Scripting (XSS)

User input is not properly validated or sanitized.

Malicious JavaScript can be injected and executed in the browser.

**Impact:**

Phishing

Open Redirection

User Session Manipulation

**🛠 Tools Used**

Burp Suite

Web Browser

Wordlists

**Proof of Concept (POC)**

Complete step-by-step demonstration with screenshots is available in the report:

📎 POC_test_php.pdf

# ⚠️ Disclaimer

This repository is intended strictly for educational and authorized security testing purposes.
Testing systems without permission is illegal.
The author is not responsible for misuse of this information.

# 👤 Author

Gopi Kumar                   
Cyber Security Intern              
DROP Organization
