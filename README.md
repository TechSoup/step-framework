---
layout: default
title: STEP Framework
description: "Strengthening and Tiered Evaluation Process — an open standard for civil society organization due diligence and capacity assessment."
nav_order: 1
---

# STEP Framework — Strengthening and Tiered Evaluation Process

> A shared, open standard for civil society organization (CSO) due diligence and capacity assessment.

![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-blue.svg)
![Framework Version](https://img.shields.io/badge/framework-v0.1.0--alpha-orange)
![Translations](https://img.shields.io/badge/translations-EN%20%7C%20ES%20%7C%20FR%20%7C%20SW-green)
![Maintained by TechSoup](https://img.shields.io/badge/maintained%20by-TechSoup%20Global%20Network-blueviolet)

**[Learn more about STEP on TechSoup](https://step.techsoup.org)** | **[Support STEP](https://www.every.org/techsoup)**

---

## Why STEP Exists

Funders and civil society organizations (CSOs) worldwide lose hundreds of collective hours to
duplicated, inconsistent due diligence processes. Every funder has a different checklist.
Every CSO fills out the same information repeatedly. Smaller, grassroots organizations
are disproportionately burdened — and frequently locked out of funding as a result.

STEP addresses this in two ways. First, it is a **shared framework** that defines *what* good organizational capacity looks like, expressed in an open standard that any funder or CSO can use — eliminating duplicated assessment cycles. Second, and equally important, it is a **strengthening tool**: STEP functions as an organizational diagnostic, giving CSOs a clear picture of where they stand and a concrete roadmap for building capacity over time. The "S" in STEP is Strengthening — it comes first deliberately.

**This repo is the framework specification itself** — the criteria, scoring rubric, and
guidance documents that define the standard.

### Open Source Strategy

STEP is part of TechSoup's strategic effort to open source key components of its infrastructure — including frameworks — so that the broader civil society ecosystem can contribute to, adapt, and build upon them. We believe that shared standards for organizational due diligence should be developed in the open, shaped by the communities they serve.

---

## The Assessment Domains

STEP assesses CSOs across a set of **domain areas** (referred to as "streams" by TechSoup), each representing a critical dimension of organizational health and capacity. Each domain is assessed independently — a CSO can achieve different tiers in different domains, reflecting real variation in organizational maturity. Domains are published as criteria files in this repo as they are finalized.

| #  | Domain                                | Status         | Folder                          |
|----|---------------------------------------|----------------|---------------------------------|
| 1  | Governance                            | Published | `domains/governance/`           |
| 2  | Financial Controls                    | Published | `domains/financial-controls/`   |
| 3  | Legal Compliance                      | Published | `domains/legal-compliance/`     |
| 4  | Operational Planning and Continuity   | Published | `domains/operational-planning/` |
| 5  | Risk Management                       | Published | `domains/risk-management/`      |
| 6  | Commitment to Community Engagement    | Published | `domains/community-engagement/` |
| 7  | Data Privacy and Security             | Published | `domains/data-privacy-security/`|
| 8  | Safeguarding                          | Published | `domains/safeguarding/`         |
| 9  | Working with Implementing Partners    | Published | `domains/implementing-partners/`|
| 10 | Human Resources                       | Coming Soon    | `domains/human-resources/`      |
| 11 | Program Delivery                      | Coming Soon    | `domains/program-delivery/`     |

> **Note:** Domains marked "Coming Soon" are under active development by the Framework Working Group. Watch this repo or check the [CHANGELOG](CHANGELOG.md) for release announcements.

---

## The Four Tiers

STEP uses a tiered model so that small, grassroots organizations can participate without being held to the same compliance requirements as large, established agencies. Each domain is scored independently — a CSO receives a tier rating per domain, not a single org-wide tier. This reflects the reality that organizations often have stronger capacity in some areas than others.

| Tier   | Name         | Target CSO Profile                          | Typical Use Case                              |
|--------|--------------|---------------------------------------------|-----------------------------------------------|
| Tier 1 | **Basic**       | Grassroots, early-stage organizations       | Community grants, small donor partnerships    |
| Tier 2 | **Foundation**  | Established CSOs with formal structures     | Mid-size grants, program funding              |
| Tier 3 | **Agency**      | Mature CSOs with robust internal systems    | Institutional funding, large grants           |
| Tier 4 | **Plus**        | Large-scale, high-capacity organizations    | Major institutional funding, UN contracts     |

Within each domain, the tiers are additive — Tier 2 criteria include all Tier 1 requirements plus additional standards. Funders specify which tier(s) they accept across the relevant domains for a given funding opportunity. See [docs/tiered-framework.md](docs/tiered-framework.md) for the full design rationale.

---

## Getting Started

### For Civil Society Organizations (CSOs)

STEP helps you demonstrate your organizational capacity in a structured, reusable way. Here's how to start:

1. **Understand the tiers.** Review the [Tiered Framework Design](docs/tiered-framework.md) to determine which tier matches your organization's size and complexity.
2. **Review the domain criteria.** Browse the `domains/` folders to see what's assessed. Use these criteria to benchmark your own organization and identify areas for development.
3. **Use the tiers for planning.** Even before a formal assessment, the tier requirements provide a roadmap for building organizational capacity. A Tier 1 organization can use Tier 2 criteria as growth targets.
4. **Contribute your perspective.** CSO practitioners are the most valuable contributors to this framework. See [CONTRIBUTING.md](CONTRIBUTING.md) if criteria don't reflect how your organization actually operates.

### For Funders and Grantmakers

STEP gives funders a consistent, transparent basis for evaluating CSO readiness — reducing duplicative due diligence and streamlining the grant-making process.

1. **Map to your requirements.** Review the [tier definitions](docs/tiered-framework.md) and [domain criteria](domains/) to see how STEP aligns with your existing due diligence process.
2. **Use tiers to set expectations.** Specify which tier(s) you accept for a given funding opportunity. This helps CSOs understand what's expected and reduces back-and-forth.
3. **Support CSO development.** The tiered model lets you use STEP not just for evaluation but also as a capacity-building framework — identifying where a CSO stands and what they need to work on.
4. **Streamline readiness assessment.** By adopting STEP tiers as your evaluation baseline, you can reduce the burden on CSOs who have already been assessed, and focus your diligence effort where it matters most.

---

## Ways to Contribute

We love the fact that you're here. STEP is strongest when shaped by the communities it serves.

| Contribution Type          | Who             | Where to Start           |
|----------------------------|-----------------|--------------------------|
| Criteria feedback           | Anyone          | Open a GitHub Issue      |
| Translation / localization  | Fluent speakers | `translations/{locale}/` |
| New criterion proposal      | Domain experts  | RFC process in `rfcs/`   |

Read [CONTRIBUTING.md](CONTRIBUTING.md) for full details. No coding required for many contributions — criteria feedback and translations are equally valuable.

---

## Acknowledgements

<!-- TODO: Melvin to review and expand with full acknowledgements from the Word overview document -->

STEP has been developed through the collaborative effort of many individuals and organizations across the global civil society ecosystem. We are grateful to all contributors, reviewers, pilot participants, and the regional partner organizations who have shaped this framework.

**Framework Development Lead**
- Melvin Chibole, TechSoup Global Network

**Key Contributors**
- [Martha Lackritz-Peltier](https://www.linkedin.com/in/martha-lackritz-peltier/)
- [Caroline Burrage](https://www.linkedin.com/in/caroline-burrage/)

**Funders and Supporting Organizations**
- [Conrad N. Hilton Foundation](https://www.hiltonfoundation.org/)
- [Amplify Change](https://amplifychange.org/)
- TechSoup Global Network

**The Compliance Conundrum Collaboration**

STEP emerged in part from the work of the [Compliance Conundrum Collaboration](https://catalystnow.net/collaborations/compliance-conundrum/) — a joint initiative convened by Catalyst Now to reform risk and due diligence frameworks to better support locally-led development. The Collaboration brought together the Conrad N. Hilton Foundation, TechSoup, EPIC-Africa, KujaLink/ADESO, and Warande Advisory to harmonize due diligence processes and advance more equitable, trust-based funding for local civil society actors. Their collective work directly informed the design principles underlying STEP.

<!-- **Regional Partners and Reviewers**
To be completed from the Word overview document -->

<!-- **Pilot Participants**
To be completed from the Word overview document -->

> Full acknowledgements are being compiled and will be expanded as STEP moves from alpha to general release. If you have contributed to STEP and are not listed here, please open an issue or contact the maintainers.

---

## License

Framework content (criteria, rubric, documentation) is licensed under
**[Creative Commons Attribution-ShareAlike 4.0](LICENSE)**.

You are free to use, adapt, and redistribute this framework — including for commercial
platforms — provided you share adaptations under the same terms and credit STEP.
