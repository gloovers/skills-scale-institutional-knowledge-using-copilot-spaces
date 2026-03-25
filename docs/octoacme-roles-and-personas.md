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

## QA Lead

### Role Summary
The QA Lead owns the quality strategy for the project. They coordinate test planning, lead defect triage, and provide the go/no-go signal on release readiness.

### Responsibilities
- Define and maintain test plans, test cases, and acceptance criteria coverage
- Lead defect triage and prioritize bug fixes with Developers
- Validate that Definition of Done and acceptance criteria are met before release
- Manage test environments in coordination with DevOps Engineer
- Report quality status and coverage metrics to the Project Manager

### Goals
- Prevent regressions and ensure high-quality releases
- Reduce the cost of defects by catching issues early in the cycle
- Maintain clear quality gates throughout the project lifecycle

### Typical Communication
- Daily standups to flag blocking defects and test progress
- Weekly delivery syncs to report quality status and coverage
- Pre-release go/no-go sign-off with PM and PdM
- Retrospective input on defect trends and process improvements

---

## UX Designer

### Role Summary
The UX Designer advocates for end-user needs throughout the project lifecycle. They create wireframes, prototypes, and usability test plans that guide development decisions.

### Responsibilities
- Conduct user research and translate insights into design artifacts
- Create wireframes, prototypes, and interaction specifications
- Collaborate with Product Managers on user flows and feature scoping
- Provide developers with design assets and answer design questions
- Facilitate usability testing and incorporate findings into designs

### Goals
- Ensure the product is intuitive, accessible, and valuable to users
- Reduce ambiguity for Developers by providing clear design specifications
- Bring user evidence into prioritization and trade-off discussions

### Typical Communication
- Scoping and planning sessions with Product Manager
- Design review sessions with Developers before implementation
- Usability findings shared at weekly syncs and retrospectives
- Async feedback via design tool comments and PR reviews

---

## Technical Writer

### Role Summary
The Technical Writer produces and maintains user-facing and internal documentation. They ensure release notes, onboarding guides, and API docs are accurate and up to date.

### Responsibilities
- Author and maintain user guides, API references, and onboarding materials
- Draft and review release notes in coordination with Developers and PdM
- Collaborate with QA Lead to document user-impacting changes and known issues
- Keep process documentation and runbooks current as the project evolves

### Goals
- Ensure users and internal teams have clear, accurate documentation
- Reduce support burden through self-service documentation
- Keep docs in sync with each release

### Typical Communication
- Planning sessions with PdM and Developers to capture upcoming changes
- Pre-release checklist coordination to finalize release notes
- Retrospective input on documentation gaps identified during the sprint

---

## DevOps Engineer

### Role Summary
The DevOps Engineer manages CI/CD pipelines, automates deployment and infrastructure, and ensures system reliability and observability.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Manage test, staging, and production environments
- Implement monitoring, alerting, and logging infrastructure
- Support QA Lead with test environment provisioning
- Lead rollback procedures and incident response during deployments
- Communicate infrastructure risks and deployment impacts to the Project Manager

### Goals
- Enable fast, reliable, and repeatable deployments
- Minimize production incidents through automation and observability
- Support development velocity without compromising stability

### Typical Communication
- Sprint planning to surface infrastructure dependencies and risks
- Weekly delivery syncs to report pipeline and environment health
- Pre-release readiness checks with PM and QA Lead
- Incident updates and post-incident retrospectives

---

## Role Interaction Summary (RACI-ish)

The table below maps key project activities to primary (**P**) and supporting (**S**) roles.

| Activity | PdM | PM | Dev | QA Lead | UX Designer | Tech Writer | DevOps |
|---|---|---|---|---|---|---|---|
| Initiation & problem statement | P | S | S | | S | | |
| Planning & scope definition | P | P | S | S | S | S | S |
| Execution & feature delivery | S | S | P | S | S | | S |
| Quality gates & testing | | S | S | P | | | S |
| Risk & communication management | S | P | S | S | | | S |
| Release & deployment | S | P | S | P | | P | P |
| Retrospective & continuous improvement | S | P | S | S | S | S | S |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

