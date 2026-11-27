# Backlog

Generated from `orchestration/state.json` by `plan-state render`. Do not edit by hand: edit the state file, or use the service's tools, and run `plan-state render --write`. `plan-state check` fails when this file differs from the rendering.

Reader: the owner, and any session working on the project. The reader
knows the README. The state file is the progress truth; this file is
a rendering of it, one row per node of the plan, in dependency order.
[The project plan](plan.md) shows the same nodes with their outcomes.

Each row has four fields, in this order: what, when, status, pointer.

## Completed

None.

## Upcoming

- [ ] **Fixture line of work** (P1-N001) — When: not dated. Status: broken-down, in progress, its children carry the work. Pointer: `orchestration/state.json`.
- [ ] **Fixture leaf for a write** (P1-N002) — When: not dated. Status: identified, ready, starts automatically. Pointer: `orchestration/state.json`.
