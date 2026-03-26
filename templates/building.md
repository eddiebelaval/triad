---
title: "BUILDING.md"
date: [YYYY-MM-DD]
author: [Name]
product: [Product Name]
---

# BUILDING.md -- Build Journal
## [Product Name]

> How we got here.
> Last updated: [YYYY-MM-DD]

---

## Origin Story

[How this project started. What prompted it. What the first version looked like.
This section is written once and rarely changes.]

## Build Timeline

### [Month Year] -- [Phase Name]

**Decision:** [Key decision and why]

[What was built, what was learned, what changed direction.]

### [Month Year] -- [Phase Name]

[Continue chronologically. Each section captures what shipped, key decisions,
and anything that looked wrong but was intentional.]

---

## Architecture Decisions

| Date | Decision | Why | Alternative Considered |
|------|----------|-----|----------------------|
| [YYYY-MM-DD] | [What was decided] | [Why this path] | [What was rejected and why] |

---

## Known Gotchas

[Things that look wrong but are intentional. Workarounds still in place.
"We tried X but Y" entries. This section protects future contributors from
"fixing" things that aren't broken.]

- [Gotcha]: [Why it exists, what breaks if you change it]

---

**Companion documents:** `VISION.md` (what it is BECOMING), `SPEC.md` (what it IS now).
**The journey from here to VISION is the work.**

**Derived outputs:** `/roadmap` `/drift` `/changelog` `/pitch` `/debt` `/onboard` -- computed from the triangle, never stored.
