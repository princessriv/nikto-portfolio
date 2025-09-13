# Nikto — Web Server Scanner (Portfolio Entry)

> Documentation project for my portfolio — exploring Nikto, an open-source web server scanner.

**⚠️ Important:** This repository is for academic and professional demonstration only. All notes and examples are from safe, authorized lab environments. Do not use tools like Nikto against systems you do not own or have explicit written permission to test.

---

## About Me

**Name:** SARITA GURUNG  
**Student:** Bachelor’s in AI MANAGEMENT  
**Interest:** Cybersecurity, Vulnerability Assessment, Penetration Testing, Red Teaming

---

## What I Learned in This Project

- How to use **Nikto** to identify outdated software versions, insecure HTTP headers, and common misconfigurations.  
- Understanding false positives vs genuine vulnerabilities, and how to verify findings manually.  
- How to sanitize sensitive output so it can be shared publicly.  
- Best practices when writing vulnerability reports: clarity, context, risk rating, and remediation suggestions.

---

## Lab Setup (How to Reproduce)

1. Setup a test web server (e.g. Apache or Nginx) on a local VM or container.  
2. Optionally install some test vulnerabilities (e.g. outdated server software, known misconfigured directories).  
3. Run Nikto like:

```bash
nikto -h <target IP or hostname> -o output.txt

## What is Nikto?

Nikto is an open-source scanner that performs comprehensive tests against web servers. It checks for:
- Potentially dangerous files and directories,
- Outdated server components,
- Common misconfigurations,
- Issues that may require further manual analysis.

Nikto focuses on *discovery and reporting* rather than exploitation. Results are leads, not proofs.

---

## Purpose of this project

This repository demonstrates:
- My understanding of how Nikto works,
- Documentation of study notes (see `docs/nikto-notes.md`),
- Sanitized sample output,
- A professional vulnerability report template (`docs/report-template.md`).

---

## Example (safe usage style)

This is a *non-actionable* command form, shown for documentation purposes:

```bash
# Example form (do not run on unauthorized systems)
nikto -h <target-host-or-ip>
