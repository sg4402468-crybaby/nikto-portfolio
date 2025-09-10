# nikto-portfolio
Documentation project on Nikto, an open-source web server scanner — includes study notes, sanitized outputs, and a professional reporting template.
# Nikto — Web Server Scanner (Portfolio Entry)

> Documentation project for my portfolio — exploring Nikto, an open-source web server scanner.

**⚠️ Important:** This repository is for academic and professional demonstration only. All notes and examples are from safe, authorized lab environments. Do not use tools like Nikto against systems you do not own or have explicit written permission to test.

---

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
