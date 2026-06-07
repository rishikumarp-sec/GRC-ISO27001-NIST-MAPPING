# Project 2 – ISO 27001 Control Mapping & NIST CSF Crosswalk Exercise

**Analyst:** Rishikumar P  
**Standard Applied:** ISO 27001:2013 | NIST Cybersecurity Framework (CSF) v1.1  
**Date:** June 2026  
**Context:** Self-study GRC project developed as part of preparation for a GRC Analyst internship role

---

## Objectives

1. Map 15 ISO 27001:2013 Annex A controls to real-world scenarios relevant to a small business (QuickMart)
2. Evaluate a sample ISMS policy document and identify non-conformities against ISO 27001 requirements
3. Crosswalk 10 NIST CSF subcategories (2 per function) to equivalent ISO 27001 controls
4. Document findings in a structured format with observations, gaps, and improvement recommendations

---

## Files in This Project

| File | Description |
|---|---|
| `ISO27001_Control_Mapping.csv` | 15 ISO 27001 Annex A controls mapped to real-world QuickMart scenarios with policy gap identification |
| `NIST_CSF_ISO27001_Crosswalk.csv` | 10 NIST CSF subcategories (across all 5 functions) crosswalked to ISO 27001 controls with mapping rationale |
| `Policy_NonConformity_Analysis.md` | Structured analysis of 4 non-conformities identified in a sample ISMS policy document |

---

## Part 1 – ISO 27001 Control Mapping (15 Controls)

Controls reviewed span the following Annex A domains:

| Domain | Controls Covered |
|---|---|
| A.5 – Information Security Policies | A.5.1 |
| A.6 – Organisation of Information Security | A.6.1 |
| A.7 – Human Resource Security | A.7.1 |
| A.8 – Asset Management | A.8.1, A.8.2 |
| A.9 – Access Control | A.9.1, A.9.2, A.9.4 |
| A.10 – Cryptography | A.10.1 |
| A.11 – Physical & Environmental Security | A.11.1 |
| A.12 – Operations Security | A.12.1, A.12.3, A.12.4 |
| A.16 – Incident Management | A.16.1 |
| A.18 – Compliance | A.18.1 |

---

## Part 2 – Policy Non-Conformity Analysis (4 Non-Conformities)

| NC ID | Control | Gap | Priority |
|---|---|---|---|
| NC-01 | A.5.1 | No policy review cycle or management approval | High |
| NC-02 | A.6.1 / A.9.2 | No defined roles; no access review or JML process | High |
| NC-03 | A.8.1 / A.16.1 | No asset inventory; no incident response procedure | Critical |
| NC-04 | A.8.2 | No data classification scheme | High |

---

## Part 3 – NIST CSF to ISO 27001 Crosswalk (10 Subcategories)

Coverage across all 5 NIST CSF core functions:

| NIST CSF Function | Subcategories Mapped | ISO 27001 Controls |
|---|---|---|
| Identify | ID.AM-1, ID.AM-2 | A.8.1 |
| Protect | PR.AC-1, PR.AC-4, PR.DS-1 | A.9.2, A.9.1, A.10.1 |
| Detect | DE.CM-1, DE.AE-1 | A.12.4, A.12.1 |
| Respond | RS.RP-1, RS.CO-2 | A.16.1 |
| Recover | RC.RP-1 | A.17.1 |

---

## Key Frameworks Applied

- **ISO 27001:2013** – Annex A control objectives and requirements
- **NIST Cybersecurity Framework v1.1** – Core functions, categories, and subcategories
- **CIA Triad** – Applied in risk assessment context (see Project 1)
- **Risk-based thinking** – Observations prioritised by potential business impact

---

## Interview Notes (How to Explain This Project)

**Q: What did you do in this project?**  
A: I reviewed 15 ISO 27001 Annex A controls, wrote down what each one does and what real-world risk it addresses in a small business context. Then I reviewed a sample ISMS policy document and identified 4 places where it failed to meet ISO 27001 requirements. Finally, I built a crosswalk table mapping 10 NIST CSF subcategories to the equivalent ISO 27001 controls.

**Q: Why did you do it?**  
A: To understand how international security standards translate to real controls, and to practise the kind of gap analysis a GRC analyst would do when assessing an organisation's compliance posture.

**Q: What did you find?**  
A: The biggest gaps in the sample policy were the absence of an asset inventory process and no incident response procedure — both are critical for ISO 27001 compliance and would likely be major findings in a formal audit.

**Q: How does it relate to GRC?**  
A: Control mapping and gap analysis are core GRC analyst activities — whether supporting an ISO 27001 certification audit, conducting a compliance review, or onboarding a new vendor. This project built my foundational ability to read a standard, apply it to a real scenario, and document findings clearly.

---

*This is a self-study GRC project. It does not represent work performed for a client or organisation.*
