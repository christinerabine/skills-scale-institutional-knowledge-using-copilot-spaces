# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths

### Technical Issues
- **Level 1**: Developer → Team Lead → DevOps Engineer (for infrastructure/deployment issues)
- **Level 2**: Team Lead → Engineering Manager → PM
- **Level 3**: PM → Product Lead → Engineering Director
- **Level 4**: Director → VP/Sponsor

### Customer Issues
- **Level 1**: Support/Customer Success Lead → Product Manager
- **Level 2**: Product Manager → PM + Engineering Lead
- **Level 3**: PM → Product Lead → VP
- **Critical**: Direct escalation to on-call and incident commander for production-impacting issues

### Project/Timeline Risks
- **Level 1**: Team-level triage in daily standup
- **Level 2**: PM escalates to Product Lead and dependent teams
- **Level 3**: Product Lead → Sponsor for business-impacting issues
- **Level 4**: Sponsor-level escalation for strategic decisions

### Cross-functional Dependencies
- **Level 1**: Identified by Business Analyst or PM during planning
- **Level 2**: PM coordinates with dependent team PMs
- **Level 3**: Product Leads resolve conflicts and reprioritize
- **Level 4**: Executive steering committee for organizational blockers

### Security Incidents
- Follow the security incident runbook and notify Security on-call immediately
- Escalation path: Security on-call → Security team lead → CISO
- Parallel notification to DevOps Engineer, PM, and Product Lead

### Design/UX Issues
- **Level 1**: UX/UI Designer → Design Lead
- **Level 2**: Design Lead → Product Manager for scope/priority decisions
- **Level 3**: Product Manager → PM for timeline impact
- **Critical**: Direct escalation for accessibility compliance issues

## Accountability for Escalations
- **Escalation Owner**: Person raising the escalation is responsible for tracking resolution
- **Response SLA**: Level 1 (same day), Level 2 (within 24 hours), Level 3 (within 48 hours)
- **Resolution Tracking**: All escalations logged in Risk Register with status and next actions
- **Communication**: Escalation owner must update all stakeholders on resolution
