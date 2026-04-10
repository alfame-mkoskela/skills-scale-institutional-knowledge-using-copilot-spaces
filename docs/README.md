# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management Documentation hub. This repository serves as the central reference for all project management processes, workflows, and guidelines used across OctoAcme's delivery teams. Whether you are onboarding to a new project, planning a release, or looking to improve team practices, you'll find the guidance you need here.

## Overview

OctoAcme follows a structured, iterative project management approach grounded in customer-first delivery, clear ownership, and data-informed decision-making. The methodology is organized into five distinct lifecycle phases: Initiation, Planning, Execution, Release, and Close & Retrospective. At its core, the approach emphasizes psychological safety, small testable increments, and transparent communication across all stakeholders. Each project is led by clearly defined roles—a Project Manager who coordinates delivery and schedules, and a Product Manager who owns outcomes and success metrics—ensuring accountability and clarity throughout the project lifecycle.

## Key Workflows and Execution Practices

OctoAcme's execution model relies on a disciplined project board structure (using columns: Backlog, Ready, In Progress, In Review, QA, Done) and a lean pull request workflow that prioritizes code quality and collaboration. Teams follow a daily standup cadence (15 minutes) focused on progress and blockers, complemented by weekly delivery syncs and demo/review sessions at sprint milestones. The planning phase emphasizes breaking work into shippable increments with clear acceptance criteria and a documented Definition of Done. Risk management is embedded throughout, with a Risk Register maintained to track impact, likelihood, mitigation plans, and ownership. Quality assurance is comprehensive, including unit tests, integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance when necessary.

## Stakeholder Communication and Escalation

Communication in OctoAcme follows a structured cadence designed to keep stakeholders informed and aligned: weekly syncs between PM and Product Manager, twice-weekly standups for the delivery team, and monthly stakeholder updates. A single source of truth is maintained through project READMEs and release documentation. When issues arise, escalation follows a clear three-level path (team-level triage → PM escalation → sponsor-level escalation for business-impacting issues). Release and deployment processes are standardized with pre-release requirements including passing CI, security scans, and prepared rollback plans. After each sprint, release, or significant milestone, teams conduct blameless retrospectives to capture learnings and convert them into actionable improvements, ensuring continuous evolution of both the product and the processes themselves.

---

## Documentation Index

| Document | Description |
|---|---|
| [Project Management Overview](./octoacme-project-management-overview.md) | Core principles, lifecycle phases, and the overall PM framework |
| [Project Initiation Guide](./octoacme-project-initiation.md) | Steps and artifacts for starting a new project |
| [Project Planning](./octoacme-project-planning.md) | Planning processes, sprint structure, and Definition of Done |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Day-to-day execution workflows, board management, and standups |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | Risk registers, escalation paths, and stakeholder communication cadences |
| [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Release criteria, deployment steps, and rollback procedures |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Blameless retrospective format and improvement tracking |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Definitions and responsibilities for all project roles |
