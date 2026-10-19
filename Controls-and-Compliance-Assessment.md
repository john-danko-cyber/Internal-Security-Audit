# Controls and Compliance Assessment

## Overview

This assessment evaluates the security controls and compliance posture of the fictional organization Botium Toys. The assessment was conducted using information provided in the organization's scope, goals, and risk assessment documentation.

The purpose of the assessment was to identify existing security controls, determine security gaps, evaluate compliance considerations, and recommend improvements to reduce organizational risk.

---

## Security Controls Assessment

| Security Control | Status | Assessment |
|---|---|---|
| Least Privilege | ❌ Not Implemented | Access to sensitive information is not sufficiently restricted according to employee responsibilities. |
| Disaster Recovery Plan | ❌ Not Implemented | A formal disaster recovery plan has not been established. |
| Password Policies | ⚠️ Implemented / Needs Improvement | Password requirements exist, but current requirements are insufficient for protecting organizational systems and accounts. |
| Separation of Duties | ❌ Not Implemented | Critical responsibilities and access permissions are not adequately separated. |
| Firewall | ✅ Implemented | A firewall is installed and configured with security rules. |
| Intrusion Detection System (IDS) | ❌ Not Implemented | The organization does not currently have an IDS deployed. |
| Backups | ❌ Not Implemented | Critical organizational data is not adequately backed up. |
| Antivirus Software | ✅ Implemented | Antivirus software is installed and monitored. |
| Legacy System Monitoring | ⚠️ Implemented / Needs Improvement | Legacy systems are monitored manually, but a consistent maintenance schedule is needed. |
| Encryption | ❌ Not Implemented | Sensitive information is not adequately protected through encryption. |
| Password Management System | ❌ Not Implemented | A centralized password management solution has not been implemented. |
| Physical Locks | ✅ Implemented | Physical locations are protected using locks. |
| CCTV Surveillance | ✅ Implemented | CCTV surveillance is used as a physical security control. |
| Fire Detection and Prevention | ✅ Implemented | Fire detection and prevention systems are in place. |

---

## PCI DSS Assessment

| Requirement | Status |
|---|---|
| Restrict access to cardholder information to authorized users | ❌ Not Met |
| Securely store, process, and transmit credit card information | ❌ Not Met |
| Implement encryption procedures | ❌ Not Met |
| Implement secure password management policies | ❌ Not Met |

### Assessment

The organization requires significant improvements to its payment-card security controls. Access restrictions, encryption, and password management should be prioritized to better protect cardholder information.

---

## GDPR Assessment

| Requirement | Status |
|---|---|
| Secure and protect EU customer data | ❌ Not Met |
| Maintain breach notification procedures | ✅ Implemented |
| Properly classify and inventory data | ❌ Not Met |
| Establish privacy policies and procedures | ✅ Implemented |

### Assessment

Although some privacy procedures exist, additional technical and administrative controls are required to appropriately protect customer information and strengthen the organization's data protection practices.

---

## SOC Assessment

| Requirement | Status |
|---|---|
| Establish appropriate user access policies | ❌ Not Met |
| Maintain confidentiality of sensitive information | ❌ Not Met |
| Maintain data integrity | ✅ Implemented |
| Restrict data availability to authorized individuals | ❌ Not Met |

### Assessment

The primary weaknesses involve access control and confidentiality. Implementing stronger authorization mechanisms and protecting sensitive information would improve the organization's security posture.

---

## Conclusion

The assessment identified several significant control gaps that increase organizational risk. The most important areas for improvement include access control, encryption, backup and recovery capabilities, intrusion detection, and password security.

These findings will be used to develop prioritized remediation recommendations as part of the internal security audit.
