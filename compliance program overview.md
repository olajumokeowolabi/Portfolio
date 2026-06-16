# Compliance Programme Overview
## CareHaven Residential Services Ltd — ISO 27001:2022 ISMS Initiative

**Document Reference:** CPO-001
**Version:** 1.0
**Classification:** Internal — Restricted
**Author:** Information Security & Compliance Function
**Review Date:** December 2025

---

## 1. Purpose

This document provides a concise overview of CareHaven Residential Services Ltd's Information Security Management System (ISMS) initiative. It summarises the programme scope, the rationale for the chosen compliance framework, the stated security objectives, and the organisation's current information security maturity level. It is intended for review by the Executive Leadership Team, the Data Protection Officer (DPO), and any external advisors or auditors engaged to support certification readiness.

---

## 2. Organisation Background

CareHaven Residential Services Ltd is a registered provider of residential care services in England, operating three care homes in the East Midlands region with approximately 130 staff. The organisation delivers 24-hour residential and dementia care to adult and elderly residents, processing a significant volume of sensitive personal and special category data including health records, medication administration records, financial information, and social care assessments.

CareHaven is registered with the Care Quality Commission (CQC) and, as an organisation that shares data with NHS and local authority partners, has obligations under the NHS Data Security & Protection Toolkit (DSPT). The organisation processes personal data as both a Data Controller and, in limited third-party contexts, as a Data Processor, placing it firmly within scope of the UK General Data Protection Regulation (UK GDPR) and the Data Protection Act 2018.

A previous internal review identified the absence of a formally documented Information Security Management System as a material risk, particularly in light of increasing regulatory scrutiny and a rise in ransomware and phishing attacks targeting the health and social care sector.

---

## 3. Framework Selection — ISO 27001:2022

Following an evaluation of applicable frameworks, the organisation has selected **ISO/IEC 27001:2022** as the foundation of its compliance programme, for the following reasons:

- It is an internationally recognised and auditable standard that provides independently verifiable certification
- The 2022 revision of Annex A aligns more closely with modern threat landscapes including cloud security, data leakage prevention, and threat intelligence
- ISO 27001 certification is increasingly requested as a condition of NHS and local authority data sharing agreements
- The framework's risk-based approach integrates naturally with the organisation's existing CQC compliance obligations
- Certification supports the organisation's DSPT submission by demonstrating a structured approach to data security governance

Where applicable, cross-references are drawn to the **NIST Cybersecurity Framework (CSF) v1.1** and **UK GDPR Articles 5, 25, and 32**, ensuring that controls satisfy both security and data protection requirements simultaneously.

---

## 4. Programme Scope

The ISMS scope covers all information assets, systems, people, processes, and physical locations used to support the delivery of residential care services across CareHaven's three sites. This includes:

- All electronic patient/resident records and care management systems
- HR, payroll, and staff scheduling platforms
- Corporate IT infrastructure (endpoints, servers, network equipment)
- Cloud-hosted applications and third-party processing arrangements
- Physical care home premises, reception, and administration areas
- All staff with access to personal or sensitive organisational data

A detailed scoping statement and asset inventory are provided in the accompanying **Scope and Asset Register (SAR-001)**.

---

## 5. Programme Objectives

The ISO 27001 compliance programme has been initiated to achieve the following objectives within a 12-month target timeline:

| # | Objective | Target Date |
|---|---|---|
| 1 | Complete formal ISMS scoping and document organisational context (Clause 4) | Month 1 |
| 2 | Conduct ISO 27001 gap assessment across all Annex A control domains | Month 2 |
| 3 | Establish and maintain an information asset register with classification | Month 2 |
| 4 | Develop and implement an information security risk assessment and treatment methodology | Month 3 |
| 5 | Produce and approve the Statement of Applicability (SoA) | Month 4 |
| 6 | Develop, review, and approve core ISMS policies and procedures | Month 4–5 |
| 7 | Remediate high-priority control gaps identified in the gap assessment | Month 3–7 |
| 8 | Deliver organisation-wide security awareness training programme | Month 5 |
| 9 | Conduct internal ISMS audit | Month 9 |
| 10 | Engage external certification body for Stage 1 audit | Month 11 |
| 11 | Achieve ISO 27001:2022 Stage 2 certification | Month 12 |

---

## 6. Current Maturity Assessment

A high-level maturity assessment has been conducted using a five-level scale aligned to the Capability Maturity Model Integration (CMMI) framework, as follows:

| Level | Label | Description |
|---|---|---|
| 1 | Initial | Ad hoc, undocumented, reactive |
| 2 | Developing | Some processes exist but are inconsistent |
| 3 | Defined | Documented, standardised, and consistently applied |
| 4 | Managed | Monitored, measured, and reported |
| 5 | Optimising | Continuously improved and fully embedded |

### Overall Maturity Rating: **Level 2 — Developing**

CareHaven currently operates with several informal information security practices in place; however, the majority of controls lack formal documentation, defined ownership, or consistent application across all three sites. Key observations from the initial assessment include:

- **Strengths:** Physical security controls at care home premises are reasonably mature; basic antivirus and perimeter firewall controls are in place; the organisation has an appointed DPO with active UK GDPR compliance activity under way.
- **Weaknesses:** No formal ISMS documentation exists; security awareness training is ad hoc and undocumented; vulnerability management and patch management processes are informal and inconsistent; there is no formal process for reviewing user access rights or managing privileged accounts; third-party and cloud service risk assessments are absent.

A detailed breakdown of control-level maturity is provided in the **ISO 27001 Control Matrix (CM-001)**.

---

## 7. Governance Structure

| Role | Responsibility |
|---|---|
| Chief Executive Officer (CEO) | Executive sponsor; ultimate accountability for ISMS |
| Head of Operations | Programme owner; approves scope and policy |
| Data Protection Officer (DPO) | UK GDPR compliance lead; supports control mapping |
| IT Manager | Technical control owner; leads technical remediation |
| HR Manager | People controls owner; leads awareness training |
| Registered Care Home Managers (×3) | Site-level compliance champions |
| External GRC Adviser (Contracted) | Supports ISMS implementation and audit preparation |

---

## 8. Regulatory Alignment Summary

| Regulation / Standard | Relevance to CareHaven | Alignment Approach |
|---|---|---|
| UK GDPR / DPA 2018 | Core obligation as data controller; processes special category health data | ISO 27001 controls mapped to Articles 5, 25, and 32 |
| NHS DSPT | Required for NHS data sharing agreements | DSPT assertions supported by ISMS evidence artefacts |
| CQC Registration | Data security expectations embedded in CQC Key Lines of Enquiry | ISMS framework supports CQC 'Well-Led' domain evidence |
| ISO/IEC 27001:2022 | Target certification framework | Full Annex A gap assessment underway |
| NIST CSF v1.1 | Reference framework for control benchmarking | Cross-reference mapping included in control matrix |

---

## 9. Document Register

| Ref | Document | Status |
|---|---|---|
| CPO-001 | Compliance Programme Overview | ✅ Complete |
| SAR-001 | Scope and Asset Register | ✅ Complete |
| CM-001 | ISO 27001 Control Matrix | ✅ Complete |
| GAP-001 | Gap Analysis & Remediation Plan | ✅ Complete |
| RAMP-001 | Risk Assessment Methodology & Procedure | 🔄 In Progress |
| SoA-001 | Statement of Applicability | ⏳ Pending |
| POL-001 | Information Security Policy | ⏳ Pending |
| POL-002 | Acceptable Use Policy | ⏳ Pending |
| POL-003 | Data Classification & Handling Policy | ⏳ Pending |

---

*This document is subject to annual review or following any material change to the organisation's information environment, risk profile, or regulatory obligations.*

*CareHaven Residential Services Ltd | Compliance Programme Overview | CPO-001 v1.0 | June 2025*
