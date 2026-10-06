# Botium Toys Security Audit Findings

## Executive Summary

The internal security audit identified several weaknesses in Botium Toys' security controls and compliance practices.

The organization's reported risk score is **8/10**, indicating a relatively high level of risk. The most significant concerns involve access control, protection of sensitive customer information, business continuity, and compliance.

## Control Assessment

| Control                    | Status            | Finding                                                                     |
| -------------------------- | ----------------- | --------------------------------------------------------------------------- |
| Least Privilege            | Not Implemented   | Employees have broad access to internally stored data.                      |
| Disaster Recovery Plans    | Not Implemented   | No disaster recovery plan is currently in place.                            |
| Password Policies          | Needs Improvement | Existing password requirements are below recommended complexity standards.  |
| Separation of Duties       | Not Implemented   | Separation of duties has not been established.                              |
| Firewall                   | Implemented       | A firewall is configured with defined security rules.                       |
| Intrusion Detection System | Not Implemented   | No IDS is currently installed.                                              |
| Backups                    | Not Implemented   | Critical data is not backed up.                                             |
| Antivirus Software         | Implemented       | Antivirus software is installed and regularly monitored.                    |
| Legacy System Monitoring   | Needs Improvement | Legacy systems are monitored, but there is no regular maintenance schedule. |
| Encryption                 | Not Implemented   | Customer credit card information is not encrypted.                          |
| Password Management        | Not Implemented   | No centralized password management system exists.                           |
| Physical Locks             | Implemented       | The physical location has sufficient locks.                                 |
| CCTV Surveillance          | Implemented       | Up-to-date CCTV surveillance is in place.                                   |
| Fire Detection/Prevention  | Implemented       | Fire detection and prevention systems are functioning.                      |

## Key Risks

### 1. Unauthorized Access

Employees may have access to sensitive internal data beyond what is required for their roles. This increases the potential impact of compromised accounts or malicious insider activity.

### 2. Sensitive Data Exposure

Customer credit card information is stored without encryption, creating a significant confidentiality risk.

### 3. Business Continuity

The absence of backups and a disaster recovery plan increases the risk of data loss and disruption following a security incident or other major event.

### 4. Weak Authentication Controls

The existing password policy does not meet stronger password complexity requirements, and there is no centralized password management system.

### 5. Limited Threat Detection

The organization has a firewall and antivirus software but does not have an intrusion detection system, reducing its ability to identify certain suspicious network activity.

### 6. Asset Management

Botium Toys does not have adequate asset management and classification practices, making it more difficult to determine which assets require additional protection.

## Overall Assessment

Botium Toys has several foundational security controls in place, particularly around network filtering, endpoint protection, and physical security. However, significant gaps remain in access control, data protection, recovery capabilities, authentication, monitoring, and asset management.

The reported **8/10 risk score** is consistent with the number and importance of these control gaps.

## Priority

The organization should prioritize:

1. Protecting sensitive customer data.
2. Implementing least privilege and separation of duties.
3. Establishing backups and disaster recovery.
4. Strengthening password and account management.
5. Improving asset inventory and classification.
6. Enhancing security monitoring and detection.
