# OctoAcme Project Management Process Docs

Welcome to OctoAcme's project management knowledge center. These docs capture our proven processes, roles, and workflows to help you deliver consistently and collaboratively.

## Overview of OctoAcme's Project Management Approach

OctoAcme operates under a structured, customer-first project lifecycle that emphasizes iterative delivery and clear ownership. The organization follows five distinct phases: **Initiation** (validating business need and stakeholder alignment), **Planning** (breaking work into shippable increments with defined acceptance criteria), **Execution** (managing day-to-day delivery through standups and iterative cycles), **Release** (deploying to production with rigorous safety checks), and **Close & Retrospective** (capturing learnings for continuous improvement). This phased approach ensures that every project begins with a validated problem statement and measurable success metrics, and ends with structured reflection to drive process improvements across teams.

The organization defines clear roles and responsibilities across three core personas: **Developers** implement features and maintain code quality through tests and reviews; **Product Managers** define what should be built by prioritizing the backlog and validating solutions through user research and metrics; and **Project Managers** coordinate delivery, manage risks and dependencies, and facilitate communication across stakeholders. Each project has a named PM and Product Lead, ensuring accountability and clear decision-making authority. This separation of concerns allows teams to move efficiently while maintaining alignment on customer value and business outcomes.

Communication flows through a consistent cadence: daily 15-minute standups focused on progress and blockers, weekly delivery syncs between PM and Product Lead, twice-weekly team standups (or as agreed), monthly stakeholder updates, and ad-hoc escalations as needed. OctoAcme uses GitHub Projects for visibility, with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) and small PR-based workflows (≤400 lines when possible). A three-level risk escalation path (team triage → PM escalation → sponsor escalation) ensures that blocking issues surface quickly without creating noise. Risk registers are maintained and updated weekly to track dependencies, impact, and mitigation strategies.

Quality and delivery consistency are embedded throughout the lifecycle via multiple practices: acceptance criteria and Definition of Done are documented before work begins; unit and integration tests are required for new logic; automated CI/CD pipelines run tests, linting, and security scanning before PRs are merged; and at least one approval is required before merging (or per team policy). End-to-end smoke tests validate critical flows before release, and rollback/incident playbooks provide guardrails for production deployments. Retrospectives held after each sprint or milestone—structured around what went well, what could improve, and prioritized action items—institutionalize learning and drive measurable, iterative improvements to process and team performance.

## Quick Links

### Getting Started
- [Project Management Overview](octoacme-project-management-overview.md) - Start here to understand OctoAcme's principles and roles
- [Roles & Personas](octoacme-roles-and-personas.md) - Learn who does what

### Project Lifecycle
1. [Project Initiation](octoacme-project-initiation.md) - Validate ideas and align stakeholders
2. [Project Planning](octoacme-project-planning.md) - Turn approvals into actionable plans
3. [Execution & Tracking](octoacme-execution-and-tracking.md) - Manage day-to-day delivery
4. [Release & Deployment](octoacme-release-and-deployment.md) - Ship to production safely
5. [Retrospective & Improvement](octoacme-retrospective-and-continuous-improvement.md) - Capture learnings

### Cross-cutting Concerns
- [Risk Management & Communication](octoacme-risks-and-communication.md) - Identify, escalate, and communicate

## For Your Role

**Developers:** Start with [Execution & Tracking](octoacme-execution-and-tracking.md) and [Roles & Personas](octoacme-roles-and-personas.md).

**Product Managers:** Begin with [Project Initiation](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md).

**Project Managers:** Review [Project Management Overview](octoacme-project-management-overview.md), then dive into [Project Planning](octoacme-project-planning.md), [Execution & Tracking](octoacme-execution-and-tracking.md), and [Risk Management](octoacme-risks-and-communication.md).

## OctoAcme Principles

- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Ship small, testable increments
- **Clear ownership:** Every project has a named PM and Product Lead
- **Data-informed decisions:** Measure and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning
