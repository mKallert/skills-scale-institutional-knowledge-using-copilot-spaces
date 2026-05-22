# OctoAcme RACI Matrix

This document maps each project lifecycle stage and key activity to the roles that are **R**esponsible, **A**ccountable, **C**onsulted, or **I**nformed.

**Key**
| Code | Meaning |
|------|---------|
| **R** | Responsible — does the work |
| **A** | Accountable — owns the outcome; single point of authority |
| **C** | Consulted — provides input before decisions are made |
| **I** | Informed — kept up to date on progress and decisions |

> Role abbreviations: **PM** = Project Manager · **PdM** = Product Manager · **Dev** = Developer · **QA** = QA/Testing · **UX** = UX Designer · **DA** = Data Analyst · **CS** = Customer Success · **Arch** = System Architect · **RM** = Release Manager · **Stake** = Stakeholders

---

## Stage 1 — Initiation

| Activity | PM | PdM | Dev | QA | UX | DA | CS | Arch | RM | Stake |
|---|---|---|---|---|---|---|---|---|---|---|
| Define problem statement & business case | C | **A/R** | C | I | C | C | C | C | I | C |
| Identify stakeholders and sponsors | **A/R** | R | I | I | I | I | I | I | I | C |
| Draft project one-pager / charter | **A/R** | R | C | I | I | I | I | C | I | C |
| Approve project initiation | I | C | I | I | I | I | I | I | I | **A/R** |
| Assign initial roles and responsibilities | **A/R** | C | I | I | I | I | I | C | I | I |

---

## Stage 2 — Planning

| Activity | PM | PdM | Dev | QA | UX | DA | CS | Arch | RM | Stake |
|---|---|---|---|---|---|---|---|---|---|---|
| Prioritize backlog and define scope | C | **A/R** | C | C | C | C | C | C | I | C |
| Create project plan, milestones, timeline | **A/R** | C | C | I | I | I | I | C | C | I |
| Define success metrics and KPIs | C | **A/R** | I | I | I | R | C | I | I | C |
| Architecture review and technical design | I | C | R | I | I | I | I | **A/R** | I | I |
| Write acceptance criteria and Definition of Done | C | **A/R** | R | R | R | I | I | C | I | C |
| UX research and wireframes | I | C | I | I | **A/R** | I | C | I | I | C |
| Risk register creation | **A/R** | C | C | I | I | I | I | C | C | I |
| Release planning | **A/R** | C | C | I | I | I | I | C | R | I |

---

## Stage 3 — Execution and Tracking

| Activity | PM | PdM | Dev | QA | UX | DA | CS | Arch | RM | Stake |
|---|---|---|---|---|---|---|---|---|---|---|
| Implement features | I | C | **A/R** | I | C | I | I | C | I | I |
| Code review and PR merges | I | I | **A/R** | I | I | I | I | C | I | I |
| Test execution and defect tracking | I | I | R | **A/R** | I | I | I | I | I | I |
| Design review and UX validation | I | C | C | I | **A/R** | I | C | I | I | I |
| Metrics instrumentation | I | C | R | I | I | **A/R** | I | I | I | I |
| Sprint status reporting | **A/R** | C | I | I | I | I | I | I | I | I |
| Blocker escalation | **A/R** | C | R | C | I | I | I | C | I | C |
| Risk updates | **A/R** | C | C | I | I | I | I | C | C | I |

---

## Stage 4 — Release and Deployment

| Activity | PM | PdM | Dev | QA | UX | DA | CS | Arch | RM | Stake |
|---|---|---|---|---|---|---|---|---|---|---|
| Release readiness review (go/no-go) | C | C | C | R | I | I | I | C | **A/R** | I |
| QA sign-off | I | I | I | **A/R** | I | I | I | I | R | I |
| Deployment execution | I | I | R | I | I | I | I | C | **A/R** | I |
| Post-deploy smoke testing | I | I | R | **A/R** | I | I | I | I | R | I |
| Release notes and stakeholder comms | C | C | I | I | I | I | R | I | **A/R** | I |
| Customer-facing communication | I | C | I | I | I | I | **A/R** | I | R | C |
| Rollback decision and execution | C | C | R | R | I | I | I | C | **A/R** | I |
| Post-deploy metrics review | I | C | I | I | I | **A/R** | C | I | I | I |

---

## Stage 5 — Retrospective and Continuous Improvement

| Activity | PM | PdM | Dev | QA | UX | DA | CS | Arch | RM | Stake |
|---|---|---|---|---|---|---|---|---|---|---|
| Facilitate retrospective | **A/R** | C | C | C | C | C | C | C | C | I |
| Capture and assign action items | **A/R** | C | C | C | C | C | C | C | C | I |
| Review delivery metrics and velocity | C | C | I | I | I | **A/R** | I | I | I | C |
| Review release process health | C | I | C | C | I | I | I | C | **A/R** | I |
| Communicate improvements to stakeholders | **A/R** | C | I | I | I | I | C | I | I | I |

---

## Notes
- A single cell may show **A/R** when the same person is both accountable and doing the work (common in small teams).
- Where a role is not listed (blank), they have no direct involvement in that activity.
- Adjust this matrix to reflect your actual team composition on each project.
- See [Roles and Personas](./octoacme-roles-and-personas.md) for full descriptions of each role.
