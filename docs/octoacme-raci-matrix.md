# OctoAcme — RACI Matrix: Who Does What

## Purpose
Define clear ownership for key activities across the project lifecycle to eliminate ambiguity, prevent duplication of effort, and ensure every task has an accountable owner.

## When to Use
- At project kickoff to align the team on responsibilities
- During onboarding of new team members
- When clarifying ownership disputes or gaps
- As input to the [Role Handoffs Checklist](octoacme-role-handoffs-checklist.md)

## RACI Key
| Code | Meaning |
|------|---------|
| **R** | **Responsible** — Does the work |
| **A** | **Accountable** — Owns the outcome; approves deliverables |
| **C** | **Consulted** — Provides input before/during the activity |
| **I** | **Informed** — Kept up to date on progress/decisions |

> Each activity should have exactly one **A** (Accountable). Multiple **R** entries are permitted where work is shared.

---

## Lifecycle RACI Matrix

### Role Abbreviations
| Abbreviation | Role |
|-------------|------|
| PM | Project Manager |
| PdM | Product Manager |
| Dev | Developers |
| SM | Scrum Master |
| UX | UX Designer |
| BA | Business Analyst |
| QA | QA Lead |
| SH | Stakeholders |

---

### Initiation Phase

| Activity | PM | PdM | Dev | SM | UX | BA | QA | SH |
|----------|----|----|-----|----|----|----|----|-----|
| Define problem statement & business case | C | A | I | I | C | R | I | C |
| Identify and map stakeholders | A | C | I | I | I | R | I | I |
| Draft Project One-pager | A | R | I | I | I | C | I | C |
| Define success metrics | C | A | I | I | C | R | C | C |
| Conduct initial user research | I | C | I | I | A/R | C | I | C |
| Document initial risk list | A | C | I | I | I | C | C | I |
| Go/no-go decision gate | A | R | I | I | I | C | I | A |

---

### Planning Phase

| Activity | PM | PdM | Dev | SM | UX | BA | QA | SH |
|----------|----|----|-----|----|----|----|----|-----|
| Decompose requirements into user stories | C | A | C | C | C | R | C | I |
| Define acceptance criteria | C | A | C | C | C | R | C | I |
| Create wireframes and UX prototypes | I | C | C | I | A/R | C | I | C |
| Estimate effort and capacity | C | I | R | A | C | C | C | I |
| Define test strategy | C | I | C | C | C | C | A/R | I |
| Build release plan and milestone timeline | A | C | C | C | I | I | C | I |
| Identify dependencies and integration points | A | C | R | C | I | C | C | I |
| Confirm resource availability | A | C | C | C | C | C | C | I |
| Stakeholder planning alignment | A | R | I | I | I | C | I | C |

---

### Execution Phase

| Activity | PM | PdM | Dev | SM | UX | BA | QA | SH |
|----------|----|----|-----|----|----|----|----|-----|
| Sprint planning facilitation | C | C | R | A | C | C | C | I |
| Daily standup facilitation | I | I | R | A | I | I | I | I |
| Feature implementation | I | I | A/R | C | C | C | C | I |
| Design implementation review | I | I | R | I | A | I | I | I |
| Code review and PR approval | I | I | A/R | I | I | I | C | I |
| Unit and integration testing | I | I | R | C | I | I | A | I |
| Requirements clarification during sprint | I | C | C | I | C | A | C | I |
| Update risk register | A | C | C | C | I | I | C | I |
| Weekly delivery sync facilitation | A | C | C | C | I | I | C | I |
| Blocker escalation | A | C | C | R | I | I | C | I |

---

### Release Phase

| Activity | PM | PdM | Dev | SM | UX | BA | QA | SH |
|----------|----|----|-----|----|----|----|----|-----|
| Pre-release QA sign-off | C | C | C | C | C | C | A/R | I |
| Release readiness review | A | C | C | C | I | I | R | C |
| User Acceptance Testing (UAT) | C | C | C | I | C | A | R | R |
| Deployment execution | A | I | R | I | I | I | C | I |
| Release notes authoring | C | A | C | I | I | R | C | I |
| Stakeholder release communication | A | R | I | I | I | I | C | I |
| Post-release monitoring | C | C | R | I | I | I | A | I |
| Rollback decision (if needed) | A | R | R | C | I | I | C | C |

---

### Retrospective & Continuous Improvement Phase

| Activity | PM | PdM | Dev | SM | UX | BA | QA | SH |
|----------|----|----|-----|----|----|----|----|-----|
| Retrospective facilitation | C | I | R | A | R | R | R | I |
| Capture action items | C | I | R | A | R | R | R | I |
| Assign and track action item owners | A | I | C | R | C | C | C | I |
| Process improvement documentation | C | I | C | A | C | C | C | I |
| Lessons learned shared with org | A | C | C | C | C | C | C | I |

---

## Notes
- This matrix reflects typical project structures. Adjust role assignments based on team size and project complexity.
- When a role is not filled on a project (e.g., no dedicated Scrum Master), the closest equivalent role inherits those responsibilities — typically the Project Manager.
- Review and update this matrix at the start of each new project or when significant team changes occur.
