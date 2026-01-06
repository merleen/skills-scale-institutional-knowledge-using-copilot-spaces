# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documents and quick references. The guidance here describes how we initiate, plan, execute, release, and improve work across cross-functional teams so contributors and stakeholders can move from idea to production with predictable quality and visible progress.

OctoAcme follows an iterative, customer-first approach with clearly named owners for delivery and product outcomes. Projects start with a lightweight one‑pager to define the problem, success metrics, stakeholders, and a go/no‑go decision. Approved initiatives move into planning where work is broken into shippable increments, acceptance criteria are defined, dependencies and risks are captured in a risk register, and a release/milestone map is created.

Day-to-day execution uses a project board and a small‑PR + CI-based pull request workflow that enforces automated tests, linting, security scans, and at least one approval before merging. Team rhythm includes daily standups for blockers and progress, regular delivery syncs and demos, and a documented escalation path for blockers. Releases follow a standardized checklist (staging smoke tests, rollback plan, post-deploy verification) and incident playbooks for rapid response.

Continuous improvement is enforced through timeboxed retrospectives after sprints, releases, and incidents. Action items from retrospectives are owned, tracked in the backlog, and reviewed in weekly PM syncs to ensure measurable impact. Use the links below to jump to the detailed process documents in this folder.

Process documents
- octoacme-project-management-overview.md
- octoacme-project-initiation.md
- octoacme-project-planning.md
- octoacme-execution-and-tracking.md
- octoacme-risks-and-communication.md
- octoacme-release-and-deployment.md
- octoacme-retrospective-and-continuous-improvement.md
- octoacme-roles-and-personas.md

How to use this folder
- Keep the Project One-pager and project README updated in the project repo.
- Add process-specific or team-specific variants into `.copilot/` if you want Copilot Spaces to use them as context.
- Use the provided issue template (.github/ISSUE_TEMPLATE/) to propose updates to any of these docs.
