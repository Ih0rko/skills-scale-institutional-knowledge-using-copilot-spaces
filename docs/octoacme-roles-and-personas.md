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

## Release / Deployment Leads

### Role Summary
Release / Deployment Leads own release readiness and coordinate the safe movement of approved changes from staging to production.

### Responsibilities
- Plan release activities and deployment windows
- Confirm rollout, smoke-test, rollback, and communication plans
- Coordinate release verification and post-deploy checks
- Identify release dependencies and unresolved release risks

### Goals
- Deliver predictable, low-risk releases
- Minimize deployment disruption and recovery time
- Improve release observability and repeatability

### Interactions with Existing Roles
- Aligns timing and stakeholder communications with Project Managers
- Confirms scope and acceptance with Product Managers
- Coordinates implementation and rollback readiness with Developers
- Works with QA and Security stakeholders on validation and sign-off
- Partners with Change / Support Leads on operational readiness

### Typical Communication
- Release planning and readiness reviews
- Deployment and rollback coordination
- Post-release verification summaries

---

## UX / Design Leads

### Role Summary
UX / Design Leads define and maintain the user experience vision, ensuring solutions are usable, accessible, and consistent.

### Responsibilities
- Facilitate discovery and translate user needs into designs
- Conduct design reviews and maintain design consistency
- Incorporate accessibility and usability requirements
- Collaborate on acceptance criteria and usability validation

### Goals
- Improve usability and accessibility
- Create consistent, understandable experiences
- Reduce rework caused by unclear or infeasible designs

### Interactions with Existing Roles
- Partners with Product Managers on outcomes, prioritization, and user feedback
- Works with Developers on technical feasibility and implementation quality
- Collaborates with QA / Testing on acceptance criteria and usability checks
- Provides Project Managers with design dependencies and review milestones

### Typical Communication
- Discovery sessions and design critiques
- Backlog and acceptance-criteria reviews
- Usability validation and handoff sessions

---

## Data / Analytics Leads

### Role Summary
Data / Analytics Leads define how project success is measured, instrumented, reported, and evaluated after delivery.

### Responsibilities
- Define success metrics and measurement plans
- Specify instrumentation and data-quality requirements
- Validate dashboards and reporting accuracy
- Analyze release and adoption outcomes

### Goals
- Make outcomes measurable and evidence-based
- Improve the reliability of product and delivery metrics
- Surface adoption, quality, and risk trends quickly

### Interactions with Existing Roles
- Aligns success measures and evaluation plans with Product Managers
- Provides findings and risk signals to Project Managers
- Defines telemetry needs and validates data collection with Developers
- Uses QA and stakeholder feedback to assess data quality and completeness

### Typical Communication
- Metric and telemetry planning
- Data-quality reviews
- Release outcome and retrospective reporting

---

## Security Leads

### Role Summary
Security Leads ensure security risks are identified, controls are defined, and incidents receive appropriate escalation and coordination.

### Responsibilities
- Lead threat modeling and security-risk assessments
- Define required controls and security acceptance criteria
- Coordinate security reviews and remediation
- Support security incident escalation and follow-up

### Goals
- Reduce preventable security risk
- Embed security checks throughout delivery
- Improve incident readiness and remediation speed

### Interactions with Existing Roles
- Advises Product Managers on risk trade-offs and scope
- Helps Project Managers identify security dependencies and escalation needs
- Partners with Developers on secure implementation and remediation
- Coordinates validation with QA / Testing and the organization's Security on-call
- Works with Release / Deployment Leads on secure, supported releases

### Typical Communication
- Threat-modeling and security review sessions
- Risk and remediation updates
- Security incident escalation and follow-up reviews

---

## Change / Support Leads

### Role Summary
Change / Support Leads prepare users and support teams for new releases, coordinate operational readiness, and collect post-release feedback.

### Responsibilities
- Plan documentation, training, and stakeholder communication
- Confirm support coverage and escalation procedures
- Gather and prioritize operational or customer feedback
- Coordinate handoffs from delivery to ongoing operations

### Goals
- Improve stakeholder and user readiness
- Reduce avoidable support burden
- Accelerate feedback and operational issue resolution

### Interactions with Existing Roles
- Coordinates launch timing and status communications with Project Managers
- Validates customer-facing scope and messaging with Product Managers
- Surfaces implementation and readiness gaps to Developers
- Works with Release / Deployment Leads on launch and rollback communications
- Brings operational findings into retrospectives and improvement work

### Typical Communication
- Stakeholder readiness and launch planning
- Support coverage and escalation reviews
- Post-release feedback and retrospective sessions

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
