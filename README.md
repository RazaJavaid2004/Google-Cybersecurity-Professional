<div align="center">

# 📘 Google Cybersecurity Professional Certificate Portfolio

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Program](https://img.shields.io/badge/Program-Google%20Cybersecurity%20Certificate-4285F4?style=for-the-badge&logo=google&logoColor=white)](#)
[![Focus](https://img.shields.io/badge/Focus-GRC%20%7C%20SecOps%20%7C%20Incident%20Response-34A853?style=for-the-badge)](#)
[![Linux & SQL](https://img.shields.io/badge/Tools-Linux%20%7C%20SQL%20%7C%20Wireshark%20%7C%20SIEM-EA4335?style=for-the-badge)](#)

*A curated collection of security audits, incident response journals, threat models, vulnerability assessments, and technical labs completed during the Google Cybersecurity Professional Certificate.*

</div>

---

## 📌 Overview
This repository houses **15 hands-on deliverables**—including technical reports (`.docx`), visual presentations (`.pptx`), and asset spreadsheets (`.xlsx`)—developed during the **Google Cybersecurity Professional Certificate** program. Each artifact demonstrates applied skills across Governance, Risk, and Compliance (GRC), Incident Response, Threat Modeling, Network Traffic Analysis, Linux Administration, and SQL Log Investigation.

---

## 🗂️ Portfolio Deliverables Index

All artifacts are located inside the [`Cybersecurity Learning/`](./Cybersecurity%20Learning/) directory and are categorized below by core security domain:

### 🛡️ 1. Governance, Risk & Compliance (GRC) & Threat Modeling
| Deliverable | Format | Key Highlights & Objectives |
| :--- | :---: | :--- |
| **[Security Audit](./Cybersecurity%20Learning/Security%20Audit.docx)** | `.docx` | Compliance-aligned internal security audit evaluating organizational controls against NIST CSF & ISO 27001 standards. |
| **[Risk Register](./Cybersecurity%20Learning/Risk%20Register.docx)** | `.docx` | Structured risk documentation detailing Risk IDs, threat categories, likelihood/impact scoring, and mitigation plans. |
| **[PASTA Threat Model](./Cybersecurity%20Learning/PASTA.docx)** | `.docx` | Process for Attack Simulation and Threat Analysis (PASTA) 7-stage risk-centric threat modeling exercise. |
| **[Access Controls](./Cybersecurity%20Learning/Access%20Controls.docx)** | `.docx` | Implementation and review of Principle of Least Privilege (PoLP), RBAC, and identity management controls. |
| **[Home Asset Inventory](./Cybersecurity%20Learning/Home%20Asset%20Inventory.xlsx)** | `.xlsx` | Comprehensive hardware/software asset classification, criticality rating, and exposure tracking spreadsheet. |
| **[Professional Statement](./Cybersecurity%20Learning/Professional%20Statement.docx)** | `.docx` | Personal cybersecurity mission statement highlighting core values, ethical commitment, and career focus. |

### 🚨 2. Incident Response & Threat Intelligence
| Deliverable | Format | Key Highlights & Objectives |
| :--- | :---: | :--- |
| **[Incident Handler Journal](./Cybersecurity%20Learning/Incident%20Handler%20Journal.docx)** | `.docx` | Case study documenting a security incident across the 5W1H framework, timeline reconstruction, and lessons learned. |
| **[Phishing Incident Response](./Cybersecurity%20Learning/Phishing%20Incident%20Response.docx)** | `.docx` | Playbook execution for triaging, containing, and remediating an enterprise email phishing campaign. |
| **[Data Leak Review](./Cybersecurity%20Learning/Data%20Leak%20Review.docx)** | `.docx` | Post-incident root cause analysis (RCA) and containment strategy following an unauthorized data exposure event. |
| **[VirusTotal Report](./Cybersecurity%20Learning/Virus%20Total%20Report.pptx)** | `.pptx` | Visual threat intelligence presentation analyzing malicious file hashes, IoCs, and sandbox behavior in VirusTotal. |

### 🌐 3. Network Security, Vulnerability Assessment & Technical Labs
| Deliverable | Format | Key Highlights & Objectives |
| :--- | :---: | :--- |
| **[Vulnerability Assessment Report](./Cybersecurity%20Learning/Vulnerability%20Assessment%20Report.docx)** | `.docx` | Comprehensive assessment of system vulnerabilities, CVE analysis, severity ratings, and remediation roadmaps. |
| **[Network Traffic Analysis](./Cybersecurity%20Learning/Network%20Traffic%20Analysis.docx)** | `.docx` | Deep packet inspection report identifying anomalous HTTP/DNS traffic patterns and protocol irregularities. |
| **[Wireshark & tcpdump Similarity](./Cybersecurity%20Learning/Wireshark%20%26%20tcpdump%20similarity.pptx)** | `.pptx` | Comparative presentation examining packet capture workflows, BPF filters, and CLI vs. GUI analysis in `tcpdump` and `Wireshark`. |
| **[SQL Queries](./Cybersecurity%20Learning/SQL%20Queries.docx)** | `.docx` | Security log investigation using SQL filters (`WHERE`, `AND`, `OR`, `LIKE`) to detect failed logins and privilege misuse. |
| **[File Permissions in Linux](./Cybersecurity%20Learning/File%20permissions%20in%20Linux.docx)** | `.docx` | Practical Linux security lab auditing directory privileges (`ls -la`) and enforcing least privilege via `chmod`. |

---

## 🛠️ Core Competencies Demonstrated
- **Frameworks & Compliance:** NIST CSF, NIST SP 800-61 (Incident Response), ISO/IEC 27001, PASTA Threat Modeling, CIA Triad
- **Incident Detection & Response:** Triage playbooks, Phishing analysis, Incident Handler Journaling, Root Cause Analysis (RCA), VirusTotal IoC hunting
- **Network & Protocol Analysis:** Packet sniffing, `Wireshark`, `tcpdump`, DNS/HTTP anomaly detection, firewall rule evaluation
- **System & Database Security:** Linux CLI file permission hardening (`chmod`), SQL query filtering for authentication and access audits, Vulnerability management

---

## 📂 Repository Structure

```text
Cybersecurity-Learning-Portfolio/
│
├── Cybersecurity Learning/
│   ├── Access Controls.docx                  → Identity & Access Management (IAM) control analysis
│   ├── Data Leak Review.docx                 → Data breach root-cause & remediation report
│   ├── File permissions in Linux.docx        → Linux CLI authorization & chmod auditing lab
│   ├── Home Asset Inventory.xlsx             → Asset management & risk classification spreadsheet
│   ├── Incident Handler Journal.docx         → Structured incident documentation & timeline log
│   ├── Network Traffic Analysis.docx         → Packet inspection & network anomaly report
│   ├── PASTA.docx                            → 7-stage PASTA threat modeling analysis
│   ├── Phishing Incident Response.docx       → Email phishing triage & containment report
│   ├── Professional Statement.docx           → Cybersecurity career & ethics statement
│   ├── Risk Register.docx                    → Likelihood/impact risk scoring & mitigation register
│   ├── Security Audit.docx                   → NIST/ISO compliance audit report
│   ├── SQL Queries.docx                      → SQL log analysis & anomaly detection queries
│   ├── Virus Total Report.pptx               → Malware hash & IoC analysis presentation
│   ├── Vulnerability Assessment Report.docx  → System vulnerability triage & patching report
│   └── Wireshark & tcpdump similarity.pptx   → Network protocol analyzers comparison deck
│
├── LICENSE                                   → MIT License
└── README.md                                 → Portfolio index & documentation
```

---

## 🚀 How to Navigate

1. **Clone the repository:**
   ```bash
   git clone https://github.com/RazaJavaid2004/Cybersecurity-Learning-Portfolio.git
   ```
2. **Explore by Format:**
   - Open **`.pptx`** files for visual presentations on malware analysis (`Virus Total Report.pptx`) and packet capture tools (`Wireshark & tcpdump similarity.pptx`).
   - Open **`.docx`** files for detailed written audits, incident response playbooks, threat models, and Linux/SQL technical labs.
   - Open **`.xlsx`** files to review structured asset inventory and risk tracking templates.

---

## 📜 License
This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 👤 Author
**Muhammad Raza**  
🔗 [GitHub Profile](https://github.com/RazaJavaid2004)
