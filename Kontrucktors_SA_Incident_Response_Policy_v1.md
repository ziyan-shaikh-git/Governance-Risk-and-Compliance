 

**KONTRUCKTORS SA**

Leasing and Sales of Trucks and Construction Equipment

Geneva  |  Lausanne  |  Zurich  |  Lugano

 

 

 

**INFORMATION SECURITY**

**INCIDENT RESPONSE POLICY AND PROCEDURE**

 

| Document Reference | KSA-ISP-005 |
| :---- | :---- |
| **Version** | 1.0 |
| **Classification** | Internal |
| **Effective Date** | 29 September 2026 |
| **Review Date** | 29 September 2027 |
| **Document Owner** | Information Security Manager |
| **Approved By** | Chief Executive Officer |
| **Applies To** | All employees, contractors, and IT personnel across all Kontrucktors SA offices |
| **Related Documents** | KSA-ISP-002 Information Security Policy; KSA-RM-001 Risk Register; KSA-ISP-003 Access Control Policy |
| **ISO 27001:2022 Controls** | A.5.24, A.5.25, A.5.26, A.5.27, A.5.28 |

 

**1\. Purpose**

This Incident Response Policy and Procedure establishes the framework for identifying, reporting, assessing, containing, eradicating, recovering from, and learning from information security incidents at Kontrucktors SA. It ensures that all security incidents are handled in a consistent, coordinated, and timely manner to minimise their impact on the company's operations, reputation, and legal obligations.

This document serves as both a policy, defining mandatory requirements and responsibilities, and a procedure, providing step-by-step guidance for incident handlers. It is aligned with ISO/IEC 27001:2022 Annex A controls A.5.24 through A.5.28 and applicable requirements of the Swiss Federal Act on Data Protection (FADP/LPD) and the General Data Protection Regulation (GDPR).

**2\. Scope**

This policy applies to all actual or suspected information security incidents affecting Kontrucktors SA information systems, data, or personnel, regardless of origin, whether internal or external, accidental or deliberate. It covers all four office locations in Geneva, Lausanne, Zurich, and Lugano, as well as remote working environments and third-party systems that process company data.

**3\. Definitions**

| Term | Definition |
| :---- | :---- |
| Security Event | Any observable occurrence in an information system that may indicate a security concern but has not yet been confirmed as an incident. |
| Security Incident | A confirmed or highly probable breach of the confidentiality, integrity, or availability of company information or systems that requires a formal response. |
| Data Breach | Any incident resulting in the accidental or unlawful destruction, loss, alteration, unauthorised disclosure of, or access to personal data, triggering potential notification obligations under FADP/LPD or GDPR. |
| Incident Response Team (IRT) | The designated group of individuals responsible for managing and coordinating the response to security incidents at Kontrucktors SA. |
| Indicators of Compromise (IoC) | Technical artefacts or behavioural patterns that suggest a system has been compromised, including unusual login times, unexpected data transfers, or known malicious file hashes. |
| Containment | Actions taken to limit the spread or impact of a security incident while investigation and eradication are underway. |
| Eradication | The process of removing the root cause of an incident from affected systems, such as deleting malware, revoking compromised credentials, or patching exploited vulnerabilities. |

**4\. Incident Severity Classification**

All security incidents must be classified by severity to ensure that response resources and escalation procedures are proportionate to the risk. The following four-tier classification scheme applies:

 

| Severity | Rating | Description | Examples |
| ----- | ----- | :---- | :---- |
| **SEV-1** | **Critical** | Severe and immediate impact on business operations, data security, or regulatory compliance. Requires immediate escalation to CEO and potential regulatory notification. | Active ransomware encryption; confirmed data breach of customer personal data; complete loss of critical system availability; credible threat to life or safety. |
| **SEV-2** | **High** | Significant impact on a business system or data asset. Requires urgent response outside normal business hours if necessary. | Confirmed malware infection on multiple systems; unauthorised access to confidential data; compromise of privileged account; significant service outage. |
| **SEV-3** | **Medium** | Moderate impact on a system or process. Response during business hours is acceptable but must be prioritised. | Malware on a single endpoint; phishing email that was clicked but credentials not confirmed compromised; unauthorised access attempt detected and blocked. |
| **SEV-4** | **Low** | Minimal impact. No confirmed data loss or system compromise. Response within normal business hours. | Blocked phishing email; failed login attempts within normal thresholds; minor policy violation with no data impact; spam campaign targeting company email. |

**5\. Incident Response Team**

Kontrucktors SA maintains a standing Incident Response Team (IRT) responsible for coordinating the response to all security incidents. The IRT is activated by the Information Security Manager upon confirmation of a SEV-1 or SEV-2 incident, or upon their assessment that a SEV-3 incident warrants coordinated response.

 

| Role | IRT Position | Responsibility |
| :---- | :---- | :---- |
| Information Security Manager | Incident Commander | Lead the overall response. Coordinate the IRT. Make containment and escalation decisions. Report to senior management. |
| IT Manager | Technical Lead | Execute technical containment, investigation, eradication, and recovery actions. Preserve evidence and logs. |
| Chief Executive Officer | Executive Sponsor | Approve major containment decisions. Authorise external notifications. Manage board and external communications. |
| Legal Counsel | Legal Advisor | Advise on regulatory notification obligations. Review external communications. Support any legal proceedings. |
| HR Manager | HR Advisor | Support incidents involving employee actions. Manage personnel-related aspects of investigations. |
| Department Manager (affected area) | Business Representative | Represent business impact. Support prioritisation decisions. Coordinate with affected teams. |

**6\. Incident Reporting**

**6.1 Who Must Report**

All Kontrucktors SA employees, contractors, and third-party users are required to report any actual or suspected security incident immediately upon discovery. There is no threshold for reporting: if something does not look right, it must be reported. The cost of investigating a false alarm is always lower than the cost of an undetected breach.

**6.2 How to Report**

Incidents must be reported through the following channels, in order of preference:

* Primary: IT Security Incident Hotline: \+41 21 000 0002 (available 24 hours, 7 days a week)  
* Secondary: Email to security@kontrucktors.ch with subject line SECURITY INCIDENT  
* In-person: Report directly to your line manager or the IT Department if the above channels are unavailable

 

Reports must include: the date and time the incident was discovered, a description of what was observed, the systems or data believed to be affected, the name and contact details of the person reporting, and any immediate actions already taken.

**6.3 What Must Not Be Done**

* Do not attempt to investigate or remediate the incident independently  
* Do not switch off or reboot affected systems unless instructed by IT, as this may destroy forensic evidence  
* Do not discuss the incident with colleagues beyond those directly involved in the response  
* Do not communicate externally about the incident without approval from the CEO or Legal Counsel  
* Do not delete any files, emails, or logs that may be relevant to the investigation

**7\. Incident Response Procedure**

The following six-phase procedure applies to all confirmed security incidents at Kontrucktors SA. Each phase must be documented in the Incident Log (see Section 9).

**Phase 1: Detection and Identification**

The objective of this phase is to determine whether a reported event constitutes a confirmed security incident and, if so, to classify its severity.

1. Receive the incident report through the reporting channels defined in Section 6.2  
2. Assign an Incident ID using the format INC-YYYY-NNN, for example INC-2026-001  
3. Gather initial information from the reporting party and any available system logs  
4. Determine whether the event meets the definition of a security incident as defined in Section 3  
5. If confirmed as an incident, classify the severity using the framework in Section 4  
6. Notify the Incident Commander (Information Security Manager) immediately  
7. Open the Incident Log and record all findings to date

**Phase 2: Containment**

The objective of this phase is to limit the spread and impact of the incident while preserving evidence for investigation.

8. Activate the Incident Response Team appropriate to the severity level  
9. Implement immediate short-term containment actions, such as isolating affected systems from the network, disabling compromised accounts, or blocking malicious IP addresses  
10. Preserve system state and logs before making any changes where possible. Take forensic images of affected systems if required  
11. Determine whether longer-term containment measures are required, such as rebuilding systems in a parallel environment while investigation continues  
12. Communicate containment status to the IRT and update the Incident Log  
13. For SEV-1 and SEV-2 incidents, notify the CEO and Legal Counsel within one hour of containment initiation

**Phase 3: Investigation and Analysis**

The objective of this phase is to understand the full scope, root cause, and impact of the incident.

14. Identify all affected systems, data, and users  
15. Collect and analyse logs, network traffic captures, and forensic data to establish the attack timeline and method  
16. Identify indicators of compromise and determine whether any data was accessed, exfiltrated, modified, or destroyed  
17. Assess the impact on the confidentiality, integrity, and availability of company information  
18. Determine whether personal data has been affected, triggering potential notification obligations under FADP/LPD or GDPR  
19. Document all findings in the Incident Log with timestamps and evidence references

**Phase 4: Eradication**

The objective of this phase is to remove the root cause of the incident from all affected systems.

20. Remove all malware, unauthorised access tools, or compromised credentials identified during investigation  
21. Patch or remediate all exploited vulnerabilities  
22. Reset all credentials that may have been compromised, including associated accounts and service accounts  
23. Implement additional controls to prevent recurrence of the same attack vector  
24. Verify that no persistence mechanisms remain on affected systems  
25. Document all eradication actions taken and confirm completion with the Technical Lead

**Phase 5: Recovery**

The objective of this phase is to restore affected systems and services to normal operation safely and in a controlled manner.

26. Restore affected systems from clean backups or rebuild from trusted baseline configurations  
27. Verify system integrity and confirm that no indicators of compromise remain before returning systems to production  
28. Restore access for affected users only after systems have been confirmed clean  
29. Monitor restored systems intensively for a minimum of 72 hours following recovery  
30. Communicate recovery status to affected business units and obtain sign-off from the relevant department manager  
31. Update the Incident Log with recovery actions and completion date

**Phase 6: Post-Incident Review**

The objective of this phase is to learn from the incident and improve the company's security posture and response capability.

32. Conduct a post-incident review meeting within five business days of incident closure, involving all relevant IRT members  
33. Prepare a Post-Incident Report covering: incident timeline, root cause analysis, impact assessment, effectiveness of the response, lessons learned, and recommended improvements  
34. Update the Risk Register (KSA-RM-001) to reflect any new or changed risks identified  
35. Implement all recommended improvements within agreed timelines and track through to completion  
36. Share anonymised lessons learned with all staff where appropriate to improve security awareness  
37. Close the Incident Log and archive all documentation for a minimum of three years

**8\. Regulatory Notification Obligations**

**8.1 Swiss FADP/LPD**

Under the Swiss Federal Act on Data Protection (nFADP/LPD, effective September 2023), Kontrucktors SA is required to notify the Federal Data Protection and Information Commissioner (FDPIC) as soon as possible if a data security breach is likely to result in a high risk to the personality or fundamental rights of the affected individuals. Notification must be made without undue delay and should include: the nature of the breach, the categories and approximate number of individuals affected, the likely consequences, and the measures taken or proposed.

**8.2 GDPR**

Where Kontrucktors SA processes personal data of individuals in the European Union and a data breach occurs, notification to the relevant supervisory authority must be made within 72 hours of becoming aware of the breach, where feasible. If notification cannot be made within 72 hours, the reasons for the delay must be documented. Where the breach is likely to result in a high risk to the rights and freedoms of individuals, those individuals must also be notified without undue delay.

**8.3 Notification Decision Process**

The decision to notify regulatory authorities or affected individuals must be made jointly by the Information Security Manager, Legal Counsel, and CEO. All notification decisions and their rationale must be documented in the Incident Log. Legal Counsel must review all regulatory notifications before submission.

**9\. Incident Log**

A formal Incident Log must be maintained for every confirmed security incident. The Incident Log must be created at the point of incident identification and updated throughout the response lifecycle. It must be stored securely and accessible only to IRT members and senior management.

The Incident Log must record as a minimum:

* Incident ID, date and time reported, date and time confirmed  
* Incident description and severity classification  
* Systems, data, and users affected  
* Chronological record of all response actions taken, with timestamps and responsible individuals  
* Evidence collected and its location  
* Containment, eradication, and recovery actions and outcomes  
* Regulatory notification decisions and actions  
* Post-incident review findings and improvement recommendations  
* Incident closure date and authorising signature

**10\. Escalation Matrix**

| Severity | Notify Within | Primary Contact | Escalate To | External Notify |
| ----- | :---- | :---- | :---- | :---- |
| **SEV-1** | Immediately | Information Security Manager | CEO, Legal Counsel, Board | FDPIC within 72hrs if personal data affected |
| **SEV-2** | Within 1 hour | Information Security Manager | CEO, Legal Counsel | Assess within 24hrs |
| **SEV-3** | Within 4 hours | IT Manager | Information Security Manager | Assess within 48hrs |
| **SEV-4** | Next business day | IT Department | Information Security Manager if escalation needed | Not required |

**11\. Testing and Exercises**

The effectiveness of this Incident Response Policy and Procedure must be tested at least annually through one or more of the following exercise formats:

* Tabletop exercise: a discussion-based walkthrough of an incident scenario with IRT members, used to identify gaps in the procedure and decision-making  
* Simulated phishing exercise: a controlled test of employee reporting behaviour and IT detection capability  
* Technical response drill: a live test of containment and recovery procedures against a controlled test environment

 

The results of all exercises must be documented and used to update this policy and the related Risk Register. Exercise findings must be presented to senior management within 10 business days of completion.

**12\. Roles and Responsibilities Summary**

| Role | Responsibility |
| :---- | :---- |
| All Staff | Report suspected incidents immediately. Do not investigate independently. Preserve evidence. Follow instructions from the IRT. |
| Information Security Manager | Serve as Incident Commander. Activate and lead the IRT. Make containment decisions. Manage regulatory notifications. Conduct post-incident review. |
| IT Manager | Execute technical response actions. Preserve forensic evidence. Lead containment, eradication, and recovery. Maintain incident logs. |
| CEO | Approve major response decisions. Authorise external communications and regulatory notifications. Manage board-level communication. |
| Legal Counsel | Advise on notification obligations. Review all external communications. Support any legal proceedings arising from the incident. |
| HR Manager | Support incidents involving employee conduct. Advise on personnel actions. Coordinate return of company assets if required. |

**13\. Policy Review**

This policy is reviewed annually by the Information Security Manager and approved by the Chief Executive Officer. It is also reviewed immediately following any SEV-1 or SEV-2 incident, or following any significant change to the company's IT environment or applicable regulatory requirements. All staff with incident response responsibilities must be notified of material updates and confirm their understanding.

 

**Approval and Sign-Off**

 

| Role | Name | Signature and Date |
| :---- | :---- | :---- |
| Chief Executive Officer |   |   |
| Information Security Manager |   |   |

   
 

Kontrucktors SA  |  KSA-ISP-005  |  Version 1.0  |  Internal  |  Incident Response Policy and Procedure

