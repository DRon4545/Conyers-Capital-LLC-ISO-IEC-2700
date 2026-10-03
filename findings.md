# Conyers Capital — Audit Findings Register

> Fictional findings for portfolio / training use.

## Finding summary

| ID | Classification | Area | Risk | Status |
|---|---|---|---|---|
| NC-01 | Minor NC | ISMS process integration | High | Open |
| NC-02 | Minor NC | Risk assessment | High | Open |
| NC-03 | Minor NC | Risk treatment | High | Open |
| NC-04 | Minor NC | Objectives/KPIs | Medium | Open |
| NC-05 | Major NC | Internal audit | Critical | Open |
| NC-06 | Minor NC | Management review | Medium | Open |
| OBS-01 | Observation | Roles | Low | Open |
| OBS-02 | Observation | Document control | Low | Open |
| OBS-03 | Observation | Continual improvement | Low | Open |

## NC-01 — ISMS process integration

**Requirement:** ISO/IEC 27001 Clause 4.4

**Condition:** The fictional ISMS documentation describes policies and risk processes, but interfaces between risk management, supplier assurance, incident management, and management review are not consistently mapped.

**Objective evidence:** ISMS process map v1.0; risk register; supplier review procedure; management-review agenda.

**Risk:** Process owners may complete individual activities without demonstrating that ISMS outputs are consistently feeding downstream decisions.

**Classification:** Minor Nonconformity

**Corrective action:** Create an ISMS process interaction map and assign inputs, outputs, owners, metrics, and review frequency.

---

## NC-02 — Risk assessment traceability

**Requirement:** ISO/IEC 27001 Clauses 6.1.2 and 8.2

**Condition:** The risk register contains risk statements and scores, but two sampled risks did not clearly identify the affected information asset, owner, or review trigger.

**Objective evidence:** Risk register sample R-004 and R-009.

**Risk:** Management may be unable to demonstrate that risk decisions are consistently tied to business assets and changing conditions.

**Classification:** Minor Nonconformity

**Corrective action:** Require every risk record to contain asset/process, threat, vulnerability, impact, likelihood, owner, treatment, residual risk, and review trigger.

---

## NC-03 — Risk treatment traceability

**Requirement:** ISO/IEC 27001 Clauses 6.1.3 and 8.3

**Condition:** Risk treatment actions exist, but treatment owners and target completion dates were missing from two sampled actions.

**Risk:** Accepted or treated risks may remain unresolved without clear accountability.

**Classification:** Minor Nonconformity

**Corrective action:** Add owner, due date, treatment status, evidence link, and residual-risk acceptance to every treatment action.

---

## NC-04 — Information-security objectives and metrics

**Requirement:** ISO/IEC 27001 Clauses 6.2 and 9.1

**Condition:** Security objectives are documented, but KPI definitions and accountable owners are inconsistent.

**Risk:** Management cannot reliably determine whether information-security objectives are being achieved.

**Classification:** Minor Nonconformity

**Corrective action:** Establish measurable objectives and a KPI register containing metric definition, owner, frequency, target, threshold, and management action.

---

## NC-05 — Internal audit program

**Requirement:** ISO/IEC 27001 Clause 9.2

**Condition:** The fictional organization has an internal-audit policy and an audit schedule, but there is insufficient objective evidence that the ISMS audit program has been executed according to planned frequency and independence requirements.

**Risk:** Significant ISMS weaknesses may remain unidentified or unresolved.

**Classification:** Major Nonconformity

**Corrective action:** Establish a risk-based internal-audit program covering all applicable ISMS processes and relevant controls, assign an independent/appropriately objective auditor, retain working papers, record findings, and verify corrective-action closure.

**Verification evidence:** Approved audit program; auditor assignment; completed audit reports; working papers; finding tracker; closure evidence.

---

## NC-06 — Management review inputs/outputs

**Requirement:** ISO/IEC 27001 Clause 9.3

**Condition:** Management-review minutes document discussion of incidents and risks, but do not consistently show review of audit results, objective performance, and continual-improvement decisions.

**Risk:** Senior management may not receive a complete view of ISMS effectiveness.

**Classification:** Minor Nonconformity

**Corrective action:** Standardize management-review agenda and minutes around required inputs, decisions, actions, owners, and due dates.

---

## OBS-01 — Role backup

The CEO is identified as a principal information-security decision maker, but certain approval responsibilities do not identify a backup owner.

**Recommendation:** Establish deputies for security, access approval, incident escalation, and risk acceptance.

## OBS-02 — Document control

Some working documents use version numbers but lack consistent review-date and document-owner fields.

**Recommendation:** Standardize document metadata.

## OBS-03 — Continual improvement

The organization tracks improvement actions, but lessons learned from incidents and exercises are not consistently linked to the ISMS improvement register.

**Recommendation:** Link incidents, audit findings, exercises, and management-review decisions to improvement actions.
