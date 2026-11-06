# PayGo Financial Technologies Ltd.
## SOC 2 Readiness and Evidence Assessment

**Framework:** SOC 2 Trust Services Criteria  
**Assessment Focus:** Security, Availability and Confidentiality  
**Systems in Scope:** Payment platform and supporting infrastructure

---

## 1. Assessment Scope and Methodology

The assessment covers the following Trust Services Categories:

| Category | Assessment Focus |
|---|---|
| Security | Protection against unauthorized access, security threats and operational vulnerabilities |
| Availability | System availability, operational resilience, backup and recovery capabilities |
| Confidentiality | Protection of information designated as confidential throughout its processing and retention |

### Assessment Approach

1. Identify applicable SOC 2 criteria and control areas.
2. Review available information about existing security practices.
3. Identify documented control weaknesses.
4. Record areas where operating evidence is unavailable.
5. Evaluate potential risks to security, availability and confidentiality.
6. Recommend corrective actions and supporting audit evidence.

## 2. Security Trust Services Criteria Assessment

The Security category covers the nine Common Criteria groups, CC1–CC9.

| Criterion | Control Area | Assessment Finding | Recommended Action |
|---|---|---|---|
| CC1 | Control Environment | Governance structure, control ownership and management oversight require supporting evidence | Verify approved policies, assigned responsibilities and management oversight |
| CC2 | Communication and Information | Security responsibilities and control documentation are not fully evidenced | Verify policy communication, employee acknowledgements and assigned responsibilities |
| CC3 | Risk Assessment | A complete risk register and documented risk assessment process are not established by the available information | Obtain risk methodology, risk register, treatment plans and assigned risk owners |
| CC4 | Monitoring Activities | Access reviews are missing for customer support and central logging; evidence of timely security alert review is inadequate | Establish periodic control reviews, monitoring procedures and documented follow-up |
| CC5 | Control Activities | Access management weaknesses and inconsistent change documentation affect confidence in control operation | Strengthen procedures and verify consistent control implementation |
| CC6 | Logical and Physical Access Controls | Permissions are not fully mapped to approved roles; periodic reviews are missing for two systems; MFA coverage is undocumented | Complete role mapping, access reviews and system-by-system MFA verification |
| CC7 | System Operations | Timely alert review is unproven; incident response has not been tested in 12 months; restoration testing lacks evidence | Establish monitoring evidence, conduct incident response exercises and verify recovery testing |
| CC8 | Change Management | Change records do not consistently demonstrate approvals and testing | Enforce documented approvals, testing and deployment procedures |
| CC9 | Risk Mitigation | Vendor risk assessments and ongoing security monitoring are incomplete | Complete vendor risk reviews and establish periodic monitoring |

### Key Security Findings

**Access Management - Confirmed Gap**

Permissions are not fully mapped to approved roles, and periodic access reviews are missing for the customer support and central logging systems.

This creates a risk that inappropriate or outdated access permissions may remain undetected.

**MFA Coverage - Evidence Gap**

The available information does not establish which systems enforce MFA or whether exceptions exist.

MFA configuration records and coverage reports are required before control effectiveness can be determined.

**Security Monitoring - Evidence Gap**

The timeliness of critical security alert reviews cannot be verified.

Timestamped alert records, investigation tickets and monitoring service-level expectations should be examined.

**Incident Response - Confirmed Gap**

Incident response procedures have not been tested within the previous 12 months.

PayGo should conduct a tabletop exercise, document the results and track corrective actions.

**Change Management - Confirmed Gap**

Change records do not consistently contain evidence of approval and testing.

A standardized change management process should require documented authorization, testing and appropriate implementation records.

**Third-Party Risk Management - Confirmed Gap**

Vendor security assessments and ongoing monitoring are incomplete.

PayGo should maintain current vendor assessments, evaluate applicable security obligations and retain evidence of periodic reviews.

## 3. Availability Readiness Assessment

Availability concerns whether systems and services remain operational and accessible in accordance with established commitments.

| Control Area | Assessment Finding | Evidence Required |
|---|---|---|
| Availability Commitments | Service availability objectives and supporting commitments are not specified | Approved service commitments and availability targets |
| Backup and Recovery | Backup restoration testing is not evidenced | Backup schedules, restoration test reports and recovery procedures |
| Operational Monitoring | Evidence of timely critical-alert review is inadequate | Monitoring records, alert tickets and escalation reports |
| Incident Response | Incident response procedures have not been tested in 12 months | Exercise results, corrective action records and incident response procedures |

### Availability Findings

The absence of documented restoration testing limits assurance that PayGo can recover systems and data within its intended recovery objectives.

Additionally, the available information does not establish the organization's availability commitments or provide sufficient evidence to evaluate whether supporting controls meet those commitments.

**Recommended Actions**

- Define and document applicable availability commitments.
- Conduct and document backup restoration testing.
- Verify recovery objectives and escalation procedures.
- Retain evidence of operational monitoring and incident response exercises.

These findings indicate areas requiring improvement or verification; they do not establish that PayGo's services are currently unavailable.

## 4. Confidentiality Readiness Assessment

Confidentiality focuses on protecting information designated as confidential from unauthorized access, use or disclosure.

| Control Area | Assessment Finding | Evidence Required |
|---|---|---|
| Information Classification | Classification requirements and supporting implementation evidence are not established | Approved classification policy and information inventory |
| Access Restrictions | Permissions are not fully mapped to approved roles | Role-based access matrix and completed access reviews |
| Authentication | MFA coverage is undocumented | MFA configuration reports and exception records |
| Third-Party Protection | Vendor security assessments and monitoring are incomplete | Vendor assessments, agreements and security assurance records |
| Confidentiality Commitments | Applicable confidentiality commitments and supporting controls are not fully specified | Documented commitments and control evidence |

### Confidentiality Findings

The identified access governance weaknesses and incomplete vendor oversight create potential exposure to unauthorized access or disclosure of sensitive information.

Additional documentation is required to evaluate information classification, confidentiality commitments and the effectiveness of supporting safeguards.

**Recommended Actions**

- Establish or verify documented information classification requirements.
- Review access permissions against approved business roles.
- Verify MFA implementation and documented exceptions.
- Review third-party confidentiality obligations and security controls.
- Retain evidence demonstrating how confidentiality requirements are enforced.

## 5. SOC 2 Evidence Register

The following register identifies evidence required to support the assessment of control design and operating effectiveness.

| Evidence ID | Control Area | Required Evidence | Assessment Status |
|---|---|---|---|
| SOC-E01 | Governance | Approved policies, control ownership and management oversight records | Evidence required |
| SOC-E02 | Risk Assessment | Risk register, risk methodology and treatment records | Evidence required |
| SOC-E03 | Access Management | Approved role matrix and completed periodic access reviews | Confirmed control gap |
| SOC-E04 | MFA | System-by-system MFA inventory, configuration reports and exception records | Evidence required |
| SOC-E05 | Security Monitoring | Timestamped alert tickets, review records and monitoring reports | Evidence required |
| SOC-E06 | Incident Response | Tabletop exercise results and corrective action tracking | Confirmed control gap |
| SOC-E07 | Change Management | Change requests, approvals, testing records and deployment evidence | Confirmed control gap |
| SOC-E08 | Backup and Recovery | Restoration test reports, backup records and recovery objectives | Evidence required |
| SOC-E09 | Third-Party Risk | Vendor risk assessments, agreements and monitoring records | Confirmed control gap |
| SOC-E10 | Availability | Service commitments, availability objectives and supporting monitoring evidence | Evidence required |
| SOC-E11 | Confidentiality | Classification policy, confidentiality commitments and supporting controls | Evidence required |

### Evidence Evaluation Principles

For each control, supporting evidence should establish:

- **Design:** Whether the control is appropriately defined to address its intended objective.
- **Implementation:** Whether the control has been established.
- **Operating Effectiveness:** Whether the control consistently functions as intended over the relevant assessment period.

The existence of a policy alone does not establish that the associated control is operating effectively.

## 6. Risk Prioritization and Remediation

| Priority | Control Area | Risk / Concern | Recommended Remediation |
|---|---|---|---|
| High | Access Management | Excessive or outdated permissions | Complete access reviews and align permissions with approved roles |
| High | MFA | Authentication coverage cannot be verified | Validate MFA enforcement and remediate identified exceptions |
| High | Security Monitoring | Delayed identification or investigation of security events | Establish alert review expectations and retain timestamped evidence |
| High | Incident Response | Untested response procedures | Conduct tabletop exercises and track corrective actions |
| High | Change Management | Inadequately approved or tested changes | Enforce change approvals, testing and documentation |
| High | Backup and Recovery | Recovery capability cannot be demonstrated | Perform restoration testing and document outcomes |
| Medium | Third-Party Risk | Incomplete supplier assurance and monitoring | Complete vendor assessments and ongoing reviews |
| Medium | Availability and Confidentiality | Commitments and supporting controls are insufficiently documented | Verify service commitments, classification requirements and supporting evidence |

**Prioritization Basis:** These are recommended remediation priorities based on identified weaknesses, evidence limitations and potential business impact. They are not measured residual-risk scores.

## 7. Recommended Readiness Improvements

### Immediate Priorities

- Complete outstanding access reviews and validate role assignments.
- Verify MFA coverage across relevant systems.
- Establish evidence of timely security alert review.
- Conduct an incident response tabletop exercise.
- Standardize change approval and testing documentation.
- Perform and document backup restoration testing.

### Ongoing Control Improvements

- Establish periodic vendor risk assessments.
- Maintain current security policies and control ownership records.
- Define availability and confidentiality commitments.
- Implement consistent evidence retention and control monitoring procedures.
- Review corrective actions and outstanding control exceptions.

## 8. Conclusion

The SOC 2 readiness assessment identified significant opportunities to strengthen PayGo's security governance, operational controls and audit evidence.

Access management, incident response testing, change management and third-party oversight require corrective action. MFA, security monitoring, recovery capabilities and controls supporting availability and confidentiality require further verification.

Implementing the recommended improvements would strengthen PayGo's control environment and support preparation for a future independent SOC 2 examination.

The next stage is to consolidate overlapping GDPR and SOC 2 findings into an integrated, risk-based remediation plan.
