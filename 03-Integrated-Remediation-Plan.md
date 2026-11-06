# PayGo Financial Technologies Ltd.
## Integrated GDPR & SOC 2 Remediation Plan

**Frameworks:** EU General Data Protection Regulation (GDPR) | SOC 2 Trust Services Criteria  
**Assessment Focus:** Risk Prioritization, Corrective Actions, Control Improvement & Audit Readiness

---

## 1. Purpose and Scope

This remediation plan consolidates findings from PayGo Financial Technologies Ltd.'s GDPR gap assessment and SOC 2 readiness assessment.

It provides a structured approach for addressing identified control weaknesses, resolving evidence gaps, assigning remediation responsibilities, and verifying corrective actions.

The plan covers 13 remediation items across data protection, access governance, security operations, operational resilience, and third-party risk management.

## 2. Remediation Methodology

Findings are evaluated based on potential security, privacy, operational, and compliance impacts.

**Assessment Status**

- **Confirmed Gap:** An identified weakness requiring corrective action.
- **Evidence Gap:** Insufficient documentation to establish whether a control is implemented or operating effectively.

**Priority Classification**

- **High:** Issues requiring urgent attention because of potential security, privacy, or operational impact.
- **Medium:** Issues requiring planned remediation, documentation improvements, or additional verification.

Priorities reflect proposed remediation urgency rather than calculated residual-risk scores.

## 3. Integrated Remediation Register

### 3.1 High-Priority Findings

| ID | Finding | Framework Mapping | Corrective Action | Proposed Owner |
|---|---|---|---|---|
| REM-01 | Access permissions not fully mapped to approved roles; missing periodic access reviews | GDPR Art. 32; SOC 2 CC6 | Align permissions with roles, enforce least privilege, and complete access reviews | IT Security / IAM Lead |
| REM-02 | MFA coverage undocumented | GDPR Art. 32; SOC 2 CC6 | Verify MFA across in-scope systems and remediate identified exceptions | IT Security Lead |
| REM-03 | Timeliness of critical security alert reviews unverified | GDPR Art. 32; SOC 2 CC7 | Verify review timeframes, strengthen escalation, and retain monitoring evidence | Security Operations Lead |
| REM-04 | Incident response procedures not tested within 12 months | GDPR Art. 32; SOC 2 CC7 | Conduct tabletop exercises, document results, and address weaknesses | Incident Response Lead |
| REM-05 | Backup restoration testing not evidenced | GDPR Art. 32; SOC 2 Availability | Verify recovery capability through documented restoration testing | IT Operations / Recovery Lead |
| REM-07 | Incomplete vendor security assessments and monitoring | GDPR Arts. 28, 32; SOC 2 CC9 | Complete vendor risk assessments and implement ongoing monitoring | Vendor Risk Management Lead |
| REM-10 | Incomplete retention justifications and deletion testing | GDPR Art. 5(1)(e), 5(2) | Document retention rationale and test deletion across systems and providers | Privacy / Records Management Lead |
| REM-13 | International transfer arrangements not consistently documented | GDPR Arts. 44–49 | Verify transfer arrangements and document applicable safeguards | Privacy / Legal Lead |

### 3.2 Medium-Priority Findings

| ID | Finding | Framework Mapping | Corrective Action | Proposed Owner |
|---|---|---|---|---|
| REM-06 | Inconsistent change approval and testing records | SOC 2 CC8 | Strengthen change approval, testing, and exception documentation | Change Management Lead |
| REM-08 | Incomplete records of processing activities | GDPR Art. 30 | Complete and maintain the RoPA using verified processing information | Privacy / Compliance Lead |
| REM-09 | Privacy notice omits some recipient categories and retention information | GDPR Arts. 12–14 | Update disclosures and obtain appropriate approvals | Privacy / Legal Lead |
| REM-11 | Incomplete documentation of third-party processing roles and locations | GDPR Art. 28 | Verify provider responsibilities, processing locations, and agreements | Privacy / Vendor Management Lead |
| REM-12 | Lawful bases for processing activities not specified | GDPR Art. 6 | Confirm and document the applicable lawful basis for each activity | Privacy / Compliance Lead |

## 4. Remediation Evidence Requirements

Remediation should be supported by evidence demonstrating that corrective actions have been implemented and reviewed.

| ID | Evidence Required for Closure |
|---|---|
| REM-01 | Approved role-permission matrix, access review reports, remediation records |
| REM-02 | MFA configuration reports, system coverage inventory, approved exceptions |
| REM-03 | Alert logs, review timestamps, investigation and escalation records |
| REM-04 | Tabletop exercise reports, corrective action records, testing schedule |
| REM-05 | Restoration test reports, backup logs, recovery results |
| REM-06 | Approved change requests, testing results, deployment records |
| REM-07 | Vendor risk assessments, monitoring reports, remediation tracking |
| REM-08 | Completed RoPA, supporting processing records, review approvals |
| REM-09 | Revised privacy notice, recipient inventory, approval records |
| REM-10 | Approved retention rationale, deletion test reports, corrective actions |
| REM-11 | Updated provider register, role assessments, relevant agreements |
| REM-12 | Lawful basis assessments, updated processing records |
| REM-13 | Transfer inventory, provider location records, applicable safeguard documentation |

## 5. Recommended Implementation Roadmap

| Phase | Timeline | Key Activities |
|---|---|---|
| Phase 1: Immediate Risk Reduction | Days 1–30 | Begin access reviews, verify MFA coverage, strengthen alert monitoring, schedule incident response and recovery testing, and initiate GDPR documentation updates |
| Phase 2: Control Remediation | Days 31–60 | Conduct incident response and restoration exercises, improve change management, document lawful bases, and address identified control weaknesses |
| Phase 3: Third-Party and Data Lifecycle Controls | Days 31–90 | Complete vendor assessments, verify international transfer arrangements, document processing responsibilities, and test deletion across relevant systems |
| Phase 4: Evidence Consolidation and Readiness Validation | Days 61–90 and ongoing | Consolidate control evidence, verify remediation completion, review outstanding exceptions, and reassess SOC 2 readiness |

These timelines are proposed implementation targets and should be adjusted according to risk exposure, operational requirements, and available resources.

## 6. Remediation Tracking and Closure Criteria

A finding should only be marked as **Closed** when sufficient evidence demonstrates that the corrective action has addressed the identified weakness or evidence gap.

Closure requirements include:

1. Corrective action has been implemented.
2. Supporting documentation has been collected and reviewed.
3. Control effectiveness has been tested where applicable.
4. The designated reviewer has approved the remediation outcome.
5. Outstanding exceptions or residual risks have been documented and appropriately approved.

### Recommended Tracking Statuses

| Status | Description |
|---|---|
| Open | Finding recorded; remediation not yet initiated |
| In Progress | Corrective action underway |
| Pending Validation | Action completed; supporting evidence awaiting review |
| Closed | Remediation verified and approved |
| Risk Accepted | Remaining risk formally assessed and accepted by authorized management |

## 7. Conclusion

The integrated remediation plan provides PayGo with a structured approach to addressing GDPR compliance gaps and SOC 2 readiness weaknesses.

Prioritizing access governance, security monitoring, incident response, recovery testing, third-party oversight, and data lifecycle controls would strengthen the organization's overall control environment.

Consistent remediation tracking, documented accountability, and evidence-based closure would also improve ongoing compliance monitoring and preparation for future independent assurance activities.
