# SOC Alert Triage Simulation — 10 Real-World Scenarios

## Overview
This project documents my independent analysis of 10 simulated SOC alert scenarios completed as part of my self-directed transition into cybersecurity. Each scenario is based on real-world attack patterns. I researched, analysed, and documented each case independently — covering the full triage process a Tier 1 / Tier 2 SOC Analyst would follow in a production environment.

## Scenarios Covered
| # | Alert | Severity | Classification |
|---|-------|----------|----------------|
| 1 | Brute Force SSH Attack | HIGH | True Positive |
| 2 | Phishing — Credential Harvesting | CRITICAL | True Positive |
| 3 | Encoded PowerShell Execution | HIGH | True Positive |
| 4 | Impossible Travel — Account Compromise | MEDIUM | True Positive |
| 5 | Emotet Malware Detection | CRITICAL | True Positive |
| 6 | SQL Injection via WAF | HIGH | True Positive |
| 7 | DNS Tunnelling — Data Exfiltration | HIGH | True Positive |
| 8 | Active Directory Enumeration | MEDIUM | False Positive |
| 9 | LockBit Ransomware — Multi-Host | CRITICAL | True Positive |
| 10 | Insider Threat — Bulk Data Download | MEDIUM | True Positive |

## Each Scenario Includes
- Alert metadata (source IP, affected host, timestamp, tool detected)
- Initial analysis and investigation steps
- Evidence gathered and threat intelligence enrichment
- Classification decision (True Positive / False Positive) with reasoning
- Recommended response and escalation actions
- Lessons learned and detection improvements

## Tools & Frameworks Used
- MITRE ATT&CK v14
- NIST SP 800-61 (Incident Handling Guide)
- Splunk Free (SIEM analysis)
- TryHackMe SOC Level 1 Path
- LetsDefend Alert Simulation Platform
- VirusTotal (threat intelligence enrichment)
- AbuseIPDB (IP reputation)

## Skills Demonstrated
- SOC alert triage and investigation methodology
- Threat intelligence enrichment and IOC analysis
- True positive vs false positive classification
- Incident escalation decision making
- MITRE ATT&CK TTP mapping
- Written analysis and professional reporting

## About Me
**Vishwas M H** | B.Tech Computer Science & Engineering  
Former .NET Full Stack Developer | Transitioning to Cybersecurity  
Actively preparing for MSc Cybersecurity (Ireland, 2026 intake)  
📧 Connect with me on [www.linkedin.com/in/vishwas-m-h-6830bb1b9]
