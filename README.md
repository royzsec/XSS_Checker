# XSS_Checker
XSS-Checker: Automated XSS Vulnerability Scanner

Developed by Royzsec (Prince Roy) – Security researcher for NASA, US/UK government, and Fortune 500 companies.

Overview
XSS-Checker is a professional-grade tool that automates detection of Cross-Site Scripting (XSS) vulnerabilities. It combines subdomain discovery, historical URL analysis, and smart payload testing to identify security flaws efficiently.

Key Features
Subdomain Enumeration: Discovers live subdomains using subfinder and httpx.

Wayback Machine Integration: Collects historical URLs to find deprecated but vulnerable endpoints.

Payload Testing: Tests against Royzsec’s curated XSS payload list (with fallback defaults).

Clear Reporting: Generates structured vulnerability reports (xss_vulnerabilities.txt).

Why Use It?
Accuracy: Targets only live hosts and relevant historical data.

Speed: Automates reconnaissance for faster audits.

Professional Credibility: Built by a researcher trusted by global enterprises.

Usage
bash
Copy
./xss_checker.sh example.com  
Output: Organized results in a timestamped directory.

For Security Teams & Bug Hunters
Pre-Audit Scans: Quickly find vulnerable endpoints.

Bug Bounties: Expand attack surfaces with archived URLs.

Ethical Note: Always obtain authorization before scanning.
