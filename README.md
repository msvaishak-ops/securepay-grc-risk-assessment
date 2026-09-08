
# 🔐 GRC Risk Assessment & ISO 27001 Gap Analysis — SecurePay Solutions

## 📌 Project Overview

This project presents a **simulated Governance, Risk, and Compliance (GRC) assessment** conducted for **SecurePay Solutions Pvt. Ltd.**, a fictional FinTech organization providing online payment services.

The purpose of this project is to demonstrate practical understanding of **cybersecurity risk management, security controls, compliance assessment, and remediation planning** in a GRC environment.

The assessment uses **ISO/IEC 27001** as the primary reference framework and applies a structured risk assessment methodology based on **likelihood and business impact**.

> ⚠️ **Disclaimer:** SecurePay Solutions Pvt. Ltd. is a fictional organization created solely for educational and portfolio purposes. All assets, risks, controls, evidence, findings, and assessment results in this project are simulated. No real customer, production, or confidential information was used. This project does not represent an official ISO/IEC 27001 audit or certification.

---

## 🎯 Project Objectives

The main objectives of this assessment are to:

* Identify and classify critical organizational assets.
* Identify cybersecurity threats, vulnerabilities, and associated risks.
* Assess risks based on likelihood and business impact.
* Develop a structured cybersecurity risk register.
* Identify and document security controls.
* Map identified risks to relevant security controls.
* Perform an ISO 27001-based compliance gap assessment.
* Identify control weaknesses and compliance gaps.
* Develop risk treatment and remediation recommendations.
* Track remediation activities and ownership.
* Develop an Excel-based GRC dashboard for management reporting.

---

## 🏢 Organization Profile

**Organization:** SecurePay Solutions Pvt. Ltd.
**Industry:** Financial Technology / Online Payments
**Organization Type:** Fictional Private Limited Company
**Employees:** Approximately 50
**Headquarters:** Bengaluru, Karnataka, India
**Assessment Type:** Simulated GRC Risk Assessment
**Primary Framework:** ISO/IEC 27001
**Supporting Framework:** NIST Cybersecurity Framework
**Assessment Period:** September 2026

### Business Overview

SecurePay Solutions is a fictional online payment platform that enables customers and business users to manage accounts, initiate digital payments, view transaction information, and receive payment notifications.

The organization relies on cloud infrastructure, web applications, databases, identity management, employee endpoints, and network security technologies to support its operations.

Due to the sensitive nature of payment-related and customer information, **confidentiality, integrity, and availability** are considered key security objectives.

---

## 🔍 Assessment Scope

### In Scope

The assessment covers:

* Customer-facing web application
* Customer database
* Cloud infrastructure
* Employee laptops
* Employee accounts
* Corporate email
* VPN
* Firewall
* Backup infrastructure
* Source code repository
* Identity and access management
* Vulnerability management
* Security monitoring
* Incident response
* Security awareness

### Out of Scope

The following areas were excluded:

* Physical data center security
* Detailed financial auditing
* Third-party payment processor assessments
* Penetration testing
* Actual production infrastructure
* Real customer information
* Legal or regulatory certification activities

---

## 🛠️ Tools & Frameworks

### Tools

* **Microsoft Excel** — Risk register, control inventory, gap assessment, remediation tracking, and dashboard
* **GitHub** — Project documentation and proof of work

### Frameworks & Methodologies

* **ISO/IEC 27001** — Information security management and control reference
* **NIST Cybersecurity Framework** — Supporting cybersecurity reference
* **CIA Triad** — Confidentiality, Integrity, and Availability
* **Risk Assessment Methodology** — Likelihood × Impact
* **Risk Treatment** — Mitigate, Avoid, Transfer, Accept

---

## 🔄 GRC Assessment Methodology

The assessment follows the workflow below:

```text
Asset Identification
        ↓
Threat Identification
        ↓
Risk Identification
        ↓
Likelihood & Impact Assessment
        ↓
Risk Scoring
        ↓
Control Identification
        ↓
Risk-Control Mapping
        ↓
ISO 27001-Based Gap Assessment
        ↓
Risk Treatment
        ↓
Remediation Planning
        ↓
GRC Dashboard & Reporting
```

---

## 📊 Risk Assessment Methodology

Risk is calculated using:

```text
Risk Score = Likelihood × Impact
```

### Likelihood Scale

| Score | Description    |
| ----: | -------------- |
|     1 | Rare           |
|     2 | Unlikely       |
|     3 | Possible       |
|     4 | Likely         |
|     5 | Almost Certain |

### Impact Scale

| Score | Description   |
| ----: | ------------- |
|     1 | Insignificant |
|     2 | Minor         |
|     3 | Moderate      |
|     4 | Major         |
|     5 | Severe        |

### Risk Classification

| Risk Score | Rating   |
| ---------: | -------- |
|        1–4 | Low      |
|        5–9 | Medium   |
|      10–16 | High     |
|      17–25 | Critical |

---

## 📦 Key Assets Identified

The assessment identified 10 major business and technology assets:

| Asset ID | Asset                  | Criticality |
| -------- | ---------------------- | ----------- |
| AST-001  | Customer Database      | Critical    |
| AST-002  | Web Application        | Critical    |
| AST-003  | Cloud Infrastructure   | Critical    |
| AST-004  | Employee Laptops       | High        |
| AST-005  | Corporate Email        | High        |
| AST-006  | Employee Accounts      | Critical    |
| AST-007  | Backup System          | Critical    |
| AST-008  | Firewall               | High        |
| AST-009  | VPN                    | High        |
| AST-010  | Source Code Repository | High        |

---

## ⚠️ Risk Assessment Results

A total of **15 cybersecurity risks** were identified and assessed.

Major risk areas included:

* Phishing and credential compromise
* SQL injection
* Cloud misconfiguration
* Ransomware
* Weak passwords
* Insider threats
* Backup failure
* DDoS attacks
* Lost or stolen devices
* Unpatched systems
* Excessive user privileges
* Source code repository compromise
* Email account compromise
* Firewall misconfiguration
* Delayed security incident detection

### Highest-Priority Risks

| Risk ID | Risk                                       | Score | Rating   |
| ------- | ------------------------------------------ | ----: | -------- |
| RSK-001 | Phishing causing account compromise        |    20 | Critical |
| RSK-010 | Exploitation of unpatched systems          |    20 | Critical |
| RSK-004 | Ransomware affecting endpoints             |    16 | High     |
| RSK-005 | Weak passwords causing unauthorized access |    16 | High     |
| RSK-013 | Employee email account compromise          |    16 | High     |

---

## 🛡️ Security Controls

The assessment documented controls across preventive, detective, and corrective categories.

Key controls include:

* Multi-Factor Authentication
* Role-Based Access Control
* Endpoint Protection
* Security Awareness Training
* Vulnerability Management
* Data Backup
* Firewall
* Logging & Monitoring
* Incident Response Plan
* Access Reviews
* Password Policy
* Secure Coding Practices
* Email Security
* Device Encryption
* Change Management

Controls were assessed as:

* **Implemented**
* **Partially Implemented**
* **Not Implemented**

---

## 🔗 Risk-Control Mapping

Identified risks were mapped to relevant security controls.

Example:

```text
RSK-001 Phishing
       ↓
CTRL-001 MFA
       +
CTRL-004 Security Awareness Training
```

```text
RSK-010 Unpatched Systems
       ↓
CTRL-005 Vulnerability Management
       +
CTRL-015 Change Management
```

This mapping helps determine whether existing controls adequately address identified risks.

---

## 📋 ISO 27001-Based Gap Assessment

A simulated gap assessment was performed across key information security areas, including:

* Information security policies
* Asset management
* Access control
* Authentication
* Security awareness
* Vulnerability management
* Logging and monitoring
* Incident management
* Backup and recovery
* Secure development
* Endpoint security
* Change management

### Key Findings

Major gaps identified included:

* Incomplete MFA coverage
* Inconsistent access reviews
* Formal vulnerability management process requiring improvement
* Limited centralized security monitoring
* Incident response plan requiring testing
* Incomplete endpoint encryption coverage
* Secure development processes requiring additional documentation

> **Note:** This is an ISO 27001-based portfolio assessment and is not an official ISO 27001 certification audit.

---

## 🔧 Remediation Plan

Priority remediation actions were developed for identified risks and control gaps.

Examples include:

| Finding                         | Recommended Action                           | Priority |
| ------------------------------- | -------------------------------------------- | -------- |
| Incomplete MFA coverage         | Enable MFA for all users                     | Critical |
| Incomplete access reviews       | Conduct quarterly access reviews             | High     |
| Vulnerability management gap    | Establish monthly vulnerability scanning     | High     |
| Limited monitoring              | Improve centralized logging and alerting     | High     |
| Untested incident response      | Conduct tabletop exercises                   | High     |
| Incomplete endpoint encryption  | Enable encryption on corporate devices       | High     |
| Inconsistent awareness training | Implement annual security awareness training | Medium   |

---

## 📑 Evidence Management

An **Evidence Register** was created to demonstrate how GRC assessments track supporting documentation.

Examples include:

* MFA configuration records
* Access control configurations
* Endpoint protection reports
* Vulnerability scan reports
* Backup reports
* Firewall configuration reviews
* Incident response documentation
* Access review records
* Security awareness training records

All evidence within this project is **simulated** and created for demonstration purposes.

---

## 📊 GRC Dashboard

The Excel dashboard provides a management-level view of:

* Total risks
* Critical and high risks
* Risk distribution
* Control implementation status
* Compliance gaps
* Remediation status
* Top risks requiring attention

### Dashboard Preview

![GRC Dashboard](Evidence/dashboard.png)

---

## 📸 Project Evidence

### Risk Register

![Risk Register](Evidence/risk_register.png)

### Risk Matrix

![Risk Matrix](Evidence/risk_matrix.png)

### ISO 27001 Gap Assessment

![ISO 27001 Gap Assessment](Evidence/iso27001_gap_assessment.png)

---

## 📁 Project Structure

```text
securepay-grc-risk-assessment/
│
├── README.md
│
├── SecurePay_GRC_Assessment.xlsx
│
├── Report/
│   └── SecurePay_GRC_Assessment_Report.pdf
│
├── Evidence/
│   ├── dashboard.png
│   ├── risk_register.png
│   ├── risk_matrix.png
│   └── iso27001_gap_assessment.png
│
├── Policies/
│   ├── Access_Control_Policy.pdf
│   ├── Password_MFA_Policy.pdf
│   └── Incident_Response_Policy.pdf
│
└── Documentation/
    ├── Risk_Assessment_Methodology.md
    └── Scope_and_Assumptions.md
```

---

## 🎓 Skills Demonstrated

This project demonstrates practical understanding of:

* Governance, Risk & Compliance (GRC)
* Cybersecurity Risk Assessment
* Risk Identification
* Risk Scoring
* Risk Treatment
* Asset Management
* Control Assessment
* Risk-Control Mapping
* ISO 27001 Concepts
* Compliance Gap Analysis
* Remediation Tracking
* Evidence Management
* Security Policy Development
* Excel-based GRC Reporting
* Management Dashboard Development
* Technical Documentation

---

## 🚀 Key Learning Outcomes

Through this project, I developed practical understanding of how a GRC analyst can:

1. Identify and classify organizational assets.
2. Identify threats, vulnerabilities, and cybersecurity risks.
3. Evaluate risk using likelihood and impact.
4. Determine appropriate security controls.
5. Map risks to controls.
6. Identify compliance and control gaps.
7. Prioritize remediation activities.
8. Maintain evidence for assessment purposes.
9. Communicate cybersecurity risks through dashboards and reports.
10. Document GRC activities in a structured and auditable manner.

---

## ⚠️ Disclaimer

This project is entirely **simulated and created for educational and portfolio purposes**.

**SecurePay Solutions Pvt. Ltd. is a fictional organization.** All organizational information, assets, risks, controls, evidence, findings, and assessment results are fictional or simulated.

No real customer data, confidential information, production systems, or organizational security information was used.

This project does **not** represent an official ISO/IEC 27001 audit, certification, compliance attestation, penetration test, or professional security assessment.

---

## 👤 Author

**Vaishak M S**

Cybersecurity | GRC | Risk & Compliance

[GitHub](https://github.com/)

---

⭐ **If you found this project useful, feel free to explore the assessment workbook and project evidence.**
