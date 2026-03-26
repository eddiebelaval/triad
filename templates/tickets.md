---
last-updated: [YYYY-MM-DD]
status: CURRENT
active-milestone: [N]
---

# TICKETS.md -- [Product Name] Execution Board

> Canonical ticket board for agent-driven execution.
> Strategy and sequencing: `ROADMAP.md`
> Milestone grouping: `MILESTONE_TASKLISTS.md`
> Current milestone deep-dive: `MILESTONE_[N]_CHECKLIST.md`

---

## How Agents Should Use This File

This file is the operational source of truth for execution.

### Rules
- Work from the top down.
- Always prefer the **highest-priority unblocked ticket**.
- Only mark a ticket `done` when it is built, verified, and reflected in docs if needed.
- If work uncovers new necessary tasks, add new tickets under the right milestone instead of burying them in notes.
- If a ticket is too large for one session, split it into smaller tickets before starting.
- Future milestone tickets are stubs. Before starting a new milestone, expand its tickets to include Goal, Primary Targets, and Verification details (matching the depth of the current milestone).

### Status Values
- `todo` -- ready to pick up
- `in_progress` -- currently being worked
- `blocked` -- cannot proceed yet
- `done` -- completed and verified

### Update Protocol
When an agent starts work:
- change one ticket to `in_progress`
- add short progress notes if helpful

When an agent finishes work:
- change the ticket to `done`
- record verification evidence
- update any affected docs

When an agent gets blocked:
- change the ticket to `blocked`
- add the reason in `Notes`
- create follow-up tickets if needed

---

## Current Priority Order

1. Milestone 1 -- [Name]
2. Milestone 2 -- [Name]

---

## Milestone 1 -- [Name]

### M1-01 [Ticket title]
- Status: `todo`
- Priority: `P0`
- Depends on: none
- Goal: [one sentence describing the outcome]
- Primary targets:
  - `path/to/file.ts`
  - `path/to/other-file.ts`
- Verification:
  - [testable assertion]
  - [testable assertion]
- Notes:
  - [any context an agent needs to start immediately]

### M1-02 [Ticket title]
- Status: `todo`
- Priority: `P0`
- Depends on: `M1-01`
- Goal: [one sentence]
- Primary targets:
  - `path/to/file.ts`
- Verification:
  - [testable assertion]

### M1-XX Reconcile docs after milestone ships
- Status: `todo`
- Priority: `P1`
- Depends on: [all other M1 tickets]
- Goal: keep triad and execution docs truthful after the milestone lands
- Primary targets:
  - Triad: `VISION.md`, `SPEC.md`, `BUILDING.md`
  - Execution: `ROADMAP.md`, `MILESTONE_TASKLISTS.md`, `TICKETS.md`
  - Current checklist: `MILESTONE_[N]_CHECKLIST.md` (archive or replace with next checklist)
- Verification:
  - docs reflect the shipped state and remaining gaps
  - all frontmatter timestamps updated
  - `active-milestone` incremented where applicable

---

## Milestone 2 -- [Name]

[Stub tickets -- expand to full depth before starting this milestone]

### M2-01 [Ticket title]
- Status: `todo`
- Priority: `P0`
- Depends on: [final M1 ticket]
