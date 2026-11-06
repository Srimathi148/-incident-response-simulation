
# Incident Attack Flow Diagram

## Phishing-Based Account Compromise and Suspected Ransomware Activity

This diagram represents the sequence of events in the fictional Apex Technologies incident.

```mermaid
flowchart TD
    A["Employee receives fake IT verification email"] --> B["Employee enters credentials on simulated fake login page"]
    B --> C["Credentials assumed compromised"]
    C --> D["Unusual account login detected"]
    D --> E["Unauthorised email forwarding rule identified"]
    E --> F["Suspicious file modification activity detected"]
    F --> G["Incident declared by response team"]
    G --> H["Containment: Disable account and revoke sessions"]
    H --> I["Remove unauthorised forwarding rule"]
    I --> J["Isolate potentially affected workstation"]
    J --> K["Eradication: Investigate and remove confirmed malicious components"]
    K --> L["Recovery: Verify backups and restore files if required"]
    L --> M["Reset credentials and enforce MFA"]
    M --> N["Monitor systems and conduct post-incident review"]
    N --> O["Incident closed after verification"]
```

## Explanation of the Flow

1. **Attack initiation:** An employee receives a fraudulent IT verification email.
2. **Credential compromise:** The employee enters credentials on a simulated fake login page.
3. **Detection:** Monitoring identifies an unusual login and an unauthorised forwarding rule.
4. **Suspicious activity:** Unusual file modifications raise concern about possible ransomware activity.
5. **Incident response:** The response team declares an incident and begins containment.
6. **Eradication:** The team investigates and removes malicious components if confirmed.
7. **Recovery:** Backups are verified, affected services are restored if necessary, and account security is strengthened.
8. **Post-incident review:** The team documents lessons learned and monitors the environment.

## Important Clarification

The suspicious file activity is not proof of a ransomware infection. The scenario treats it as a potential ransomware indicator requiring investigation.

All events and activities shown are fictional and created for an academic simulation.
