# OctoAcme Project Management Docs

Welcome! This README is the entry point for OctoAcme's project management documentation. It provides a concise overview of our processes and links to each process document for deeper reading.

## Overview

OctoAcme follows a customer-first, iterative project management methodology that balances structure with flexibility. Projects move through five lifecycle stages: **Initiation** (problem statement, stakeholder alignment, project charter), **Planning** (scope, milestones, resource and dependency mapping), **Execution & Tracking** (iterative build-test-review cycles on a GitHub Projects board with columns: Backlog → Ready → In Progress → In Review → QA → Done), **Release & Deployment** (staged rollout with pre-release checklist, smoke tests, and a rollback/incident playbook), and **Retrospective & Continuous Improvement** (structured learnings converted into backlog action items after every sprint, release, or incident).

Every project is supported by a set of named roles: the **Project Manager (PM)** coordinates delivery, schedules, and risks; the **Product Manager (PdM)** owns the vision, backlog prioritization, and success metrics; **Developers** implement and review features; **QA/Testing** validates acceptance criteria; and **Stakeholders** provide inputs and approvals. Clear ownership ensures accountability at every stage.

Communication follows a defined cadence — twice-weekly standups for the delivery team, weekly PM–PdM syncs, and monthly stakeholder updates — all anchored to a single source of truth (project README or release doc). Status reports use a consistent template (progress · next steps · risks & blockers · decisions needed), and escalation follows a clear path: Team → PM → Product Lead → Sponsor, with a dedicated security incident runbook for security events.

Quality is built into every step: pull requests are kept small (≤ 400 lines where possible), linked to issues with acceptance criteria, and require passing CI (tests, lint, security scans) plus at least one approval before merge. Releases require all acceptance criteria met, passing CI and security scans, drafted release notes, and smoke tests on staging before production promotion. Any deployment failure triggers the rollback/incident playbook, followed by a blameless post-incident retrospective.

## Docs Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, and lifecycle summary |
| [Project Initiation Guide](octoacme-project-initiation.md) | Problem statement, charter, and stakeholder alignment |
| [Project Planning](octoacme-project-planning.md) | Scope, milestones, dependencies, and resource planning |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Board workflow, PR conventions, QA, metrics, and escalation |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, communication templates, and escalation paths |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Release types, deployment checklist, rollback playbook |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, action item tracking, improvement culture |
| [Roles and Personas](octoacme-roles-and-personas.md) | Detailed responsibilities and communication patterns for each role |

---
_This README is intended to help contributors, PMs, and stakeholders quickly find OctoAcme's main process references. Closes #2._
