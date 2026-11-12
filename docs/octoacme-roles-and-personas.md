# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

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

Projects can adopt the following roles when they add useful expertise or clarify accountability. A person may hold more than one role on a small team, but decision ownership should remain explicit. Not every project needs every role.

## Executive Sponsors

### Role Summary
Executive Sponsors champion the project, connect it to organizational goals, and help secure the support and resources needed to deliver it.

### Responsibilities
- Confirm the business case and strategic outcomes
- Secure organizational support and help resolve resource constraints
- Make or escalate major funding, scope, and priority decisions
- Remove organizational blockers that the delivery team cannot resolve

### Goals
- Achieve the intended organizational outcomes
- Ensure the project has appropriate sponsorship and resources
- Resolve high-impact decisions and escalations promptly

### Typical Communication
- Strategic outcome, funding, and scope discussions with organizational leaders
- Escalations and resource constraints with the Project Manager
- Outcome and priority alignment with the Product Manager

### Interactions with Existing Roles
- Align with the Product Manager on strategic outcomes while leaving product vision and backlog prioritization with the Product Manager
- Partner with the Project Manager on escalations, organizational dependencies, and resource constraints without taking over day-to-day coordination
- Consult Developers and technical leads on feasibility when evaluating major scope or funding decisions; the sponsor owns major funding and strategic scope decisions, while product backlog prioritization remains with the Product Manager

## Technical Leads / Architects

### Role Summary
Technical Leads and Architects guide technical design and help the team make sound engineering decisions.

### Responsibilities
- Guide architecture, technical standards, and design decisions
- Identify technical risks, constraints, and cross-component dependencies
- Help Developers decompose and estimate work
- Promote maintainability, security, reliability, and appropriate technical documentation

### Goals
- Deliver a coherent, maintainable technical solution
- Address technical risks and dependencies early
- Enable Developers to make consistent implementation decisions

### Typical Communication
- Design reviews, technical documentation, and implementation discussions with Developers
- Feasibility and trade-off discussions with the Product Manager
- Dependency and delivery-risk updates with the Project Manager

### Interactions with Existing Roles
- Work with Developers on design, implementation choices, reviews, and technical problem-solving
- Explain feasibility, technical trade-offs, and risks to the Product Manager so product decisions are informed; the Product Manager owns product priorities, while technical direction remains with the technical lead
- Keep the Project Manager aware of technical dependencies and delivery risks; the Project Manager coordinates the plan and day-to-day delivery

## QA / Test Leads

### Role Summary
QA and Test Leads coordinate the approach to verifying that the product meets its quality expectations and acceptance criteria.

### Responsibilities
- Define test strategy, coverage, and quality checks appropriate to the project
- Coordinate test planning and make verification results visible
- Surface defects, quality risks, and gaps in testability
- Provide evidence to inform release-readiness decisions

### Goals
- Detect quality issues early and reduce regression risk
- Ensure important acceptance criteria and user paths are verifiable
- Make quality status and remaining risks transparent

### Typical Communication
- Test plans, verification results, and defect reports with Developers
- Acceptance-criteria and coverage discussions with the Product Manager
- Quality-risk and milestone updates with the Project Manager

### Interactions with Existing Roles
- Work with the Product Manager to make acceptance criteria clear and testable
- Collaborate with Developers on testability, automated checks, and defect resolution; the QA / Test Lead owns the test approach and evidence, while quality remains a shared team responsibility
- Coordinate test milestones and communicate quality risks to the Project Manager for schedule and risk tracking

## UX / Accessibility Specialists

### Role Summary
UX and Accessibility Specialists help ensure that solutions address user needs and can be used by people with a range of abilities.

### Responsibilities
- Research user needs and map relevant user journeys
- Create or review interaction designs and usability guidance
- Identify accessibility requirements and evaluate designs against them
- Validate proposed solutions with users or appropriate usability methods

### Goals
- Make product experiences useful, understandable, and accessible
- Reduce the risk of building solutions that do not meet user needs
- Give the team actionable design and accessibility guidance

### Typical Communication
- User research and design reviews with the Product Manager
- Design handoffs and accessibility guidance with Developers
- Usability and accessibility validation with QA / Test Leads

### Interactions with Existing Roles
- Partner with the Product Manager to connect user needs to product outcomes and acceptance criteria; product priorities remain with the Product Manager
- Work with Developers to clarify designs and accessibility expectations during implementation
- Coordinate with Developers and QA / Test Leads on how usability and accessibility requirements will be verified
- Share research and design dependencies with the Project Manager for planning and coordination

## Business Analysts / Domain SMEs

### Role Summary
Business Analysts and Domain Subject Matter Experts clarify business processes, terminology, rules, and constraints relevant to the project.

### Responsibilities
- Explain current workflows, domain concepts, and operational constraints
- Identify assumptions, edge cases, and dependencies in business requirements
- Help validate that proposed changes support real business needs
- Provide timely answers and document domain decisions where useful

### Goals
- Reduce ambiguity in requirements and business rules
- Ensure the solution reflects relevant domain knowledge
- Help teams identify process impacts and edge cases early

### Typical Communication
- Requirement and terminology clarification with the Product Manager
- Domain questions and examples with Developers
- Decision needs, dependencies, and stakeholder availability with the Project Manager

### Interactions with Existing Roles
- Work with the Product Manager to clarify requirements and validate that they support product outcomes; domain guidance informs requirements, while prioritization remains with the Product Manager
- Answer Developers' domain questions and help validate behavior against business rules
- Coordinate with the Project Manager to surface decision needs, dependencies, and stakeholder availability

## Operations / Release Owners

### Role Summary
Operations and Release Owners represent the needs of deploying, monitoring, supporting, and maintaining the solution.

### Responsibilities
- Identify operational readiness requirements, including monitoring and support needs
- Coordinate release, deployment, rollback, and handover planning
- Surface service, infrastructure, and operational risks
- Confirm that operational documentation and support arrangements are prepared

### Goals
- Make releases predictable and supportable
- Reduce service disruption and clarify ownership after release
- Ensure operational risks are understood before deployment

### Typical Communication
- Deployment, monitoring, and support planning with Developers
- Verification evidence and readiness risks with QA / Test Leads
- Release dependencies and impacts with the Project Manager and Product Manager

### Interactions with Existing Roles
- Work with Developers on deployment, observability, and operational design
- Coordinate with QA / Test Leads on release evidence and readiness risks
- Share release dependencies and operational readiness risks with the Project Manager for scheduling and escalation; release approval follows the project's agreed decision process
- Inform the Product Manager of service or customer impacts that affect product outcomes

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
