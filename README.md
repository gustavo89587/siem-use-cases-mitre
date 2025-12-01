# SIEM Use Cases — MITRE ATT&CK Based
Coleção profissional de casos de detecção para SIEM (Splunk, Microsoft Sentinel, Elastic Security) + Sigma Rules, todos mapeados ao MITRE ATT&CK.

Os casos seguem boas práticas recomendadas por:
- MITRE ATT&CK Framework
- NIST SP 800-61 (Incident Handling)
- SANS Blue Team Level 1/2
- Elastic Detection Engineering Guides
- Microsoft Sentinel Hunting Best Practices

## 🛡️ Categorias de Detecção
- Brute Force (ATT&CK: T1110)
- Credential Access (T1003)
- Persistence (T1053, T1547)
- Lateral Movement (T1021)
- Exfiltration (T1048)
- Defense Evasion (T1562)

## 📁 Estrutura
- `splunk/` → SPL queries
- `sentinel/` → KQL detections
- `elastic/` → KQL/Lucene queries
- `sigma/` → Sigma rules YAML
- `mitre_mapping/` → JSON com ATT&CK mappings

## 🚀 Objetivo
Fornecer detecções prontas para uso, bem documentadas e mapeadas ao MITRE ATT&CK, demonstrando experiência prática com SIEMs modernos.
