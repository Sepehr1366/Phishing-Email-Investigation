# Phishing Email Investigation

## Overview

This project demonstrates an end-to-end phishing email investigation performed using industry-standard SOC Analyst methodologies. The investigation includes email header analysis, IOC extraction, threat intelligence research, and MITRE ATT&CK mapping to determine the nature of the phishing attempt.

The objective of this project is to simulate a real-world phishing investigation while documenting each step of the analysis process.

---

## Objectives

- Analyze a phishing email sample (.eml)
- Examine email headers
- Verify SPF, DKIM, and DMARC records
- Extract Indicators of Compromise (IOCs)
- Investigate IP addresses, domains, and URLs
- Perform threat intelligence analysis
- Map attacker behavior to the MITRE ATT&CK Framework
- Produce professional investigation reports

---

## Tools Used

- VirusTotal
- MXToolbox
- WHOIS
- CyberChef
- MITRE ATT&CK
- GitHub

---

## Skills Demonstrated

- Email Header Analysis
- Email Authentication (SPF, DKIM, DMARC)
- IOC Extraction
- Threat Intelligence Analysis
- URL Reputation Analysis
- IP Reputation Analysis
- Domain Investigation
- Base64 Decoding
- MITRE ATT&CK Mapping
- Incident Documentation
- Technical Report Writing

---

## Repository Structure

```
Phishing-Email-Investigation/
│
├── Sample_Email/
│   ├── sample-1.eml
│   └── README.md
│
├── IOCs/
│   └── IOCs.pdf
│
├── Report/
│   ├── Analysis Report.pdf
│   └── Incident Report.pdf
│
└── Screenshots/
    └── Investigation screenshots
```

---

## Investigation Workflow

### Phase 1 – Email Collection

- Collected the phishing email sample
- Preserved the original email (.eml)

### Phase 2 – Header Analysis

- Reviewed email headers
- Identified sender information
- Verified SPF, DKIM, and DMARC
- Traced the sender IP

### Phase 3 – IOC Extraction

Extracted:

- IP Addresses
- Domains
- Email Addresses
- URLs
- Message IDs

---

### Phase 4 – Threat Intelligence

Investigated extracted IOCs using:

- VirusTotal
- MXToolbox
- WHOIS

The investigation included:

- IP reputation
- Domain reputation
- URL reputation
- Registration information
- Blacklist status

---

### Phase 5 – MITRE ATT&CK Mapping

Mapped observed attacker behavior to the MITRE ATT&CK Framework.

Technique Used:

- **T1566.002 – Phishing: Spearphishing Link**

Tactic:

- Initial Access

---

## Key Findings

- The email impersonated a trusted financial institution.
- The sender attempted to persuade the recipient to click a phishing link.
- Threat intelligence analysis showed no active malware detections; however, the email exhibited multiple phishing indicators.
- Multiple IOCs were extracted and documented.
- MITRE ATT&CK mapping identified the phishing technique as **T1566.002 – Spearphishing Link**.

---

## Reports

This repository includes:

- Email Analysis Report
- Incident Response Report
- IOC Report

---

## Learning Outcomes

Through this project, I gained hands-on experience with:

- Email forensic analysis
- IOC extraction
- Threat intelligence research
- MITRE ATT&CK mapping
- Professional cybersecurity documentation
- GitHub project organization

---

## Disclaimer

This repository is intended for educational purposes only. The phishing email sample is analyzed in a controlled environment to demonstrate SOC Analyst investigation techniques.
