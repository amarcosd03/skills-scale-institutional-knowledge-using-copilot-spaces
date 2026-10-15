# OctoAcme Project Management Docs

## Overview

OctoAcme runs projects iteratively with clear ownership and measurable outcomes. Work begins with a lightweight Project One-pager that captures the problem, goals, success metrics, stakeholders, and an initial timeline. Projects progress through a simple lifecycle 9 Initiation  Planning  Execution  Release  Retrospective  with decision gates before moving between phases to ensure alignment and readiness.

Planning focuses on breaking approved initiatives into shippable increments with acceptance criteria, estimating scope, and identifying dependencies and risks in a Risk Register. Execution follows a project board workflow (Backlog  Ready  In Progress  In Review  QA  Done), emphasizes small pull requests, and requires CI checks (tests, linting, security scans) before review. Team rhythm includes daily standups, weekly delivery syncs, and demos at the end of each sprint or milestone to surface progress and blockers.

Roles and responsibilities are explicit: Product Managers define outcomes and prioritize the backlog; Project Managers coordinate delivery, timelines, and stakeholder communication; Developers implement features and maintain tests; QA validates acceptance criteria and manages quality gates; Stakeholders provide input and approvals. These personas ensure clear handoffs, escalation paths, and accountability throughout delivery.

Quality and release practices combine automated testing (unit, integration, smoke), CI gates, and security scanning with manual QA where needed. Releases follow pre-release checklists (release notes, rollback plans, smoke tests) and include incident communication and post-release retrospectives. Regular reporting (velocity, dashboards, weekly status) and tracked retrospective action items close the loop and drive continuous improvement.

## Process documents

- [Project management overview](./octoacme-project-management-overview.md)
- [Project initiation guide](./octoacme-project-initiation.md)
- [Project planning](./octoacme-project-planning.md)
- [Execution & tracking](./octoacme-execution-and-tracking.md)
- [Risk management & communication](./octoacme-risks-and-communication.md)
- [Release & deployment guide](./octoacme-release-and-deployment.md)
- [Retrospective & continuous improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & personas](./octoacme-roles-and-personas.md)

## Acceptance criteria

- README links to all process documents in docs/
- README includes a concise summary of workflows, roles, communication cadence, and quality practices
- README improves discoverability and supports Copilot Spaces indexing
