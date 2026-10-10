# SOC Investigation 001: Phishing Email Analysis

## Scenario
A fictional healthcare company, Northwind Health, received reports of a suspicious password expiry email.

## Objective
Determine whether the email was malicious, identify affected users and recommend containment actions.

## Evidence Reviewed
- Email sender, authentication results and suspicious URL
- Web proxy logs
- Mailbox audit logs

## Key Findings
1. The email used a lookalike domain to impersonate IT Support.
2. j.ortiz showed evidence of account compromise and a suspicious forwarding rule.
3. a.patel submitted a form on the phishing page and may have exposed credentials.
4. m.chen visited the page, but no form submission was recorded.

## Recommended Actions
1. Block the phishing URL.
2. Secure j.ortiz and revoke active sessions.
3. Secure a.patel and revoke active sessions.
4. Remove the suspicious forwarding rule and investigate further.

## What I Learned
I learned how to connect email evidence, web activity and mailbox changes to assess a suspected phishing incident.


### Disclaimer

This project is based on my firsthand experience and practical involvement in cybersecurity investigations, security operations, and related technical activities. The work presented reflects projects I have contributed to either independently, directly, or as part of a collaborative team.

**To protect confidentiality and comply with professional and ethical standards, all company names, email addresses, domains, personal information, and other sensitive identifiers have been anonymised, replaced with fictional details, or omitted.**

Where necessary, certain scenarios, technical details, and supporting evidence have been recreated or adapted for educational and portfolio purposes while preserving the core technical concepts, investigation methods, and lessons learned.

Although some information has been fictionalised, the projects are grounded in genuine hands-on experience and practical knowledge.

These projects are shared strictly for **educational purposes, professional development, and cybersecurity portfolio demonstration**. They do not disclose confidential organisational information or imply endorsement by any employer, client, or organisation.

All contributions are described in accordance with my actual involvement, with collaborative work appropriately acknowledged.
