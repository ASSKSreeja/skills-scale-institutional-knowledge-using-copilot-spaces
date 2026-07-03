# OctoAcme Project Management Docs

This README collects the OctoAcme project management process documents and provides a short summary of the project management processes used across OctoAcme.

## Overview of OctoAcme Project Management Processes

OctoAcme follows a structured, iterative project management approach built on five core principles: customer-first focus, iterative delivery, clear ownership, data-informed decisions, and psychological safety. The framework encompasses the complete project lifecycle—from initiation through retrospective—with clearly defined roles for Project Managers, Product Managers, Developers, and QA/Testing specialists. Each project is assigned a named PM and Product Lead to ensure accountability and consistent execution across all cross-functional initiatives.

Projects progress through five distinct phases: **Initiation** (problem statement, stakeholder alignment, high-level timeline), **Planning** (scope definition, resource allocation, backlog prioritization), **Execution** (build, test, review, iterate), **Release** (deployment with verification and rollback planning), and **Close & Retrospective** (capture learnings and improvements). During execution, teams follow a structured pull request workflow with small PRs (≤400 lines), automated testing and linting in CI, and at least one approval before merging. Progress is tracked using GitHub Projects with columns for Backlog, Ready, In Progress, In Review, QA, and Done, supported by daily 15-minute standups, weekly delivery syncs, and end-of-sprint demos.

OctoAcme emphasizes transparent, tiered communication across stakeholders. The communication cadence includes weekly syncs between PM and Product Manager, twice-weekly team standups, and monthly stakeholder updates, with ad-hoc escalations as needed. Risk management is formalized through a Risk Register tracking ID, description, impact/likelihood, owner, and mitigation plans. Quality assurance is embedded throughout execution with unit and integration tests for new logic, end-to-end smoke tests before release, security scanning in CI, and manual QA for feature acceptance when needed.

The framework closes the loop through structured retrospectives held after each sprint, release, or milestone. Action items are tracked with clear owners and timelines, reviewed in weekly PM syncs, and measured for impact. Release governance includes pre-release requirements (met acceptance criteria, passing CI/security scans, drafted release notes, documented rollback plans) and a post-deployment verification process, with a rollback and incident playbook to minimize production risk.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md) — concise introduction to roles, principles, lifecycle, and key artifacts.
- [Project Initiation Guide](octoacme-project-initiation.md) — how to validate ideas, create a one-pager, and decide to move into planning.
- [Project Planning](octoacme-project-planning.md) — turning approved initiatives into backlogs, estimates, and release plans.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — daily rhythms, workflows, PR conventions, and tracking guidance.
- [Risks & Communication](octoacme-risks-and-communication.md) — maintaining the risk register and stakeholder communication templates.
- [Release & Deployment](octoacme-release-and-deployment.md) — release types, deployment checklist, rollback playbook, and release notes template.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — running retrospectives and tracking action items.
- [Roles & Personas](octoacme-roles-and-personas.md) — role summaries and responsibilities used across the docs.

## How to Use

- Link this README from the repository root README to surface process docs during onboarding.
- Keep document titles and links in this file updated when adding or renaming docs.
- Use the process documents as the single source of truth for project management guidance across OctoAcme.
