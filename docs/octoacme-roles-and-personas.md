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

## QA Lead / Quality Assurance Manager

### Role Summary
QA Leads own the quality strategy, manage testing resources, and ensure acceptance criteria and quality standards are validated before features are released to production.

### Responsibilities
- Define test plans and QA approach for each feature or release
- Coordinate manual QA, automated testing, and security scanning
- Validate acceptance criteria and Definition of Done
- Identify and triage quality issues and regressions
- Manage QA resources and capacity planning
- Ensure test coverage metrics are tracked and communicated

### Goals
- Prevent production defects and regressions
- Provide early feedback to developers on quality issues
- Establish and maintain quality standards across releases
- Reduce time to quality and time spent in QA phase

### Typical Communication
- Sprint planning and review meetings
- Test case and acceptance criteria discussions
- Defect reports and prioritization discussions
- Weekly quality metrics and test coverage updates

### Interaction with Other Roles
- **Developers**: Collaborate on test design, provide feedback on code quality and testability
- **Product Managers**: Validate acceptance criteria and define quality expectations
- **Project Managers**: Report quality metrics, identify blocking issues, coordinate testing schedule
- **Technical Leads**: Align on testing strategy and automation approach

---

## Technical Lead / Architect

### Role Summary
Technical Leads guide architectural decisions, lead design reviews, and ensure technical solutions are scalable, maintainable, and aligned with system standards.

### Responsibilities
- Review and approve technical designs and architecture decisions
- Mentor developers on best practices and code quality
- Identify technical risks and propose mitigation strategies
- Lead technical design reviews and code reviews for complex features
- Ensure system scalability, security, and maintainability
- Document technical decisions and rationale (ADRs)

### Goals
- Deliver technically sound, maintainable solutions
- Reduce technical debt and system complexity
- Build and share technical knowledge across the team
- Prevent architectural misalignment and integration issues

### Typical Communication
- Technical design reviews and architecture discussions
- Code review feedback and design consultation
- Technical documentation and ADR creation
- Mentoring and knowledge-sharing sessions

### Interaction with Other Roles
- **Developers**: Provide technical guidance, review designs and code, mentor on best practices
- **Product Managers**: Discuss technical feasibility and trade-offs during planning
- **Project Managers**: Flag technical risks and dependencies affecting timeline
- **QA Leads**: Collaborate on testability and quality requirements from technical perspective

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters facilitate agile team processes, remove blockers, and ensure agile practices and ceremonies are followed. They act as coaches to help the team continuously improve.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Remove impediments and blockers affecting team productivity
- Coach the team on agile practices and methodologies
- Track and report on team velocity and sprint metrics
- Foster psychological safety and continuous improvement culture
- Escalate risks and dependencies when needed

### Goals
- Enable team efficiency and predictability
- Maintain sprint commitments and sustainable pace
- Build team cohesion and psychological safety
- Drive continuous improvement through retrospectives

### Typical Communication
- Daily standups and sprint ceremonies
- One-on-one coaching sessions
- Retrospective facilitation and action item tracking
- Metrics reviews and team health assessments

### Interaction with Other Roles
- **Developers**: Remove blockers, facilitate collaboration, support team well-being
- **Product Managers**: Manage backlog refinement, prioritization discussions
- **Project Managers**: Coordinate cross-team dependencies, escalate risks
- **QA Leads & Technical Leads**: Ensure their inputs are reflected in sprint planning and execution

---

## Release Manager

### Role Summary
Release Managers coordinate deployment activities, manage release calendars, and ensure smooth handoffs to production. They oversee the release process from planning through post-deployment verification.

### Responsibilities
- Plan and schedule release windows and deployment timelines
- Coordinate pre-release activities (testing, documentation, migration prep)
- Manage release notes and communication to stakeholders and customers
- Execute deployment procedures and post-deployment verifications
- Manage rollback procedures and incident response during releases
- Track release metrics and compliance requirements

### Goals
- Deliver releases on schedule with minimal risk and downtime
- Ensure smooth communication and stakeholder coordination
- Maintain auditability and compliance of release processes
- Enable fast, safe rollback if issues occur

### Typical Communication
- Release planning and coordination meetings
- Deployment status updates and post-release reporting
- Stakeholder and customer announcements
- Incident and rollback communications

### Interaction with Other Roles
- **Developers**: Coordinate code freeze and merge procedures
- **QA Leads**: Confirm smoke test readiness and quality sign-off
- **Project Managers**: Align on timeline and dependencies
- **Operations/Support**: Coordinate pre-deployment notification and post-deployment monitoring

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, prioritization guidance, and approval authority for major decisions. They represent customer needs and organizational interests in project decisions.

### Responsibilities
- Provide business context and strategic guidance for projects
- Prioritize initiatives based on business value and customer impact
- Approve major decisions and trade-offs
- Represent customer and organizational perspectives
- Review progress against strategic objectives
- Provide feedback and validate outcomes

### Goals
- Ensure projects deliver business value
- Align projects with organizational strategy
- Make informed prioritization decisions
- Maintain visibility and alignment on project progress

### Typical Communication
- Monthly stakeholder updates and reviews
- Decision-making meetings on major trade-offs
- Progress reviews against success metrics
- Executive summaries and status reports

### Interaction with Other Roles
- **Product Managers**: Provide business priorities and customer insights
- **Project Managers**: Review progress, approve scope changes, escalate risks
- **All Roles**: Provide strategic context and decision-making authority

---

## Support / Operations Lead

### Role Summary
Support and Operations Leads represent customer and operational perspectives in project decisions. They manage production incidents, gather customer feedback, and ensure operational readiness.

### Responsibilities
- Define operational requirements and support processes
- Gather and communicate customer feedback and pain points
- Manage production incidents and escalations
- Ensure documentation and runbooks are complete and accurate
- Coordinate between product team and support organization
- Track and report on customer-facing quality metrics

### Goals
- Ensure operational readiness and support capability
- Reduce mean time to resolution (MTTR) for incidents
- Maximize customer satisfaction and reduce support burden
- Provide early warning of production issues

### Typical Communication
- Sprint planning and acceptance criteria reviews
- Post-deployment support handoff meetings
- Incident reports and customer feedback summaries
- Operational metrics and health dashboards

### Interaction with Other Roles
- **Developers**: Provide customer feedback and operational constraints
- **QA Leads**: Test against operational requirements and failure scenarios
- **Project Managers**: Report customer impact and operational risks
- **Release Manager**: Coordinate support readiness for releases

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the "Interaction with Other Roles" section to understand cross-functional dependencies and communication patterns.
