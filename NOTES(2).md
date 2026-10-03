# Auditor Notes — Conyers Capital ISO 27001 Project

## Project purpose

This project creates a realistic, portfolio-ready example of an ISO/IEC 27001:2022 internal audit for a fictional private-equity acquisition company.

The company and evidence are fictional. The project should not be represented as an actual audit performed on a real organization.

## GRC-style structure

The project follows a practical GRC workflow:

**Governance → Risk → Controls → Evidence → Testing → Findings → Corrective Action → Verification → Reporting**

This makes the repository useful as a demonstration of how an auditor could connect governance requirements to operational evidence and risk.

## Auditor mindset

The audit is intentionally evidence-based.

Examples:

- A policy alone is not treated as proof that a control operates.
- A risk register alone is not treated as proof that risk treatment is effective.
- An access-control policy is not enough without sampled access evidence.
- An audit schedule is not enough without completed audit records.
- Management-review minutes should demonstrate inputs, decisions, and outputs.

## Why NC-05 is major

The fictional internal-audit program is treated as the most significant finding because Clause 9.2 is itself part of the ISMS performance-evaluation mechanism.

Without effective internal auditing, management has reduced assurance that the ISMS is operating as planned.

This classification is a fictional auditor judgment for training purposes and would need to be validated against actual evidence, scope, systemic impact, and the organization's certification-audit methodology.

## Risk-rating rationale

The project uses a simple 5×5 likelihood/impact matrix:

- 1–4 Low
- 5–9 Moderate
- 10–16 High
- 17–25 Critical

This is a project-specific risk model, not an ISO-mandated scoring system.

ISO/IEC 27001 requires an information-security risk assessment and treatment process; it does not prescribe this exact numerical matrix.

## Lead-auditor observations

For a real engagement, the auditor should verify:

1. ISMS scope is approved.
2. Context and interested-party requirements are current.
3. Risk criteria are defined and consistently applied.
4. Risk owners are assigned.
5. Risk treatment decisions are traceable.
6. The Statement of Applicability reflects risk treatment.
7. Objectives are measurable where practicable.
8. Controls are operating, not merely documented.
9. Internal-audit independence/objectivity is protected.
10. Management review includes required inputs and outputs.
11. Corrective actions address root causes.
12. Effectiveness is verified before closure.

## Sources used for framework grounding

The project is based on the publicly available description of ISO/IEC 27001:2022 and ISO's published auditing guidance.

Reference:
- ISO/IEC 27001:2022 — Information security management systems — Requirements
- ISO/IEC 27001:2022 Amendment 1:2024
- ISO/IEC 27001 Auditing Practices Group guidance on Annex A
- ISO/IEC 27001 Auditing Practices Group guidance on Statement of Applicability

## Certification disclaimer

An internal audit report does not itself establish ISO/IEC 27001 certification.

Certification is a separate conformity-assessment activity performed by an independent certification body.

## Suggested portfolio enhancements

Future GitHub additions could include:

- `evidence/` with sanitized fictional evidence
- `templates/` for audit interviews
- `templates/` for evidence requests
- `templates/` for corrective-action verification
- a control-to-risk traceability matrix
- an audit working-paper index
- a management-review template
- a supplier security assessment
- an ISO 27001 internal-auditor interview script
- a dashboard showing finding aging and CAPA status
