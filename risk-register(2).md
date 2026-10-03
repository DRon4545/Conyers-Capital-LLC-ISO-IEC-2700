# Conyers Capital — Information Security Risk Register

> Fictional risk register supporting the simulated ISO/IEC 27001 audit.

## Scoring methodology

**Likelihood:** 1–5  
**Impact:** 1–5  
**Inherent risk = Likelihood × Impact**

| Score | Rating |
|---:|---|
| 1–4 | Low |
| 5–9 | Moderate |
| 10–16 | High |
| 17–25 | Critical |

Residual risk should be reassessed after controls and treatment actions are implemented.

## Register

| ID | Risk | Asset/process | L | I | Inherent | Key controls | Residual | Treatment |
|---|---|---|---:|---:|---:|---|---:|---|
| R-001 | Unauthorized access to deal documents | Deal data room | 3 | 5 | 15 High | MFA, RBAC, access review | 6 Moderate | Reduce |
| R-002 | Phishing compromises executive account | Email/identity | 4 | 5 | 20 Critical | MFA, filtering, training | 8 Moderate | Reduce |
| R-003 | Vendor exposes confidential diligence data | Third parties | 3 | 5 | 15 High | Due diligence, contracts | 9 Moderate | Reduce |
| R-004 | Incomplete asset inventory | ISMS/IT assets | 3 | 4 | 12 High | Asset register | 8 Moderate | Reduce |
| R-005 | Ransomware disrupts operations | Endpoints/SaaS | 3 | 5 | 15 High | EDR, backup, response plan | 6 Moderate | Reduce |
| R-006 | Loss of critical SaaS service | Business continuity | 3 | 4 | 12 High | Continuity planning | 8 Moderate | Reduce |
| R-007 | Terminated user retains access | Identity lifecycle | 2 | 5 | 10 High | Offboarding checklist | 5 Moderate | Reduce |
| R-008 | Sensitive files transmitted without approved encryption | Communications | 2 | 5 | 10 High | Encryption requirements | 4 Low | Reduce |
| R-009 | Security incidents not escalated consistently | Incident response | 3 | 4 | 12 High | IR plan/tabletop | 6 Moderate | Reduce |
| R-010 | Audit findings remain unresolved | ISMS governance | 3 | 4 | 12 High | CAPA tracking | 9 Moderate | Reduce |

## Risk acceptance

Risk acceptance should be documented by an authorized risk owner and should identify:

- risk description;
- current score;
- residual score;
- rationale;
- compensating controls;
- acceptance period;
- review date;
- approving authority.

## Audit traceability

The audit findings primarily affect R-004, R-009, and R-010, with secondary governance impacts across the ISMS.
