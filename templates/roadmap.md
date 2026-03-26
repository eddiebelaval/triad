---
last-updated: [YYYY-MM-DD]
status: CURRENT
active-milestone: [N]
---

# ROADMAP.md -- [Product Name]

> Execution roadmap derived from the triad: `VISION.md`, `SPEC.md`, `BUILDING.md`.
> Operational companion: `MILESTONE_TASKLISTS.md`
> Canonical execution board: `TICKETS.md`
> Current milestone deep-dive: `MILESTONE_[N]_CHECKLIST.md`

---

## Execution Layer

The triad (`VISION.md`, `SPEC.md`, `BUILDING.md`) defines what the product is.
The execution layer defines what to do about it, at four zoom levels:

| Doc | Role | Audience |
|---|---|---|
| `ROADMAP.md` | Strategy, sequencing, gates | Humans and agents |
| `MILESTONE_TASKLISTS.md` | Tactical task lists per milestone | Humans and agents |
| `TICKETS.md` | Agent-executable work units with dependencies | Agents (primary), humans |
| `MILESTONE_N_CHECKLIST.md` | Deep-dive for the current milestone with file-level targets | Agents |

**Naming convention:** The current milestone always has a dedicated checklist named `MILESTONE_N_CHECKLIST.md` (e.g., `MILESTONE_1_CHECKLIST.md`). When a milestone closes, its checklist is archived and replaced with the next milestone's checklist. Only one active checklist exists at a time.

**Reconciliation:** Each milestone's final ticket updates all triad and execution docs to reflect shipped state. Frontmatter timestamps are updated. The `active-milestone` field increments.

---

## Current Read

[Product Name] is in **[Stage/Phase]** and is best understood as [honest one-line assessment].

What is true right now:
- [Factual statement about current state]
- [Factual statement about current state]

What is not true yet:
- [Honest gap]
- [Honest gap]

## Planning Principles

- **[Principle name].** [One sentence explaining the rule and why.]
- **[Principle name].** [One sentence explaining the rule and why.]
- **[Principle name].** [One sentence explaining the rule and why.]

## Universal Definition of Done

Before calling any milestone done, confirm all three:
- **Built:** the feature exists in code.
- **Verified:** the workflow passes tests and manual validation.
- **Adopted:** a real user can use it without fallback tools or undocumented workarounds.

If one of those is missing, the work is still in progress. Each milestone checklist has its own exit criteria that operationalize these three conditions.

## Success Definition

[Product Name] succeeds in the near term if [target user] can:
- [observable action],
- [observable action],
- and [prefer this over the current alternative].

---

## Now

### Milestone 1 -- [Name]
**Window:** [timeframe]
**Goal:** [one sentence]

#### Deliverables
- [Deliverable]
- [Deliverable]

#### Workstreams
- **[Workstream name]**
  [One sentence describing the work.]

#### Exit Criteria
- [Testable criterion]
- [Testable criterion]

---

## Next

### Milestone 2 -- [Name]
**Window:** [relative to previous]
**Goal:** [one sentence]

[Same structure as above]

---

## Later

### Milestone 3 -- [Name]
**Goal:** [one sentence]

[Same structure, less detail]

---

## Not Now

These are intentionally deferred so the roadmap stays on the critical path:
- [Deferred scope]
- [Deferred scope]

---

## Priority Stack

The canonical priority order and ticket dependencies live in `TICKETS.md`. At a glance:

1. [Priority item] (M1)
2. [Priority item] (M1)
3. [Priority item] (M2)
