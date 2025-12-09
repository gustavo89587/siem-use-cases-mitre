# SIEM Use Cases-MITRE ATT & CK Based
Professional collection of detection cases for SIEM (Splunk, Microsoft Sentinel, Elastic Security) + Sigma Rules, all mapped to MITRE ATT&CK.

Cases follow best practices recommended by:
- MITRE ATT & CK Framework
- NIST SP 800-61 (Incident Handling)
- SANS Blue Team Level 1/2
- Elastic Detection Engineering Guides
- Microsoft Sentinel Hunting Best Practices

## 🛡️ Detection categories
- Brute Force (ATT&CK: T1110)
- Credential Access (T1003)
- Persistence (T1053, T1547)
- Lateral Movement (T1021)
- Exfiltration (T1048)
- Defense Evasion (T1562)

## 📁 Structure
- 'splunk/' → SPL queries
- 'sentinel /' → KQL detections
- 'elastic/' → kql / Lucene queries
- 'sigma/' → Sigma rules YAML
- 'mitre_mapping /' → JSON with ATT&CK mappings

## 🚀 Goal
Provide well-documented, off-the-shelf detections mapped to MITRE ATT & CK, demonstrating hands-on experience with Moderna SIEMs.
