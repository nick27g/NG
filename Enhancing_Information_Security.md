# Case Study: Azumer Water

## Overview
Azumer Water is an NGO providing clean drinking water to urban communities in the southwestern U.S. affected by disasters. Partnered with FEMA, their mission is to deliver bottled water within 24 hours post-impact. With 10 employees and over 1,000 regional volunteers, Azumer Water uses a local database to manage volunteer information, including contact details, background checks, and the last 4 digits of SSNs for identity verification.

## Current IT Environment
- Volunteer data stored on a local database with no backup copies, often copied to USB drives.
- Employee email domain is @azumerwater.org, while volunteers use personal emails.
- Network protected by an unconfigured firewall and WEP wireless protocol.
- IT managed by Pruhart Tech; CEO Maria Rodriguez is the main contact.

## Security Concerns
- **Threat Actor**: Elecktores, a hacktivist group, targets Azumer Water for its limited mission focus.
- **Incident**: Volunteer coordinator John received a phishing email, clicked on it, and later noticed the volunteer database was missing.
- Volunteers received suspicious donation requests, causing confusion and frustration.

## Key Issues
- Lack of database backups
- Weak security protocols (WEP, unchanged passwords)
- No security awareness training for employees

---

# Analysis

### A. Vulnerabilities and Attack Success
- **Phishing Susceptibility**: John clicked on a phishing link, exposing Azumer’s database.
- **Outdated Security**: The use of WEP and lack of training left Azumer vulnerable.
- **Improvement Needed**: Security awareness training and stronger wireless security are essential.

### B. CIA Compromises
- **Confidentiality**: Unauthorized access to the volunteer database compromised personal data.
- **Integrity**: Phishing emails to volunteers impacted the integrity of Azumer’s communications.
- **Availability**: The missing database disrupted operations, with no backups available.

### C. Federal Regulation
Azumer Water’s non-compliance with FISMA endangers their FEMA partnership. Implementing FISMA’s standards, such as regular security audits and maintaining updated security controls, is critical.

### D. Immediate Steps
1. **Isolate John’s Computer**: Run anti-malware scans.
2. **Recover Database**: Use data recovery or USB backups.
3. **Notify Volunteers**: Inform them of the breach, provide security training, and reassure them of preventive measures.

### E. Incident Response Plans
A robust incident response plan would have guided John in handling the phishing breach, reducing downtime and data loss. Employee training would also improve recognition of phishing attempts.

### F. Processes for Compliance
- **Data Encryption**: Protect sensitive data in transit and at rest.
- **Enhanced Security Controls**: Implement intrusion detection systems, SIEM, and access policies.

### G. Technical Controls
1. **Upgrade Wireless Security**: Replace WEP with WPA-2 for stronger encryption.
2. **Configure Firewall**: Improve defense against phishing attacks and secure network access.

### H. Organizational Structure Recommendations
1. **Chief Information Security Officer (CISO)**: Oversee IT and security, reporting to the CEO.
2. **Database Systems Administrator**: Maintain database security, backups, and user management.
3. **IT Help Desk**: Address technical issues, report incidents to CISO.

### I. Risk Management
#### Phishing Attacks
- **Likelihood**: Medium
- **Severity**: Medium
- **Impact**: Low (can be mitigated with training)

#### Unauthorized Database Access
- **Likelihood**: High
- **Severity**: High
- **Impact**: High (jeopardizes PII and FEMA relationship)

**Risk Management Framework**: Following NIST 800-37, Azumer Water should implement steps to prepare, categorize, select, implement, assess, authorize, and monitor their security controls.

---

## References
- **ISO 27002**: Information Security Management Standards.
- **Lord, N.** (2023). *What is FISMA compliance?*. Digital Guardian.
- **McCallister, E., Grance, T., & Scarfone, K. A.** (2010). *Guide to Protecting the Confidentiality of Personally Identifiable Information (PII)*.
- **NIST** (2018). *Risk Management Framework for Information Systems and Organizations*.
