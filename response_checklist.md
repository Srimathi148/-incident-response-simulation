
# Incident Response Checklist

## Project: Apex Technologies Pvt. Ltd.
**Incident:** Phishing-Based Account Compromise and Suspected Ransomware Activity  
**Document Type:** Simulated Incident Response Checklist

> All events, systems, alerts, and actions in this checklist are fictional and created for academic simulation. No real attack was conducted.

---

## 1. Preparation

- [ ] Identify the incident response team and assign responsibilities.
- [ ] Maintain an updated list of critical systems and data assets.
- [ ] Ensure authentication, email, and endpoint logs are available.
- [ ] Verify that backups are maintained and restoration procedures are documented.
- [ ] Establish an incident communication and escalation process.
- [ ] Ensure employees know how to report suspicious emails.

**Responsible:** Incident Response Lead and IT Administrator.

## 2. Detection and Identification

- [ ] Record the reported phishing email and its received time.
- [ ] Review authentication logs for unusual login activity.
- [ ] Check for unfamiliar login locations, devices, or sessions.
- [ ] Inspect email forwarding rules for unauthorised external addresses.
- [ ] Review file server alerts for unusual file renaming or modification.
- [ ] Identify potentially affected accounts, devices, and services.
- [ ] Record all findings with timestamps.
- [ ] Classify the incident according to its severity.

**Responsible:** Security Analyst.

**Expected outcome:** A suspected account compromise is identified and escalated for investigation.

## 3. Analysis

- [ ] Determine which account may have been compromised.
- [ ] Review the time and source of suspicious authentication events.
- [ ] Identify any unauthorised changes to email settings.
- [ ] Investigate suspicious file activity on the file server.
- [ ] Determine whether other accounts or systems may be affected.
- [ ] Preserve relevant logs and available evidence.
- [ ] Distinguish confirmed findings from unverified suspicions.

**Responsible:** Security Analyst and Incident Response Lead.

**Expected outcome:** The possible scope and impact of the incident are documented.

## 4. Containment

- [ ] Temporarily disable the compromised account.
- [ ] Revoke active authentication sessions.
- [ ] Remove unauthorised email forwarding rules after recording the relevant evidence.
- [ ] Isolate potentially affected workstations from the network.
- [ ] Restrict suspicious access to affected systems.
- [ ] Protect unaffected systems and critical backups.
- [ ] Inform relevant internal stakeholders.

**Responsible:** IT Administrator and Network Administrator.

**Expected outcome:** Further unauthorised access and potential spread are restricted.

## 5. Eradication

- [ ] Examine affected systems for malicious files or unauthorised access mechanisms.
- [ ] Review account permissions and security settings.
- [ ] Remove confirmed malicious components, if discovered.
- [ ] Reset compromised credentials.
- [ ] Review and correct security misconfigurations.
- [ ] Scan affected endpoints using approved security tools.
- [ ] Document remediation actions.

**Responsible:** Security Analyst and IT Administrator.

**Expected outcome:** Identified causes and confirmed malicious components are addressed.

## 6. Recovery

- [ ] Verify the integrity and availability of backups.
- [ ] Restore affected files only when necessary and from verified clean backups.
- [ ] Reconnect isolated systems only after security checks.
- [ ] Enforce multi-factor authentication (MFA).
- [ ] Confirm that email forwarding settings are secure.
- [ ] Test affected services and business applications.
- [ ] Monitor authentication and file activity for further suspicious behaviour.
- [ ] Obtain approval from the Incident Response Lead before closing the incident.

**Responsible:** IT Administrator and Incident Response Lead.

**Expected outcome:** Essential services are safely restored and monitored.

## 7. Post-Incident Review

- [ ] Prepare a final incident summary.
- [ ] Compare actual simulated actions with the planned response.
- [ ] Identify delays, gaps, and communication issues.
- [ ] Document lessons learned.
- [ ] Recommend improvements to security controls and employee awareness.
- [ ] Update incident response procedures.
- [ ] Record the final incident status.

**Responsible:** Incident Response Lead and Security Analyst.

**Expected outcome:** The organisation identifies improvements to reduce the likelihood and impact of similar incidents.

---

## 8. Incident Closure Criteria

The simulated incident can be considered closed when:

- The compromised account has been secured.
- Unauthorised sessions and forwarding rules have been addressed.
- Affected systems have been investigated and cleared for recovery.
- Required data has been verified or restored.
- Security monitoring is active.
- The incident report and lessons learned have been documented.

**Final Status:** Closed after successful verification and approval.

---

## 9. Important Note

This checklist represents a planned response for a fictional cybersecurity incident. The listed actions are simulated response activities and do not represent a real organisational breach or actual system recovery.
