# Nikto Study Notes

These notes summarize my exploration of **Nikto**, based on my learning and reference material.

---

## Overview
- Nikto is a web server scanner.
- It checks for insecure files, outdated server versions, and misconfigurations.
- Results are not confirmations, but indicators for further analysis.

---

## Features
- Scans for common files and directories.
- Identifies outdated web servers.
- Reports potential security issues.
- Plugin system for extending checks.

---

## Usage patterns
Example forms (documentation only):
- `nikto -h <host>` → scan a host.
- `nikto -Plugins <plugin>` → run a specific plugin.
- `nikto -Display V` → verbose output.

---

## Strengths
- Comprehensive checks.
- Regularly updated signatures.
- Simple command-line interface.

---

## Limitations
- Produces false positives — requires manual verification.
- Not a stealthy tool (easily logged by IDS/IPS).
- Meant for initial assessments, not exploitation.

---

## Ethical reminder
Nikto is a **defensive tool**. Use responsibly and only with permission.
