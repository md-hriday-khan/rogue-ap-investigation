# 🔍 Wireless Interception & Insider Threat Case Study UK
# Digital Forensics & Incident Response (DFIR) Project
 Simulating a rogue wireless (wardriving) attack and insider threat scenario in a corporate environment.
> A corporate forensic investigation scenario based in Luton, UK, involving suspected wireless traffic interception, trade secret theft, and cybercrime.

---
## 🛡️ Overview

This project presents a realistic digital forensics investigation scenario based in Luton, UK, involving:

A suspected rogue access point (AP) / wardriving attack
Possible unauthorised interception of wireless communications
Indicators of credential harvesting and financial data theft
A potential insider threat linked to corporate data leakage

The case is analysed using industry-standard DFIR practices, including forensic evidence handling, incident response, and UK legal compliance.

## 📋 Table of Contents

- [Scenario Overview](#scenario-overview)
- [Assignment Brief](#assignment-brief)
- [Investigation Objectives](#investigation-objectives)
- [Key Questions](#key-questions)
- [Deliverables](#deliverables)
- [ACPO Principles](#acpo-principles)
- [Relevant Legislation](#relevant-legislation)
- [Evidence Checklist](#evidence-checklist)
- [Security Cycle Analysis](#security-cycle-analysis)
- [Report Requirements](#report-requirements)
- [Team & Contributions](#team--contributions)

---

## 🗂️ Scenario Overview

On **1st October 2025**, An abandoned device setup was recovered containing:

- 💻 A laptop system
- 📡 A wireless network card
- 🔌 An external serial antenna

It is suspected that this equipment was used for **malicious wardriving** — a technique where a perpetrator drives within range of Wireless Access Points (WAPs) to:

- Intercept and capture unencrypted internet traffic
- Steal financial information (bank card details, credentials)
- Harvest usernames and passwords illegally

---

**Context:** AS a corporate forensic investigator employed by a digital forensics organisation in **Luton, UK**.

**Situation:**
- Rumours indicate a portfolio manager / marketing lead is planning to defect to a competitor based in **Bedford**.
- The organisation has begun noticing that this competitor is targeting its potential customers.
- Suspicious activity has been identified internally.

---

## 🎯 Investigation Objectives

| # | Objective |
|---|-----------|
| 1 | Critically assess the case from a **Computer Security** perspective |
| 2 | Compile a list of **Digital Forensic investigation evidence** |
| 3 | Analyse the role of the **Security Cycle** in this investigation |
| 4 | Prove the **ACPO 5-principle audit trail** |
| 5 | Identify and analyse any **cybercrime attempts** |
| 6 | Ensure compliance with UK laws **relevant computer laws** and forensic standards  |

---

## ❓ Key Questions

1. Does this scenario qualify as a **Digital Forensics investigation case**? 
2. What digital evidence could be recovered from the abandoned equipment?
3. What cybercrime offences may have been committed?
4. How does the suspected insider threat relate to the wardriving activity?
5. What are the legal implications under UK computer law?


```

 🔍 Investigation Approach

🧪 Forensic Methodology

The investigation follows structured DFIR processes using tools such as:

Wireshark – packet capture & traffic analysis
Autopsy – disk and artefact examination
FTK Imager – forensic acquisition and hashing

 ⚠️ Threat & Attack Analysis
The case indicates potential use of:

Man-in-the-middle attack
Packet sniffing
Rogue access point deployment
Credential interception and session hijacking

🧠 Risk Context
Sensitive data exposure (credentials, financial details)
Corporate espionage risk
Insider-assisted targeting of customers

📂 Evidence Overview
Physical Evidence
Laptop device (forensic imaging required)
Wireless adapter (MAC, chipset analysis)
External antenna (range amplification capability)
Digital Evidence
Packet capture files (.pcap)
Wireless scanning logs (SSID/BSSID mapping)
Browser artefacts & stored credentials
User activity logs and timestamps
Network Evidence
Access point logs
DHCP / authentication logs
Corporate network access records

```
---

## 🏛️ ACPO Principles

The investigation must demonstrate compliance with all **5 ACPO (Association of Chief Police Officers) Good Practice Guide** principles for digital evidence:

| Principle | Description |
|-----------|-------------|
| **1** | No action taken should change data held on a computer or storage media which may subsequently be relied upon in court |
| **2** | In exceptional circumstances where it is necessary to access original data, the person doing so must be competent and able to give evidence explaining the relevance and implications of their actions |
| **3** | An audit trail or other record of all processes applied to computer-based evidence should be created and preserved; an independent third party should be able to examine those processes and achieve the same result |
| **4** | The person in charge of the investigation has overall responsibility for ensuring that the law and these principles are adhered to |
| **5** | Any agency using this guidance must ensure it is implemented and regularly reviewed |

---

## ⚖️ Relevant Legislation

The following UK laws are relevant to this case and should be discussed in the report:

- **Computer Misuse Act 1990** — Unauthorised access, modification, and intent to commit further offences
- **Police and Criminal Evidence Act (PACE) 1984** — Rules governing seizure and handling of digital evidence
- **Data Protection Act 2018 / UK GDPR** — Unlawful processing of personal data intercepted
- **Fraud Act 2006** — Obtaining financial information by deception / dishonestly
- **Regulation of Investigatory Powers Act (RIPA) 2000** — Interception of communications
- **Human Rights Act 1998** — Privacy considerations during investigation
- **Criminal Justice and Police Act 2001** — Powers of seizure

---


---

## 🔄 Security Cycle Analysis

The report must critically analyse the role within the **Security Cycle**:

```
     ┌─────────────┐
     │   IDENTIFY  │ ← Recognise threats and vulnerabilities
     └──────┬──────┘
            ▼
     ┌─────────────┐
     │   PROTECT   │ ← Implement safeguards
     └──────┬──────┘
            ▼
     ┌─────────────┐
     │   DETECT    │ ← Monitor for incidents
     └──────┬──────┘
            ▼
     ┌─────────────┐
     │   RESPOND   │ ← Contain and investigate
     └──────┬──────┘
            ▼
     ┌─────────────┐
     │   RECOVER   │ ← Restore and learn
     └─────────────┘
```

Consider where the organisation failed in the cycle and how Digital Forensics fits within the **Respond** and **Recover** phases.

---


---

## ⚠️ Disclaimer

> This repository is created for **academic purposes only** as part of a Digital Forensics university unit. All scenarios described are fictional and intended solely to support learning outcomes in digital forensics investigation methodology.

---

*Last updated: October 2025 | Luton, UK | Digital Forensics Unit*
