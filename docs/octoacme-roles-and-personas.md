# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Release Manager

### Role Summary
The Release Manager owns release planning and execution to ensure features are delivered safely and predictably to environments and production.

### Responsibilities
- Coordinate release schedules, windows, and cutover plans
- Maintain rollback and mitigation plans
- Verify completion of pre-release checks (CI, security scans, QA sign-off, smoke tests)
- Communicate release status to stakeholders and support teams
- Drive post-release verification and monitoring

### Interactions
- Works with PM/PdM to align release timing with product priorities
- Coordinates with Developers, QA, and Security Lead to confirm readiness
- Partners with Support Liaison for post-release monitoring and customer communications

### Typical Communication
- Release notes, deployment runbooks, and status updates
- Release planning meetings and deployment runbooks

---

## Technical Program Manager (TPM)

### Role Summary
The TPM coordinates complex technical initiatives across multiple teams, managing dependencies and ensuring timely delivery of cross-team milestones.

### Responsibilities
- Identify and track cross-team technical dependencies and risks
- Drive milestone alignment across engineering teams
- Facilitate technical design trade-offs and integration plans
- Track progress and unblock cross-team impediments

### Interactions
- Collaborates with Project Manager and Engineering Leads to align timelines
- Works closely with Developers and Data Engineer where integrations are required
- Escalates unresolved cross-team technical risks to PM/PdM or Product Leadership

### Typical Communication
- Dependency maps, technical milestone updates, and integration status reports
- Cross-team syncs and RFC/design review coordination

---

## UX Researcher

### Role Summary
The UX Researcher leads research to inform product decisions, validate designs, and ensure usability acceptance criteria are practical and measurable.

### Responsibilities
- Design and run user research (interviews, usability tests, surveys)
- Synthesize findings into actionable recommendations and acceptance criteria
- Validate design hypotheses with target users
- Collaborate on user-facing acceptance criteria and success metrics

### Interactions
- Partners with PdM to prioritize research questions and interpret results
- Works with Developers and QA to translate usability findings into acceptance criteria and automated/manual test plans
- Feeds insights into backlog refinement and prioritization

### Typical Communication
- Research reports, user journey maps, and usability test summaries
- Presentations to product and engineering teams

---

## Security Lead

### Role Summary
The Security Lead ensures that security considerations are integrated into planning, design, and release activities to reduce vulnerabilities and maintain compliance.

### Responsibilities
- Define security requirements and threat models for initiatives
- Conduct security reviews of designs and PRs
- Coordinate security scans and remediation tracking
- Advise on secure defaults, secrets management, and incident prevention

### Interactions
- Works with Developers and TPM to address technical security risks
- Coordinates with PM/Project Manager for security-related scheduling and trade-offs
- Engages with Support Liaison and Incident Response teams during security incidents

### Typical Communication
- Security review notes, vulnerability reports, and compliance checklists
- Security escalation paths and incident runbooks

---

## Data Engineer / Analytics Owner

### Role Summary
The Data Engineer ensures telemetry, metrics, and data pipelines are in place so teams can measure outcomes and validate success criteria.

### Responsibilities
- Define and implement instrumentation and telemetry for features
- Maintain data pipelines and ensure data quality for product metrics
- Provide analysis to validate success metrics and support experiments
- Support event/schema design and coordinate analytics deployments

### Interactions
- Partners with PdM to define measurable success criteria and dashboards
- Works with Developers to implement instrumentation and with QA to validate telemetry
- Coordinates with TPM for cross-system data integrations

### Typical Communication
- Metric definitions, dashboard links, and data quality reports
- Analytics runbooks and deployment notes

---

## Support Liaison / Customer Success Representative

### Role Summary
The Support Liaison represents post-release customer experience, surfaces recurring issues, and coordinates support escalations and knowledge base updates.

### Responsibilities
- Triage and surface customer-reported issues relevant to ongoing projects
- Provide context on customer impact and priority to the product and project teams
- Coordinate knowledge base updates and post-release customer communications
- Assist in reproducing and validating fixes for customer-reported problems

### Interactions
- Feeds customer impact and priority information to PM/PdM and Developers
- Works with Release Manager on post-release monitoring and communications
- Coordinates with Security Lead and QA for incident response when required

### Typical Communication
- Support triage notes, customer impact summaries, and escalation tickets
- Post-release incident summaries and knowledge base content

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
