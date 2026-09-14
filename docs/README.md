# OctoAcme Project Management Documentation

## Overview
OctoAcme follows a structured, outcome-driven approach to project management. This documentation suite is the single entry point for guidance, templates, and checklists that support projects from initiation through closure. The goal is to improve discoverability, reduce onboarding time, and provide a consistent reference for team members.

## Brief overview of OctoAcme processes
OctoAcme manages work through a clear lifecycle: Initiation, Planning, Execution, Release, and Close/Retrospective. Projects begin with a lightweight Project One-pager to capture the problem, measurable goals, stakeholders, and a high-level timeline. Approved initiatives move into planning where the team defines a prioritized backlog, acceptance criteria, estimates, and a Definition of Done (DoD) before development starts.

Execution uses an agile workflow with a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined pull request process: small, reviewable PRs, CI gates (tests, linting, security scans), and at least one approval before merging. Releases are categorized (patch/minor/major) and require pre-release checks, rollback plans, and post-deploy verifications. Continuous improvement is supported through retrospectives where prioritized action items are tracked and fed back into the backlog.

Roles and communication are explicit: Product Managers set outcomes and priorities, Project Managers coordinate delivery and risks, Developers implement and test, and QA validates acceptance criteria. The team cadence includes daily standups for blockers, weekly delivery syncs for progress and risks, sprint demos for stakeholder validation, and defined escalation paths for unresolved issues or incidents.

## Key Principles
- Customer-first: prioritize customer value and usability  
- Iterative delivery: deliver small, testable increments  
- Clear ownership: each project has a named Project Manager (PM) and Product Lead  
- Data-informed decisions: measure impact and iterate based on evidence  
- Psychological safety: encourage feedback and learning

## Core Process Documents
- [Project Initiation](./octoacme-project-initiation.md)  
- [Project Planning](./octoacme-project-planning.md)  
- [Execution & Tracking](./octoacme-execution-and-tracking.md)  
- [Risks & Communication](./octoacme-risks-and-communication.md)  
- [Release & Deployment](./octoacme-release-and-deployment.md)  
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)  
- [Project Management Overview](./octoacme-project-management-overview.md)  
- [Roles & Personas](./octoacme-roles-and-personas.md)

## Quick Reference (How to use these docs)
- New project start: Read Project Initiation and use the Project One-pager template.  
- Planning a sprint: See Project Planning for backlog templates and DoD guidance.  
- Day-to-day delivery: Follow Execution & Tracking for board states, PR expectations, and CI gating.  
- Preparing a release: Use Release & Deployment checklist and Release Notes template.  
- After a milestone or incident: Run a Retrospective and add action items to the backlog.

## Contribution
To propose updates or new process content, open an issue using the "Add Content to Project Management Process Docs" template in .github/ISSUE_TEMPLATE/ and reference this README or the specific process doc.

## Acceptance Criteria
- Content aligns with existing process docs  
- Update improves clarity or closes a documented gap  
- Proposed content has been reviewed with stakeholders (if needed)
