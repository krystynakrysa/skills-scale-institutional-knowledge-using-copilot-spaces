# OctoAcme — Role Handoffs Checklist

## Purpose
Ensure that all key information, decisions, and artifacts are transferred cleanly between project phases, with clear accountability at each handoff point. This checklist reduces gaps caused by assumptions, missing context, or unclear ownership as the project moves through its lifecycle.

## When to Use
- At the transition point between each project phase
- During project kickoff to plan and communicate handoff expectations
- When onboarding new team members mid-project
- As a reference in retrospectives to identify handoff breakdowns

---

## Phase 1 → Phase 2: Initiation to Planning

**Triggered when:** The go/no-go decision gate is approved.

**Handoff Owner:** Project Manager (PM)

### Checklist

#### From Initiation (inputs to Planning)
- [ ] Project One-pager reviewed and approved by Product Manager and Stakeholder sponsor
- [ ] Success metrics defined and agreed upon (Product Manager confirmed)
- [ ] Stakeholder list documented with contact, communication preference, and engagement level
- [ ] Initial risk list created and reviewed by PM
- [ ] High-level timeline and key milestones documented
- [ ] Resource needs identified (team roles, rough effort estimate)
- [ ] Go/no-go decision formally recorded

#### Roles Involved in Handoff
| Hand-Off Item | From | To |
|--------------|------|----|
| Project One-pager | Business Analyst / PM | Product Manager, Developers |
| Stakeholder map | Business Analyst | PM |
| Initial risk list | PM | All roles (briefing) |
| Success metrics | Product Manager | All roles |
| Resource plan | PM | Scrum Master |

#### Planning Phase Kickoff Confirmation
- [ ] Planning kickoff meeting scheduled with PM, PdM, SM, BA, QA Lead, UX Designer
- [ ] RACI matrix reviewed and team roles confirmed (see [RACI Matrix](octoacme-raci-matrix.md))
- [ ] Initial backlog seeding session scheduled (Product Manager + Business Analyst)

---

## Phase 2 → Phase 3: Planning to Execution

**Triggered when:** Release plan is approved and Sprint 1 is ready to begin.

**Handoff Owner:** Scrum Master (SM)

### Checklist

#### From Planning (inputs to Execution)
- [ ] Backlog groomed with user stories and acceptance criteria (Business Analyst + Product Manager)
- [ ] Sprint 1 backlog committed and capacity confirmed (Scrum Master + Developers)
- [ ] UX designs / wireframes handed off to Developers for Sprint 1 stories
- [ ] Test strategy documented and shared with Developers (QA Lead)
- [ ] Definition of Done agreed and documented (QA Lead + Scrum Master + Developers)
- [ ] CI/CD pipeline configured and verified (Developers + QA Lead)
- [ ] Risk register updated with planning-phase risks (PM)
- [ ] Dependencies mapped and owners assigned (PM)

#### Roles Involved in Handoff
| Hand-Off Item | From | To |
|--------------|------|----|
| Groomed backlog with acceptance criteria | Business Analyst / PdM | Developers, QA Lead |
| UX designs for Sprint 1 | UX Designer | Developers |
| Test strategy | QA Lead | Developers, SM |
| Definition of Done | QA Lead / SM | All delivery team members |
| Risk register | PM | SM, QA Lead |

#### Execution Kickoff Confirmation
- [ ] Sprint 1 planning completed (Scrum Master facilitated)
- [ ] Project board set up with Sprint 1 work (PM / Scrum Master)
- [ ] All team members have access to required tools and repos

---

## Phase 3 → Phase 4: Execution to Release

**Triggered when:** All sprint goals for the release milestone are met and QA sign-off is ready.

**Handoff Owner:** Project Manager (PM) + QA Lead

### Checklist

#### From Execution (inputs to Release)
- [ ] All acceptance criteria for release scope validated by QA Lead
- [ ] Pre-release QA sign-off completed (QA Lead)
- [ ] No open P0/P1 defects (QA Lead confirmed)
- [ ] UAT completed and signed off by Stakeholders and Business Analyst
- [ ] UX review of release scope completed (UX Designer)
- [ ] Release notes drafted (Business Analyst / Product Manager)
- [ ] Deployment runbook prepared and reviewed (Developers + PM)
- [ ] Rollback plan documented (Developers + PM)
- [ ] Stakeholder release communication prepared (PM + Product Manager)
- [ ] Risk register reviewed for any open release-blocking risks (PM)

#### Roles Involved in Handoff
| Hand-Off Item | From | To |
|--------------|------|----|
| QA sign-off | QA Lead | PM, Stakeholders |
| UAT sign-off | Business Analyst / Stakeholders | PM |
| Release notes | Business Analyst / PdM | PM, Stakeholders |
| Deployment runbook | Developers | PM, QA Lead |
| Stakeholder communication draft | PM / PdM | Stakeholders |

#### Release Readiness Gate
- [ ] Release readiness meeting held (PM, PdM, QA Lead, Developers)
- [ ] Deployment window confirmed with operations/infrastructure teams
- [ ] Monitoring and alerting verified for release scope

---

## Phase 4 → Phase 5: Release to Retrospective

**Triggered when:** Release deployment is complete and post-release monitoring period has passed.

**Handoff Owner:** Scrum Master (SM)

### Checklist

#### From Release (inputs to Retrospective)
- [ ] Post-release monitoring results documented (Developers + QA Lead)
- [ ] Any post-release incidents or hotfixes documented
- [ ] Success metrics measured against baselines (Product Manager)
- [ ] Stakeholder feedback collected (PM + Business Analyst)
- [ ] Release notes published and communicated
- [ ] Open items or carry-over work triaged to next backlog (Product Manager)

#### Roles Involved in Handoff
| Hand-Off Item | From | To |
|--------------|------|----|
| Post-release monitoring summary | Developers / QA Lead | SM, PM |
| Success metrics results | Product Manager | SM, Stakeholders |
| Stakeholder feedback summary | PM / BA | SM, PdM |
| Carry-over backlog items | Product Manager | Business Analyst, Developers |

#### Retrospective Kickoff Confirmation
- [ ] Retrospective session scheduled (all team members: Dev, SM, PM, PdM, UX, BA, QA)
- [ ] Pre-retro survey or async input collected (optional, SM facilitated)
- [ ] Action items from previous retrospective reviewed for closure

---

## Phase 5: Retrospective Output Handoff

**Triggered when:** Retrospective is complete.

**Handoff Owner:** Scrum Master (SM) + Project Manager (PM)

### Checklist

#### Retrospective Outputs to Carry Forward
- [ ] Action items documented with named owners and due dates
- [ ] Action items added to project board or backlog
- [ ] Process changes identified and assigned to Process owner (PM / SM)
- [ ] Learnings documented in retrospective notes (shared with team)
- [ ] Org-level learnings identified and shared with leadership (PM)
- [ ] Updated process docs committed if process changes were agreed (PM / SM)

---

## Tips for Effective Handoffs
- **Communicate early:** Notify receiving roles of upcoming handoffs at least one sprint ahead.
- **Use artifacts:** Every handoff should include written documentation — not just a verbal briefing.
- **Confirm receipt:** Receiving role should explicitly acknowledge and confirm understanding of handoff items.
- **Track gaps:** If a handoff item is missing, document it as a risk in the risk register rather than proceeding silently.
