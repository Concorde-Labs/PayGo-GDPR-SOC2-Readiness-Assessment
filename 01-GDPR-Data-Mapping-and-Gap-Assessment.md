# PayGo Financial Technologies Ltd.
## GDPR Data Mapping & Compliance Gap Assessment

**Framework:** EU General Data Protection Regulation (GDPR)  
**Assessment Scope:** Personal Data Processing, Data Governance & Compliance Controls

---

## 1. Executive Summary

PayGo Financial Technologies Ltd. is a Dublin-based fintech organization providing digital payment services across Ireland and other EU countries. Its operations involve processing customer, employee, transaction, and security-related information through internal systems and third-party service providers.

The GDPR assessment covers seven personal data processing activities, examines how personal information is collected, used, retained, and shared, and evaluates identified data protection practices against relevant GDPR requirements.

The assessment identified weaknesses in privacy notice disclosures, records of processing activities, retention and deletion assurance, access governance, and third-party oversight. Additional evidence is required to evaluate several other GDPR obligations.

## 2. Assessment Scope and Methodology

The assessment covers:

- Personal data inventory and processing activities.
- Data sources, systems, recipients, and data movement.
- Lawfulness, fairness, transparency, and data protection principles.
- Records of processing activities (RoPA).
- Retention schedules and deletion assurance.
- Information security and access governance.
- Third-party processing arrangements.
- Data subject rights, breach procedures, and international transfers.

**Assessment Methodology**

1. Identify processing activities and associated personal data.
2. Document known data subjects, purposes, systems, and retention periods.
3. Describe data movement using available scenario information.
4. Evaluate practices against relevant GDPR requirements.
5. Distinguish identified control gaps from information requiring verification.
6. Recommend corrective actions and supporting evidence.

## 3. Personal Data Inventory

| Processing Activity | Personal Data Categories | Data Subjects | System / Recipient | Retention |
|---|---|---|---|---|
| Customer Registration | Name, email, phone number, address, date of birth | Customers | PayGo web and mobile applications | Active account period plus 5 years after closure |
| Identity Verification | Identity details, document information, verification results | Customers | External identity verification provider | 5 years after account closure |
| Payment Processing | Transaction reference, amount, currency, date, status, payer and recipient account identifiers | Customers involved in transactions | PayGo payment platform and database | 7 years recorded in the submitted inventory |
| Customer Support | Customer details, ticket descriptions, screenshots and attachments | Customers | Customer support ticketing system | 3 years after ticket closure |
| Employee Administration | Employee details, job information, department and payroll information | Employees | HR system | 6 years after employment ends |
| Security Monitoring | Account identifiers, login times, IP addresses, authentication results and security events | System users | Central logging platform | 12 months |
| Card Payments | Payment token, card brand, last four digits and authorization result | Cardholders | External payment processor | Not separately specified |

### Data Inventory Observations

The inventory establishes the main processing activities and available retention information. However, several important details require confirmation:

- Applicable lawful bases for each processing activity.
- Complete external recipient information.
- Actual storage and processing locations.
- Controller and processor responsibilities.
- Retention justifications and deletion procedures.
- International transfer arrangements, where applicable.

The seven-year payment processing retention entry should also be reconciled with the separately documented card-payment activity and its unspecified retention period.

## 4. Data Flow Assessment

The following descriptions distinguish documented processing from data movements that require confirmation.

| Processing Activity | Data Source | Processing Destination | Documented Movement / Use | Verification Required |
|---|---|---|---|---|
| Customer Registration | Customers | PayGo web and mobile applications | Customers submit registration information to create accounts | Subsequent transfers, storage locations and deletion procedures |
| Identity Verification | Customer identity information | External identity verification provider | Identity information is used for verification | Collection method, integration, onward transfers and provider deletion arrangements |
| Payment Processing | Payment transactions initiated by platform users | PayGo payment platform and database | Transaction information is processed and recorded | Field-level sources, onward sharing and storage arrangements |
| Customer Support | Customer-submitted information and other ticket records | Customer support ticketing system | Information is used to respond to support requests | Sources of all ticket fields, provider access and onward transfers |
| Employee Administration | Employee information and HR records | HR system | Personal and payroll information supports employee administration | Collection methods and specific payroll-provider transfers |
| Security Monitoring | System-generated security and authentication events | Central logging platform | Event information supports monitoring and investigation | Originating systems, onward transfers and deletion coverage |
| Card Payments | Cardholder and transaction information | External payment processor | Card payment information is processed to complete transactions | Processor-specific flows, storage, retention and deletion arrangements |

### Data Flow Findings

The case study identifies the systems and external providers involved in processing but does not establish a complete, verified end-to-end data-flow architecture.

PayGo should document the collection points, internal transfers, third-party disclosures, storage locations, retention arrangements, and deletion processes for each activity.

**Required Evidence:** System architecture diagrams, data-flow diagrams, processing records, integration documentation, vendor agreements, and deletion procedures.

## 5. GDPR Compliance Gap Assessment

| ID | GDPR Requirement | Assessment Finding | Recommended Corrective Action |
|---|---|---|---|
| GDPR-01 | Articles 5(1)(a), 12–14 - Transparency | Privacy notices do not fully explain recipient categories and applicable retention periods | Update notices to reflect actual processing, recipients and retention arrangements |
| GDPR-02 | Article 6 - Lawful Basis | Lawful bases for the seven processing activities are not established by the available evidence | Document and verify the appropriate lawful basis for each activity |
| GDPR-03 | Article 5(1)(b) - Purpose Limitation | Complete documentation of processing purposes and potential further uses is unavailable | Verify documented purposes and assess any further processing |
| GDPR-04 | Article 5(1)(c) - Data Minimisation | Necessity of all collected personal data categories cannot be verified | Review collection fields against documented processing purposes |
| GDPR-05 | Article 5(1)(d) - Accuracy | Data validation and correction procedures are not described | Obtain and assess accuracy controls and correction workflows |
| GDPR-06 | Article 5(1)(e) - Storage Limitation | Retention justifications are incomplete and deletion testing does not cover all systems and providers | Document retention justifications and perform deletion verification |
| GDPR-07 | Article 30 - Records of Processing Activities | RoPA documentation is incomplete | Complete and maintain records for applicable processing activities |
| GDPR-08 | Article 28 - Processor Relationships | Provider roles, processing locations and risk oversight are incompletely documented | Verify processing roles, contractual requirements and provider assessments |
| GDPR-09 | Article 32 - Security of Processing | Access governance weaknesses are identified; MFA and several security controls require further evidence | Strengthen role mapping and access reviews; verify authentication, monitoring and recovery controls |
| GDPR-10 | Articles 12, 15–22 - Data Subject Rights | Request-handling procedures cannot be evaluated from the available information | Verify request intake, identity checks, tracking and response procedures |
| GDPR-11 | Articles 33–34 - Personal Data Breaches | GDPR-specific notification arrangements are not established by the scenario | Review and test breach assessment, escalation and notification procedures |
| GDPR-12 | Articles 44–49 - International Transfers | Provider locations and applicable transfer safeguards are not fully documented | Identify relevant transfers and verify appropriate safeguards |

### Assessment Interpretation

The findings fall into two categories:

**Identified Gaps:** Weaknesses expressly described in the case study, including incomplete privacy notices, RoPA documentation, retention and deletion assurance, access governance, and provider oversight.

**Evidence Required:** Areas where available information does not establish whether an applicable GDPR requirement is satisfied, including lawful bases, data minimisation, accuracy controls, data subject rights procedures, and international transfer safeguards.

Missing evidence is a verification requirement; it is not automatically proof of a regulatory violation.

## 6. Risk Prioritization

| Priority | Risk Area | Business Implication | Recommended Response |
|---|---|---|---|
| High | Access Governance and Security | Unauthorized access or exposure of personal information | Review role permissions, address missing access reviews and verify security controls |
| High | Retention and Deletion Assurance | Personal information may remain beyond intended retention periods | Validate retention justifications and test deletion across relevant systems and providers |
| High | Processing Records and Transparency | Incomplete accountability and inadequate information to data subjects | Complete RoPA documentation and update privacy notices |
| High | Third-Party Processing Oversight | Unclear responsibilities and insufficient visibility into provider safeguards | Review processing arrangements, roles, contracts and vendor risk assessments |
| Medium | Data Subject Rights Procedures | Potential delays or inconsistencies in handling individual requests | Obtain and test documented request-handling procedures |
| Medium | International Transfer Verification | Potential exposure where restricted transfers lack required safeguards | Confirm processing locations and applicable transfer mechanisms |

**Risk Rating Basis:** Priorities reflect the significance of the identified weaknesses and potential impact on personal data protection. Final risk scoring should incorporate defined likelihood, impact, and existing-control criteria.

## 7. Recommended Corrective Actions and Evidence

| Remediation Area | Corrective Action | Expected Evidence |
|---|---|---|
| Privacy Transparency | Update privacy notices and validate disclosures against processing activities | Approved notices, processing records and publication evidence |
| RoPA | Complete processing records and establish review responsibilities | Updated RoPA and review records |
| Retention and Deletion | Document retention justifications and test deletion across relevant environments | Retention schedule, deletion logs and provider test results |
| Access Governance | Map permissions to approved roles and complete outstanding reviews | Access matrices, review records and remediation evidence |
| Third-Party Oversight | Confirm processing responsibilities and complete vendor risk reviews | Agreements, role assessments and vendor assurance records |
| Data Subject Rights | Establish and verify request-handling procedures | Procedures, request register and completed case records |
| Breach Management | Review notification processes and test response procedures | Breach response documentation, exercise reports and decision records |
| International Transfers | Verify processing locations and applicable safeguards | Transfer mapping, agreements and supporting assessments |

## 8. Conclusion

The GDPR assessment identified important weaknesses in PayGo's data governance, transparency, retention assurance, security controls, and third-party processing oversight.

The data inventory and flow assessment also identified information required to establish a more complete understanding of personal data processing across the organization.

Addressing these findings would strengthen GDPR accountability, improve the reliability of processing records, and support more consistent privacy risk management.

The associated SOC 2 readiness assessment and integrated remediation plan will address the related security control requirements, evidence needs, and implementation priorities.
