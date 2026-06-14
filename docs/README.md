# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation. This folder contains comprehensive guides for how we run projects from initiation through retrospective. Whether you're new to the team or looking for specific process guidance, you'll find everything you need here.

## Quick Start

New to OctoAcme? Start with the [Project Management Overview](./octoacme-project-management-overview.md) for a high-level introduction to our principles, roles, and key artifacts.

## Process Documentation

### Core Lifecycle Phases

- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Validate business needs, align stakeholders, and create a lightweight plan. Use the Project One-pager template and decision gate framework.

- **[Project Planning](./octoacme-project-planning.md)** — Turn approved initiatives into actionable backlogs with clear acceptance criteria, estimates, and release timelines. Includes Definition of Done and risk/dependency management.

- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Day-to-day guidance on standups, pull request workflows, CI/CD integration, testing requirements, and blocker escalation.

- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardized approach to releasing features to production, including pre-release requirements, deployment checklists, rollback procedures, and release notes templates.

- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — How to run effective retrospectives, capture learnings, and convert action items into documented improvements.

### Cross-Cutting Concerns

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Risk register templates, risk lifecycle, stakeholder communication strategies, escalation paths, and incident communication playbooks.

- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Definitions of key roles (Product Manager, Project Manager, Developers, QA) including responsibilities, goals, and typical communication patterns.

- **[Project Management Overview](./octoacme-project-management-overview.md)** — Foundational framework covering OctoAcme's principles, core roles, key artifacts, and high-level lifecycle.

---

## OctoAcme Approach: Overview

**Lifecycle and Core Workflows**

OctoAcme follows a structured yet lightweight project lifecycle consisting of five key phases: Initiation, Planning, Execution, Release, and Close & Retrospective. During Initiation, teams validate business needs, identify stakeholders, and define success metrics through a Project One-pager. The Planning phase transforms approved initiatives into actionable backlogs with prioritized, estimated work items and clear acceptance criteria. Execution emphasizes iterative delivery through small pull requests (≤400 lines), daily standups, and continuous integration with automated testing and security scanning. Release involves staged deployment to staging and production with pre-release verification and smoke testing. Finally, retrospectives capture learnings and convert them into documented action items for continuous improvement.

**Defined Roles and Clear Ownership**

The OctoAcme framework establishes clear role separation to ensure accountability and alignment. The **Product Manager (PdM)** owns the product vision, prioritizes the backlog, and measures success against defined metrics. The **Project Manager (PM)** coordinates delivery, manages schedules, risks, and cross-team communication, ensuring teams meet commitments and escalate blockers appropriately. **Developers** implement features, write tests, participate in reviews, and help estimate work while identifying technical risks. **QA/Testing** validates quality against acceptance criteria and performs manual acceptance testing when needed. **Stakeholders** provide inputs and approvals at key decision gates. This clear separation prevents ambiguity and ensures each function has explicit ownership.

**Communication Cadence and Risk Management**

Communication flows through a deliberate cadence: daily standups (15 min) for progress and blocker triage, weekly PM-PdM syncs, twice-weekly team standups, and monthly stakeholder updates. Risk and dependency management is formalized through a Risk Register that tracks ID, Description, Impact, Probability, Owner, and Mitigation strategies, with escalation paths progressing from team-level triage to PM to Product Lead to Sponsor for business-impacting issues. Status updates follow a structured template covering progress, next steps, risks, blockers, and decisions needed. This multi-layered communication approach ensures transparency, early identification of issues, and coordinated escalation.

**Quality Assurance and Definition of Done**

Quality is enforced through a defined Definition of Done (DoD) and multi-layer testing strategy. Teams must ensure unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows before release. All code changes require CI validation (tests, linting, security scanning) and at least one peer approval before merging. The framework emphasizes both automated quality gates (CI pipeline) and manual QA for feature acceptance. Success is measured through velocity and burndown tracking, monitoring of key metrics (errors, latency, usage), and regular demo/review cycles at sprint or milestone boundaries. This combination of automated and manual quality gates, paired with clear acceptance criteria, ensures consistent delivery of reliable, tested features.

---

## Key Principles

- **Customer-first:** Prioritize customer value and usability in every decision
- **Iterative delivery:** Deliver small, testable increments regularly
- **Clear ownership:** Each project has a named PM and Product Lead
- **Data-informed decisions:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback, learning, and continuous improvement

---

## How to Use These Docs

1. **Onboarding:** Start with the [Project Management Overview](./octoacme-project-management-overview.md) and [Roles & Personas](./octoacme-roles-and-personas.md)
2. **Starting a new project:** Follow the [Project Initiation Guide](./octoacme-project-initiation.md)
3. **During execution:** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) for daily guidance
4. **Managing risks:** Use [Risk Management & Communication](./octoacme-risks-and-communication.md) templates
5. **Before release:** Follow the [Release & Deployment Guide](./octoacme-release-and-deployment.md)
6. **After project close:** Run a retrospective using [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

---

## Questions?

If you have questions about OctoAcme processes, please:
- Check the relevant documentation file for your question
- Reach out to your Project Manager or Product Lead
- Suggest improvements by creating an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
