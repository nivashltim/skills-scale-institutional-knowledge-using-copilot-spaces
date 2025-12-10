```markdown
# OctoAcme Project Management Overview

OctoAcme runs a lightweight, iterative project management approach focused on delivering measurable customer value. Projects begin with a concise Project One‑pager capturing the problem, SMART objectives, success metrics, stakeholders, and a high‑level timeline. A small decision gate ensures initiatives move into planning only when success metrics are clear, stakeholders are aligned, and team availability is confirmed.

During planning the team breaks approved initiatives into shippable increments and a prioritized backlog using a standard backlog‑item template (title, description, acceptance criteria, estimate, owner). Planning includes estimates (T‑shirt sizing or story points), a Definition of Done, identification of dependencies and risks (recorded in the Risk Register), and a release plan with milestones and an initial QA approach.

Day‑to‑day execution is governed by a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined pull request workflow: keep PRs small, include the linked issue and acceptance criteria in PR descriptions, run CI tests and linters before requesting review, and require at least one approval before merging. Regular cadence items—daily standups, weekly delivery or PM+PdM syncs, milestone demos, and monthly stakeholder updates—ensure visibility. Clear escalation paths (team → PM → Product Lead → Sponsor) and an execution checklist (branching/PR conventions, CI, scheduled demos, risk register updates) help surface and resolve blockers quickly.

Quality assurance and release controls are integrated into delivery: unit and integration tests, end‑to‑end smoke tests for critical flows, CI security scanning, and manual QA as needed. Releases are classified (patch/minor/major) and gated by passing CI/security checks, release notes, rollback plans, and smoke tests; deployments follow a staging → production flow with post‑deploy verifications. Retrospectives after sprints, releases, or incidents capture prioritized action items with owners and due dates, which are added back into the backlog to drive continuous improvement.

For detailed, process‑specific guidance see the documents in this folder:
- docs/octoacme-project-management-overview.md
- docs/octoacme-project-initiation.md
- docs/octoacme-project-planning.md
- docs/octoacme-execution-and-tracking.md
- docs/octoacme-risks-and-communication.md
- docs/octoacme-release-and-deployment.md
- docs/octoacme-retrospective-and-continuous-improvement.md
- docs/octoacme-roles-and-personas.md
```
