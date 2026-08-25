---
name: plan-delegate-execute
description: Plan, delegate, and execute non-trivial work through lightweight Markdown specs.
---

# Plan, Delegate & Execute

For non-trivial work, maintain persistent Markdown state under `docs/`:

- `docs/plan.md` — overall intent, scope, constraints, and phases; treat it as the source of truth.
- `docs/phase-{NN}-{short-title}.md` — the current executable slice and its acceptance conditions, e.g. `phase-01-api-contract.md`.
- `docs/progress.md` — completed work, decisions, blockers, and the next step.
- `docs/handoff.md` — resumable context only when work must continue in another session or agent.

Plan before implementation. Keep phases small and verifiable.

Delegate independent or mechanical work when useful, while keeping important decisions, integration, and final review with the lead agent.

Keep specs synchronized with implementation as reality changes. Verify the current phase before advancing.

Prefer updating existing workflow files over creating duplicates, and skip planning, delegation, or documentation when the task is simple enough that they add no value.
