# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management process documentation. This folder contains comprehensive guides for running projects across all delivery phases—from initial concept through retrospective and continuous improvement.

## Quick Start: Project Management Overview

OctoAcme follows a structured **five-phase project lifecycle**:

1. **Initiation** — Validate business need, identify stakeholders, and create a Project One-pager
2. **Planning** — Break work into shippable increments, identify dependencies, and establish timeline
3. **Execution** — Deliver through iterative sprints with daily standups and continuous testing
4. **Release** — Deploy to production with standardized checklists and rollback plans
5. **Close & Retrospective** — Capture learnings and drive continuous improvement

### Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

### Core Roles

- **Project Manager (PM)** — Coordinates delivery, schedules, risk, and communications
- **Product Manager (PdM)** — Defines outcomes, prioritizes backlog, measures success
- **Developers** — Implement features, collaborate on design and testability
- **QA/Testing** — Validate quality and acceptance criteria
- **Stakeholders** — Provide inputs and approvals

### Communication Cadence

- **Weekly sync** between PM + Product Manager
- **Twice-weekly standups** for delivery team (or as agreed)
- **Monthly stakeholder updates**
- **Ad-hoc escalations** as needed

---

## Process Documentation

### 📋 [Project Management Overview](./octoacme-project-management-overview.md)
Concise introduction to how OctoAcme runs projects, including core roles, key artifacts, and the high-level lifecycle.

### 🚀 [Project Initiation Guide](./octoacme-project-initiation.md)
Initial steps to validate and authorize work, align stakeholders, and create a lightweight plan. Includes the Project One-pager template and initiation checklist.

### 📝 [Project Planning](./octoacme-project-planning.md)
Turn an approved initiative into an actionable plan and backlog. Covers kickoff, backlog prioritization, estimation, Definition of Done, and risk/dependency management.

### ⚙️ [Execution & Tracking](./octoacme-execution-and-tracking.md)
Manage day-to-day execution and track progress toward milestones. Defines team rhythm, PR workflows, quality practices, reporting metrics, and blocker escalation.

### ⚠️ [Risk Management & Communication](./octoacme-risks-and-communication.md)
Identify, manage, and communicate risks and dependencies. Includes risk register template, stakeholder communication strategies, and escalation paths.

### 🎯 [Release & Deployment Guide](./octoacme-release-and-deployment.md)
Standardize how OctoAcme releases features to production. Covers release types, pre-release requirements, deployment checklist, rollback playbook, and release notes template.

### 🔄 [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
Capture learnings after sprints, releases, or milestones. Includes retrospective structure, action item tracking, and continuous improvement culture.

### 👥 [Roles & Personas](./octoacme-roles-and-personas.md)
Detailed definitions of typical roles (Developers, Product Managers, Project Managers) and their responsibilities, goals, and communication patterns.

---

## Quality & Testing Practices

OctoAcme embeds quality throughout the entire project lifecycle:

- **Unit tests** for new logic
- **Integration tests** where applicable
- **End-to-end smoke tests** for critical flows before release
- **Security scanning** in CI pipelines
- **Manual QA** for feature acceptance when needed
- **Velocity and burndown tracking** for metrics-driven decisions

---

## How to Use These Docs

1. **New to OctoAcme?** Start with [Project Management Overview](./octoacme-project-management-overview.md)
2. **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md)
3. **In execution?** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risk Management & Communication](./octoacme-risks-and-communication.md)
4. **Preparing to release?** Use the [Release & Deployment Guide](./octoacme-release-and-deployment.md)
5. **Wrapping up?** Run a structured [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

Keep the Project Charter updated in your project repo. Add process-specific docs to `.copilot/` if you want Copilot Spaces to use them as context.

---

## Contributing to Process Docs

To request updates or add new content to the OctoAcme process documentation, use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.

---

**Last Updated:** 2026-05-17
