# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management process docs. This folder contains comprehensive guidance for running projects successfully across OctoAcme, from initial conception through delivery and continuous improvement.

## What is OctoAcme?

OctoAcme follows a structured yet flexible project management approach that emphasizes:
- Customer-first thinking - prioritizing customer value and usability
- Iterative delivery - shipping small, testable increments
- Clear ownership - named Project Managers and Product Leads for every project
- Data-informed decisions - measuring impact and iterating based on evidence
- Psychological safety - encouraging feedback and learning

## Project Management Approach

OctoAcme's project management approach is structured around a clear lifecycle: initiation, planning, execution, release, and retrospective. The process begins with a validated project idea, where teams define the business problem, success metrics, stakeholders, and rough timeline in a project one-pager before moving into planning. From there, the team turns the initiative into a backlog, estimates effort, aligns on milestones, identifies dependencies, and defines a shared Definition of Done. This keeps work focused on delivering measurable value through small, testable increments rather than large, risky releases.

The operating model relies on a small set of core roles with distinct responsibilities. Product managers define outcomes and prioritize the roadmap, project managers coordinate execution, budget constraints, dependencies, and communication, and developers are responsible for building, testing, and iterating on work. QA/testing validates acceptance criteria and quality, while stakeholders provide approvals and strategic input. These personas are used consistently across the documentation to frame responsibilities, clarify ownership, and support cross-functional coordination throughout the project life cycle.

Communication is intentionally regular and structured to reduce ambiguity and escalation. The team follows a cadence of weekly updates, standups, milestone reviews, and stakeholder reporting, while also using project boards and centralized documentation as a shared source of truth. Risks and blockers are tracked in a risk register and escalated through explicit paths from the team to project leadership and, if needed, sponsors. This makes communication not just informational but operational—ensuring that decisions, dependencies, and risks are visible and acted on before they become critical issues.

Quality assurance is embedded in execution and release practices rather than treated as a final stage. Teams are expected to write tests, run CI checks, review pull requests with acceptance criteria, and use smoke tests for critical user flows before deployment. Release management includes pre-release checks, rollback plans, and post-deploy verification, while retrospectives capture learning and turn them into concrete improvement actions. In short, OctoAcme combines disciplined planning, role clarity, transparent communication, and quality gates to support reliable and repeatable delivery.

## Project Lifecycle Overview

Every OctoAcme project follows these phases:

1. [Initiation](octoacme-project-initiation.md) - Validate business need, align stakeholders, confirm success metrics
2. [Planning](octoacme-project-planning.md) - Create actionable backlog, estimate scope, identify dependencies
3. [Execution & Tracking](octoacme-execution-and-tracking.md) - Build, test, demo, track progress daily
4. [Release & Deployment](octoacme-release-and-deployment.md) - Standardized deployment process with rollback plans
5. [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) - Capture learnings and drive improvements

## Documentation Hub

### Core Framework
- [OctoAcme Project Management Overview](octoacme-project-management-overview.md) - Start here for a complete introduction to roles, artifacts, and communication cadence
- [OctoAcme Roles & Personas](octoacme-roles-and-personas.md) - Detailed definitions of Project Managers, Product Managers, Developers, and their responsibilities

### Phase-Specific Guides
- [Project Initiation Guide](octoacme-project-initiation.md) - How to validate and authorize new work
- [Project Planning](octoacme-project-planning.md) - Creating backlogs, estimating, and defining dependencies
- [Execution & Tracking](octoacme-execution-and-tracking.md) - Daily rhythms, PR workflows, quality standards, and escalation
- [Risk Management & Communication](octoacme-risks-and-communication.md) - Risk registers, communication templates, and escalation paths
- [Release & Deployment Guide](octoacme-release-and-deployment.md) - Release types, checklists, and rollback procedures
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) - Structured retrospectives and tracking improvements

## Key Artifacts at a Glance

- Project Charter / One-pager - Problem, goal, success metrics, stakeholders, timeline, risks
- Roadmap & Release Plan - High-level vision and delivery schedule
- Sprint/Iteration Backlog - Prioritized, estimated work items
- Acceptance Criteria & Definition of Done - Quality standards for completion
- Risk Register - Tracked risks with mitigation plans
- Retrospective Notes - Learnings and action items

## Core Roles

Three primary roles coordinate every project:

- Project Manager (PM) - Coordinates delivery, manages schedules, risks, and communications
- Product Manager (PdM) - Defines outcomes, prioritizes backlog, measures success
- Developers & QA - Implement, test, and validate features

See [OctoAcme Roles & Personas](octoacme-roles-and-personas.md) for full descriptions.

## Communication Cadence

- Daily - Team standups (15 min)
- Weekly - PM + PdM sync, delivery team check-ins
- Weekly - Risk register review
- Monthly - Stakeholder updates
- Ad-hoc - Escalations and incident communications

## How to Use These Docs

1. New to OctoAcme? Start with the [Project Management Overview](octoacme-project-management-overview.md)
2. Starting a new project? Begin with the [Initiation Guide](octoacme-project-initiation.md)
3. Need phase-specific guidance? Refer to the relevant phase guide above
4. Need a checklist or template? Each phase guide includes actionable checklists and templates
5. Want to understand a specific role? See [Roles & Personas](octoacme-roles-and-personas.md)

## Keeping These Docs Current

These process docs are living artifacts. As the team learns and evolves, we update them collaboratively. To propose changes:
- Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template
- Include rationale for the change and stakeholder feedback if applicable

---

*Last updated: October 4, 2026*
