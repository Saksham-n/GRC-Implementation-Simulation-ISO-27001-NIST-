# Enterprise GRC Implementation Simulation 

##  Overview
This project simulates a full-cycle **Governance, Risk, and Compliance (GRC)** implementation for a technology-driven enterprise. It demonstrates the practical application of industry frameworks (**ISO 27001**, **NIST CSF**, **DPDP Act**) to identify risks, govern security policies, and manage third-party vendors.

> **Technical Integration:** This GRC framework is designed to work alongside my **Automated Compliance Auditor**.
> 🔗 **[View the Java Automation Tool Repository Here]((https://github.com/Saksham-n/Security-Configuration-Compliance-Auditor-Java-))**

---

##  Project Artifacts

### 1. Risk Register (`02-Risk-Register/`)
A dynamic risk assessment engine based on the standard risk formula:
$$Risk = Likelihood \times Impact$$
* **Methodology:** 5x5 Risk Matrix.
* **Key Feature:** Each identified risk is mapped directly to an **ISO 27001 Annex A Control** (e.g., *A.12.3 Backup*).
* **Scenarios Covered:** Ransomware, Cloud Misconfiguration (AWS), Supply Chain attacks, and TLS Protocol vulnerabilities.
* ### 2. Risk Scoring Methodology (The 5x5 Matrix)
To calculate the **Risk Score** in the CSV file, I utilized a standard 5x5 multiplication matrix ($Likelihood \times Impact$).

| Likelihood / Impact | **1 (Negligible)** | **2 (Minor)** | **3 (Moderate)** | **4 (Major)** | **5 (Catastrophic)** |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **5 (Almost Certain)** | Medium (5) | High (10) | High (15) | **Critical (20)** | **Critical (25)** |
| **4 (Likely)** | Low (4) | Medium (8) | High (12) | High (16) | **Critical (20)** |
| **3 (Possible)** | Low (3) | Medium (6) | Medium (9) | High (12) | High (15) |
| **2 (Unlikely)** | Low (2) | Low (4) | Medium (6) | Medium (8) | High (10) |
| **1 (Rare)** | Low (1) | Low (2) | Low (3) | Low (4) | Medium (5) |

**Scoring Legend:**
* 🟢 **1-4 (Low):** Accept Risk (Tolerate)
* 🟡 **5-9 (Medium):** Monitor Risk
* 🟠 **10-19 (High):** Mitigate within 30 days
* 🔴 **20-25 (Critical):** Immediate Action Required (e.g., Ransomware)

### 2. Vendor Due Diligence (`04-Vendor-Due-Diligence/`)
A simulated Third-Party Risk Management (TPRM) workflow to evaluate vendor security posture before onboarding.
* **Focus:** Assesses compliance with **SOC 2** and **ISO 27001**.
* **Critical Checks:** Encryption standards (AES-256), Data Residency (India/DPDP), and Breach Notification SLAs.

### 3. ISMS Policy Architecture (`03-ISMS-Policies/`)
Drafted governance policies aligned with **ISO 27001** standards:
* **Access Control:** Enforcing **Least Privilege** and **Role-Based Access Control (RBAC)** (ISO A.9.2).
* **Data Classification:** Categorizing assets (Public, Confidential, Restricted) to determine encryption requirements.

### 4. Data Privacy Compliance (`05-Data-Privacy-Compliance/`)
Documentation ensuring alignment with India's **Digital Personal Data Protection (DPDP) Act 2023**.
* **Privacy Notice:** Drafting transparency clauses regarding data collection purposes.
* **Key Principles:** Focusing on **Consent Architecture** and **Purpose Limitation** (collecting data only for specific, stated reasons).

---

##  Frameworks Applied

| Framework | Application in Project |
| :--- | :--- |
| **NIST Cybersecurity Framework (CSF)** | Mapped risks to *Identify, Protect,* and *Recover* functions. |
| **ISO/IEC 27001:2013** | Used for control mapping and ISMS Policy structure. |
| **Shared Responsibility Model** | Applied to Cloud/AWS risk scenarios (e.g., S3 Bucket configurations). |
| **DPDP Act 2023** | Applied to privacy notices and data retention schedules. |

---
*This simulation was built to demonstrate readiness for the Infosec - GRC Engineer role.*
