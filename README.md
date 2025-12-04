# Enterprise GRC Implementation Simulation 

## Overview
This project simulates a full-cycle **Governance, Risk, and Compliance (GRC)** implementation for a technology-driven enterprise. It demonstrates the practical application of industry frameworks (**ISO 27001**, **NIST CSF**, **DPDP Act**) to identify risks, govern security policies, and manage third-party vendors.

##  Project Artifacts

### 1. Risk Register (`Risk_Register.csv`)
A dynamic risk assessment engine based on the standard risk formula:
$$Risk = Likelihood \times Impact$$

* **Methodology:** 5x5 Risk Matrix.
* **Key Feature:** Each identified risk is mapped directly to an **ISO 27001 Annex A Control** (e.g., *A.12.3 Backup*).
* **Scenarios Covered:** Ransomware, Cloud Misconfiguration (AWS), Supply Chain attacks, and TLS Protocol vulnerabilities.

### 2. Vendor Due Diligence
A simulated Third-Party Risk Management (TPRM) workflow to evaluate vendor security posture before onboarding.
* **Focus:** Assesses compliance with **SOC 2** and **ISO 27001**.
* **Critical Checks:** Encryption standards (AES-256), Data Residency (India/DPDP), and Breach Notification SLAs.

### 3. ISMS Policy Architecture
Drafted governance policies aligned with **ISO 27001** standards:
* **Access Control:** Enforcing *Least Privilege* and *Role-Based Access Control (RBAC)*.
* **Data Privacy:** Compliance with the **Digital Personal Data Protection (DPDP) Act 2023**, focusing on *Consent* and *Purpose Limitation*.

##  Frameworks Applied
* **NIST Cybersecurity Framework (CSF):** Mapped risks to Identify, Protect, and Recover functions.
* **ISO/IEC 27001:2013:** Used for control mapping and ISMS structure.
* **Shared Responsibility Model:** Applied to Cloud/AWS risk scenarios.

---
*This simulation was built to demonstrate readiness for the Infosec - GRC Engineer role.*
