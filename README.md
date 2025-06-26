# cyber-task-3
Vulnerability-Scan

##  Tool Used
**Tenable Nessus Essentials**  

##  Scan Target
**Local Machine** — 127.0.0.1 (loopback IP)

##  Scan Summary
- Scan Type: Basic Network Scan
- Scanner: Local
- Date: 26 June 2025
- Duration: 7 minutes

###  Vulnerabilities Detected
| Severity | Count |
|----------|-------|
| Critical | 0     |
| High     | 0     |
| Medium   | 2     |
| Low      | 0     |
| Info     | 30    |
| **Total**| **32**|

---

##  Example Vulnerabilities

### 1. **SSL Certificate Cannot Be Trusted**
- **Plugin ID:** 51192
- **Severity:** Medium
- **Description:** The SSL certificate used by the host is not trusted. This may indicate a self-signed certificate or one issued by an untrusted CA.

### 2. **SMB Signing Not Required**
- **Plugin ID:** 57608
- **Severity:** Medium
- **Description:** SMB signing is not required, which can allow man-in-the-middle attacks on SMB traffic.


---

##  What I Learned
- How to set up and run Nessus for local system vulnerability scanning
- How to interpret CVSS scores and plugin-based vulnerability reports
- The importance of SSL certificates and proper SMB configurations in securing a host


