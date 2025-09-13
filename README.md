
# Nikto Web Vulnerability Scanner – Study Portfolio

## 📌 Overview
This repository documents my hands-on learning with **Nikto**, an open-source web server vulnerability scanner.  
It contains my study notes, sanitized sample outputs, and a vulnerability report template.

⚠️ **Disclaimer**: This project is for educational purposes only.  
Do **not** run Nikto or any other security tool against systems you do not own or have explicit authorization to test.

---

## 🗂️ Repository Contents
- `nikto-notes.md` → My study notes while learning Nikto.  
- `Sample-output.txt` → Sanitized example of Nikto scan results.  
- `report-template.md` → Structured vulnerability report format.  
- `CONTRIBUTING.md` → Contribution guidelines (for practice in open-source hygiene).  
- `LICENSE` → MIT License.

---

## 🔬 What I Learned
- How to install and run **Nikto** scans.  
- How to interpret scan results (e.g., outdated versions, missing headers, misconfigurations).  
- The importance of **sanitizing outputs** before sharing publicly.  
- Distinguishing between **false positives** and genuine findings.  
- Writing professional **vulnerability reports**.

---

## ⚙️ Lab Setup
1. Create a safe test environment (VM or container).  
2. Install a web server (e.g., Apache or Nginx).  
3. Install Nikto:
   ```bash
   sudo apt-get install nikto
