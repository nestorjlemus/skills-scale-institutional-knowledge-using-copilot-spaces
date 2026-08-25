# OctoAcme Project Management Docs — README

## Purpose

A single entrypoint for OctoAcme project management process documents. This README summarizes the project management processes used by OctoAcme and links to the full documents in this folder.

## Project Management Processes Summary

**OctoAcme** follows a structured, customer-first project lifecycle that emphasizes iterative delivery, clear ownership, and data-informed decision-making. The approach spans five key phases:

- **Initiation**: Validate the business need and create a lightweight one-pager that aligns stakeholders on problem statement, success metrics, and high-level timeline. Move into planning only when success metrics are clear and stakeholder approval is confirmed.

- **Planning**: Break approved work into a prioritized backlog with acceptance criteria, estimates, and release milestones. Define Definition of Done, identify dependencies and risks, and create a delivery roadmap.

- **Execution & Tracking**: Run daily standups, use a project board (Backlog → Ready → In Progress → In Review → QA → Done), enforce PR and CI conventions, track velocity and blockers, and measure against success metrics.

- **Release & Deployment**: Follow pre-release checks (passing CI, security scans, release notes, rollback plan), deploy to staging and production via automated pipelines when possible, run smoke tests, and announce to stakeholders.

- **Retrospective & Continuous Improvement**: Capture learnings after each sprint or milestone, identify 2–3 top action items with clear owners, track improvements in the backlog, and measure impact over time.

- **Risk Management & Communication**: Maintain a Risk Register (ID, description, impact, likelihood, owner, mitigation), use weekly status templates, follow escalation paths (team → PM → Product Lead → Sponsor), and keep stakeholders informed.

## Core Roles

- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications.
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success.
- **Developers**: Implement features, write tests, and participate in design and code reviews.
- **QA/Testing**: Validate quality and acceptance criteria.
- **Stakeholders**: Provide inputs and approvals.

## Documentation

| Document | Purpose |
|----------|---------|
| [octoacme-project-management-overview.md](octoacme-project-management-overview.md) | High-level introduction to OctoAcme processes, roles, key artifacts, and lifecycle. Start here for a primer. |
| [octoacme-project-initiation.md](octoacme-project-initiation.md) | Steps to validate and authorize work, align stakeholders, and decide go/no-go for planning. |
| [octoacme-project-planning.md](octoacme-project-planning.md) | Turn an approved initiative into an actionable plan, backlog, and release schedule. |
| [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md) | Day-to-day execution guidance: standups, board workflow, PR conventions, quality standards, and metrics. |
| [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md) | Identify, assess, and mitigate risks; stakeholder communication templates and escalation paths. |
| [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md) | Standardize releases, deployment checklists, rollback plans, and incident response. |
| [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md) | Run retrospectives, capture learnings, track action items, and measure improvement. |
| [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) | Detailed role definitions for PMs, Product Managers, Developers, and other personas. |

## How to Use These Docs

1. **New team members**: Start with [octoacme-project-management-overview.md](octoacme-project-management-overview.md) for a 5-minute overview.
2. **Starting a new project**: Follow the workflow: Initiation → Planning → Execution → Release → Retrospective.
3. **Looking for a specific topic**: Use the table above to find the relevant document.
4. **Adding or updating content**: See [`.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) for the process to request updates.

## Quick Links

- [OctoAcme Project Management Overview](octoacme-project-management-overview.md) — Start here
- [All Docs](.) — Browse all process documents in this folder
- [Issue Template for Process Doc Updates](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) — Request changes to docs

---

**Last updated**: 2026  
**Maintained by**: OctoAcme Team
