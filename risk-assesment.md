# Cybersecurity Risk Assessment

## Overview

This document demonstrates a basic cybersecurity risk assessment for a small organization. The assessment identifies common threats, evaluates their likelihood and potential impact, and recommends security controls to reduce risk.

The purpose of this assessment is to demonstrate practical understanding of risk identification, risk analysis, and security controls.

---

## 1. Scope

The assessment covers the following areas:

- Employee workstations
- User accounts and authentication
- Company network
- Business data
- Email systems
- Cloud services
- Internet-connected devices

---

## 2. Risk Assessment Methodology

Risks are evaluated using two primary factors:

### Likelihood

| Rating | Description |
|---|---|
| Low | Unlikely to occur |
| Medium | Possible to occur |
| High | Likely to occur |

### Impact

| Rating | Description |
|---|---|
| Low | Minimal effect on the organization |
| Medium | Noticeable disruption or limited data loss |
| High | Significant financial, operational, or data impact |

### Risk Level

Risk level is determined by considering both likelihood and impact.

| Likelihood | Impact | Risk |
|---|---|---|
| Low | Low | Low |
| Low | Medium | Low |
| Low | High | Medium |
| Medium | Low | Low |
| Medium | Medium | Medium |
| Medium | High | High |
| High | Low | Medium |
| High | Medium | High |
| High | High | Critical |

---

## 3. Identified Risks

### Risk 1: Phishing Attacks

**Threat:** Attackers send fraudulent emails designed to steal credentials or deliver malware.

**Asset affected:**
- User accounts
- Company data
- Email systems

**Likelihood:** High

**Impact:** High

**Risk Level:** High

**Recommended controls:**
- Security awareness training
- Multi-factor authentication (MFA)
- Email filtering
- Phishing simulations
- User reporting procedures

---

### Risk 2: Weak or Reused Passwords

**Threat:** Attackers obtain or guess weak passwords and gain unauthorized access.

**Asset affected:**
- User accounts
- Business applications
- Company data

**Likelihood:** High

**Impact:** High

**Risk Level:** High

**Recommended controls:**
- Strong password requirements
- Multi-factor authentication
- Password managers
- Account lockout or rate limiting
- Monitoring for suspicious login activity

---

### Risk 3: Malware Infection

**Threat:** Malware is introduced through malicious attachments, downloads, websites, or removable media.

**Asset affected:**
- Workstations
- Servers
- Business data

**Likelihood:** Medium

**Impact:** High

**Risk Level:** High

**Recommended controls:**
- Endpoint protection
- Regular software updates
- Application controls
- Email security
- User awareness training
- Network monitoring

---

### Risk 4: Unpatched Software

**Threat:** Attackers exploit known vulnerabilities in outdated operating systems or applications.

**Asset affected:**
- Computers
- Servers
- Applications
- Network devices

**Likelihood:** Medium

**Impact:** High

**Risk Level:** High

**Recommended controls:**
- Regular vulnerability scanning
- Patch management
- Automatic security updates where appropriate
- Asset inventory
- Prioritization of critical vulnerabilities

---

### Risk 5: Unauthorized Access

**Threat:** An unauthorized person gains access to an account, device, application, or system.

**Asset affected:**
- User accounts
- Sensitive information
- Internal systems

**Likelihood:** Medium

**Impact:** High

**Risk Level:** High

**Recommended controls:**
- MFA
- Role-based access control
- Least privilege
- Account reviews
- Strong authentication policies
- Logging and monitoring

---

### Risk 6: Data Loss

**Threat:** Important data is accidentally deleted, corrupted, encrypted by ransomware, or otherwise lost.

**Asset affected:**
- Business data
- Customer information
- Financial records

**Likelihood:** Medium

**Impact:** High

**Risk Level:** High

**Recommended controls:**
- Regular backups
- Offline or immutable backups
- Backup testing
- Access controls
- Data recovery procedures

---

## 4. Risk Register

| ID | Risk | Likelihood | Impact | Risk Level | Priority |
|---|---|---|---|---|---|
| R-01 | Phishing attacks | High | High | High | 1 |
| R-02 | Weak/reused passwords | High | High | High | 2 |
| R-03 | Malware infection | Medium | High | High | 3 |
| R-04 | Unpatched software | Medium | High | High | 4 |
| R-05 | Unauthorized access | Medium | High | High | 5 |
| R-06 | Data loss | Medium | High | High | 6 |

---

## 5. Risk Treatment

### Phishing

**Treatment:** Reduce

Implement MFA, email filtering, security awareness training, and phishing simulations.

### Weak Passwords

**Treatment:** Reduce

Enforce strong authentication requirements and MFA.

### Malware

**Treatment:** Reduce

Deploy endpoint protection, patch systems, and monitor network activity.

### Unpatched Software

**Treatment:** Reduce

Establish a formal patch management process and regularly scan for vulnerabilities.

### Unauthorized Access

**Treatment:** Reduce

Use least privilege, MFA, access reviews, and centralized logging.

### Data Loss

**Treatment:** Reduce

Maintain regular backups and test recovery procedures.

---

## 6. Security Recommendations

The organization should prioritize the following actions:

1. Enable multi-factor authentication for important accounts.
2. Implement strong password policies.
3. Maintain an up-to-date asset inventory.
4. Establish a regular patch management process.
5. Deploy endpoint security controls.
6. Perform regular vulnerability assessments.
7. Maintain tested backups.
8. Provide cybersecurity awareness training.
9. Monitor security logs for suspicious activity.
10. Develop an incident response procedure.

---

## 7. Conclusion

This risk assessment identifies several common cybersecurity risks that could affect a small organization.

The highest priorities are phishing, weak authentication, malware, unpatched systems, unauthorized access, and data loss.

Implementing appropriate security controls can reduce the likelihood and impact of these threats and improve the organization's overall security posture.

This project demonstrates foundational skills in:

- Risk identification
- Risk analysis
- Risk prioritization
- Security controls
- Risk treatment
