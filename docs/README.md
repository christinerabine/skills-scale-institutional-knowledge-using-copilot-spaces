# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management process documentation! This guide serves as the central entry point for understanding how we run projects, from inception to delivery and continuous improvement.

## Project Management Process Summary

At OctoAcme, we follow a **structured, iterative approach** built on customer-first principles and data-informed decision-making. Our methodology emphasizes delivering small, testable increments while maintaining clear ownership and fostering psychological safety. Every project is guided by measurable outcomes, with teams empowered to make evidence-based decisions and learn from each iteration.

Our project lifecycle consists of **five key phases**: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During Initiation, we validate the business need and align stakeholders around a clear problem statement. Planning translates approved initiatives into actionable backlogs with defined acceptance criteria and risk mitigation strategies. Execution involves daily delivery work with continuous quality checks and progress tracking. The Release phase ensures safe, verified deployments to production with rollback plans in place. Finally, Close & Retrospective sessions capture learnings and convert them into actionable improvements for future work.

**Core roles** in our process include **Project Managers (PMs)** who coordinate delivery, schedules, risks, and communications; **Product Managers (PdMs)** who define outcomes, prioritize the backlog, and measure success; **Developers** who implement features and collaborate on design and testability; **QA/Testing** teams who validate quality and acceptance criteria; and **Stakeholders** who provide essential inputs and approvals throughout the lifecycle.

Our **communication rhythms** include daily standups focused on progress and blockers, weekly delivery syncs between PMs and engineering teams, sprint demos at milestone completion, and regular stakeholder updates. **Quality assurance practices** are embedded throughout: we require unit tests for new logic, integration tests for component interactions, CI pipelines that run automated tests and security scans, pre-release requirements including smoke tests and rollback plans, and retrospectives after each sprint or milestone to drive continuous improvement.

---

## Documentation Structure

### Overview & Roles

- **[octoacme-project-management-overview.md](octoacme-project-management-overview.md)**  
  High-level introduction to OctoAcme's project management principles, core roles, key artifacts, lifecycle overview, and communication cadence.

- **[octoacme-roles-and-personas.md](octoacme-roles-and-personas.md)**  
  Detailed definitions of Developers, Product Managers, and Project Managers, including their responsibilities, goals, and typical communication patterns.

### Project Lifecycle Phases

- **[octoacme-project-initiation.md](octoacme-project-initiation.md)**  
  Guidance for validating project ideas, creating the Project One-pager, aligning stakeholders, and making go/no-go decisions before planning.

- **[octoacme-project-planning.md](octoacme-project-planning.md)**  
  Steps for turning approved initiatives into actionable plans, including backlog creation, estimation, Definition of Done, and release planning.

- **[octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md)**  
  Day-to-day execution guidance covering team rhythms, PR workflows, quality & testing practices, metrics, and blocker escalation.

- **[octoacme-release-and-deployment.md](octoacme-release-and-deployment.md)**  
  Standards for releasing features to production, including pre-release requirements, deployment checklists, rollback procedures, and release notes.

- **[octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md)**  
  Framework for capturing learnings after sprints, releases, or milestones and converting them into actionable improvements.

### Cross-cutting Concerns

- **[octoacme-risks-and-communication.md](octoacme-risks-and-communication.md)**  
  Risk register management, risk lifecycle, stakeholder communication templates, and escalation paths.

---

## Quick Start Guide

### I'm a new team member
1. Start with the **[Overview](octoacme-project-management-overview.md)** to understand principles and roles
2. Review **[Roles and Personas](octoacme-roles-and-personas.md)** to understand your responsibilities
3. Check current project boards and read any active Project One-pagers
4. Attend daily standups and introduce yourself to the team

### I'm starting a new project
1. Create a **Project One-pager** using the **[Initiation Guide](octoacme-project-initiation.md)**
2. Identify stakeholders and get approval to proceed to planning
3. Follow the **[Planning Guide](octoacme-project-planning.md)** to create your backlog and timeline
4. Review the **[Risk Management](octoacme-risks-and-communication.md)** doc to set up your risk register

### I'm in execution mode
1. Use the **[Execution & Tracking](octoacme-execution-and-tracking.md)** guide for daily workflows
2. Keep the project board updated (Backlog → Ready → In Progress → In Review → QA → Done)
3. Update the **[Risk Register](octoacme-risks-and-communication.md)** weekly
4. Follow PR best practices: small PRs, clear descriptions, automated tests

### I'm preparing to ship
1. Review **[Release & Deployment](octoacme-release-and-deployment.md)** pre-release requirements
2. Ensure all acceptance criteria are met and CI is passing
3. Draft release notes and document rollback plans
4. Run smoke tests in staging before production deployment
5. Plan your announcement to stakeholders and support teams

### I just finished a milestone
1. Schedule a **[Retrospective](octoacme-retrospective-and-continuous-improvement.md)** session
2. Use the retrospective framework: What went well, What could improve, Action items
3. Add action items to your backlog with clear owners and due dates
4. Update process docs if you discovered gaps or improvements

---

## Key Artifacts Reference

| Artifact | Purpose | Created During | Owner |
|----------|---------|----------------|-------|
| **Project One-pager** | Problem statement, goals, success metrics, stakeholders | Initiation | PM + PdM |
| **Project Charter** | Formal authorization and high-level plan | Initiation | PM |
| **Roadmap & Release Plan** | Timeline, milestones, delivery schedule | Planning | PdM + PM |
| **Sprint/Iteration Backlog** | Prioritized work items with acceptance criteria | Planning & Execution | PdM + Team |
| **Definition of Done** | Quality standards and completion criteria | Planning | Team |
| **Risk Register** | Active risks, impact, likelihood, mitigations | Planning & Execution | PM |
| **Release Notes** | Summary of changes, migration steps, known issues | Release | PM + Team |
| **Retrospective Notes** | Learnings and action items | Close & Retrospective | PM + Team |

---

## Communication Cadence

| Meeting/Update | Frequency | Participants | Purpose |
|----------------|-----------|--------------|---------|
| **Daily Standup** | Daily (15 min) | Delivery team | Progress, blockers, dependencies |
| **Weekly Delivery Sync** | Weekly | PM + PdM + Engineering leads | Progress updates, risk review, decisions |
| **Sprint Demo** | End of sprint/milestone | Team + Stakeholders | Show completed work, gather feedback |
| **Stakeholder Updates** | Weekly or milestone-based | PM → Stakeholders | Status, risks, asks |
| **Retrospective** | After sprint/release/milestone | Delivery team | Learnings, improvements, action items |

---

## Contributing to Process Documentation

Found a gap in our process docs? Have a suggestion for improvement? We welcome contributions!

**To propose changes or additions:**
1. Use our [issue template](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)
2. Select the document you want to update (or choose "new document")
3. Describe your proposed content and rationale
4. Submit the issue for review by the OctoAcme Project Management Team

Changes should:
- Align with existing process documents
- Improve clarity or close documented gaps
- Be reviewed with stakeholders when needed

---

## Metadata

**Last Updated:** 2026-01-02  
**Maintained by:** OctoAcme Project Management Team

---

## Additional Resources

- Project boards and active projects: Check your GitHub organization
- `.copilot/` directory: Add project-specific docs here for Copilot Spaces context
- Security incident runbook: Follow security incident procedures for security-related issues

For questions or support, reach out to the OctoAcme Project Management Team or your assigned PM.
