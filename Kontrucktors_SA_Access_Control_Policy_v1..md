 

**KONTRUCKTORS SA**

Leasing and Sales of Trucks and Construction Equipment

Geneva  |  Lausanne  |  Zurich  |  Lugano

 

 

 

**INFORMATION SECURITY**

**ACCESS CONTROL POLICY**

 

| Document Reference | KSA-ISP-003 |
| :---- | :---- |
| **Version** | 1.0 |
| **Classification** | Internal |
| **Effective Date** | 22 September 2026 |
| **Review Date** | 22 September 2027 |
| **Document Owner** | Information Security Manager |
| **Approved By** | Chief Executive Officer |
| **Applies To** | All employees, contractors, and third-party users across all Kontrucktors SA offices |
| **Related Documents** | KSA-ISP-002 Information Security Policy; KSA-RM-001 Risk Register; KSA-ISP-AUP-001 Acceptable Use Policy |
| **ISO 27001:2022 Controls** | A.5.15, A.5.16, A.5.17, A.5.18, A.8.2, A.8.3, A.8.4, A.8.5, A.8.6 |

 

**1\. Purpose**

This Access Control Policy establishes the rules and standards governing access to Kontrucktors SA information systems, applications, data, and physical facilities. It defines how access rights are granted, maintained, reviewed, and revoked, and ensures that access to company resources is restricted to authorised individuals based on business need and the principle of least privilege.

This policy supports Kontrucktors SA's commitment to protecting the confidentiality, integrity, and availability of information assets as defined in the Information Security Policy (KSA-ISP-002), and is aligned with the requirements of ISO/IEC 27001:2022 Annex A controls A.5.15 through A.5.18 and A.8.2 through A.8.6.

**2\. Scope**

This policy applies to all access to Kontrucktors SA information systems, including but not limited to: corporate network infrastructure, fleet management systems, customer contract databases, financial and billing systems, HR and payroll platforms, cloud services, email and collaboration tools, and physical office facilities at Geneva, Lausanne, Zurich, and Lugano.

It applies to all individuals who access company systems, including permanent employees, temporary staff, contractors, consultants, and third-party vendors.

**3\. Access Control Principles**

**3.1 Least Privilege**

Every user, system, and process must be granted only the minimum level of access necessary to perform their defined job function. Broad or administrative access must not be granted by default. Access rights must be scoped to the specific systems and data required for the role, and no further.

**3.2 Need to Know**

Access to sensitive or confidential information is permitted only where the individual has a documented business requirement to access that information. The need to know principle applies regardless of the technical access rights a user may hold.

**3.3 Separation of Duties**

Where possible, critical or sensitive processes must be distributed across multiple individuals to prevent any single person from having end-to-end control. This applies particularly to financial transactions, payroll processing, and system administration activities.

**3.4 Default Deny**

Access to all systems and data is denied by default. Access is permitted only when it has been explicitly requested, approved, provisioned, and documented. Any access not covered by an approved request or role profile must be treated as unauthorised.

**3.5 Accountability**

All access to Kontrucktors SA systems must be individually attributed to a named user account. Shared or generic accounts are prohibited except where operationally necessary and specifically approved by the Information Security Manager with compensating controls in place.

**4\. User Access Management**

**4.1 Access Request and Approval**

All requests for access to company systems or data must be submitted through the IT Department using the standard access request process. Access requests must specify: the system or application required, the level of access requested, the business justification, and the duration if temporary. Requests must be approved by the relevant department manager before provisioning.

**4.2 Joiner Process**

Upon joining Kontrucktors SA, new employees and contractors must have their access provisioned before or on their first day based on their approved role profile. Access is determined by the department manager in coordination with HR and IT. The following steps apply:

* HR notifies IT of all new joiners at least three business days before the start date  
* IT provisions access in accordance with the approved role-based access profile for the position  
* The new user receives their credentials and completes mandatory security awareness training before accessing company systems  
* All access granted at joining is documented in the access management log

**4.3 Mover Process**

When an employee or contractor changes role, location, or responsibilities, their access rights must be reviewed and updated to reflect the new position. The following requirements apply:

* The department manager notifies HR and IT of the change before or on the effective date  
* IT removes all access associated with the previous role that is no longer required  
* New access is provisioned in accordance with the approved profile for the new role  
* Access changes are documented and an updated access record is maintained  
* Temporary retention of previous access rights must not exceed five business days and requires written approval from the Information Security Manager

**4.4 Leaver Process**

Upon termination of employment or contract, all access to Kontrucktors SA systems must be revoked promptly. The following mandatory steps apply:

* HR notifies IT of all leavers on the same business day as the confirmed departure date  
* IT revokes all system access, including remote access, cloud accounts, email, and VPN, no later than the end of the final working day  
* Company devices, access tokens, and physical access credentials must be returned on the final day  
* Email accounts are disabled immediately upon departure and retained for a maximum of 30 days for business continuity purposes, with access restricted to the line manager only  
* The leaver's access record is archived and retained for a minimum of three years

**5\. Privileged and Administrative Access**

**5.1 Definition**

Privileged access includes any access rights that exceed those of a standard user, including system administrator rights, database administrator access, network device management, cloud platform administration, and security tool configuration. Privileged accounts pose a significantly higher risk to the organisation if compromised.

**5.2 Controls for Privileged Accounts**

* Privileged accounts must be separate from standard user accounts. No individual may use a privileged account for routine day-to-day tasks such as email or web browsing  
* Privileged access must be granted on a just-in-time basis where technically feasible, meaning access is elevated only for the duration of a specific task and revoked immediately upon completion  
* All privileged account activity must be logged and logs retained for a minimum of 12 months  
* Multi-factor authentication is mandatory for all privileged account logins without exception  
* The number of privileged accounts must be kept to the minimum operationally required  
* Privileged account credentials must be stored in an approved password management solution and rotated at least every 90 days  
* Third-party vendors requiring privileged access must use individually named accounts and must not be granted standing administrative access

**5.3 Emergency Access**

Emergency or break-glass access procedures must be defined and documented for critical systems. Emergency access credentials must be stored securely, sealed, and accessible only with the approval of two senior managers. All use of emergency access credentials must be logged and reviewed within 24 hours.

**6\. Authentication Requirements**

**6.1 Password Standards**

All user accounts must be protected by passwords that meet the following minimum requirements:

* Minimum length of 12 characters  
* Must include at least one uppercase letter, one lowercase letter, one number, and one special character  
* Must not contain the user's name, username, or common dictionary words  
* Must not be reused from any of the previous 12 passwords  
* Must be changed immediately upon any suspicion of compromise  
* Temporary passwords issued at account creation must be changed on first login

**6.2 Multi-Factor Authentication**

Multi-factor authentication (MFA) is mandatory for all of the following:

* All remote access to company systems including VPN and remote desktop  
* All cloud-based application logins including Microsoft 365, Google Workspace, and any SaaS platforms  
* All privileged and administrative account logins  
* All access to financial, HR, and payroll systems  
* All access to the customer contract and fleet management databases

 

Approved MFA methods include authenticator applications such as Microsoft Authenticator or equivalent, hardware security keys, and SMS verification where no stronger method is available. SMS verification is considered the least preferred method and should be replaced with a stronger option wherever technically feasible.

**6.3 Session Management**

* Workstations must lock automatically after a maximum of five minutes of inactivity  
* Users must not leave workstations unlocked when unattended  
* Remote sessions must time out after 15 minutes of inactivity  
* Concurrent logins from multiple locations should be flagged for review

**7\. Access Reviews and Recertification**

Access rights must be reviewed at regular intervals to ensure they remain appropriate and aligned with current business requirements. Accumulation of access rights over time, known as privilege creep, represents a significant security risk and must be actively managed.

| Review Type | Frequency | Responsibility |
| :---- | :---- | :---- |
| Standard user access review | Every 6 months | Department managers with IT support |
| Privileged and administrative access review | Every 3 months | Information Security Manager and IT Manager |
| Third-party and vendor access review | Every 6 months | Information Security Manager |
| Access review following role change | Immediately on change | Line manager and IT Department |
| Access review following security incident | Within 48 hours | Information Security Manager |

 

Access rights that are found to be excessive, inappropriate, or no longer required during a review must be revoked within five business days. All review outcomes and any access changes made must be documented and retained for a minimum of two years.

**8\. Remote Access**

Remote access to Kontrucktors SA systems is permitted for authorised users with a legitimate business need. All remote access must be secured in accordance with the following requirements:

* Remote access must be established through the company-approved VPN solution only. Direct remote access to internal systems without VPN is prohibited  
* MFA is mandatory for all VPN connections without exception  
* Remote access from personal or unmanaged devices requires explicit approval from the IT Manager and must use a virtual desktop environment that prevents data being stored locally on the personal device  
* Remote access from public or unsecured Wi-Fi networks is discouraged and must only be conducted over the approved VPN  
* Remote access sessions must not be left unattended and must be disconnected when no longer actively required  
* Remote access logs are reviewed monthly by the IT Department for anomalous activity

**9\. Third-Party and Vendor Access**

Third-party access to Kontrucktors SA systems must be strictly controlled and limited to the minimum required for the contracted service. The following requirements apply:

* All third-party access must be approved in advance by the Information Security Manager  
* Third parties must be issued individually named accounts. Shared accounts are prohibited  
* Third-party access must be time-limited and expire automatically at the end of the contract or engagement period  
* All third-party access must be subject to MFA  
* Third-party access rights must be reviewed every six months and revoked immediately upon contract termination  
* Third parties must not share their access credentials with any other individual or subcontractor without written approval  
* All third-party activity on company systems must be logged and subject to monitoring

**10\. Physical Access Control**

Physical access to Kontrucktors SA office premises and IT facilities is controlled to prevent unauthorised entry and to protect information assets from physical threats.

**10.1 Office Access**

* All office premises in Geneva, Lausanne, Zurich, and Lugano are protected by electronic access control using key cards or equivalent  
* Physical access rights are provisioned by the Facilities Manager in coordination with HR and are based on the employee's role and office location  
* Physical access rights are reviewed every six months and revoked immediately upon departure  
* Visitors must be registered at reception, issued a temporary visitor badge, and accompanied by a Kontrucktors SA employee at all times  
* Visitor records are retained for a minimum of six months

**10.2 Server Room and IT Infrastructure Access**

* Access to server rooms and network infrastructure areas is restricted to authorised IT personnel only  
* A record of all access to server rooms must be maintained either electronically through the access control system or via a manual log  
* No equipment may be removed from server rooms without written authorisation from the IT Manager  
* Unescorted access by third-party vendors to server rooms is prohibited unless explicitly approved in writing by the IT Manager

**11\. Logging and Monitoring**

Access to Kontrucktors SA information systems must be logged to support security monitoring, incident investigation, and audit activities. The following minimum logging requirements apply:

* Successful and failed login attempts must be logged for all systems  
* Privileged account activity including commands executed and data accessed must be logged  
* Access to sensitive data including customer contracts, HR records, and financial data must be logged  
* Remote access connection and disconnection events must be logged  
* Access control changes including account creation, modification, and deletion must be logged

 

Logs must be retained for a minimum of 12 months and must be protected from modification or deletion. Logs are reviewed by the IT Department on a weekly basis and by the Information Security Manager monthly. Anomalous access patterns must be investigated and, where appropriate, reported as security incidents under the Incident Response Policy (KSA-ISP-005).

**12\. Roles and Responsibilities**

| Role | Responsibility |
| :---- | :---- |
| Information Security Manager | Own this policy. Approve privileged access and exceptions. Conduct periodic access reviews. Report to senior management. |
| IT Department | Provision, modify, and revoke access in accordance with approved requests. Maintain access logs. Manage MFA and VPN. Support access reviews. |
| Department Managers | Approve access requests for their team. Notify HR and IT of role changes and departures. Conduct six-monthly access reviews for direct reports. |
| Human Resources | Notify IT of joiners, movers, and leavers on the same business day. Coordinate return of company assets at offboarding. |
| Facilities Manager | Manage physical access control systems. Provision and revoke physical access credentials. Maintain visitor logs. |
| All Users | Use only their own credentials. Report lost, stolen, or compromised credentials immediately. Comply with all access control requirements. |

**13\. Exceptions and Deviations**

Any deviation from the requirements of this policy requires written approval from the Information Security Manager and, where the risk is assessed as High or Critical, from the Chief Executive Officer. All approved exceptions must be documented, time-limited, reviewed at least every three months, and accompanied by documented compensating controls that reduce the associated risk to an acceptable level.

**14\. Policy Violations**

Violations of this policy, including attempting to access systems beyond authorised rights, sharing credentials, or circumventing access controls, will be investigated and may result in disciplinary action up to and including termination of employment or contract, and referral to the appropriate Swiss legal authorities where applicable.

**15\. Policy Review**

This policy is reviewed annually by the Information Security Manager and approved by the Chief Executive Officer. It is also reviewed following any significant change to the company's IT environment, organisational structure, or applicable regulatory requirements.

 

**Approval and Sign-Off**

 

| Role | Name | Signature and Date |
| :---- | :---- | :---- |
| Chief Executive Officer |   |   |
| Information Security Manager |   |   |

   
 

Kontrucktors SA  |  KSA-ISP-003  |  Version 1.0  |  Internal  |  Access Control Policy

