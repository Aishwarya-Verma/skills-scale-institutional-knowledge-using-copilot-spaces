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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Operational & Cross-functional Personas (proposed additions)

Below are proposed personas to add to the Roles & Personas document. Each entry includes a role summary, responsibilities, and how the persona typically interacts with the existing roles.

### Delivery Lead

Role summary
- Coordinates day-to-day delivery across teams and ensures sprint commitments and release readiness.

Responsibilities
- Maintain sprint cadence and remove impediments to progress
- Track and surface delivery risks and cross-team dependencies
- Coordinate release readiness activities (release checklist, staging verification)
- Facilitate team-level coordination across squads for cross-cutting work

Interactions
- Works closely with Project Managers (scheduling and risk), Product Managers (scope alignment), Engineering Managers and Developers (capacity and technical trade-offs), and QA (release acceptance).
- Escalates unresolved blockers to PM or Product Lead as needed.

### Engineering Manager

Role summary
- Responsible for people management, technical quality, and capacity planning within engineering teams.

Responsibilities
- Manage and develop engineering team members
- Oversee capacity planning and staffing decisions
- Support technical design reviews and coding standards
- Own engineering-side risk mitigation and technical debt prioritization

Interactions
- Collaborates with Project Managers and Delivery Leads on resourcing and timelines.
- Works with Developers to unblock technical issues and with Product Managers on trade-offs that affect implementation effort.

### UX Researcher / Product Designer

Role summary
- Owns user research, interaction design, and validation of usability and accessibility.

Responsibilities
- Conduct user research and usability testing
- Produce design assets, prototypes, and accessibility checks
- Provide acceptance criteria and UX-related validation steps for backlog items
- Advocate for user needs throughout the lifecycle

Interactions
- Partners with Product Managers to define user needs and acceptance criteria.
- Works with Developers and QA during planning and validation to ensure deliverables meet usability and accessibility standards.

### Support Lead / Customer Operations

Role summary
- Frontline owner for customer issue intake, triage, and operational context.

Responsibilities
- Triage incoming customer issues and map to product/engineering work
- Maintain operational runbooks and support documentation
- Provide production context and impact analysis for incidents
- Feed customer-driven priorities back into the backlog

Interactions
- Informs Project Managers and Product Managers of customer-impacting issues and trends.
- Coordinates with SRE/Platform and on-call Engineers during incident triage and postmortems.

### Security Engineer / Security Liaison

Role summary
- Focuses on threat modeling, security reviews, and ensuring compliance with security requirements.

Responsibilities
- Perform security reviews for designs and pull requests
- Define security requirements and remediation priorities
- Run/interpret security scans and coordinate fixes
- Provide guidance on data-handling and compliance where applicable

Interactions
- Engages during planning and PR review stages to surface security considerations.
- Works with Developers and Release owners on mitigations and release gating for security findings.
- Coordinates with Project Managers when security risks impact timelines.

### SRE / Platform Engineer

Role summary
- Ensures production reliability, observability, and healthy platform/deployment pipelines.

Responsibilities
- Maintain deployment pipelines, monitoring, and alerting
- Define and update runbooks and on-call procedures
- Lead incident response and postmortems for production issues
- Drive capacity planning and reliability improvements

Interactions
- Supports Release & Deployment activities and verifies operational readiness.
- Works with Developers on instrumentation and remediation during incidents.
- Collaborates with Support Lead during incident triage.

### Data / Analytics Lead

Role summary
- Ensures measurement plans, instrumentation, and analytics support product success metrics.

Responsibilities
- Define instrumentation requirements and success metric tracking
- Maintain dashboards and support experiment/analysis needs
- Validate data quality and advise on metric interpretation
- Support A/B testing and measurement for feature launches

Interactions
- Partners with Product Managers to align on success metrics and dashboards.
- Works with Developers and SRE/Platform to ensure instrumentation is implemented and reliable.

---

## Why adding these personas improves outcomes

- Clarifies ownership for operational tasks (releases, incident response, security)
- Reduces delays caused by unclear handoffs and missing role responsibilities
- Improves onboarding with explicit role expectations and contacts
- Ensures cross-functional concerns (security, reliability, support, design, data) are considered earlier in planning and execution

---

## Suggested next steps

1. Add draft role entries above into docs/octoacme-roles-and-personas.md (this file).
2. Review with PM, PdM, Engineering Manager, Security, and Support representatives for completeness and accuracy.
3. Iterate and publish the update via the existing Issue Template (Add Content to Project Management Process Docs).
