# OctoAcme Project Management Documentation

## Overview

OctoAcme employs a structured, lifecycle-based approach to project management grounded in customer value, iterative delivery, and clear accountability. This documentation suite provides comprehensive guidance on how we run projects from initiation through retrospective and continuous improvement.

## Core Principles

- **Customer-first**: prioritize customer value and usability
- **Iterative delivery**: deliver small, testable increments
- **Clear ownership**: each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: measure impact and iterate based on evidence
- **Psychological safety**: encourage feedback and learning

## How OctoAcme Runs Projects

OctoAcme operates through five distinct phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. Each phase is supported by lightweight but comprehensive documentation, including project charters, one-pagers, backlogs, and risk registers. The framework emphasizes early stakeholder alignment and measurable success criteria, requiring projects to pass decision gates before advancing to the next phase.

Execution and delivery are managed through a combination of agile ceremonies and clear quality standards. The team follows a pull-request-driven workflow with small PRs (≤400 lines when possible), automated CI/CD testing, security scanning, and at least one code review approval before merging. Daily standups (15 minutes) focus on progress and blockers, while weekly delivery syncs showcase progress and flag risks.

OctoAcme defines clear roles and responsibilities to ensure accountability and coordination. **Project Managers** own schedules, risks, and communications; **Product Managers** define outcomes, prioritize the backlog, and measure success; **Developers** implement features and collaborate on design and testability; and **QA/Testing** validates quality and acceptance criteria. Communication flows through multiple channels with structured escalation paths for critical blockers.

Finally, OctoAcme embeds learning and continuous improvement into every project cycle. Retrospectives are held after each sprint, release, or milestone, and action items from retrospectives and incidents are tracked in the project backlog with clear success criteria and timelines. This commitment to blameless retrospectives and iterative process refinement fosters psychological safety and drives the organization's ability to deliver reliably while continuously raising its standards.

## Process Documentation

### Getting Started

- [Project Management Overview](octoacme-project-management-overview.md) — High-level introduction to roles, principles, and artifacts
- [Roles and Personas](octoacme-roles-and-personas.md) — Detailed descriptions of team roles and responsibilities

### Project Lifecycle

1. **Initiation**: [Project Initiation Guide](octoacme-project-initiation.md) — Validate business need, align stakeholders, create initial plan
2. **Planning**: [Project Planning](octoacme-project-planning.md) — Break work into shippable increments, identify risks and dependencies
3. **Execution**: [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day management, standups, quality standards
4. **Release**: [Release & Deployment Guide](octoacme-release-and-deployment.md) — Standardized deployment and rollback procedures
5. **Close**: [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and drive improvements

### Cross-Cutting Concerns

- [Risk Management & Communication](octoacme-risks-and-communication.md) — Risk registers, escalation paths, and stakeholder updates

## Navigate by Role

- **Developers**: Start with [Execution & Tracking](octoacme-execution-and-tracking.md) and [Roles and Personas](octoacme-roles-and-personas.md)
- **Project Managers**: Read the [Overview](octoacme-project-management-overview.md), then follow the full lifecycle docs
- **Product Managers**: Focus on [Initiation](octoacme-project-initiation.md) and [Planning](octoacme-project-planning.md)
- **New Team Members**: Start with the [Overview](octoacme-project-management-overview.md) and [Roles and Personas](octoacme-roles-and-personas.md)

## How to Use These Docs

- Keep the Project Charter updated in your project repo
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context
- Contribute updates and improvements via pull requests using the [Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template
