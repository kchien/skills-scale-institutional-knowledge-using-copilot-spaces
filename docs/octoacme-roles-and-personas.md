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

## Release Manager / Release Lead

### Role Summary
The Release Manager or Release Lead owns release readiness and coordinates deployments, stakeholder announcements, and rollback decisions.

### Responsibilities
- Maintain release checklists and deployment windows
- Coordinate go/no-go readiness reviews
- Communicate release status and notable changes
- Coordinate rollback or mitigation actions with incident responders
- Track release dependencies across teams

### Goals
- Deliver releases safely and predictably
- Reduce deployment risk and recovery time
- Keep stakeholders informed of release status

### Interactions with Existing Roles
- Works with the Project Manager on schedules, risks, dependencies, and stakeholder updates.
- Coordinates with Developers on code readiness and rollback artifacts.
- Partners with QA/Testing to confirm acceptance and smoke-test completion.
- Aligns with Product Managers on release scope and customer impact.
- Consults with Site Reliability Engineers on operational readiness and observability.

---

## Scrum Master / Delivery Lead

### Role Summary
The Scrum Master or Delivery Lead facilitates delivery practices, protects team focus, and helps remove impediments while coaching the team toward repeatable execution.

### Responsibilities
- Facilitate sprint or iteration ceremonies and team working agreements
- Help the team remove blockers and improve delivery flow
- Coach teams on ownership, transparency, and continuous improvement
- Surface delivery constraints and cross-team dependencies
- Support follow-through on retrospective action items

### Goals
- Improve team flow and predictability
- Reduce avoidable impediments and meeting overhead
- Strengthen psychological safety and continuous improvement

### Interactions with Existing Roles
- Partners with the Project Manager on dependencies, capacity, and risk visibility.
- Works with Developers and QA/Testing on flow, readiness, and Definition of Done.
- Supports Product Managers in maintaining a prepared, prioritized backlog.
- Escalates persistent organizational or cross-team impediments through the Project Manager.

---

## UX Designer / UX Lead

### Role Summary
The UX Designer or UX Lead is accountable for usability, accessibility, interaction design, and design-system consistency across the project lifecycle.

### Responsibilities
- Research user needs and usability risks
- Translate requirements into flows, prototypes, and interaction specifications
- Review accessibility and content requirements
- Validate designs through usability testing and feedback
- Maintain design patterns and support implementation consistency

### Goals
- Improve task success, usability, and accessibility
- Reduce rework caused by late usability discoveries
- Align the solution with customer needs and brand standards

### Interactions with Existing Roles
- Collaborates with Product Managers to clarify problems, success outcomes, and priorities.
- Works with Developers on feasibility, implementation details, and design review.
- Coordinates with QA/Testing on acceptance criteria for usability and accessibility.
- Provides the Project Manager with design dependencies, validation milestones, and risks.

---

## Site Reliability Engineer / Operations Lead

### Role Summary
The Site Reliability Engineer or Operations Lead owns operational readiness, reliability objectives, monitoring, incident preparedness, and production handoffs.

### Responsibilities
- Define service-level objectives and operational requirements
- Build or review monitoring, alerting, and capacity plans
- Prepare runbooks and incident escalation paths
- Support deployment and post-deployment validation
- Analyze incidents and coordinate reliability improvements

### Goals
- Improve availability, performance, and recovery time
- Make operational risk visible before release
- Strengthen observability and incident response

### Interactions with Existing Roles
- Partners with Developers on observability, resilience, and technical mitigations.
- Supports the Release Manager on deployment readiness and rollback planning.
- Provides the Project Manager with reliability risks, dependencies, and milestones.
- Works with Product Managers on service objectives and customer-impact trade-offs.
- Coordinates with QA/Testing on operational smoke tests and failure scenarios.

---

## Security Lead

### Role Summary
The Security Lead coordinates security requirements, risk review, vulnerability response, and relevant compliance activities for the project.

### Responsibilities
- Facilitate threat modeling and security risk assessment
- Define or validate security requirements and controls
- Coordinate security testing and vulnerability triage
- Advise on compliance and data protection needs
- Support incident response for security events

### Goals
- Reduce security and compliance risk
- Embed security review early in delivery
- Improve the speed and effectiveness of vulnerability resolution

### Interactions with Existing Roles
- Works with Developers to define secure implementation and remediation actions.
- Supports QA/Testing with security test scope and release readiness checks.
- Advises Product Managers on risk, user impact, and remediation trade-offs.
- Provides the Project Manager with security risks, approvals, and escalation needs.
- Coordinates through the documented security incident process rather than bypassing specialized response channels.

---

## Data Analyst / Data Lead

### Role Summary
The Data Analyst or Data Lead defines the evidence needed to measure outcomes, analyzes project and product data, and advises on experiment quality.

### Responsibilities
- Define measurement plans and success-metric calculations
- Advise on experiment design and statistical validity
- Analyze usage, adoption, quality, and outcome data
- Validate data definitions and reporting accuracy
- Communicate findings and evidence to decision-makers

### Goals
- Improve the accuracy and usability of project evidence
- Support timely, data-informed decisions
- Detect unintended outcomes and product risks

### Interactions with Existing Roles
- Partners with Product Managers to define success metrics and interpret outcomes.
- Works with Developers on instrumentation, event specifications, and data quality.
- Supports QA/Testing with data validation and edge-case checks.
- Helps the Project Manager identify measurement dependencies and reporting milestones.

---

## Customer Support / Customer Success Representative

### Role Summary
The Customer Support or Customer Success Representative represents customer impact, operational feedback, and field experience during planning and delivery.

### Responsibilities
- Share recurring issues, usage patterns, and customer feedback
- Support customer-facing release readiness and communication
- Help reproduce, classify, and prioritize reported issues
- Identify training or support-documentation needs
- Report post-release adoption and customer impact

### Goals
- Improve customer readiness and experience
- Reduce avoidable customer friction and repeated issues
- Feed validated customer evidence into prioritization and quality decisions

### Interactions with Existing Roles
- Provides Product Managers with customer evidence and prioritization context.
- Coordinates with QA/Testing on issue reproduction and release validation.
- Partners with the Release Manager on announcements, support readiness, and known issues.
- Gives the Project Manager visibility into customer-impact risks and dependencies.
- Collaborates with Developers and UX on clarifying customer scenarios and proposed fixes.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Assign roles based on team capacity; multiple personas may be covered by the same person, and role-specific responsibilities should remain explicit.

