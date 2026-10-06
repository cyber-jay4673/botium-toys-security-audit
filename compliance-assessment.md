# Botium Toys Compliance Assessment

## Overview

The audit reviewed Botium Toys against selected compliance best practices associated with PCI DSS, GDPR, and SOC.

## PCI DSS

| Best Practice                                                                                   | Assessment |
| ----------------------------------------------------------------------------------------------- | ---------- |
| Only authorized users have access to customers' credit card information                         | **No**     |
| Credit card information is stored, accepted, processed, and transmitted in a secure environment | **No**     |
| Data encryption procedures protect credit card transaction data                                 | **No**     |
| Secure password management policies are adopted                                                 | **No**     |

### PCI DSS Findings

Botium Toys currently allows all employees to access internally stored data, which may include cardholder data. Credit card information is also not encrypted. Password requirements are weak and there is no centralized password management system.

These gaps increase the risk of unauthorized access and exposure of payment information.

## GDPR

| Best Practice                                                      | Assessment |
| ------------------------------------------------------------------ | ---------- |
| E.U. customers' data is kept private/secured                       | **Yes**    |
| A plan exists to notify E.U. customers within 72 hours of a breach | **Yes**    |
| Data is properly classified and inventoried                        | **No**     |
| Privacy policies, procedures, and processes are enforced           | **Yes**    |

### GDPR Findings

Botium Toys has established privacy policies and procedures and has a plan to notify E.U. customers within 72 hours of a security breach.

However, the organization does not adequately classify and inventory its assets and data, creating a gap in its overall data protection practices.

## SOC

| Best Practice                                                                | Assessment |
| ---------------------------------------------------------------------------- | ---------- |
| User access policies are established                                         | **No**     |
| Sensitive data (PII/SPII) is confidential/private                            | **No**     |
| Data integrity ensures data is consistent, complete, accurate, and validated | **Yes**    |
| Data is available to authorized individuals                                  | **Yes**    |

### SOC Findings

Botium Toys has controls supporting data integrity and availability. However, access controls have not been properly implemented, and all employees may have access to sensitive information.

## Overall Compliance Assessment

Botium Toys has several compliance practices in place but has significant gaps involving:

* Access control
* Sensitive data protection
* Encryption
* Password management
* Data classification and inventory

Addressing these weaknesses would reduce the organization's compliance and security risks.
