# ISMS Policy Non-Conformity Analysis
**Project:** ISO 27001 Control Mapping Exercise  
**Analyst:** Rishikumar P  
**Standard Applied:** ISO 27001:2013  
**Date:** June 2026  
**Subject:** Review of a sample Information Security Management System (ISMS) policy document against ISO 27001:2013 requirements  

---

## Objective

To evaluate a sample ISMS policy document against ISO 27001:2013 Annex A control requirements, identify non-conformities (gaps where the policy fails to meet standard requirements), and recommend corrective actions.

---

## Methodology

1. Obtained a publicly available sample ISMS / Information Security Policy document
2. Reviewed the document against 15 ISO 27001:2013 Annex A controls (A.5 through A.18)
3. Identified clauses where the policy was absent, incomplete, or ambiguous
4. Documented non-conformities with reference to the applicable ISO 27001 control
5. Produced corrective action recommendations for each non-conformity

---

## Non-Conformity Register

### NC-01 — Absent Policy Review Cycle and Management Approval

| Field | Detail |
|---|---|
| **Non-Conformity ID** | NC-01 |
| **ISO 27001 Control** | A.5.1 – Information Security Policies |
| **Requirement** | The information security policy shall be reviewed at planned intervals or if significant changes occur, to ensure its continuing suitability, adequacy, and effectiveness |
| **Observation** | The sample policy document contained no version number, no approval date, no named management approver, and no defined review frequency. It is not possible to determine whether the policy is current or formally approved. |
| **Risk if Unaddressed** | Without management approval and a review cycle, the policy may become outdated, fail to reflect current threats, and would not satisfy ISO 27001 clause 5.2 (Policy) during a formal audit |
| **Recommended Corrective Action** | Add a document control section including: version number, effective date, approved by (name and title), next review date. Establish an annual review cycle with management sign-off. |
| **Priority** | High |

---

### NC-02 — No Defined Roles, Responsibilities, or Access Review Process

| Field | Detail |
|---|---|
| **Non-Conformity ID** | NC-02 |
| **ISO 27001 Control** | A.6.1 – Information Security Roles and Responsibilities; A.9.2 – User Access Management |
| **Requirement** | All information security responsibilities shall be defined and allocated. A formal user registration and de-registration process shall be implemented for granting and revoking access rights. |
| **Observation** | The policy stated that "access is role-based" but did not define: (a) who is responsible for enforcing controls, (b) who approves access requests, (c) how access is granted or revoked when staff join or leave, or (d) how often access rights are reviewed. |
| **Risk if Unaddressed** | Without defined roles, accountability gaps exist — no individual is formally responsible for enforcing controls. Without an access review process, former employees or over-privileged accounts may retain access indefinitely, increasing insider threat and data breach risk. |
| **Recommended Corrective Action** | Create a RACI matrix defining information security responsibilities by role. Document a formal joiner-mover-leaver (JML) process specifying access provisioning on hire, access modification on role change, and access revocation within 24 hours of departure. Define a quarterly access review cycle. |
| **Priority** | High |

---

### NC-03 — No Asset Inventory Process and No Incident Reporting Procedure

| Field | Detail |
|---|---|
| **Non-Conformity ID** | NC-03 |
| **ISO 27001 Control** | A.8.1 – Inventory of Assets; A.16.1 – Management of Information Security Incidents |
| **Requirement** | Assets associated with information and information processing facilities shall be identified and an inventory of these assets shall be drawn up and maintained. Responsibilities and procedures shall be established to ensure a quick, effective, and orderly response to information security incidents. |
| **Observation** | The policy contained no asset register or asset inventory process. There was no definition of what constitutes an information asset, no asset owner assignment, and no classification scheme. Additionally, the policy contained no incident reporting procedure, no defined severity levels, no escalation path, and no requirement to log or document incidents. |
| **Risk if Unaddressed** | Without an asset inventory, the organisation cannot apply proportionate controls to critical assets — protection is applied inconsistently or not at all. Without an incident response procedure, security events go undetected, uncontained, and unreported, increasing breach impact and regulatory exposure (particularly under India's DPDP Act 2023). |
| **Recommended Corrective Action** | Develop and maintain an information asset register identifying: asset name, type, owner, classification level, and applicable controls. Create an incident response procedure covering: identification, containment, eradication, recovery, and reporting phases. Define severity levels (P1/P2/P3) with corresponding escalation timeframes. |
| **Priority** | Critical |

---

### NC-04 — No Data Classification Scheme

| Field | Detail |
|---|---|
| **Non-Conformity ID** | NC-04 |
| **ISO 27001 Control** | A.8.2 – Classification of Information |
| **Requirement** | Information shall be classified in terms of legal requirements, value, criticality, and sensitivity to unauthorised disclosure or modification |
| **Observation** | The sample policy made no reference to data classification. There was no classification taxonomy (e.g., Public / Internal / Confidential / Restricted), no guidance on how to classify information assets, and no handling instructions based on classification level. |
| **Risk if Unaddressed** | Without classification, all data is treated equally — sensitive customer PII and public marketing materials receive the same controls (or lack thereof). This increases the risk of accidental disclosure of sensitive data and makes it impossible to apply proportionate, risk-based controls. |
| **Recommended Corrective Action** | Define a four-tier classification scheme: Public, Internal, Confidential, Restricted. Document handling procedures for each tier covering: storage, transmission, access, and disposal. Train all staff on how to identify and handle classified data. Apply classification labels to all information assets in the asset register. |
| **Priority** | High |

---

## Summary of Findings

| NC ID | Control Reference | Gap Description | Priority |
|---|---|---|---|
| NC-01 | A.5.1 | No policy review cycle or management approval documented | High |
| NC-02 | A.6.1 / A.9.2 | No roles defined; no access review or JML process | High |
| NC-03 | A.8.1 / A.16.1 | No asset inventory; no incident response procedure | Critical |
| NC-04 | A.8.2 | No data classification scheme or handling guidance | High |

---

## Conclusion

The sample ISMS policy reviewed contained foundational language about information security intent but lacked the operational specificity required to satisfy ISO 27001:2013. Four non-conformities were identified across critical control domains: policy governance, access management, asset management, and incident response. These gaps would represent major findings in a formal ISO 27001 audit and should be remediated before any certification assessment.

---

*This analysis was conducted as a self-study GRC project applying ISO 27001:2013 Annex A to a sample policy document. It does not represent a formal audit.*
