# Nikto Web Vulnerability Scanner – Study Portfolio

## 📌 Overview
This repository documents my hands-on learning with **Nikto**, an open-source web server vulnerability scanner.  
It contains my study notes, sanitized sample outputs, and a vulnerability report template.

⚠️ **Disclaimer**: This project is for educational purposes only.  
Do **not** run Nikto or any other security tool against systems you do not own or have explicit authorization to test.

---

## 🗂️ Repository Contents
- [Nikto Study Notes](nikto-notes.md)  
- [Sample Sanitized Output](Sample-output.txt)  
- [Vulnerability Report Template](report-template.md)  
- [Contributing Guidelines](CONTRIBUTING.md)  
- [License](LICENSE)

---

## 🔬 What I Learned  
- How to install and run Nikto scans in a safe test environment.  
- The kinds of vulnerabilities Nikto can identify (e.g., outdated versions, default files, missing security headers).  
- How to distinguish **false positives** from real findings.  
- How to sanitize output before sharing publicly.  
- How to structure a professional vulnerability report.

---

## ⚙️ Lab Setup   
Steps I followed to reproduce my scans:

1. Created a test environment (Ubuntu VM).  
2. Installed Apache web server with default settings.  
3. Installed Nikto:  
   ```bash
   sudo apt-get install nikto
