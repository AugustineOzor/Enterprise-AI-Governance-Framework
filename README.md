# Enterprise AI Governance Framework — Northstar Financial Services
<img width="1100" height="480" alt="banner (2)" src="https://github.com/user-attachments/assets/450a0521-1373-4006-8705-6771dbc6a2f4" />


This project demonstrating a complete, operational **AI Management System (AIMS)** for a financial services enterprise — policy, governance structure, roles, RACI, lifecycle, risk classification, approval workflow, incident escalation, monitoring, and retirement — aligned with the NIST AI RMF, ISO/IEC 42001, and ISO/IEC 27001.

## About this repository

This repository contains a single-file portfolio framework covering eleven artifacts:

1. The AI Governance Policy (purpose, scope, and core requirements)
2. The AI Governance Framework (NIST AI RMF alignment and governance domains)
3. The AI Governance Committee structure
4. AI roles and responsibilities
5. An enterprise AI governance RACI matrix
6. The AI lifecycle governance process and gates
7. A four-tier AI risk classification methodology
8. The AI approval workflow and approval authority
9. The AI incident escalation process and severity levels
10. AI monitoring requirements and dashboard metrics
11. The AI retirement and decommissioning process

An appendix embeds a companion one-page diagram — an **AI-Generated Records Governance Framework** — illustrating how the "Data" and "Compliance" governance domains from the main framework apply specifically to records created or captured by AI tools (e.g., Copilot-generated meeting summaries).

**Scenario:** The framework is built for **Northstar Financial Services**, a fictional financial institution establishing enterprise-wide AI governance across business-owned AI systems, vendor AI solutions, generative AI tools, machine learning models, and automated decision-support systems.

## Frameworks referenced

- NIST AI Risk Management Framework — Govern, Map, Measure, Manage
- ISO/IEC 42001 — AI Management Systems
- ISO/IEC 27001 — Security Governance
- Three-Lines-of-Defense governance model
- Enterprise Risk Management practices

> **Disclaimer:** This is a fictional portfolio project. Northstar Financial Services, its committee members, and all governance artifacts are illustrative. This framework demonstrates AI governance design skills, not a certified or legally reviewed compliance programme.

---

# 1. AI Governance Policy

## Purpose

The purpose of this policy is to establish requirements for the responsible, secure, transparent, and accountable use of Artificial Intelligence (AI) systems throughout Northstar Financial Services.

This policy ensures that AI systems:

- Support business objectives
- Operate within risk tolerance
- Protect individuals and customers
- Comply with applicable laws and regulations
- Meet enterprise security and privacy requirements
- Are subject to appropriate human oversight
- Are monitored throughout their lifecycle

## Scope

Applies to:

- Employees
- Contractors
- Third-party providers
- Business-owned AI systems
- Vendor AI solutions
- Generative AI tools
- Machine learning models
- Automated decision-support systems

## Policy Requirements

### Governance

All AI systems must:

- Have a documented business owner
- Be registered in the AI inventory
- Undergo risk classification
- Follow the AI lifecycle process

### Human Oversight

Human review is mandatory for:

- High-risk AI systems
- Customer-impacting decisions
- Financial decisions
- Employment decisions

### Data Governance

AI systems must:

- Use approved data sources
- Follow retention requirements
- Meet data-quality standards
- Maintain data lineage

### Security

AI systems must comply with:

- Access-control requirements
- Logging requirements
- Security testing standards

### Monitoring

All AI systems must be monitored for:

- Performance
- Security
- Fairness
- Drift
- Incidents

# 2. AI Governance Framework

## Framework Objective

Provide enterprise-wide oversight of AI systems through a risk-based governance model.

## NIST AI RMF Alignment

**GOVERN** — Establish: Policies · Accountability · Risk Appetite · Governance Structure

**MAP** — Identify: AI Systems · Intended Purpose · Stakeholders · Risks · Impacts

**MEASURE** — Evaluate: Performance · Fairness · Privacy · Security · Reliability

**MANAGE** — Implement: Risk Treatment · Monitoring · Incident Management · Continuous Improvement

## Governance Domains

| Domain | Objective |
|---|---|
| Governance | Oversight and accountability |
| Risk | Risk identification and treatment |
| Data | Data quality and governance |
| Security | Protection of AI systems |
| Privacy | Personal-data protection |
| Compliance | Regulatory alignment |
| Monitoring | Ongoing assurance |
| Audit | Independent review |

# 3. AI Governance Committee Structure

## Enterprise AI Governance Committee

| Role | Assignment |
|---|---|
| Chair | Chief Risk Officer |
| Executive Sponsor | Chief Information Officer |

**Core Members:** AI Governance Lead · Chief Data Officer · Chief Information Security Officer · Privacy Officer · Compliance Officer · Legal Counsel · Model Risk Manager · Business Unit Representatives

**Advisory Members:** Internal Audit · Procurement · Vendor Risk

## Responsibilities

**Strategic Oversight** — Approve AI governance policies; review AI risk exposure; approve risk appetite.

**Risk Governance** — Review High-Risk AI systems; review material incidents; review exception requests.

**Monitoring** — Review AI dashboards; review compliance metrics; review emerging regulations.

# 4. AI Roles and Responsibilities

**Executive Sponsor** — Accountable for AI governance strategy.

**AI Governance Lead** — Responsible for: framework maintenance; inventory management; governance reporting; committee administration.

**AI System Owner** — Responsible for: business justification; risk assessment; monitoring; documentation; incident reporting.

**AI Developer** — Responsible for: model development; technical documentation; validation support.

**Data Owner** — Responsible for: data quality; data classification; data access authorization.

**Privacy Officer** — Responsible for: privacy assessments; data protection review.

**Information Security** — Responsible for: security assessments; security monitoring.

**Internal Audit** — Responsible for: independent assurance; control testing.

# 5. Enterprise AI Governance RACI Matrix

| Activity | Business | AI Governance | Security | Privacy | Compliance | Audit |
|---|---|---|---|---|---|---|
| Register AI | R | A | C | C | C | I |
| Risk Assessment | R | A | C | C | C | I |
| Security Review | C | C | A/R | I | I | I |
| Privacy Review | C | C | I | A/R | C | I |
| Compliance Review | C | C | I | C | A/R | I |
| High-Risk Approval | R | A | C | C | C | I |
| Monitoring | R | A | R | C | C | I |
| Incident Response | R | A | R | C | C | I |
| Audit Testing | I | C | C | C | C | A/R |

*R = Responsible · A = Accountable · C = Consulted · I = Informed*

# 6. AI Lifecycle Governance Process

```
Idea Submitted
      ↓
AI Intake Form
      ↓
Inventory Registration
      ↓
Risk Classification
      ↓
Assessment
      ↓
Approval
      ↓
Development / Procurement
      ↓
Validation
      ↓
Deployment
      ↓
Monitoring
      ↓
Periodic Review
      ↓
Change Management
      ↓
Retirement
```

## Lifecycle Gates

| Gate | Requirement |
|---|---|
| Gate 1 | Registration Complete |
| Gate 2 | Risk Assessment Approved |
| Gate 3 | Security and Privacy Reviews Complete |
| Gate 4 | Deployment Approval |
| Gate 5 | Ongoing Monitoring Approval |

# 7. AI Risk Classification Methodology

## Tier 1 — Low Risk

**Examples:** Internal transcription · Meeting summaries · Knowledge search

**Controls:** Registration · User training

## Tier 2 — Moderate Risk

**Examples:** Customer chatbots · Recommendation engines

**Controls:** Risk assessment · Human review · Monitoring

## Tier 3 — High Risk

**Examples:** Credit-risk AI · Recruitment screening · Fraud detection

**Controls:** Full assessment · Independent validation · Governance approval

## Tier 4 — Restricted

**Examples:** Unapproved surveillance · Discriminatory use · Unauthorized high-impact automation

**Action:** Not permitted

# 8. AI Approval Workflow

```
Business Request
      ↓
AI Intake Form
      ↓
Risk Classification
      ↓
Governance Review
      ↓
Security Review
      ↓
Privacy Review
      ↓
Compliance Review
      ↓
Committee Approval
      ↓
Deployment
```

## Approval Authority

| Risk Tier | Approval Required |
|---|---|
| Tier 1 | Business Owner |
| Tier 2 | AI Governance Lead |
| Tier 3 | AI Governance Committee |
| Tier 4 | Executive Review |

# 9. AI Incident Escalation Process

## AI Incident Definition

An event that causes or could cause:

- Customer harm
- Regulatory breach
- Security compromise
- Privacy breach
- Model failure
- Discriminatory outcomes

## Escalation Workflow

```
Incident Detected
      ↓
Report
      ↓
Triage
      ↓
Containment
      ↓
Investigation
      ↓
Root Cause Analysis
      ↓
Remediation
      ↓
Validation
      ↓
Closure
      ↓
Lessons Learned
```

## Severity Levels

| Severity | Response |
|---|---|
| Critical | Immediate executive escalation. |
| High | AI Governance Committee review required. |
| Medium | Owner remediation required. |
| Low | Track and review. |

# 10. AI Monitoring Requirements

| Monitoring Type | Monitors | Frequency |
|---|---|---|
| Operational Monitoring | Availability; response time; errors | Continuous |
| Risk Monitoring | Fairness; bias; drift; human overrides | Monthly |
| Compliance Monitoring | Documentation currency; review completion; policy exceptions | Quarterly |

## Governance Dashboard Metrics

Track: registered AI systems · approved systems · high-risk systems · open incidents · policy exceptions · overdue reviews · vendor assessments

# 11. AI Retirement and Decommissioning Process

## Retirement Triggers

- Business no longer uses system
- Vendor contract ends
- Technology replaced
- Excessive risk
- Regulatory changes

## Retirement Workflow

```
Retirement Request
      ↓
Risk Assessment
      ↓
Data Retention Review
      ↓
Archive Evidence
      ↓
Access Removal
      ↓
System Shutdown
      ↓
Inventory Update
      ↓
Final Approval
```

## Required Retirement Controls

**Data** — Archive required records; retain evidence; dispose of data appropriately.

**Security** — Remove access; disable integrations; remove credentials.

**Governance** — Update AI inventory; record retirement date; retain audit trail.

# Final Portfolio Positioning

These eleven artifacts transform this framework from a governance concept into an operational AI Management System (AIMS) aligned with:

- NIST AI RMF — Govern, Map, Measure, Manage
- ISO/IEC 42001 — AI Management Systems
- ISO/IEC 27001 — Security Governance
- Three-Lines-of-Defense Governance Model
- Enterprise Risk Management practices

---

# Appendix: AI-Generated Records Governance Framework (Companion Diagram)

The diagram below is a companion one-page framework that operationalizes the main framework's **Data** and **Compliance** governance domains (Section 2) specifically for records created or captured by AI tools — for example, a Microsoft Copilot-generated meeting summary that needs to be classified, registered, retained, and disposed of like any other business record.

![AI-Generated Records Governance Framework — key principles, a seven-step lifecycle (Create, Capture, Classify, Review, Register, Retain, Dispose), key controls, record-status determination, minimum metadata requirements, a RACI matrix, risk considerations, and a worked example of a Copilot-generated meeting summary moving through the lifecycle.](./assets/ai-generated-records-governance-framework.png)

**What the diagram covers:**

- **Key Principles** — Accountability, Authenticity & Integrity, Transparency, Compliance, Retention & Disposition.
- **Lifecycle Workflow** — Create → Capture → Classify → Review → Register → Retain → Dispose, each stage naming the responsible action (e.g., "Human review for accuracy, context, and appropriateness" at the Review stage).
- **Key Controls Applied Throughout** — Access control, provenance tracking, audit logging, quality assurance, and privacy protection.
- **Record Status Determination** — Official Record, Non-Record Output, Prohibited Record, and Unclear Status (routed to Records Management for further assessment).
- **Minimum Metadata Requirements** — including AI tool used, purpose, prompt/instructions summary, data sources, reviewer/approver, and retention schedule.
- **RACI Matrix** — Business Owner, Records Management, Privacy Officer, IT/Security, Legal/Compliance, and the AI Governance Committee, mapped against activities from determining record status through oversight and continuous improvement.
- **Risk Considerations** — hallucinated information, unauthorized use of sensitive data, lack of human oversight, incomplete provenance, improper retention/disposal, and security breach/data exposure.
- **Worked Example** — a Copilot-generated meeting summary: generated → reviewed and validated → classified as an Official Record → metadata captured → stored in SharePoint with a retention schedule applied → reviewed, retained, and disposed of per policy.
