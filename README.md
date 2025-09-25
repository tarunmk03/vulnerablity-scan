# Cyber Security Internship - Task 3

## Objective
Perform a basic vulnerability scan using Nessus Essentials and document the findings.

## Environment
- **Host OS:** Windows 11 (VirtualBox)
- **Guest OS:** Kali Linux 2025.2 (VirtualBox VM)
- **Tool Used:** Nessus Essentials (Free Edition)
- **Scan Target:** `127.0.0.1` (Localhost)

## Steps Performed
1. Installed Nessus Essentials on Kali Linux Virtual Machine.
2. Activated the free license and updated plugins.
3. Configured a **Basic Network Scan** with target `127.0.0.1`.
4. Ran the scan and waited for results.
5. Exported the findings report as a PDF.

## Findings (Sample)
- **Critical:** Missing OS-level patches (Privilege escalation risk).
- **High:** Outdated OpenSSL version (CVE-related vulnerabilities).
- **Medium:** Weak TLS/SSL ciphers detected (insecure communication risk).
- **Low:** Default SSH configuration (brute force exposure).

## Remediation
- Apply all pending OS and application security updates.
- Update OpenSSL to the latest stable version.
- Disable weak TLS/SSL ciphers and enforce modern protocols (TLS 1.2/1.3).
- Harden SSH configuration:
  - Disable root login.
  - Enforce key-based authentication.
  - Enable fail2ban or intrusion prevention tools.

## Deliverable
📄 [Vulnerability Scan Report (PDF)](./vulnerability_scan_report.pdf)

---

### 🔑 Key Concepts
- Vulnerability scanning  
- Risk assessment  
- CVSS (Common Vulnerability Scoring System)  
- Remediation  
- Security tools (Nessus Essentials)

---

## Outcome
This task gave me hands-on experience with basic vulnerability scanning, interpreting results, and documenting remediation strategies. It also helped me understand how common PC risks are identified and managed in real-world environments.
