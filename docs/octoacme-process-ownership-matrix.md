# OctoAcme Process Ownership Matrix (RACI)

## Purpose
Define clear accountability for key project activities and deliverables using the RACI framework:
- **R** = Responsible (does the work)
- **A** = Accountable (ultimately answerable, decision maker)
- **C** = Consulted (provides input)
- **I** = Informed (kept up to date)

## Project Initiation Phase

| Activity | PM | PdM | Dev | BA | UX/UI | DevOps | QA | Support |
|----------|----|----|-----|----|----|--------|----|----|
| **Create Project One-pager** | R/A | R/A | I | C | C | I | I | I |
| **Identify Stakeholders** | R/A | C | I | C | I | I | I | C |
| **Define Success Metrics** | R | A | I | R | C | I | I | C |
| **Initial Risk Assessment** | R/A | C | C | C | C | C | C | I |
| **Resource Planning** | R/A | C | C | I | I | C | I | I |

## Project Planning Phase

| Activity | PM | PdM | Dev | BA | UX/UI | DevOps | QA | Support |
|----------|----|----|-----|----|----|--------|----|----|
| **Create Product Backlog** | C | A | R | R | C | I | C | C |
| **Requirements Documentation** | C | C | C | R/A | C | I | C | I |
| **Design Wireframes/Mockups** | I | C | C | C | R/A | I | C | C |
| **Technical Architecture** | C | I | R/A | I | C | R | I | I |
| **Infrastructure Planning** | C | I | C | I | I | R/A | I | I |
| **Test Strategy** | C | C | C | I | I | C | R/A | I |
| **Sprint Planning** | R/A | R | R | C | C | C | C | I |
| **Definition of Done** | R | C | R/A | C | C | C | R | I |
| **Release Timeline** | R/A | R | C | I | C | R | C | I |

## Execution & Tracking Phase

| Activity | PM | PdM | Dev | BA | UX/UI | DevOps | QA | Support |
|----------|----|----|-----|----|----|--------|----|----|
| **Feature Implementation** | I | C | R/A | C | C | C | I | I |
| **Design Implementation** | I | C | R | C | R/A | I | I | I |
| **Code Reviews** | I | I | R/A | I | I | C | C | I |
| **Unit Testing** | I | I | R/A | I | I | I | C | I |
| **Integration Testing** | I | C | C | I | I | R | R/A | I |
| **CI/CD Pipeline Management** | I | I | C | I | I | R/A | C | I |
| **Daily Standups** | R/A | C | R | R | R | R | R | I |
| **Risk Register Updates** | R/A | C | C | C | C | C | C | C |
| **Progress Tracking** | R/A | C | I | I | I | I | I | I |
| **Requirements Changes** | C | A | C | R | C | I | C | C |
| **Data Analysis & Reporting** | I | C | I | R/A | I | I | I | C |

## Release & Deployment Phase

| Activity | PM | PdM | Dev | BA | UX/UI | DevOps | QA | Support |
|----------|----|----|-----|----|----|--------|----|----|
| **Pre-release Testing** | C | C | C | I | C | C | R/A | I |
| **Deployment Planning** | R | C | C | I | I | R/A | C | I |
| **Release Notes** | R/A | R | C | C | C | C | I | R |
| **Deployment Execution** | C | I | C | I | I | R/A | C | I |
| **Production Verification** | C | C | R | I | I | R | R/A | I |
| **Customer Communication** | R | C | I | I | I | I | I | R/A |
| **Knowledge Base Updates** | I | I | C | C | C | I | I | R/A |
| **Rollback (if needed)** | C | I | C | I | I | R/A | C | I |

## Close & Retrospective Phase

| Activity | PM | PdM | Dev | BA | UX/UI | DevOps | QA | Support |
|----------|----|----|-----|----|----|--------|----|----|
| **Retrospective Facilitation** | R/A | R | R | R | R | R | R | R |
| **Action Item Tracking** | R/A | C | C | C | C | C | C | C |
| **Post-launch Metrics Review** | C | R/A | C | R | C | C | C | C |
| **Process Documentation Updates** | R/A | C | C | C | C | C | C | C |
| **Lessons Learned Documentation** | R/A | R | R | R | R | R | R | R |

## Cross-functional Activities

| Activity | PM | PdM | Dev | BA | UX/UI | DevOps | QA | Support |
|----------|----|----|-----|----|----|--------|----|----|
| **Incident Response** | C | C | R | I | I | R/A | C | R |
| **Customer Escalations** | C | C | C | I | I | C | I | R/A |
| **Security Vulnerabilities** | C | I | R | I | I | R/A | R | I |
| **Performance Issues** | C | C | R | I | I | R/A | C | C |
| **User Research** | C | R | I | C | R/A | I | I | C |
| **Accessibility Compliance** | C | C | R | C | R/A | I | R | C |

## How to Use This Matrix

### For Team Members
- Review your role's responsibilities for each project phase
- Understand when you should be driving work (R), making decisions (A), providing input (C), or staying informed (I)
- Escalate if accountabilities are unclear or conflicting

### For Project Managers
- Use this matrix during project kickoff to clarify roles and expectations
- Reference when assigning tasks or resolving ownership questions
- Update as needed for project-specific circumstances

### For New Team Members
- Use this matrix during onboarding to understand your role in the project lifecycle
- Identify who to collaborate with for different activities
- Understand where you fit in decision-making processes

## Notes on Shared Accountability
- When multiple roles are marked **A** (Accountable), they share decision-making authority and must align
- **R/A** indicates the role is both responsible for execution and accountable for outcomes
- This matrix represents typical scenarios; specific projects may require adjustments
- Always document and communicate any deviations from this standard matrix

## Related Documents
- [Roles and Personas](octoacme-roles-and-personas.md) - Detailed role definitions
- [Project Management Overview](octoacme-project-management-overview.md) - Process principles and lifecycle
- [Risk Management & Communication](octoacme-risks-and-communication.md) - Escalation paths and stakeholder management

---

**Last Updated:** 2026-01-02  
**Maintained by:** OctoAcme Project Management Team
