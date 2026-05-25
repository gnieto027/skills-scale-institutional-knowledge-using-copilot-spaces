# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub! This is your entry point for understanding how OctoAcme runs projects, the roles involved, and the key processes that enable consistent, iterative delivery.

## Project Management Process Overview

OctoAcme's project delivery framework is designed to be **iterative**, **transparent**, and **outcome-focused**. We blend customer-first thinking with clear roles, rigorous planning, and continuous improvement to deliver reliable features and services.

### Core Principles
- **Customer-first:** Prioritize customer value and usability in every decision.
- **Iterative delivery:** Deliver small, testable increments rather than big-bang releases.
- **Clear ownership:** Each project has a named Project Manager and Product Lead with defined responsibilities.
- **Data-informed decisions:** Measure impact and iterate based on evidence.
- **Psychological safety:** Encourage feedback, learning, and blameless problem-solving.

### The OctoAcme Lifecycle (5 Phases)

1. **Initiation:** Define the problem, measurable goals, stakeholders, and approval gate.
2. **Planning:** Break work into shippable increments, prioritize, estimate, and identify risks and dependencies.
3. **Execution & Tracking:** Build, test, and deliver using a project board, daily standups, and regular syncs.
4. **Release & Deployment:** Deploy with confidence using checklists, smoke tests, and incident playbooks.
5. **Retrospective & Continuous Improvement:** Capture learnings, assign action items, and drive iterative improvements.

### Core Roles

OctoAcme projects typically involve four key personas:

- **Product Manager:** Defines outcomes, prioritizes the backlog, and measures success.
- **Project Manager:** Coordinates delivery, manages schedules, risks, and stakeholder communications.
- **Developers:** Implement features, write tests, and collaborate on design and code reviews.
- **QA/Testing & Stakeholders:** Validate quality, acceptance criteria, and business impact.

See [Roles & Personas](octoacme-roles-and-personas.md) for detailed responsibilities and communication patterns for each role.

### Communication Cadence

- **Daily:** Team standups (15 min) focused on progress, blockers, and dependencies.
- **Weekly:** PM + Product Manager sync; delivery team standups; risk register review.
- **Monthly:** Stakeholder updates on progress and metrics.
- **Ad-hoc:** Escalations and incident communications as needed.

### Quality & Risk Management

OctoAcme maintains high standards through:

- **Continuous testing:** Unit tests, integration tests, end-to-end smoke tests, and security scanning in CI.
- **Code review discipline:** Small PRs (≤ 400 lines) with clear acceptance criteria, running CI before review, and requiring at least one approval.
- **Risk management:** Maintaining a Risk Register reviewed weekly and escalated through three levels (team → PM → sponsor).
- **Definition of Done:** Clear, agreed criteria that all work must meet before completion.

---

## Process Document Quick Links

Navigate to the specific guidance you need:

| Document | Purpose |
|----------|---------|
| [Project Management Overview](octoacme-project-management-overview.md) | Concise introduction to OctoAcme's approach, roles, and key artifacts. Start here if you're new to OctoAcme. |
| [Project Initiation Guide](octoacme-project-initiation.md) | How to validate business needs, align stakeholders, and authorize work. Use this when exploring a new project idea. |
| [Project Planning](octoacme-project-planning.md) | Breaking work into increments, creating backlogs, estimating scope, and identifying risks and dependencies. |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day execution, team rhythm, quality standards, and blocker escalation. |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | How to identify, track, and mitigate risks; stakeholder communication templates; escalation paths. |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Standardized release process, pre-release checklists, deployment procedures, rollback playbooks. |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Running retrospectives, capturing learnings, and driving continuous improvement. |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed descriptions of each role, responsibilities, goals, and communication patterns. |

---

## How to Use These Docs

### For Project Managers
- Start with [Project Management Overview](octoacme-project-management-overview.md)
- Reference [Project Initiation Guide](octoacme-project-initiation.md) when starting a new project
- Use [Project Planning](octoacme-project-planning.md) for scope and timeline guidance
- Consult [Risk Management & Communication](octoacme-risks-and-communication.md) for status updates and escalations

### For Product Managers
- Align on roles and responsibilities with [Roles & Personas](octoacme-roles-and-personas.md)
- Define success metrics and project charter using [Project Initiation Guide](octoacme-project-initiation.md)
- Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for quality and testing standards

### For Developers
- Understand the overall process in [Project Management Overview](octoacme-project-management-overview.md)
- Review acceptance criteria and Definition of Done in [Project Planning](octoacme-project-planning.md)
- Follow PR and quality standards in [Execution & Tracking](octoacme-execution-and-tracking.md)
- Participate in retrospectives using [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

### For New Team Members
1. Start with [Project Management Overview](octoacme-project-management-overview.md) for the big picture
2. Read [Roles & Personas](octoacme-roles-and-personas.md) to understand who does what
3. Browse the lifecycle docs to understand each phase:
   - [Initiation](octoacme-project-initiation.md) → [Planning](octoacme-project-planning.md) → [Execution](octoacme-execution-and-tracking.md) → [Release](octoacme-release-and-deployment.md) → [Retrospective](octoacme-retrospective-and-continuous-improvement.md)
4. Bookmark [Risk Management & Communication](octoacme-risks-and-communication.md) for day-to-day reference

---

## Keeping These Docs Current

This documentation is a living resource. To maintain accuracy and usefulness:

- **Update docs** when process changes are approved by the team
- **Add new docs** for emerging practices or specialized workflows
- **Link related artifacts** (templates, checklists, examples) from issue templates in `.github/ISSUE_TEMPLATE/`
- **Review annually** to reflect lessons learned and evolving team practices

### Contributing Updates
If you identify gaps, have suggestions, or want to refine these processes:
1. Create an issue using the [Process Documentation template](../.github/ISSUE_TEMPLATE/octoacme-process-doc-update.md)
2. Discuss with your PM and Product Lead
3. Submit a PR with updates and link it to the issue for visibility

---

## Questions or Need Help?

- **General questions:** Reach out in the #octoacme-pm Slack channel
- **Process clarifications:** Schedule a sync with your Project Manager or Product Lead
- **Feedback on docs:** Create an issue or comment on an existing one

Happy shipping! 🚀
