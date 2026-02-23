# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

> **Abbreviation note:** Throughout OctoAcme docs, **PM** refers to the **Project Manager** and **PdM** refers to the **Product Manager**. Where a doc uses "PM" without qualification, assume Project Manager unless context indicates otherwise.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## UX Designer

### Role Summary
UX Designers create user-centred workflows, wireframes, and prototypes that ensure product features are usable, accessible, and aligned with customer needs.

### Responsibilities
- Define user flows, wireframes, and interaction prototypes
- Conduct usability reviews and accessibility checks
- Collaborate with Product Manager on user research and personas
- Partner with Developers on implementation of UI patterns
- Participate in QA sign-off for usability and accessibility acceptance criteria

### Goals
- Deliver intuitive, accessible user experiences
- Surface user needs early to avoid costly late-stage redesigns
- Maintain a shared design system and component library

### Typical Communication
- Design reviews and handoff sessions with Developers
- Usability findings shared with PdM and PM
- Sprint demos covering UX milestones and feedback

---

## QA Lead

### Role Summary
The QA Lead (also referred to as QA/Testing Lead) owns the quality strategy, test coverage planning, and release readiness gate for the team.

### Responsibilities
- Define and maintain the test strategy (unit, integration, end-to-end, performance)
- Triage defects and coordinate with Developers on fixes
- Help define acceptance criteria and Definition of Done
- Own the QA column on the project board and release sign-off
- Drive automation to reduce manual regression effort

### Goals
- Prevent regressions and maintain a high quality bar at every release
- Shorten feedback loops between development and quality validation
- Build shared ownership of quality across the team

### Typical Communication
- QA status updates in weekly delivery syncs
- Bug triage sessions with Developers and PM
- Acceptance criteria reviews with PdM and Business Analyst

---

## Technical Writer

### Role Summary
Technical Writers create and maintain documentation — feature docs, API references, release notes, onboarding guides — ensuring knowledge is accurate and accessible.

### Responsibilities
- Write and review user-facing and internal documentation
- Collaborate with Developers and PdM to keep docs aligned with product changes
- Draft and publish release notes for each release
- Support onboarding by maintaining team wikis and runbooks

### Goals
- Ensure documentation is accurate, findable, and up to date
- Reduce support load by making self-service content clear and comprehensive
- Accelerate team onboarding

### Typical Communication
- Documentation review sessions with Developers and PdM
- Release notes draft shared with PM before release announcement
- Async feedback via PRs or doc comments

---

## Customer Support/Success

### Role Summary
Customer Support/Success advocates for end-users, bringing feedback from the field into backlog planning and ensuring post-release issues are addressed quickly.

### Responsibilities
- Collect and synthesise customer feedback and bug reports
- Represent user needs during backlog grooming and sprint planning
- Assist in triaging production incidents from a customer impact perspective
- Participate in post-release and retrospective reviews

### Goals
- Ensure customer pain points are visible and prioritised
- Reduce time-to-resolution for reported issues
- Drive down support volume through proactive documentation and product improvements

### Typical Communication
- Backlog feedback provided to PdM and PM before planning sessions
- Incident impact assessments shared during triage
- Retrospective inputs on recurring customer issues

---

## Security Lead

### Role Summary
The Security Lead advises on security architecture, compliance, and risk. They ensure secure design practices are followed and lead incident response for security events.

### Responsibilities
- Review designs and PRs for security risks
- Run threat modelling during planning for high-risk features
- Ensure security scans are configured in CI and findings are addressed
- Own the security incident runbook and coordinate incident response
- Advise on compliance requirements relevant to the project

### Goals
- Prevent security vulnerabilities from reaching production
- Minimise the blast radius and time-to-remediation of security incidents
- Build a security-aware engineering culture

### Typical Communication
- Security review comments on PRs and design docs
- Risk register entries for security risks (owned by Security Lead)
- Incident communications and post-incident retrospectives

---

## Business Analyst

### Role Summary
Business Analysts clarify and document requirements, align stakeholder expectations, and ensure the team builds the right thing at the right level of scope.

### Responsibilities
- Elicit, document, and validate functional and non-functional requirements
- Facilitate scope discussions and trade-off decisions with stakeholders
- Define and verify success metrics and acceptance criteria alongside PdM
- Maintain a requirements traceability matrix for complex projects
- Bridge communication between technical teams and non-technical stakeholders

### Goals
- Reduce ambiguity and rework caused by unclear requirements
- Ensure all stakeholder needs are captured before development begins
- Support PdM in making evidence-based prioritisation decisions

### Typical Communication
- Requirements workshops during Initiation and Planning phases
- Regular check-ins with PdM, PM, and Developers during Execution
- Scope change assessments shared with PM and relevant stakeholders

---

## Role Interaction Model

The table below summarises when each role typically engages with the three core roles (PM, PdM, Developers) across the project lifecycle. See [`octoacme-role-engagement-checklist.md`](octoacme-role-engagement-checklist.md) for a per-phase checklist.

| Role | Primary interaction partners | Main engagement points |
|---|---|---|
| UX Designer | PdM, Developers | Planning (design), Execution (handoff, reviews), Release (usability sign-off) |
| QA Lead | Developers, PM, PdM | Planning (acceptance criteria), Execution (test runs, triage), Release (sign-off) |
| Technical Writer | Developers, PdM, PM | Execution (draft docs), Release (release notes), Retrospective (wiki updates) |
| Customer Support/Success | PdM, PM | Initiation (feedback), Planning (backlog input), Release (impact assessment), Retrospective |
| Security Lead | Developers, PM | Planning (threat modelling), Execution (PR reviews, CI), Release (security sign-off) |
| Business Analyst | PdM, PM, Stakeholders | Initiation (requirements), Planning (scope), Execution (clarifications), Retrospective |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

