# OctoAcme Project Management Docs

This folder centralizes OctoAcme's project management processes, artifacts, and links to detailed process guidance. Use this README as the single entry point for onboarding, runbooks, and working agreements used by teams delivering features, services, and integrations.

OctoAcme runs projects through a lightweight, iterative lifecycle: Initiation (validate the problem and define success), Planning (turn outcomes into a prioritized backlog and release plan), Execution (deliver small, testable increments with continuous feedback), Release (pre-release checks, staged deployments, and post-release verifications), and Retrospective & Continuous Improvement. Each stage uses clear artifacts — a Project One-pager, backlog items with acceptance criteria, a Risk Register, and a release checklist — so decisions and status are traceable and discoverable.

Key workflows emphasize small batch delivery and clear handoffs. Work flows across a project board (Backlog → Ready → In Progress → In Review → QA → Done). Pull requests are small, include issue links and acceptance criteria, run CI (tests and security scans) before review, and require approval per team policy. Execution cadence includes daily standups for team-level triage, weekly delivery syncs for cross-team coordination, and demos/retrospectives at milestone boundaries.

Roles and personas are explicit to reduce ambiguity: Product Managers (PdMs) define outcomes and prioritize; Project Managers (PMs) coordinate schedule, risks, and stakeholder communications; developers implement and maintain tests; QA validates acceptance criteria and supports release verification; stakeholders provide input and approvals. Communication and risk-management practices use a simple Risk Register (ID, impact, likelihood, owner, mitigation, status), a weekly status template (progress, next steps, risks, asks), and defined escalation paths (team → PM → Product Lead → Sponsor). Quality assurance is layered with unit/integration tests, E2E smoke tests for critical flows, CI security scans, manual QA when needed, and a release checklist + rollback playbook to reduce production risk.

Process document links
- octoacme-project-management-overview.md
- octoacme-project-initiation.md
- octoacme-project-planning.md
- octoacme-execution-and-tracking.md
- octoacme-risks-and-communication.md
- octoacme-release-and-deployment.md
- octoacme-retrospective-and-continuous-improvement.md
- octoacme-roles-and-personas.md

How to use this README
- Keep this file updated with any new process docs added to the `docs/` folder.
- When starting a project, add a Project One-pager and link it from the project repo README.
- To propose changes to process docs, open an issue using the "Add Content to Project Management Process Docs" template in `.github/ISSUE_TEMPLATE/`.