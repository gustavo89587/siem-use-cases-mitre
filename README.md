🧠 SIEM Use Cases mapped to MITRE ATT&CK
Practical SIEM detection use cases mapped to MITRE ATT&CK techniques, designed for SOC operations and detection engineering.
This repository focuses on how detections are built, validated, and improved, not just how alerts look on a dashboard.

🎯 Objective
To demonstrate how a SOC analyst or detection engineer:
Designs meaningful SIEM detections
Maps them to MITRE ATT&CK
Reduces false positives
Supports investigation and response
This is about detection logic, not tool-specific clicks.

🧠 Detection Philosophy
Effective detections:
Focus on behavior, not signatures
Use context and correlation
Are tuned for signal over noise
Support investigation, not alert spam
This repository reflects that mindset.
🧩 Detection Structure
Each use case follows a consistent structure:

Threat Scenario
   ↓
MITRE ATT&CK Technique
   ↓
Log Sources
   ↓
Detection Logic
   ↓
False Positives
   ↓

SOC Response Guidance
🔍 Example Use Cases
Suspicious PowerShell execution
Credential access anomalies
LOLBins abuse detection
Persistence mechanisms
Command-line pattern analysis
Privilege escalation indicators
Each case includes context, not just a rule.

🛡️ MITRE ATT&CK Mapping
Every detection is mapped to:
Tactic
Technique
Sub-technique (when applicable)
This allows:
Coverage analysis
Gap identification
Better SOC reporting

📂 Repository Structure

siem-use-cases-mitre/
├── use-cases/
│   ├── credential-access.md
│   ├── execution.md
│   ├── persistence.md
│   └── lateral-movement.md
├── mitre/
│   └── mapping.md
└── README.md

🛠️ Tools & Concepts Applied
SIEM detection logic (tool-agnostic)
Windows & Linux log analysis
Event correlation
MITRE ATT&CK framework
Alert tuning & validation
SOC triage workflows

🧠 Why This Matters
SOC teams don’t fail because they lack tools —
they fail because detections are:
noisy
shallow
poorly contextualized
This repository shows how to think about detections, not just write rules.

🎯 Target Audience
SOC Analysts (Tier 1–2)
Detection Engineers
Threat Hunters
Blue Team Engineers
SIEM Analysts

👤 Author
Gustavo Okamoto
Cybersecurity Analyst | SOC / SIEM | Threat Detection & Incident Response | Blue Team
Automation • Detection Engineering • MITRE ATT&CK
🔗 GitHub: https://github.com/gustavo89587
🔗 LinkedIn: https://linkedin.com/in/gustavo-okamoto-de-carvalho-ti

⭐ Star this repository if you value quality detections over noisy alerts.