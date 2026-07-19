# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation suite. This README provides a guide to our structured, scalable approach to running projects that deliver customer value through clear ownership, iterative delivery, and data-informed decisions.

## Quick Start

New to OctoAcme project management? Start with [OctoAcme Project Management Overview](./octoacme-project-management-overview.md) to understand our principles, roles, and key artifacts.

## OctoAcme Project Management Overview

OctoAcme follows a structured, lifecycle-based approach to project management grounded in customer-first principles and iterative delivery. The organization applies a consistent five-phase framework across all cross-functional projects: **Initiation, Planning, Execution, Release, and Close & Retrospective**. Each phase is guided by clear deliverables and decision gates.

During **Initiation**, teams validate business need and create a lightweight Project One-pager that establishes the problem statement, success metrics, stakeholder alignment, and go/no-go decision criteria. Once approved, **Planning** transforms the initiative into an actionable backlog with prioritized, estimated work items and a release timeline. This ensures scope clarity and identifies dependencies early before execution begins.

Execution and delivery are coordinated through structured communication rituals and agile practices. Teams maintain a daily standup cadence (15 minutes) focused on progress and blockers, weekly delivery syncs to flag risks, and demos at sprint or milestone endpoints. Work flows through a GitHub Projects board with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done), and Pull Requests follow a lightweight protocol: small PRs (≤400 lines), inclusion of issue links and acceptance criteria, automated CI checks, and at least one approval before merge. Quality assurance is embedded throughout via unit tests, integration tests, end-to-end smoke tests for critical flows, and security scanning in CI—ensuring that features meet acceptance criteria and maintain system reliability.

Risk and stakeholder management run parallel to delivery. A Risk Register maintained in simple tabular format captures ID, description, impact/likelihood, owner, and mitigation plan, reviewed weekly. Three-tier escalation paths (team-level → PM → Product Lead → Sponsor) ensure blockers are surfaced promptly and business-impacting issues reach decision-makers. Weekly status templates standardize communication, and incident protocols provide playbooks for rollback and blameless retrospectives. The organization defines three core delivery roles—**Project Managers** (coordinate schedules, risks, and communications), **Product Managers** (define outcomes, prioritize backlog, measure success), and **Developers** (implement features, collaborate on design and testability)—each with clear responsibilities and communication patterns.

Continuous improvement is woven into the culture through structured retrospectives held after each sprint, release, or milestone. These sessions capture what went well, what could improve, and generate 2–3 prioritized action items with named owners and due dates. Action items are tracked in the project backlog, reviewed in weekly PM syncs, and their impact is measured over time. Combined with a strong emphasis on data-informed decisions, transparent documentation (maintained in `docs/` and `.copilot/` folders), and psychological safety, OctoAcme's processes create a repeatable, scalable framework that reduces single-person dependency risk, accelerates onboarding, and ensures consistent, transparent project execution across the organization.

## Process Guides

Our project lifecycle is organized into five phases, each with detailed guidance:

1. **[Project Initiation](./octoacme-project-initiation.md)** — Validate business need, align stakeholders, create a lightweight plan
2. **[Project Planning](./octoacme-project-planning.md)** — Break work into shippable increments, identify dependencies, align timelines
3. **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day execution, track progress, maintain team rhythm
4. **[Release & Deployment](./octoacme-release-and-deployment.md)** — Standardize releases, reduce risk, improve observability
5. **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings, convert to actionable improvements

## Cross-cutting Topics

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Define typical roles and responsibilities in OctoAcme projects

## Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## How to Use These Docs

- Keep process documentation updated as your team evolves its practices
- Reference specific guides during project phases for detailed checklists and templates
- Use these docs as training material for new team members joining OctoAcme projects
- Add role-specific guidance to `.copilot/` if using Copilot Spaces for context
