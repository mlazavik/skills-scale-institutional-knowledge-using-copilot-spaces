# OctoAcme — Role Engagement Checklist

## Purpose
Describe when to involve each persona across the five project lifecycle phases so that no handoffs are missed and accountability is clear from the start.

## How to use
- Review this checklist at the start of each phase.
- Assign named individuals to each role before the phase begins.
- If a role is not staffed, the PM or PdM is responsible for covering that gap or explicitly deferring the activity.

For role definitions and interaction guidance, see [Roles and Personas](octoacme-roles-and-personas.md).

---

## Phase 1 — Initiation

Align on problem, goals, and team before investing in detailed planning.  
_Reference: [Project Initiation Guide](octoacme-project-initiation.md)_

| Role | Expected action |
|---|---|
| Project Manager (PM) | Kick off the project; create one-pager; confirm stakeholder list |
| Product Manager (PdM) | Define problem statement, goals, and success metrics |
| Business Analyst | Elicit initial requirements; facilitate stakeholder interviews |
| Customer Support/Success | Provide customer feedback and known pain points to inform scope |
| Security Lead | Flag any regulatory or compliance constraints that affect scope |
| UX Designer | Supply initial user research or personas if available |
| QA Lead | Review proposed success metrics for testability |
| Technical Writer | — (not typically engaged yet) |

**Phase gate:** One-pager signed off, go/no-go decision made.

---

## Phase 2 — Planning

Scope the work, assign resources, and de-risk before execution.  
_Reference: [Project Planning](octoacme-project-planning.md)_

| Role | Expected action |
|---|---|
| Project Manager (PM) | Create project plan, milestones, and resource map; maintain risk register |
| Product Manager (PdM) | Prioritise and groom backlog; confirm acceptance criteria |
| Business Analyst | Document detailed requirements; resolve scope ambiguities |
| UX Designer | Deliver wireframes and design specs for planned features |
| QA Lead | Define test strategy; review acceptance criteria for completeness |
| Security Lead | Run threat modelling for security-sensitive features |
| Technical Writer | Identify documentation needs; plan release notes outline |
| Customer Support/Success | Validate backlog priorities against known customer issues |
| Developers | Estimate effort; flag technical risks and dependencies |

**Phase gate:** Backlog ready, milestones agreed, risks documented.

---

## Phase 3 — Execution & Tracking

Build, test, and review iteratively toward milestones.  
_Reference: [Execution & Tracking](octoacme-execution-and-tracking.md)_

| Role | Expected action |
|---|---|
| Project Manager (PM) | Track progress on board; facilitate standups; escalate blockers |
| Product Manager (PdM) | Clarify requirements; accept or reject completed features |
| Developers | Implement, review code, and write automated tests |
| UX Designer | Support design handoff; review implemented UI for fidelity |
| QA Lead | Execute test plans; triage defects; update QA board column |
| Business Analyst | Answer requirement questions; document scope changes |
| Security Lead | Review PRs with security implications; ensure CI scans pass |
| Technical Writer | Draft feature documentation and update runbooks iteratively |
| Customer Support/Success | Monitor beta or early-access feedback if applicable |

**Phase gate:** All planned stories in Done; acceptance criteria met; risk register current.

---

## Phase 4 — Release & Deployment

Deploy to production safely and communicate the release.  
_Reference: [Release & Deployment Guide](octoacme-release-and-deployment.md)_

| Role | Expected action |
|---|---|
| Project Manager (PM) | Coordinate release window; confirm all checklists complete |
| Product Manager (PdM) | Final acceptance sign-off; approve release announcement |
| QA Lead | Run smoke tests on staging; provide release sign-off |
| Security Lead | Confirm security scans are green; approve release from security perspective |
| Technical Writer | Publish release notes and update user-facing documentation |
| UX Designer | Confirm usability and accessibility checks passed |
| Customer Support/Success | Prepare support team for incoming queries; review known issues list |
| Developers | Execute deployment; monitor for errors post-deploy |
| Business Analyst | Verify that release delivers against agreed success metrics |

**Phase gate:** All pre-release requirements met; deployment verified; stakeholders notified.

---

## Phase 5 — Retrospective & Continuous Improvement

Capture learnings and convert them into backlog improvements.  
_Reference: [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)_

| Role | Expected action |
|---|---|
| Project Manager (PM) | Facilitate retrospective; log and assign action items |
| Product Manager (PdM) | Share outcome metrics; discuss roadmap implications |
| Developers | Contribute technical learnings and process improvement ideas |
| QA Lead | Report on defect trends, test coverage gaps, and quality metrics |
| Security Lead | Share any security findings or near-misses from the cycle |
| Technical Writer | Update docs for any process changes identified in retrospective |
| Customer Support/Success | Bring post-release customer feedback and support ticket trends |
| Business Analyst | Assess whether requirements were well understood; note gaps for next cycle |
| UX Designer | Share usability feedback collected after release |

**Phase gate:** Action items logged with owners and due dates; fed back into next cycle's backlog.
