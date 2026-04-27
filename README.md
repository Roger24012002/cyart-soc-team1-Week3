#  CyArt SOC Team – Week 3  
## Advanced Security Analysis using Wazuh SIEM

---

##  Overview

This repository contains the **Week 3 SOC Advanced Analysis Task** completed as part of the **CyArt SOC Team Program**. The project focuses on practical Security Operations Center (SOC) analyst responsibilities using **Wazuh SIEM**, including:

- Advanced Log Analysis  
- Alert Triage  
- Threat Intelligence Validation  
- File Integrity Monitoring (FIM)  
- Incident Investigation  
- Evidence Collection  
- Security Reporting  

The objective was to strengthen practical SOC skills through hands-on investigation of alerts and suspicious events in a monitored lab environment.

---

##  Tools & Technologies Used

- Wazuh SIEM  
- Wazuh Threat Hunting Module  
- Windows Endpoint Agent  
- VirusTotal  
- AlienVault OTX  
- File Integrity Monitoring (FIM)  
- GitHub  

---

##  Repository Structure

```text
cyart-soc-team1-Week3/
├── Evidence/
│   └── wazuh_alert_logs.csv
├── Reports/
│   └── Week3_SOC_Report.pdf
├── Screenshots/
│   ├── agent_details.png
│   ├── agent_summary.png
│   ├── fim_event_details.png
│   ├── fim_events.png
│   ├── otx_check.png
│   ├── queue_flooded_alert.png
│   ├── queue_flooded_events.png
│   ├── threat_events.png
│   ├── threat_hunting_dashboard.png
│   ├── virustotal_check.png
│   ├── wazuh_dashboard.png
│   └── wazuh_login.png
├── Tables/
│   ├── alert_triage.txt
│   └── threat_intelligence.txt
└── README.md
````

---

#  Tasks Completed

---

##  Task 1: Advanced Log Analysis

The Wazuh Threat Hunting module was used to analyze security events and identify abnormal activity.

### Findings:

* High severity alerts detected
* Event queue flooding observed
* Multiple alerts generated in short time period

### Outcome:

Potential system overload or agent logging misconfiguration identified.

---

##  Task 2: Threat Intelligence Validation

Suspicious IP indicators were validated using:

* VirusTotal
* AlienVault OTX

### Findings:

* Checked IP reputation successfully
* No confirmed malicious external threat detected
* Private/local network indicators identified

---

##  Task 3: Alert Triage

A high severity alert was selected and investigated.

### Alert Details

| Field      | Value                     |
| ---------- | ------------------------- |
| Alert Name | Agent Event Queue Flooded |
| Rule ID    | 204                       |
| Severity   | High                      |
| Level      | 12                        |

### Analysis:

The endpoint generated a large number of events rapidly, likely due to logging noise or configuration issues.

---

##  Task 4: File Integrity Monitoring (FIM)

Wazuh FIM module was reviewed to monitor file changes and suspicious modifications.

### Outcome:

* File change events successfully logged
* File monitoring visibility confirmed
* Useful for insider threat and malware detection

---

##  Task 5: Incident Investigation & Evidence Collection

Evidence collected and documented:

* Dashboard screenshots
* Threat Hunting logs
* Alert details
* FIM events
* Exported CSV logs
* Final report documentation

---

#  Key Findings

* High severity alerts successfully detected
* Queue flooding events analyzed
* Threat intelligence checks completed
* File monitoring evidence reviewed
* SOC workflow executed successfully:

**Detection → Analysis → Triage → Investigation → Documentation**

---

#  Skills Demonstrated

* SIEM Monitoring
* Log Analysis
* Threat Hunting
* Alert Triage
* Threat Intelligence Validation
* Incident Investigation
* FIM Monitoring
* SOC Reporting

---

#  Screenshots Included

* Wazuh Login Panel
* Dashboard Overview
* Threat Hunting Dashboard
* Queue Flooded Alert
* FIM Events
* VirusTotal Check
* OTX Intelligence Check
* Agent Details

---

#  Conclusion

This Week 3 project successfully demonstrates advanced SOC analyst activities using **Wazuh SIEM**. Alerts were monitored, suspicious activity was investigated, threat intelligence checks were performed, and evidence was documented professionally.

The project provided strong practical exposure to:

* Real-time Alert Monitoring
* Incident Investigation
* Threat Intelligence Usage
* File Integrity Monitoring
* Security Documentation

This hands-on work reflects practical SOC operations used in enterprise environments.

---

#  Future Improvements

* Tune noisy alert rules
* Improve endpoint log filtering
* Add automated response playbooks
* Expand MITRE ATT&CK mapping
* Integrate additional intelligence feeds

---

# 👨‍💻 Author

**Vinayaka Reddy**
Cybersecurity Enthusiast | SOC Analyst Learner | SIEM | Threat Hunting | Incident Response

```
```
