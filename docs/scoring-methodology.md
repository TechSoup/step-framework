# Scoring Methodology

> **STATUS: DRAFT — NEEDS VALIDATION**
> This document was drafted from preliminary framework materials and has NOT been validated by the Framework Working Group. Melvin to review and confirm all scoring details before this is published. The scoring scale, domain weights, calculation methods, and critical criteria logic below may be incorrect or incomplete.

## Scoring Scale

<!-- TODO: Melvin to confirm this 0-4 scale is the correct scoring model -->

Each criterion is scored on a 0-4 scale by a certified evaluator:

| Score | Label       | Meaning                                                    |
|-------|-------------|------------------------------------------------------------|
| 0     | Absent      | No evidence of this practice existing                      |
| 1     | Aware       | Leadership is aware of the requirement but no formal practice |
| 2     | Developing  | Practice exists but is inconsistent or not documented      |
| 3     | Established | Practice is documented, consistent, and demonstrable       |
| 4     | Exemplary   | Practice exceeds standard; could be a model for others     |

Evaluators must cite specific evidence for any score above 0.
A score of 0 requires a note explaining what was absent or inaccessible.

---

## Domain Score Calculation

A domain score is the weighted average of criterion scores within that domain,
normalized to a 0-100 scale:

```
domain_score = (sum of criterion scores / max possible score) x 100
```

**Criterion weights** are defined in each domain's criteria file.
Not all criteria carry equal weight.

---

## Score Floors (Critical Criteria)

Certain criteria are designated **critical** — a score of 0 on any critical
criterion caps the overall assessment at 40/100 regardless of other scores.

Critical criteria are marked `critical: true` in the domain criteria files.

This prevents organizations from compensating a fundamental gap with strong
scores elsewhere — which would misrepresent organizational risk to funders.

---

## Red Flags

In addition to the standard scoring rubric, each domain may define **red flags** —
conditions that warrant additional scrutiny regardless of score. Red flags do not
automatically disqualify an organization, but they trigger additional assurance
questions (AAQs) and may require a compelling explanation.

Examples of red flags include:

- Criminal charges against board members, officers, or key employees
- Excessive compensation relative to organizational budget
- Past incidents of fraud or asset misuse without corrective action
- Significant data breaches without adequate remediation
- Complaints regarding treatment of vulnerable populations

Red flags are documented at the end of each domain's criteria file.

---

## Tier-Specific Scoring

Each domain has minimum requirements per tier. An organization must meet **all**
minimum requirements at its assessed tier to receive a passing score in that domain.

- **Tier 1 (Basic):** Core minimums only
- **Tier 2 (Foundation):** Tier 1 requirements + Foundation-level criteria
- **Tier 3 (Agency):** Tiers 1-2 requirements + Agency-level criteria
- **Tier 4 (Plus):** Tiers 1-3 requirements + Plus-level criteria

> **Note:** Domain weights and the overall scoring model are subject to Working Group review.
> Proposed changes require an RFC. See [rfcs/](../rfcs/) for pending proposals.
