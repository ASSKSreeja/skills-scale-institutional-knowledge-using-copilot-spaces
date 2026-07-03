# OctoAcme Project Management Docs

Welcome to the OctoAcme project management process documentation. This README provides a central hub for discovering, understanding, and following our project management processes across all initiatives.

## OctoAcme Project Management Overview

OctoAcme follows a structured, iterative project management approach built on five core principles: **customer-first focus**, **iterative delivery**, **clear ownership**, **data-informed decisions**, and **psychological safety**. The framework encompasses the complete project lifecycle—from initiation through retrospective—with clearly defined roles for Project Managers, Product Managers, Developers, and QA/Testing specialists. Each project is assigned a named PM and Product Lead to ensure accountability and consistent execution across all cross-functional initiatives.

### Project Lifecycle

Projects progress through five distinct phases:

- **Initiation** — Problem statement, stakeholder alignment, and high-level timeline
- **Planning** — Scope definition, resource allocation, and backlog prioritization  
- **Execution** — Build, test, review, and iterate with daily standups and weekly syncs
- **Release** — Deployment with verification and rollback planning
- **Retrospective** — Capture learnings and drive continuous improvements

### Key Workflows & Practices

**Pull Request Workflow**
- Small PRs (≤400 lines when possible)
- Automated CI with tests and linting before requesting review
- At least one approval required before merging
- Include issue links and acceptance criteria in PR descriptions

**Progress Tracking**
- GitHub Projects board with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Daily 15-minute standups focused on progress, blockers, dependencies
- Weekly delivery syncs to show progress and flagged risks
- End-of-sprint demos and reviews

**Quality Assurance**
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

**Risk Management & Communication**
- Formal Risk Register tracking (ID, description, impact, likelihood, owner, mitigation)
- Three-level blocker escalation: team-level triage → PM escalation → sponsor escalation
- Weekly stakeholder communication with status, risks, blockers, and decisions needed
- Escalation paths for security incidents through on-call security

---

## Process Documents

Below are the OctoAcme project management process documents. Start with the **Project Management Overview** for a concise introduction, then dive into phase-specific guides as needed.

### Core Documents

- **[Project Management Overview](octoacme-project-management-overview.md)** — Concise introduction to roles, principles, lifecycle, and key artifacts
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Role summaries and responsibilities for Developers, Product Managers, and Project Managers

### Phase-Specific Guides

- **[Project Initiation Guide](octoacme-project-initiation.md)** — How to validate ideas, create a one-pager, and decide to move into planning
- **[Project Planning](octoacme-project-planning.md)** — Turning approved initiatives into prioritized backlogs, estimates, and release plans
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Daily rhythms, team workflows, PR conventions, and progress tracking
- **[Release & Deployment](octoacme-release-and-deployment.md)** — Release types, deployment checklist, rollback playbook, and release notes template
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Running retrospectives and tracking action items

### Cross-Cutting Guides

- **[Risks & Communication](octoacme-risks-and-communication.md)** — Risk register management, stakeholder communication templates, and escalation paths

---

## How to Use These Docs

**For Onboarding**
- New team members should start with the **Project Management Overview** and **Roles & Personas** to understand how OctoAcme operates

**For Project Kickoff**
- Reference the **Project Initiation Guide** and **Project Planning** documents

**During Execution**
- Use **Execution & Tracking** and **Risks & Communication** as your daily guides

**For Release**
- Follow the **Release & Deployment** checklist

**For Continuous Improvement**
- Use **Retrospective & Continuous Improvement** to capture learnings and drive action items

**For Documentation Maintenance**
- Link this README from the repository root README to surface process docs during onboarding
- Keep document titles and links updated when adding or renaming process docs
- Process improvement suggestions? Open an issue with the template: [Add Content to Project Management Process Docs](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)

---

## Contributing to Process Docs

OctoAcme process documentation is a living, evolving resource. If you identify gaps, have suggestions, or want to share a best practice:

1. Open an issue using the [**Add Content to Project Management Process Docs**](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
2. Propose your update with rationale and suggested content
3. Get feedback from the team and stakeholders
4. Submit a PR with your changes

Together, we keep these docs accurate, relevant, and useful for the entire team.