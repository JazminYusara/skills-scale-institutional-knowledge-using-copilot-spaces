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

## Additional Personas (proposed additions)

Below are additional roles commonly involved in delivery that help clarify responsibilities and improve handoffs.

### Delivery Lead
- Responsibilities: Coordinate day-to-day delivery, manage sprint commitments, remove operational blockers, maintain the project board and sprint cadence.
- Interactions: Works closely with the PM (scheduling, risk updates), Product Manager (scope decisions), Developers and QA (task execution), and stakeholders for status.

### Technical Lead
- Responsibilities: Provide technical direction, lead design reviews, ensure architectural consistency, mentor engineers, and review complex PRs.
- Interactions: Engages with Developers for implementation, Product Manager for feasibility discussions, and Engineering Manager for staffing and technical debt prioritization.

### Engineering Manager
- Responsibilities: People and performance management, capacity planning, hiring recommendations, and career growth for engineers.
- Interactions: Coordinates with PM on resourcing, Technical Lead on capability gaps, and HR for staffing matters.

### Business Analyst (BA)
- Responsibilities: Refine requirements, write clear acceptance criteria, map stakeholder needs to backlog items, and support UAT.
- Interactions: Partners with Product Manager for requirements, Developers and QA for clarifications, and Stakeholders for validation.

### UX Researcher / Designer
- Responsibilities: Run research, validate UX assumptions, provide designs and accessibility guidance, define usability acceptance criteria.
- Interactions: Works with Product Manager for problem framing, Developers for handoff, QA for usability checks, and Stakeholders for feedback.

### Release Engineer / CI-CD Owner
- Responsibilities: Maintain release pipelines, manage deployment automation, own rollback procedures and release verification steps.
- Interactions: Coordinates with Developers, SRE/On-call, and PM for release windows and rollback plans.

### Site Reliability / On-call (SRE)
- Responsibilities: Operational stability, incident response, production monitoring, and maintaining runbooks for escalations.
- Interactions: Works with Release Engineer on deployments, Developers on incident triage, and PM on customer-impact communication.

### Data Analyst
- Responsibilities: Define and track success metrics, instrument events, provide analysis for feature validation and retrospectives.
- Interactions: Supports Product Manager for success metrics, Developers for instrumentation, and Stakeholders with insights.

---

## RACI guidance (high level)
- Responsible: Role(s) who do the work (e.g., Developers, BA)
- Accountable: Single role ultimately answerable (e.g., Product Manager for product decisions, PM for delivery commitments)
- Consulted: Roles who provide expertise (e.g., Technical Lead, UX Researcher, Data Analyst)
- Informed: Stakeholders who need status updates (e.g., Sponsors, Support)

Provide a simple RACI table per major deliverable and include it in the project kickoff checklist.

---

## Example scenarios (short)

Feature handoff
- BA/PM finalize acceptance criteria
- Developers implement
- QA validates
- Delivery Lead tracks completion and coordinates release window

Release coordination
- Release Engineer prepares pipeline and rollback
- SRE validates monitoring and runbooks
- PM communicates timing and stakeholders
- Developers and QA are on-call for post-release verification

Incident response
- SRE leads triage and notifies on-call
- Developers investigate and produce fix
- PM communicates customer impact and status
- Release Engineer performs rollback if required
