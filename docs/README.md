# OctoAcme Project Management Docs

This folder contains the official process documentation for OctoAcme's project management approach. OctoAcme follows an iterative, customer-first delivery model with clear ownership, data-informed decisions, and continuous improvement baked into every phase of a project — from initiation through retrospective.

## Overview

OctoAcme follows a structured, lifecycle-based approach to project management that spans five key phases: Initiation, Planning, Execution, Release, and Retrospective. Every project begins with a lightweight Project One-pager that defines the problem statement, SMART objectives, success metrics, and stakeholder alignment before any development work begins. A formal decision gate ensures that work only moves into planning once success metrics are clear, stakeholders agree on priority, and team availability is confirmed. From there, planning activities include running a kickoff meeting, building a prioritized backlog with acceptance criteria, T-shirt sizing or story point estimation, defining a Definition of Done, and mapping out a release plan with clear milestones and dependency tracking.

The core roles driving OctoAcme projects are the Project Manager (PM), Product Manager (PdM), Developers, QA/Testing, and Stakeholders. The PM owns delivery coordination, scheduling, risk management, and cross-team communications. The PdM defines outcomes, owns the backlog, and measures success through data-driven decisions. Developers implement features, write tests, participate in design and code reviews, and help identify technical risks. These roles are designed to ensure clear ownership at every stage — each project always has a named PM and Product Lead accountable for its outcome.

Day-to-day execution is governed by a steady team rhythm: 15-minute daily standups focused on progress and blockers, weekly delivery syncs, and demos at the end of each sprint or milestone. Work flows through a GitHub Projects board, with small pull requests, required CI checks, and at least one peer approval before merging. Blocker escalation follows a three-level path — from team-level triage in standups, to PM escalation to the Product Lead, up to sponsor-level escalation for business-impacting issues. Risk management runs in parallel through a continuously maintained Risk Register tracking impact, likelihood, ownership, and mitigation plans, reviewed every week.

Communication and quality are treated as first-class concerns throughout the lifecycle. Stakeholders receive regular weekly status updates using a consistent template, with monthly broader stakeholder briefings and ad-hoc escalations as needed. Quality is maintained through unit tests, integration tests, end-to-end smoke tests, and security scanning in CI, with manual QA reserved for feature acceptance. After every sprint, release, or significant milestone, the team runs a structured retrospective — capturing what went well, what can improve, and 2–3 prioritized action items with clear owners and due dates — feeding those learnings back into the backlog to drive continuous improvement.

## Process Summary

| Phase | Description |
|---|---|
| **Initiation** | Validate the business need, align stakeholders, define success metrics, and get go/no-go approval before planning begins. |
| **Planning** | Break approved work into shippable increments, estimate scope, identify dependencies and risks, and create a release plan. |
| **Execution & Tracking** | Manage day-to-day delivery via standups, sprint ceremonies, PR workflows, CI quality gates, and blocker escalation paths. |
| **Risk & Communication** | Maintain a risk register, monitor and mitigate issues, and keep stakeholders informed through regular structured updates. |
| **Release & Deployment** | Standardize how features ship to production with pre-release checklists, smoke tests, rollback plans, and release notes. |
| **Retrospective & Improvement** | Capture learnings after sprints, releases, and incidents; convert them into actionable backlog items and track improvements. |

## Document Index

- [Project Management Overview](octoacme-project-management-overview.md) — High-level introduction to OctoAcme's PM approach, core roles, key artifacts, and lifecycle.
- [Project Initiation](octoacme-project-initiation.md) — Steps to validate and authorize new projects, including the One-pager template and initiation checklist.
- [Project Planning](octoacme-project-planning.md) — Turning an approved initiative into an actionable backlog, release plan, and milestone map.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day delivery management, PR workflows, quality standards, metrics, and blocker escalation.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Risk register format, risk lifecycle, stakeholder communication templates, and escalation paths.
- [Release & Deployment](octoacme-release-and-deployment.md) — Release types, pre-release requirements, deployment checklist, rollback playbook, and release notes template.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Retrospective structure, running guidance, action item tracking, and continuous improvement culture.
- [Roles & Personas](octoacme-roles-and-personas.md) — Definitions, responsibilities, and goals for Developers, Product Managers, and Project Managers.
