# Tiered Framework Design

## Why Tiers?

A single compliance standard applied universally benefits large, well-resourced
organizations and excludes exactly the grassroots CSOs most in need of funding.
STEP's tiered model allows participation at the level appropriate to an
organization's size and operational complexity.

The tiers are additive — each higher tier includes all requirements from the
tiers below it, plus additional criteria. A Tier 4 assessment subsumes Tiers 1, 2, and 3.

---

## The Four Tiers

| Tier   | Name         | Description                                                                         |
|--------|--------------|-------------------------------------------------------------------------------------|
| Tier 1 | **Basic**       | Minimum requirements demonstrating the organization exists and operates legitimately. Appropriate for grassroots, early-stage CSOs. |
| Tier 2 | **Foundation**  | Demonstrates formal organizational structures, documented processes, and basic institutional capacity. Appropriate for established CSOs with growing operations. |
| Tier 3 | **Agency**      | Demonstrates mature internal systems, comprehensive policies, and the ability to manage significant resources responsibly. Appropriate for experienced CSOs managing substantial programs. |
| Tier 4 | **Plus**        | Represents the highest level of organizational capacity — strong governance, advanced risk management, institutional resilience, and the ability to manage large-scale, complex programs. Appropriate for organizations seeking major institutional funding. |

Each domain's `criteria.md` file tags every requirement with the tier at which it first applies.

---

## Criteria Tagging

Each criterion in `domains/{domain}/criteria.md` is tagged with the minimum
tier at which it applies:

```yaml
- id: GOV-001
  tier: 1                  # Required from Tier 1 (Basic) upward
  question: "Has governing documents of some sort"

- id: GOV-005
  tier: 2                  # Required at Tier 2 (Foundation) and above
  question: "Board meets at least once per year"

- id: GOV-008
  tier: 3                  # Required at Tier 3 (Agency) and above
  question: "Has a written policy governing conflicts of interest"

- id: GOV-010
  tier: 4                  # Required at Tier 4 (Plus) only
  question: "Has a written code of ethics or equivalent"
```

When a Tier 1 assessment is scored, criteria tagged `tier: 2`, `tier: 3`, and `tier: 4`
are excluded from the scoring calculation entirely.

---

## Tier Selection

CSO self-selects tier based on:

- Annual operating budget
- Number of full-time staff
- Geographic operating scope (national vs. multi-country)
- Complexity of programs and partnerships

Funders may require a minimum tier for eligibility. A CSO assessed at Tier 2
meets the requirements for any funder who accepts Tier 1 or Tier 2.

---

## Advancement

CSOs are encouraged to advance tiers over time. STEP generates recommendations
for each domain score — these recommendations explicitly flag higher-tier criteria
that the organization could begin working toward.

A re-assessment at a higher tier produces a new assessment record linked to
the prior one, creating an organizational development history.
