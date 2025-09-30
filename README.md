# Task-3-vulnerbility-scan
“Cybersecurity internship Task 3: Vulnerability assessment of localhost system.”  

## Tool Utilized  
- Nessus Essentials (Free Edition)  

## Scan Target  
- Localhost (127.0.0.1)

## Summary of Findings  
The vulnerability scan identified a total of 12 vulnerabilities across different severity levels:  

| Severity Level | Count |
|----------------|-------|
| Critical       | 2     |
| High           | 3     |
| Medium         | 5     |
| Low            | 2     |

---

## Sample Identified Vulnerabilities  

### 1. SMB Signing Not Required  
- Severity: High  
- Description:The system allows SMB communication without requiring signing, which may enable man-in-the-middle (MITM) attacks.  
- Recommended Remediation: Enable SMB signing via system/group policies.  

### 2. Outdated OpenSSL Version  
- Severity:Critical  
- Description:The detected OpenSSL version contains known vulnerabilities that may allow remote attackers to exploit the system.  
- Recommended Remediation: Update to the latest stable version of OpenSSL.  

---

## Supporting Evidence  
- Screenshots of the vulnerability scan results are attached in the screenshots/ folder for reference.  

---

## Key Learnings  
- Gained practical exposure to using vulnerability scanning tools.  
- Understood the classification of vulnerabilities based on severity (Critical, High, Medium, Low).  
- Learned the importance of applying timely patches and configurations as part of remediation.  
- Improved knowledge of basic system hardening practices.
