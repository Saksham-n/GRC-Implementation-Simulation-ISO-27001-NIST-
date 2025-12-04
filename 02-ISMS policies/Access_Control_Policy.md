# Information Security Access Control Policy
**Document ID:** ISMS-POL-09
**Effective Date:** December 2025
**Alignment:** ISO/IEC 27001:2013 (Annex A.9)

## 1. Objective
To ensure that access to information assets and information processing facilities is restricted to authorized users, protecting against unauthorized access, modification, or theft.

## 2. Scope
This policy applies to all employees, contractors, and third-party vendors accessing [Company Name/Project] infrastructure, including Cloud (AWS) and Internal Portals.

## 3. Policy Statements

### 3.1 Principle of Least Privilege (A.9.1)
Access to systems and data shall be granted only to the minimum extent necessary for a user to perform their job function.

### 3.2 User Access Provisioning (A.9.2)
* **Approval:** All access requests for production environments must be approved by the asset owner.
* **Review:** User access rights must be reviewed **quarterly** (every 90 days).
* **Revocation:** Access rights must be revoked within **24 hours** of employment termination.

### 3.3 Password Management (A.9.4)
* **MFA:** Multi-Factor Authentication (MFA) is mandatory for all:
    * Administrative/Root accounts.
    * Remote Access (VPN).
* **Complexity:** Passwords must be at least 12 characters, including mixed case, numbers, and symbols.
* **Rotation:** Passwords must be changed every 90 days.

### 3.4 Privileged Access Management (PAM)
* Root/Admin access is restricted to the DevOps and Security leads.
* All privileged sessions are logged and audited.
