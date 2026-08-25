# Plan, Delegate & Execute

A minimal AI coding-agent skill for spec-driven, phased implementation.

It keeps non-trivial work anchored in persistent Markdown state:

- `plan.md` — intent, scope, constraints, phases
- `phase-N.md` — current executable slice
- `progress.md` — completed work, decisions, blockers, next step
- `handoff.md` — resumable context when sessions or agents change

The skill intentionally avoids rigid templates and leaves implementation details to the model.

## Usage

Use [`SKILL.md`](./SKILL.md) as a skill file for your coding agent.
