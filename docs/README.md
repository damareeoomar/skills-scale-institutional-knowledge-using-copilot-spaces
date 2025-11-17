# OctoAcme Project Management Docs

OctoAcme runs projects with a pragmatic, iterative lifecycle built around clear principles: customer-first delivery, iterative increments, explicit ownership, data-informed decisions, and psychological safety. Work moves through five high-level stages — Initiation, Planning, Execution, Release, and Retrospective — with lightweight artifacts used to make decisions (Project One-pager/charter, roadmap/release plan, backlog, acceptance criteria, and a living risk register). The Initiation phase confirms the problem, stakeholders, success metrics and a go/no-go decision; Planning turns approved initiatives into prioritized, estimated backlogs and release milestones; Execution focuses on small, testable increments; Release follows a checklist-driven deployment process; and Close/Retrospective captures learnings and action items.

Core workflows emphasize predictable handoffs and visible boards. Teams use a project board with columns such as Backlog, Ready, In Progress, In Review, QA, and Done, and follow a pull request workflow that favors small PRs, includes issue links and acceptance criteria in PR descriptions, and requires CI (tests, linting, security scans) and at least one approval before merge. Backlog items follow a template (title, description, acceptance criteria, priority, estimate, owner, links), and planning activities include a kickoff, capacity-aware sprint planning, dependency identification, and a documented Definition of Done. Risk and dependency management is formalized using a Risk Register that is reviewed regularly.

Roles and responsibilities are explicit to reduce ambiguity: Project Manager (coordinates delivery, schedules, risks, communications), Product Manager (defines outcomes, prioritizes backlog, measures success), Developers (build and test), QA/Testing (validate quality and acceptance), and Stakeholders (input and approvals). These personas drive the day-to-day and governance activities — PMs run coordination and status reporting, PdMs set priorities and success metrics, developers own implementation and tests, and QA ensures acceptance criteria are met. Decision gates (e.g., move from Initiation to Planning) rely on named owners and clear criteria such as stakeholder alignment and defined success metrics.

Communication and quality assurance are baked into the rhythm and tooling: daily standups (15 minutes) and a weekly delivery sync keep the team aligned; demos/reviews occur at the end of sprints or milestones; PM+PdM weekly syncs and monthly stakeholder updates ensure broader transparency. Quality practices include unit and integration tests, end-to-end smoke tests for critical flows, automated security scanning in CI, and manual QA where needed; deployment follows a pre-release checklist (CI passing, release notes, rollback plan, staging smoke tests) and an incident/rollback playbook. Continuous improvement is enforced via regular retrospectives with prioritized action items that feed back into the backlog.

## Docs Directory

- [OctoAcme Project Management Overview](octoacme-project-management-overview.md)
- [OctoAcme Project Initiation](octoacme-project-initiation.md)
- [OctoAcme Project Planning](octoacme-project-planning.md)
- [OctoAcme Execution and Tracking](octoacme-execution-and-tracking.md)
- [OctoAcme Risks and Communication](octoacme-risks-and-communication.md)
- [OctoAcme Release and Deployment](octoacme-release-and-deployment.md)
- [OctoAcme Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [OctoAcme Roles and Personas](octoacme-roles-and-personas.md)

## How to use these docs

This directory is the single source of truth for OctoAcme project management processes. Keep the Project One-pager and process docs current in this folder. To propose changes or add new content, use the [.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.
