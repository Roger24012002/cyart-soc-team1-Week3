
---

## Task 1: Advanced Log Analysis
- Analyzed Wazuh logs using Threat Hunting module  
- Identified high severity alerts (Rule ID 204 – Agent Flooding)  
- Observed multiple system error events and alert spikes  

**Outcome:**  
Detected abnormal log volume indicating possible misconfiguration or overload.

---

## Task 2: Threat Intelligence Integration
- Investigated IP address: `192.168.152.1`  
- Checked using VirusTotal and AlienVault OTX  

**Findings:**  
- IP is a **private/local address**  
- Not listed in threat intelligence feeds  

**Conclusion:**  
No external malicious activity detected.

---

## Task 3: Alert Triage
- Selected alert: **Agent Event Queue Flooded (Rule ID 204)**  
- Severity Level: **12 (High)**  

**Analysis:**  
- High number of events generated in short time  
- Possible agent misconfiguration or system overload  

**Status:**  
Escalated for further investigation.

---

## Task 4: Incident Escalation
- Escalated alert to **Tier 2 SOC Team**  

**Summary:**  
A high-severity alert was triggered due to excessive event generation from the endpoint. Initial investigation indicates system misconfiguration rather than a cyber attack. Further analysis is required to confirm root cause.

---

## Task 5: Evidence Collection
- Exported logs from Wazuh dashboard  
- Captured screenshots of:
  - Alerts  
  - Threat hunting events  
  - FIM (File Integrity Monitoring)  
  - Dashboard overview  

**Outcome:**  
All evidence preserved for incident documentation and analysis.

---

## Key Findings
- Alert triggered due to **event flooding**
- No malicious IP detected
- System behavior indicates **configuration issue**
- Proper SOC workflow followed (Detection → Triage → Escalation → Documentation)

---

## Conclusion
The investigation confirmed that the alert was caused by system-level event flooding rather than a real cyber attack. The task successfully demonstrates practical SOC skills including monitoring, analysis, and incident handling using Wazuh SIEM.

---

## Future Improvements
- Implement alert threshold tuning  
- Improve agent configuration  
- Integrate advanced threat intelligence feeds  
- Automate incident response workflows  

---

## Author
**Vinayaka Reddy**  
Cybersecurity Enthusiast | SOC Analyst Learner  
