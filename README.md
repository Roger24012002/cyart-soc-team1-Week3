# CyArt SOC Team – Wazuh SIEM Security Monitoring

## Overview
This repository contains SOC practical work completed as part of the CyArt SOC Team tasks. The project focuses on security monitoring, alert analysis, threat intelligence, incident triage, escalation, and evidence collection using Wazuh SIEM.

## Tools Used
- Wazuh SIEM
- Windows Endpoint Agent
- VirusTotal
- AlienVault OTX
- MITRE ATT&CK
- GitHub

## Repository Structure
cyart-soc-team1/
├── Evidence/
├── Logs/
├── Reports/
├── Screenshots/
├── Tables/
└── README.md


## Task 1: Advanced Log Analysis
Wazuh logs were analyzed using the Threat Hunting module. High severity alerts were identified, including Rule ID 204 related to agent event queue flooding.

**Outcome:**  
Abnormal log volume was detected, indicating possible misconfiguration or system overload.

## Task 2: Threat Intelligence Integration
The IP address `192.168.152.1` was checked using VirusTotal and AlienVault OTX.

**Findings:**
- The IP address is private/local.
- It was not listed as malicious.
- No external threat activity was detected.

## Task 3: Alert Triage
A high severity alert was selected and analyzed.

**Alert Details:**
- Alert Name: Agent Event Queue Flooded
- Rule ID: 204
- Severity: High
- Level: 12

**Analysis:**  
The alert was caused by a high number of events generated in a short time. This may be due to system overload or agent misconfiguration.

## Task 4: Incident Escalation
The alert was escalated to the Tier 2 SOC Team for further investigation.

**Escalation Summary:**  
A high severity alert was triggered due to excessive event generation from the endpoint. Initial analysis indicates a configuration issue rather than a confirmed cyber attack.

## Task 5: Evidence Collection
Evidence was collected and organized for documentation.

**Evidence Includes:**
- Wazuh alert screenshots
- Threat hunting logs
- FIM screenshots
- Dashboard overview
- Exported logs
- Incident report

## Key Findings
- High severity alert was detected in Wazuh.
- Event flooding was observed from the endpoint.
- Threat intelligence checks showed no malicious external IP.
- The incident followed SOC workflow: Detection → Analysis → Triage → Escalation → Documentation.

## Conclusion
This task successfully demonstrates practical SOC analyst activities using Wazuh SIEM. The investigation showed that the alert was most likely caused by system-level event flooding or misconfiguration, not a confirmed cyber attack. The project helped in understanding alert monitoring, log analysis, threat intelligence checks, incident triage, and evidence collection.

## Future Improvements
- Tune Wazuh alert rules and thresholds.
- Improve endpoint agent configuration.
- Integrate more threat intelligence sources.
- Automate incident response workflow.
- Add more detailed MITRE ATT&CK mapping.

## Author
**Vinayaka Reddy**  
Cybersecurity Enthusiast | SOC Analyst Learner
