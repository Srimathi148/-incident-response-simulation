# Incident Response Report

## 1. Incident Title

**Phishing-Based Account Compromise and Suspected Ransomware Activity**

## 2. Executive Summary

This report documents a fictional cybersecurity incident response simulation conducted for Apex Technologies Pvt. Ltd., a fictional IT services organisation.

The incident begins when an employee receives a fraudulent email pretending to be an official IT department notification. The email requests the employee to verify their account through an external link. The employee unknowingly enters their login credentials on a fake authentication page.

An attacker subsequently uses the compromised credentials to access the employee's email account. The attacker creates an unauthorised email-forwarding rule and attempts to access internal company files. Later, unusual file-renaming and modification activity is detected on a company file server, raising concerns about possible ransomware-related activity.

The organisation's incident response team investigates the suspicious activities and follows five major response stages: detection, analysis, containment, eradication and recovery.

This simulation demonstrates how an organisation can identify a security incident, limit its impact, restore affected services and improve its security controls.

**Important:** All company details, employees, events, timestamps and security records in this project are fictional and created for educational simulation purposes.

## 3. Introduction

Cybersecurity incidents can affect the confidentiality, integrity and availability of an organisation's information systems. Common threats include phishing, credential theft, unauthorised account access and ransomware.

Incident response is a structured process used to identify, investigate, manage and recover from security incidents. A planned response helps an organisation reduce damage, minimise service interruptions and prevent similar incidents.

This project simulates a phishing-based account compromise followed by suspicious file activity. It demonstrates how an incident response team can investigate and manage the situation systematically.

## 4. Project Objectives

The main objectives are:

1. To design a realistic cybersecurity incident scenario.
2. To understand how phishing can lead to credential compromise.
3. To identify suspicious login activity and unauthorised account changes.
4. To document the systems and information potentially affected.
5. To demonstrate detection, analysis, containment, eradication and recovery.
6. To prepare a chronological incident timeline.
7. To assess security risks and potential organisational impact.
8. To evaluate the response and recommend security improvements.

## 5. Fictional Organisation Profile

| Attribute | Details |
|---|---|
| Organisation | Apex Technologies Pvt. Ltd. |
| Industry | Information Technology Services |
| Employees | 75 |
| IT Support Team | 4 members |
| Main Services | Software development and IT support |
| Email System | Cloud-based business email |
| File Storage | Internal company file server |
| Important Assets | Employee accounts, email records, client documents and internal files |
| Backup Arrangement | Daily backups of important files |
| Security Monitoring | Authentication alerts, email security monitoring and endpoint alerts |

The organisation and its infrastructure are fictional. They are used only to provide context for the simulation.

## 6. Incident Scenario

### 6.1 Initial Attack

At approximately 09:00 AM, an employee receives an email that appears to come from the organisation's IT department. The message claims that the employee's account requires urgent verification to avoid temporary suspension.

The email contains a link directing the employee to a fake login page. Believing the message is genuine, the employee enters their company username and password.

The credentials are assumed to have been captured by the attacker in this fictional scenario.

### 6.2 Unauthorised Account Access

At approximately 09:20 AM, an attacker uses the compromised credentials to attempt access to the employee's email account from an unfamiliar location.

The organisation's monitoring system generates an unusual-login alert. The security analyst begins investigating the activity.

### 6.3 Unauthorised Email Forwarding

At approximately 09:30 AM, the attacker creates an unauthorised email-forwarding rule. Such a rule could allow incoming messages to be forwarded to an external address without the employee's knowledge.

The security team identifies the unexpected rule during its investigation.

### 6.4 Suspicious File Activity

At approximately 09:45 AM, the file server generates an alert indicating unusual file-renaming and modification activity.

The activity raises concern about possible ransomware behaviour. However, the available simulated evidence does not independently confirm that ransomware was installed or executed.

The response team treats the event as a serious security incident and investigates the affected systems.

### 6.5 Incident Declaration

At approximately 10:00 AM, the incident response lead classifies the event as a high-priority security incident involving suspected account compromise and possible file-system impact.

The response team begins coordinated investigation and containment activities.

## 7. Attack Vectors and Techniques

| Attack vector | Description | Potential consequence |
|---|---|---|
| Phishing email | Fraudulent email impersonating the IT department | Employee is tricked into opening a malicious link |
| Credential theft | Login details are captured through a fake authentication page | Attacker obtains account credentials |
| Account compromise | Stolen credentials are used to access an employee account | Unauthorised access to email and resources |
| Email forwarding abuse | An unauthorised forwarding rule is created | Potential exposure of incoming business emails |
| Unauthorised file access | Attacker attempts to access internal files | Confidential information may be exposed |
| Suspicious file modifications | Unusual file changes and renaming are detected | Possible ransomware activity or data integrity damage |

## 8. Systems and Assets Potentially Affected

### 8.1 Employee Email Account

The compromised account may contain business correspondence, internal discussions, attachments and other sensitive information.

### 8.2 Authentication System

The organisation's authentication system may contain login records and session information relevant to the investigation.

### 8.3 Company File Server

The file server may contain internal documents, project files and client-related information. Unusual file modifications could affect data integrity and availability.

### 8.4 Employee Workstation

The employee's workstation must be examined to determine whether any malicious downloads, suspicious processes or other signs of compromise are present.

### 8.5 Business Operations

If important accounts or file services are unavailable, employees may experience delays in their daily activities.

**Scope limitation:** The simulation establishes suspicious account activity and file modifications. It does not assume that all company systems were compromised or that information was definitely stolen.

## 9. Potential Impact Assessment

The incident may affect the organisation in several ways.

**Confidentiality:** An attacker with access to the employee's email account may view sensitive business communications or attachments.

**Integrity:** Unauthorised modifications to company files may affect the accuracy and reliability of stored information.

**Availability:** If ransomware is confirmed, affected files or systems may become unavailable, interrupting business activities.

**Financial impact:** The organisation may face investigation costs, recovery expenses, employee downtime and potential business losses.

**Reputational impact:** If customer or business information is exposed, clients may lose confidence in the organisation.

## 10. Initial Detection Indicators

The following indicators are used in the fictional investigation:

1. An unusual login from an unfamiliar location.
2. Authentication activity that does not match the employee's normal behaviour.
3. Creation of an unauthorised external email-forwarding rule.
4. Unusual file-renaming and modification activity.
5. A possible connection between the compromised account and suspicious file activity.

These indicators require investigation. An unusual login or file modification alone is not sufficient proof of ransomware or data theft.

## 11. Incident Classification

**Incident category:** Phishing and account compromise with suspected ransomware-related activity.

**Simulated severity:** High.

**Reason for classification:**

- Employee credentials are assumed to be compromised.
- Unauthorised account access is identified.
- An external email-forwarding rule is created.
- Suspicious file activity may affect important company information.
- Business operations could be interrupted if file damage is confirmed.

The incident is treated as high priority until the investigation establishes its full scope.

## 12. Incident Response Strategy

The response team follows five major stages.

### 12.1 Detection

The security analyst reviews unusual login alerts, email activity and suspicious file modification notifications. The employee's report and available system records are collected.

**Expected outcome:** Identification and reporting of a suspected cybersecurity incident.

### 12.2 Analysis

The team examines the phishing email, authentication records, email-forwarding rules, account activity and file-server alerts. It identifies affected assets and determines whether other accounts or systems may be involved.

**Expected outcome:** Understanding of the incident's scope, severity and possible consequences.

### 12.3 Containment

The compromised account is temporarily disabled, active sessions are revoked, the unauthorised forwarding rule is removed and affected devices are isolated when necessary. Suspicious network destinations are blocked using approved security controls.

**Expected outcome:** Limitation of further unauthorised access and potential damage.

### 12.4 Eradication

The team checks affected devices and accounts for malware, unauthorised applications, suspicious permissions and other mechanisms that could allow continued access. Confirmed malicious components are removed, and relevant security updates are applied.

**Expected outcome:** Removal of identified malicious activity and closure of unauthorised access paths.

### 12.5 Recovery

The organisation verifies affected files, restores data from clean backups when necessary, checks system functionality and re-enables accounts only after security validation. Increased monitoring is maintained after recovery.

**Expected outcome:** Safe restoration of business operations.

## 13. Evidence and Documentation

The response team maintains records to support investigation and decision-making.

| Evidence ID | Evidence description | Purpose |
|---|---|---|
| EV-01 | Original phishing email | Identify the initial attack method |
| EV-02 | Authentication log | Investigate suspicious account access |
| EV-03 | Email-forwarding rule record | Identify unauthorised email activity |
| EV-04 | File modification alert | Investigate possible file-system impact |
| EV-05 | Endpoint security report | Check the affected workstation for malware |
| EV-06 | Backup verification record | Confirm whether recovery data is safe to use |

All evidence in this project is hypothetical. In a real investigation, records would be preserved with timestamps, access controls and documented handling procedures.

## 14. Incident Response Roles

| Role | Responsibility |
|---|---|
| Incident Response Lead | Coordinates the response and communicates with management |
| Security Analyst | Investigates alerts, reviews logs and documents findings |
| IT Administrator | Disables compromised accounts, revokes sessions and restores systems |
| Network Administrator | Isolates affected devices and manages network restrictions |
| Management Representative | Approves business decisions and stakeholder communication |
| Employee | Reports suspicious messages and cooperates with the investigation |

## 15. Risk Assessment

The incident creates several risks that must be evaluated.

| Risk | Likelihood | Impact | Priority |
|---|---|---|---|
| Credential theft | High | High | Critical |
| Unauthorised account access | High | High | Critical |
| Email information exposure | Medium | High | High |
| Ransomware infection | Medium | Critical | Critical |
| File integrity damage | Medium | High | High |
| Business interruption | Medium | High | High |

These are qualitative simulation ratings rather than measured probabilities. The detailed mitigation actions and risk evaluation are documented separately in `risk_assessment.csv`.

## 16. Post-Incident Evaluation

The simulated incident demonstrates how a phishing attack can develop into a broader organisational security problem.

The early detection of unusual login activity and unauthorised email forwarding provides an opportunity to limit further damage. However, the scenario also highlights the importance of monitoring account changes and file activity.

The response is considered effective in the simulation if the compromised account is secured, unauthorised access is removed, affected files are verified and normal services are restored safely.

The organisation should also review whether its monitoring systems generated alerts quickly enough and whether employees understood how to report suspicious emails.

## 17. Lessons Learned

1. Employees must be trained to identify suspicious messages and fake login pages.
2. Multi-factor authentication should be enforced for business accounts.
3. Unusual login attempts should trigger timely security alerts.
4. External email-forwarding rule creation should be monitored.
5. File servers should be monitored for unusual bulk modifications.
6. Backups should be protected and tested regularly.
7. Incident response responsibilities should be clearly assigned.
8. The organisation should conduct regular incident response exercises.

## 18. Recommendations

### Immediate Improvements

- Reset compromised credentials through a secure process.
- Revoke active sessions and remove unauthorised forwarding rules.
- Review account permissions and suspicious access.
- Investigate file modifications before restoring data.

### Long-Term Improvements

- Enforce phishing-resistant multi-factor authentication where supported.
- Conduct regular employee phishing-awareness training.
- Deploy centralised security monitoring and alerting.
- Implement endpoint detection and response capabilities.
- Maintain protected, tested backups.
- Review access privileges regularly.
- Conduct periodic incident response simulations.

## 19. Conclusion

This incident response simulation demonstrates how a phishing email can lead to account compromise, unauthorised email activity and possible ransomware-related file damage.

By following detection, analysis, containment, eradication and recovery, an organisation can respond in a structured manner and reduce the potential impact of a cyberattack.

The simulation also highlights the importance of employee awareness, strong authentication, continuous monitoring, evidence preservation and reliable backups.

The knowledge gained from this exercise can help organisations improve their incident response preparedness and develop a more resilient cybersecurity environment.

## 20. References

1. National Institute of Standards and Technology (NIST). *Computer Security Incident Handling Guide, Special Publication 800-61 Revision 2.* https://csrc.nist.gov/pubs/sp/800/61/r2/final

2. Cybersecurity and Infrastructure Security Agency (CISA). *Recognize and Report Phishing.* https://www.cisa.gov/secure-our-world/recognize-and-report-phishing

3. Cybersecurity and Infrastructure Security Agency (CISA). *StopRansomware Guide.* https://www.cisa.gov/stopransomware/ransomware-guide

4. MITRE. *MITRE ATT&CK Framework.* https://attack.mitre.org/

---

**Project disclaimer:** This report describes an educational simulation using fictional organisation details and hypothetical evidence. No real organisation was targeted, no unauthorised system access was performed, and no malware was deployed.
