# Botium Toys Risk Assessment

## Overall Risk

**Risk Score: 8/10 — High**

The assessment identified significant weaknesses in Botium Toys' security posture. The most important risks involve unauthorized access, sensitive customer data, business continuity, and compliance.

## Key Risk Areas

### 1. Unauthorized Access

All employees currently have access to internally stored data and may be able to access customer PII/SPII and cardholder data.

**Risk:** A compromised employee account or malicious insider could access sensitive information unnecessarily.

**Recommended mitigation:** Implement least privilege, access control policies, and separation of duties.

### 2. Customer Payment Data

Customer credit card information is not encrypted.

**Risk:** Sensitive payment information could be exposed if unauthorized individuals gain access to the database or other systems handling the data.

**Recommended mitigation:** Implement appropriate encryption procedures and restrict access to authorized personnel.

### 3. Data Loss and Business Continuity

Botium Toys does not currently maintain backups of critical data and does not have a disaster recovery plan.

**Risk:** A major security incident, system failure, or other disruptive event could result in significant data loss and business interruption.

**Recommended mitigation:** Establish regular backups and develop a disaster recovery plan.

### 4. Weak Authentication

The existing password policy does not meet stronger password complexity requirements, and there is no centralized password management system.

**Risk:** Weak authentication controls can increase the likelihood of account compromise.

**Recommended mitigation:** Strengthen password requirements and implement centralized password management.

### 5. Limited Threat Detection

Botium Toys has a firewall and antivirus software but does not currently have an intrusion detection system.

**Risk:** Suspicious or anomalous network activity may be more difficult to identify.

**Recommended mitigation:** Implement an IDS and establish appropriate monitoring procedures.

### 6. Asset Management

Botium Toys does not have adequate asset management and classification practices.

**Risk:** The organization may have difficulty identifying which assets and data require stronger protection.

**Recommended mitigation:** Maintain an accurate asset inventory and classify data according to sensitivity and business impact.

### 7. Legacy Systems

Legacy systems are monitored and maintained, but there is no regular maintenance schedule and intervention methods are unclear.

**Risk:** Outdated systems may contain vulnerabilities that remain unidentified or unresolved.

**Recommended mitigation:** Establish a documented schedule for monitoring, maintenance, and intervention.

## Risk Priority

| Risk                                  | Priority |
| ------------------------------------- | -------- |
| Unauthorized access to sensitive data | High     |
| Unencrypted customer payment data     | High     |
| Lack of backups and disaster recovery | High     |
| Weak authentication controls          | High     |
| Limited threat detection              | Medium   |
| Inadequate asset management           | Medium   |
| Legacy-system maintenance             | Medium   |

## Conclusion

Botium Toys has several security controls in place, but significant gaps remain. The organization's reported risk score of **8/10** reflects the potential impact of these weaknesses.

The highest priorities should be protecting sensitive customer information, restricting access, establishing reliable backups and recovery procedures, strengthening authentication, and improving asset management.
