# Contributing to STEP

**You do not need to know how to code to contribute.**

The most valuable contributions to this framework are:

- Feedback on whether criteria reflect real-world CSO practice
- Translations into new languages
- Case studies showing how organizations used STEP

---

## Choose Your Path

| I want to...                            | Go to                      |
|-----------------------------------------|----------------------------|
| Report a problem with criteria          | [Criteria Feedback]        |
| Suggest a new criterion                 | [RFC Process]              |
| Translate criteria to another language  | [Translation Guide]        |
| Fix a typo or clarify documentation     | [Documentation PRs]        |

---

## Criteria Feedback

If a criterion is unclear, missing, or doesn't reflect how CSOs actually operate:

1. [Open a GitHub Issue] using the **Criteria Feedback** template
2. Select the relevant domain (e.g., Governance, Financial Controls, Safeguarding, etc.)
3. Describe the problem and, if possible, what you'd suggest instead
4. A Framework Working Group member will respond within 2 weeks

You don't need a GitHub account to participate — you can email
step-framework@techsoup.org and we will open the issue on your behalf.

---

## Proposing a New or Changed Criterion (RFC Process)

Significant changes to criteria follow a Request for Comments (RFC) process:

1. Check [existing RFCs] to avoid duplicating an open discussion
2. Copy [rfcs/template.md] and open a new file as `rfcs/NNNN-your-title.md`
3. Submit a Pull Request — this opens the 30-day public comment window
4. The Framework Working Group reviews and votes on acceptance
5. Accepted RFCs are merged; criteria files are updated in the same PR

**What needs an RFC?** Any change that affects scoring, adds/removes a criterion,
or changes what tier a criterion applies to.

**What doesn't?** Typos, clarifying language, adding examples — these go straight
to a PR without an RFC.

---

## Translations

STEP prioritizes access in local languages. If you can help translate:

1. Check [translations/] to see what's already done and what's in-progress
2. Open an Issue tagged `translation` to claim a language/domain
3. Copy the English source from `domains/{domain}/criteria.md`
4. Translate into `translations/{locale}/{domain}/criteria.md`
5. Open a PR — a native-speaker reviewer from the regional partner network
   will review before merge

Current translation coverage: English (complete) | Spanish (in progress) | French (in progress) | Swahili (planned)

---

## Documentation and Minor Fixes

For typos, broken links, or clarification:

- Fork the repo, make your change, open a PR
- No issue required for changes under 10 lines
- A maintainer will review within 5 business days

---

## Contributor Certificate of Origin (DCO)

By contributing, you certify that you have the right to submit the contribution
under the CC BY-SA 4.0 license. Add this sign-off to your commits:

```
Signed-off-by: Your Name <your.email@example.com>
```

Or use `git commit -s` to add it automatically.
