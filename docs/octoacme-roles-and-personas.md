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

## Tech Lead / Solution Architect

### Role Summary
Tech Leads define solution architecture, evaluate technical trade-offs, and ensure the implementation aligns with system quality standards and long-term technical strategy.

### Responsibilities
- Review and approve technical approach and architecture decisions
- Identify technical risks and propose mitigations
- Mentor developers on design patterns and quality standards
- Support acceptance criteria definition from technical feasibility perspective
- Participate in code reviews for complex or critical components
- Advise on infrastructure, scalability, and integration requirements

### Goals
- Ensure solutions are maintainable, scalable, and aligned with technical strategy
- Reduce technical debt and rework through proactive design reviews
- Build team capability and shared ownership of quality

### Interaction with Existing Roles
- **With Developers**: Provides architectural guidance and design review feedback; helps resolve technical trade-offs in implementation
- **With Product Managers**: Advises on technical feasibility of features; helps validate acceptance criteria from a technical perspective
- **With Project Managers**: Escalates technical risks and dependencies; helps estimate effort based on architectural complexity

### Typical Communication
- Design reviews and architecture decisions
- Code review comments and technical guidance
- Technical risk register updates
- Escalations on trade-offs between speed and quality

---

## QA / Testing Lead

### Role Summary
QA Leads define the testing strategy, validate acceptance criteria, and ensure quality gates are met before release. They work closely with developers and product managers to ensure feature quality and user experience.

### Responsibilities
- Define test plan and testing strategy (unit, integration, end-to-end)
- Validate acceptance criteria and feature completeness
- Design and execute manual and automated test scenarios
- Identify quality risks and blockers
- Coordinate with developers on test coverage gaps
- Provide go/no-go recommendation for releases
- Triage and track defects through resolution

### Goals
- Ensure features meet acceptance criteria and user expectations
- Minimize production defects through comprehensive testing
- Enable fast, confident release cycles

### Interaction with Existing Roles
- **With Developers**: Collaborates on test coverage and quality standards; reviews test plans and identifies gaps
- **With Product Managers**: Validates feature acceptance criteria; provides quality metrics and readiness assessments
- **With Project Managers**: Updates quality status; escalates blockers and risk; provides release readiness recommendations

### Typical Communication
- Sprint planning and acceptance criteria refinement
- Test plan and QA status updates
- Defect reports and quality metrics
- Release readiness assessments

---

## DevOps / Release Engineer

### Role Summary
DevOps Engineers own the deployment infrastructure, CI/CD pipelines, and production reliability. They enable the team to deploy changes safely and rapidly.

### Responsibilities
- Build and maintain CI/CD pipelines and automation
- Manage infrastructure, environments, and configuration
- Coordinate and execute production deployments
- Monitor production health and performance
- Implement rollback procedures and incident response
- Advise on scalability, security, and operational requirements

### Goals
- Enable safe, repeatable, fast deployments to production
- Maintain high availability and performance of production systems
- Reduce deployment risk and manual effort

### Interaction with Existing Roles
- **With Developers**: Provides infrastructure guidance; assists with CI/CD setup and monitoring requirements
- **With Tech Leads**: Collaborates on scalability and infrastructure architecture; advises on operational requirements
- **With Project Managers**: Coordinates deployment windows; provides release status and production health visibility

### Typical Communication
- Release planning and deployment coordination
- Infrastructure and environment setup requirements
- Production incident response and post-mortems
- Monitoring and observability dashboards

---

## Sponsor / Executive Stakeholder

### Role Summary
Sponsors are business decision-makers who authorize project funding, priority, and resource allocation. They provide governance and escalation oversight.

### Responsibilities
- Authorize project scope, budget, and timeline
- Align project with business strategy and priorities
- Make trade-off decisions on scope, cost, and schedule
- Resolve cross-team dependencies and resource conflicts
- Escalate and resolve critical blockers
- Approve release to production and major milestones

### Goals
- Ensure project delivers business value
- Minimize risk and resource waste
- Maintain alignment with strategic priorities

### Interaction with Existing Roles
- **With Product Managers**: Aligns on business priorities and success metrics; approves feature scope and roadmap
- **With Project Managers**: Receives status updates; makes escalation decisions; approves resource allocation and timeline changes

### Typical Communication
- Project approval gates and decision points
- Monthly or milestone-based status updates
- Risk and issue escalations
- Release announcements and stakeholder briefings

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove blockers, and help teams adhere to processes and iteration discipline. They coach the team on continuous improvement and agile best practices.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Remove impediments and blockers that slow team progress
- Coach team members on agile practices and self-organization
- Track sprint metrics and iteration health
- Help resolve team conflicts and communication issues
- Ensure adherence to Definition of Done and process standards

### Goals
- Enable predictable, sustainable team velocity
- Foster psychological safety and continuous improvement
- Reduce process bottlenecks and ceremony drift

### Interaction with Existing Roles
- **With Developers**: Removes blockers; facilitates technical discussions; coaches on process adherence
- **With Project Managers**: Provides sprint metrics and team health visibility; escalates impediments; coordinates ceremonies
- **With Product Managers**: Facilitates backlog refinement; ensures clear acceptance criteria and priority communication

### Typical Communication
- Sprint planning and retrospective facilitation
- Daily standups and velocity tracking
- Impediment and blocker escalations
- Process improvement suggestions

---

## Design / UX Lead

### Role Summary
Design/UX Leads define user experience, validate usability, and ensure design quality across features and products. They advocate for user needs and ensure consistency in user-facing work.

### Responsibilities
- Define user experience and interaction patterns
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Validate design quality and accessibility standards
- Collaborate with developers on implementation fidelity
- Ensure design consistency across product

### Goals
- Deliver usable, delightful user experiences
- Reduce support burden through intuitive design
- Maintain design consistency and brand alignment

### Interaction with Existing Roles
- **With Product Managers**: Collaborates on user research and feature definition; ensures designs align with product goals
- **With Developers**: Provides design specs and acceptance criteria; reviews implementation fidelity; resolves technical feasibility questions
- **With QA Leads**: Participates in acceptance criteria validation; advises on usability test scenarios

### Typical Communication
- Design reviews and design-led ceremonies
- User research findings and usability testing results
- Design specifications and interaction documentation
- Feedback on implementation quality and consistency

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When working cross-functionally, reference the interaction patterns to understand how roles complement and depend on each other.
