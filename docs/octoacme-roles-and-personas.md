# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Roles may be combined or tailored to project size and context, but each responsibility and decision should have a clear owner.

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

## Project Sponsors

### Role Summary
Project Sponsors provide executive accountability for the business case, organizational support, and strategic decisions needed to deliver a project.

### Responsibilities
- Champion the project and confirm its alignment with organizational priorities
- Secure or broker resources and remove organizational obstacles
- Make or escalate decisions about scope, priority, and investment when they exceed the delivery team's authority
- Review progress, outcomes, and material risks at agreed milestones

### Interactions with Existing Roles
- Partner with the Product Manager on expected outcomes and priority trade-offs
- Work with the Project Manager on governance, escalations, resources, and milestone decisions
- Consult stakeholders and affected teams when decisions have broader organizational impact
- Rely on Developers and QA/Testing for delivery evidence, while leaving implementation decisions to the team

### Typical Communication
- Project approval and milestone reviews
- Escalation decisions and sponsor updates

---

## Business Analysts

### Role Summary
Business Analysts clarify business needs and translate them into understood, actionable requirements and workflows.

### Responsibilities
- Elicit and document business requirements, assumptions, and constraints
- Map current and proposed processes and identify gaps
- Help define clear, testable acceptance criteria and maintain traceability to the stated need
- Identify requirement changes and communicate their implications

### Interactions with Existing Roles
- Work with the Product Manager to refine problems, scope, backlog items, and acceptance criteria
- Coordinate with stakeholders and subject matter experts to validate needs and terminology
- Clarify requirements with Developers and QA/Testing during design, implementation, and validation
- Keep the Project Manager informed about requirement changes that affect scope, dependencies, or schedule

### Typical Communication
- Requirements and process maps
- Backlog refinement and stakeholder workshops

---

## UX/UI Designers and User Researchers

### Role Summary
UX/UI Designers and User Researchers help ensure that solutions are useful, accessible, and grounded in users' needs.

### Responsibilities
- Plan and conduct appropriate user research and usability validation
- Design user flows, interaction patterns, and interface concepts
- Communicate usability and accessibility considerations and unresolved questions
- Iterate designs based on user feedback and technical constraints

### Interactions with Existing Roles
- Partner with the Product Manager to connect user needs to product outcomes and priorities
- Consult stakeholders and users to validate workflows and assumptions
- Collaborate with Developers on feasibility and implementation details
- Work with QA/Testing to make user-facing acceptance criteria and usability checks verifiable
- Coordinate research and design activities with the Project Manager's plan and milestones

### Typical Communication
- Research findings, journey maps, prototypes, and design reviews

---

## Technical Leads and Architects

### Role Summary
Technical Leads and Architects guide technical design and integration so the solution is maintainable, secure, and consistent with system constraints.

### Responsibilities
- Guide architecture, technical design, and engineering standards
- Identify technical dependencies, integration points, and risks
- Support technical estimation and break work into implementable increments
- Facilitate technical decisions and document significant trade-offs

### Interactions with Existing Roles
- Collaborate with Developers on design, implementation, code quality, and technical problem solving
- Advise the Product Manager on technical options and trade-offs affecting outcomes or scope
- Work with the Project Manager to surface dependencies, risks, and estimate assumptions
- Coordinate with QA/Testing on testability and with Security/Privacy Leads on required controls

### Typical Communication
- Technical design documents, architecture decisions, and dependency reviews

---

## Release and Operations Leads

### Role Summary
Release and Operations Leads coordinate production readiness and the operational practices needed to deploy, monitor, and support a service. Depending on the team, this work may be performed by an operations specialist or Site Reliability Engineer.

### Responsibilities
- Define and coordinate release readiness, deployment, and verification activities
- Ensure monitoring, alerting, support ownership, and operational documentation are prepared
- Plan rollback or mitigation steps with the delivery team
- Identify operational risks and feed reliability learnings back into the backlog

### Interactions with Existing Roles
- Coordinate with Developers on deployment automation, observability, and operational handoff
- Work with QA/Testing to confirm smoke tests and release verification
- Align release timing, dependencies, and stakeholder communications with the Project Manager
- Consult the Product Manager on release impact and with Stakeholders or support teams on readiness and announcements

### Typical Communication
- Release checklists, runbooks, deployment plans, and post-deploy verification

---

## Security and Privacy Leads

### Role Summary
Security and Privacy Leads advise teams on security, privacy, and compliance risks and help ensure appropriate controls are included throughout delivery.

### Responsibilities
- Identify applicable security and privacy requirements, risks, and controls
- Advise on secure design, data handling, and privacy considerations
- Review or coordinate reviews of relevant changes and risk mitigations
- Escalate material concerns through the established security or privacy incident process

### Interactions with Existing Roles
- Partner with the Product Manager and Business Analyst to include security and privacy needs in requirements and acceptance criteria
- Advise the Technical Lead and Developers on design choices and implementation controls
- Coordinate with QA/Testing on appropriate security and privacy validation
- Inform the Project Manager about risks, review dependencies, or issues that could affect delivery; use the security incident runbook and notify Security on-call for security incidents
- Consult stakeholders and the Project Sponsor when decisions require business risk acceptance or organizational escalation

### Typical Communication
- Risk assessments, control requirements, review findings, and incident escalations

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- A project does not necessarily need a separate person for every role. Assign roles according to project needs and team size, and make ownership, decision authority, and handoffs explicit.
