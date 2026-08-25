---
name: plan-delegate-execute
description: Plan, delegate, and execute non-trivial work through lightweight Markdown specs.
---

# Plan, Delegate & Execute

For non-trivial work, maintain persistent Markdown state:

- `plan.md` — overall intent, scope, constraints, and phases; treat it as the source of truth.
- `phase-N.md` — the current executable slice and its acceptance conditions.
- `progress.md` — completed work, decisions, blockers, and the next step.
- `handoff.md` — resumable context only when work must continue in another session or agent.

Plan before implementation. Keep phases small and verifiable.

Delegate independent or mechanical work when useful, while keeping important decisions, integration, and final review with the lead agent.

Keep specs synchronized with implementation as reality changes. Verify the current phase before advancing.

Prefer updating existing workflow files over creating duplicates, and skip planning, delegation, or documentation when the task is simple enough that they add no value.
