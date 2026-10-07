# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This collection of guides helps teams run projects using OctoAcme’s customer-first, iterative, and evidence-driven approach to delivery.

## Brief Overview

OctoAcme’s project management process follows a clear lifecycle: initiation, planning, execution, release, and closeout. In the initiation phase, the team validates the business need, aligns stakeholders, defines success metrics, and prepares a lightweight project one-pager with goals, timeline, risks, and resource needs. Once approved, planning turns the idea into a prioritized backlog with clear acceptance criteria, estimates, milestones, and a definition of done. During execution, the team uses daily standups, weekly delivery syncs, sprint demos, and project board tracking to ensure work stays visible, accountable, and aligned with delivery goals.

The program relies on clearly defined roles and responsibilities. The Project Manager coordinates delivery, scheduling, risks, and communication; the Product Manager defines outcomes and prioritization; developers build and test the solution; QA validates quality and acceptance criteria; and stakeholders provide input, approvals, and business context. Communication is a core practice, with regular updates, escalation paths, and a single source of truth for project status. Quality is built into the process through unit and integration testing, smoke tests for critical workflows, PR review gates, security scanning, and release validation before production deployment.

## Quick Start

New to OctoAcme? Start with the [Project Management Overview](octoacme-project-management-overview.md) for a high-level introduction to the approach, roles, and key artifacts.

## Core Principles

- Customer-first: prioritize customer value and usability
- Iterative delivery: deliver small, testable increments
- Clear ownership: each project has a named PM and Product Lead
- Data-informed decisions: measure impact and iterate based on evidence
- Psychological safety: encourage feedback and learning

## Project Lifecycle & Documentation Map

### 1. Initiation
[Project Initiation Guide](octoacme-project-initiation.md) — Validate business need, identify stakeholders, define success criteria, and confirm the project is ready to plan.

### 2. Planning
[Project Planning](octoacme-project-planning.md) — Break work into shippable increments, identify dependencies, estimate scope, define Definition of Done, and create a release plan.

### 3. Execution
[Execution & Tracking](octoacme-execution-and-tracking.md) — Manage day-to-day delivery, standups, progress tracking, quality standards, and milestone reporting.

### 4. Release
[Release & Deployment Guide](octoacme-release-and-deployment.md) — Standardize production releases, document deployment checklists, prepare rollback procedures, and communicate release outcomes.

### 5. Close & Learn
[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture lessons learned, track action items, and improve the process over time.

## Cross-Cutting Guides

- [Risk Management & Communication](octoacme-risks-and-communication.md) — Identify, assess, and monitor risks; establish escalation paths; maintain stakeholder updates
- [Personas](octoacme-roles-and-personas.md) — Core roles, responsibilities, goals, and communication patterns

## Complete Document Index

- [OctoAcme Project Management Overview](octoacme-project-management-overview.md)
- [OctoAcme Project Initiation Guide](octoacme-project-initiation.md)
- [OctoAcme Project Planning](octoacme-project-planning.md)
- [OctoAcme Execution & Tracking](octoacme-execution-and-tracking.md)
- [OctoAcme Risk Management & Communication](octoacme-risks-and-communication.md)
- [OctoAcme Release & Deployment Guide](octoacme-release-and-deployment.md)
- [OctoAcme Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [OctoAcme Personas](octoacme-roles-and-personas.md)

## Key Roles Summary

- Project Manager: coordinates delivery, schedules, risks, dependencies, and communications
- Product Manager: defines outcomes, prioritizes backlog, and measures success
- Developers: implement features, collaborate on design and testability, and maintain code quality
- QA/Testing: validate acceptance criteria and release readiness
- Stakeholders: provide inputs, approvals, and alignment on success measures

## Quality Assurance Practices

OctoAcme embeds quality throughout delivery instead of treating it as a final step. Teams are expected to write unit tests for new logic, add integration tests where appropriate, and run end-to-end smoke tests for critical user flows before release. Pull requests should remain small, include issue references and acceptance criteria, and must pass automated tests and linting in CI before review. The process also requires at least one approval before merge and includes security scanning as part of the standard quality bar.

## Contributing

To suggest updates or additions to these process docs, create an issue using the [Process Doc Update](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
