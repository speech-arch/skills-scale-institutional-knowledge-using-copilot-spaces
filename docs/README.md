# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management knowledge base. This folder centralizes the processes, templates, and guidance used to run projects from initiation through retrospective and continuous improvement.

OctoAcme runs projects with a clear, stage-based lifecycle and lightweight artifacts designed to keep work focused and measurable. Initiation requires a one‑pager that captures problem, goals, success metrics, stakeholders, and a high‑level timeline; planning then breaks approved initiatives into a prioritized backlog, estimates scope, defines a Definition of Done, and maps milestones and dependencies. Execution uses a project board (Backlog → Ready → In Progress → In Review → QA → Done) and small, CI‑backed pull requests with acceptance criteria and required reviews. Releases are classified (patch/minor/major) and must meet pre‑release checks (passing CI, security scans, release notes, rollback plan) with an explicit deployment checklist and incident playbook.

Roles and responsibilities are explicitly called out to maintain clear ownership. Product Managers define outcomes and measure success; Project Managers coordinate delivery, schedules, risks, and communications; Developers implement features, tests, and reviews; QA validates acceptance. Stakeholders provide inputs and approvals. Key artifacts — one‑pager, roadmap, risk register, acceptance criteria, Definition of Done — should be kept up to date in each project repository.

Quality assurance and continuous improvement are integrated into each phase. QA practices include unit and integration tests, end‑to‑end smoke tests for critical flows, security scanning in CI, and manual QA where needed. Teams track delivery signals (velocity, burndown) and use dashboards for errors and usage. Retrospectives after sprints, releases, or incidents follow a structured format (what went well, what could improve, action items with owners and due dates) and convert improvements into backlog items.

## Table of contents
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

## Quick reference: key roles & artifacts
- Roles: Project Manager (PM), Product Manager (PdM), Developers, QA, Stakeholders
- Key artifacts: Project One‑pager / Charter, Roadmap & Release Plan, Risk Register, Sprint Backlog with Acceptance Criteria, Retrospective notes and action items
- Communication cadence: daily standups, weekly PM+PdM sync, delivery demos per sprint, monthly stakeholder updates

## How to use these docs
1. Start with the Project Management Overview to understand scope and principles.
2. Follow the phase-specific guide for the current lifecycle stage (initiation → planning → execution → release → retrospective).
3. Keep project-specific artifacts (one-pager, risk register, DoD) in the project repo.
4. Use checklists and templates inside each doc when preparing kickoffs, releases, and retrospectives.
5. To suggest changes or add process content, file an issue using the "Add Content to Project Management Process Docs" template.
