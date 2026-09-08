# Risk Assessment Methodology

## 1. Overview

This document describes the methodology used to identify, assess, prioritize, and treat cybersecurity risks as part of the simulated GRC assessment for SecurePay Solutions Pvt. Ltd.

The methodology is designed for portfolio and educational purposes and is based on a simple qualitative risk assessment approach.

---

## 2. Assessment Process

The risk assessment follows these stages:

```text
Asset Identification
        ↓
Threat Identification
        ↓
Vulnerability Identification
        ↓
Risk Identification
        ↓
Likelihood Assessment
        ↓
Impact Assessment
        ↓
Risk Score Calculation
        ↓
Risk Classification
        ↓
Risk Treatment
        ↓
Remediation Planning
```

---

## 3. Asset Identification

Critical business and technology assets were identified based on their importance to SecurePay's operations.

Examples include:

* Customer Database
* Web Application
* Cloud Infrastructure
* Employee Accounts
* Employee Laptops
* Backup System
* Corporate Email
* Firewall
* VPN
* Source Code Repository

Each asset was assigned a criticality level and evaluated using the Confidentiality, Integrity, and Availability (CIA) triad.

---

## 4. Risk Identification

Risks were identified by considering:

* Critical organizational assets
* Potential threats
* Existing vulnerabilities or weaknesses
* Potential business impact
* Existing security controls

Example:

> Threat: Phishing
> Vulnerability: Incomplete MFA coverage
> Asset: Employee Accounts
> Risk: Phishing could compromise employee credentials and allow unauthorized access to company systems.

---

## 5. Likelihood Assessment

Likelihood represents the estimated probability that a risk event could occur.

| Score | Rating         | Description                                |
| ----: | -------------- | ------------------------------------------ |
|     1 | Rare           | Very unlikely to occur                     |
|     2 | Unlikely       | Could occur but is not expected            |
|     3 | Possible       | Could reasonably occur                     |
|     4 | Likely         | Expected to occur under certain conditions |
|     5 | Almost Certain | Highly likely to occur                     |

---

## 6. Impact Assessment

Impact represents the potential consequence to the organization's confidentiality, integrity, availability, operations, finances, reputation, or compliance position.

| Score | Rating        | Description                                                    |
| ----: | ------------- | -------------------------------------------------------------- |
|     1 | Insignificant | Minimal business impact                                        |
|     2 | Minor         | Limited disruption or loss                                     |
|     3 | Moderate      | Noticeable operational or business impact                      |
|     4 | Major         | Significant business disruption or loss                        |
|     5 | Severe        | Serious impact to critical operations or sensitive information |

---

## 7. Risk Score Calculation

Risk score is calculated using:

**Risk Score = Likelihood × Impact**

Example:

```text
Likelihood = 4
Impact = 5

Risk Score = 4 × 5
           = 20
```

A score of 20 is classified as Critical.

---

## 8. Risk Classification

| Score | Rating   | Priority             |
| ----: | -------- | -------------------- |
|   1–4 | Low      | Monitor              |
|   5–9 | Medium   | Planned remediation  |
| 10–16 | High     | Priority remediation |
| 17–25 | Critical | Immediate attention  |

---

## 9. Risk Treatment

Four treatment approaches were considered:

### Mitigate

Implement or improve controls to reduce the likelihood or impact of the risk.

### Avoid

Remove the activity or condition responsible for the risk.

### Transfer

Transfer some financial or operational consequences to another party, where appropriate.

### Accept

Formally accept the risk when it falls within the organization's defined risk tolerance.

---

## 10. Control Assessment

Existing controls were reviewed to determine whether they were:

* Implemented
* Partially Implemented
* Not Implemented

Examples of assessed controls include:

* Multi-Factor Authentication
* Role-Based Access Control
* Endpoint Protection
* Vulnerability Management
* Data Backup
* Firewall
* Logging and Monitoring
* Incident Response
* Access Reviews

---

## 11. Risk-Control Mapping

Identified risks were mapped to relevant security controls.

For example:

```text
Phishing Risk
      ↓
Multi-Factor Authentication
      +
Security Awareness Training
```

This helps determine whether existing controls adequately address identified risks.

---

## 12. Risk Prioritization

Risks with higher likelihood and impact receive greater remediation priority.

Critical risks are prioritized first, followed by high, medium, and low risks.

Additional factors that may influence prioritization include:

* Criticality of affected assets
* Sensitivity of information
* Business disruption
* Existing control effectiveness
* Cost and complexity of remediation

---

## 13. Residual Risk

Residual risk represents the risk remaining after existing controls are considered.

For this portfolio assessment, the primary risk register focuses on the assessed risk level and existing controls. A formal residual-risk calculation can be incorporated into future versions of the assessment.

---

## 14. Review

The risk assessment should be reviewed periodically and whenever significant changes occur to:

* Business processes
* Technology
* Threat environment
* Organizational structure
* Critical assets
* Security controls

---

## 15. Disclaimer

This methodology is part of a simulated GRC portfolio project. SecurePay Solutions Pvt. Ltd. is a fictional organization, and the risks, controls, ratings, and assessment results are simulated for educational purposes.
