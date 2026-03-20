# OctoAcme Role Interaction Matrix

This document provides a quick reference for understanding how OctoAcme roles interact across project phases.

## Overview
The following matrix shows which roles collaborate closely (🤝), communicate regularly (📢), or have dependent activities (→) at each phase.

## Initiation Phase

| Role | Collaborators | Key Activities |
|------|---------------|-----------------|
| **Product Manager** | Stakeholders, Project Manager | Define business need, create one-pager, validate success metrics |
| **Project Manager** | Product Manager, Stakeholders | Identify resource needs, establish communication plan |
| **Business Analyst** | Stakeholders, Product Manager | Validate requirement clarity, identify edge cases |
| **Sponsors/Stakeholders** | Product Manager, Project Manager | Approve scope and prioritization |

---

## Planning Phase

| Role | Collaborators | Key Activities |
|------|---------------|-----------------|
| **Product Manager** | Business Analyst, Developers | Prioritize backlog, refine user stories |
| **Project Manager** | Product Manager, All Delivery Roles | Create project plan, identify dependencies, schedule kickoff |
| **Business Analyst** | Product Manager, Developers, QA | Detail acceptance criteria, clarify business logic |
| **UX Designer** | Product Manager, Developers | Scope design work, create design-tech dependency map |
| **Developers** | Project Manager, Business Analyst, DevOps, UX | Estimate technical work, identify infrastructure needs |
| **DevOps Engineer** | Developers, Project Manager | Plan CI/CD setup, environment provisioning |
| **QA/Testing** | Business Analyst, Developers | Plan test strategy, define acceptance criteria |

---

## Execution Phase

| Role | Collaborators | Key Activities |
|------|---------------|-----------------|
| **Developers** | UX Designer, DevOps, QA | Build features, participate in daily standups, create PRs |
| **UX Designer** | Developers, Product Manager | Validate designs, run usability tests, iterate |
| **DevOps Engineer** | Developers | Maintain CI/CD, manage environments, troubleshoot deployments |
| **QA/Testing** | Developers, Business Analyst | Execute tests, validate acceptance, report issues |
| **Project Manager** | All Roles | Facilitate standups, update risks, manage blockers, escalate as needed |
| **Business Analyst** | Developers, QA, Product Manager | Answer requirement questions, support testing validation |

---

## Release Phase

| Role | Collaborators | Key Activities |
|------|---------------|-----------------|
| **Project Manager** | DevOps, QA, Stakeholders | Coordinate release window, stakeholder communication |
| **DevOps Engineer** | Developers, QA, Project Manager | Deploy to staging/prod, run smoke tests, support rollback if needed |
| **QA/Testing** | DevOps, Project Manager | Perform post-deploy verification, sign off |
| **Developers** | DevOps, Project Manager | On-call support, bug fixes, rollback support |
| **Product Manager** | Stakeholders, Project Manager | Announce release, communicate business impact |

---

## Retrospective Phase

| Role | Collaborators | Key Activities |
|------|---------------|-----------------|
| **Project Manager** | All Roles | Facilitate retrospective, capture action items, track improvements |
| **All Roles** | Project Manager, Team | Reflect on what went well, what could improve, propose actions |

---

## Communication Best Practices by Role Pair

### Developer ↔ UX Designer
- **Frequency**: Daily/as-needed during implementation
- **What to communicate**: Design feasibility, component states, accessibility requirements
- **Output**: Updated design specs, implementation guidance, design QA notes

### Developer ↔ DevOps Engineer
- **Frequency**: Daily/as-needed, especially around deployments
- **What to communicate**: Build & deployment issues, infrastructure requests, performance concerns
- **Output**: Resolved build failures, deployment runbooks, environment updates

### Project Manager ↔ Business Analyst
- **Frequency**: Weekly, or as requirements change
- **What to communicate**: Scope changes, acceptance criteria clarifications, prioritization updates
- **Output**: Updated backlog, refined user stories, scope impact assessments

### Product Manager ↔ Developers (via Business Analyst or directly)
- **Frequency**: Weekly planning, ad-hoc questions
- **What to communicate**: Prioritization rationale, user research findings, success metrics
- **Output**: Refined backlog, technical design input, metric tracking setup

---

## Handoff Checklist Template

Use this template when handing off work between roles or phases:

- [ ] **Recipient understands the context**: Why is this being handed off now?
- [ ] **Acceptance criteria are clear**: What does "done" look like?
- [ ] **Dependencies are identified**: What else needs to happen before/after?
- [ ] **Risks are communicated**: What could go wrong?
- [ ] **Success metrics are defined**: How will we measure success?
- [ ] **Owner is assigned**: Who is accountable?
- [ ] **Timeline is confirmed**: When is this due?
- [ ] **Communication plan is set**: How will we stay in sync?
