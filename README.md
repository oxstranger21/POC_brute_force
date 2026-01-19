##🔐 Web Application Security Testing – POC

This repository contains Proof of Concept (POC) documentation for identifying and demonstrating common web application vulnerabilities discovered during authorized security testing.

##📌 Vulnerabilities Covered
1️⃣ Authentication Bypass via Brute Force

The login functionality is vulnerable to brute force attacks.

Username and password combinations can be guessed using wordlists.

No rate limiting, CAPTCHA, or account lockout is implemented.

Impact:

Account Takeover

Unauthorized Access

Data Breach

2️⃣ Cross-Site Scripting (XSS)

User input is not properly sanitized.

Malicious JavaScript can be injected and executed in the victim’s browser.

Impact:

Phishing

Open Redirection

User Session Manipulation

##🛠 Tools Used

Burp Suite

Web Browser

Wordlists

##📄 Proof of Concept (POC)

Detailed step-by-step POC with screenshots is available in the PDF report:


📎 POC_test_php.pdf

##⚠️ Disclaimer

This project is for educational and authorized security testing purposes only.
Do NOT test any system without proper permission.
The author is not responsible for misuse of this information.

##👤 Author

Gopi Kumar
Cyber Security Intern
DROP Organization
