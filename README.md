# Cyber Security Internship - Task 3

## Objective
Perform a basic vulnerability scan using Nessus Essentials.

## Steps
1. Installed Nessus Essentials on Kali Linux VM.
2. Configured a Basic Network Scan on `127.0.0.1`.
3. Ran the scan and exported results.

## Findings (Sample)
- **Critical:** Missing OS patches (Privilege escalation risk).
- **High:** Outdated OpenSSL version.
- **Medium:** Weak TLS/SSL ciphers detected.
- **Low:** Default SSH configuration.

## Remediation
- Apply all pending OS and application security updates.
- Update OpenSSL to the latest version.
- Disable weak TLS/SSL ciphers and enforce modern protocols.
- Harden SSH (disable root login, enforce key-based authentication).

## Deliverable
- [Scan Report](./vulnerability_scan_report.pdf)
