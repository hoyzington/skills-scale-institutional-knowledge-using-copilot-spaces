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

## UX/Product Designers

### Role Summary
UX/Product Designers translate user and business needs into usable experiences. They guide discovery, shape workflows and interfaces, and hand validated designs to Developers with Product Managers aligned on scope, outcomes, and acceptance expectations.

### Responsibilities
- Conduct user research and synthesize insights with Product Managers and stakeholders
- Define user journeys, wireframes, prototypes, and usability requirements
- Partner with Developers and Technical Leads on feasibility, constraints, and implementation trade-offs
- Clarify design acceptance criteria, accessibility expectations, and edge cases before delivery
- Validate delivered experiences and hand feedback to Product Managers and Developers for iteration

### Goals
- Improve usability, accessibility, and adoption
- Reduce rework by aligning design intent before development starts
- Ensure customer problems are solved in a consistent, intuitive way

### Typical Communication
- Discovery workshops with Product Managers, stakeholders, and customer-facing teams
- Design reviews with Developers and Technical Leads before implementation
- Usability feedback and release-readiness check-ins with QA and Project Managers

---

## Technical Leads/Architects

### Role Summary
Technical Leads and Architects are accountable for technical direction, architectural coherence, and engineering trade-offs across the project lifecycle. They turn product intent into implementation approaches, support delivery decisions with Developers, and escalate system-level risks to Project Managers and stakeholders when needed.

### Responsibilities
- Define technical approaches, integration patterns, and non-functional requirements
- Guide Developers through design reviews, implementation decisions, and handoffs across components
- Partner with Product Managers on scope trade-offs and sequencing when technical complexity affects delivery
- Help Project Managers surface dependencies, risks, and decision points that require stakeholder alignment
- Review readiness for release, scalability, reliability, and long-term maintainability

### Goals
- Maintain a coherent, secure, and scalable architecture
- Reduce avoidable delivery risk caused by unclear technical decisions
- Balance short-term delivery needs with long-term engineering sustainability

### Typical Communication
- Technical design reviews and architecture decision records with Developers
- Scope, dependency, and risk discussions with Product Managers and Project Managers
- Decision briefings for stakeholders when trade-offs affect timeline, cost, or strategic direction

---

## QA/Quality Engineers

### Role Summary
QA/Quality Engineers protect release quality by defining validation strategies, surfacing quality risks, and confirming that delivered work meets agreed expectations. They participate from planning through release, coordinating handoffs between Developers, Product Managers, and Project Managers for acceptance and launch readiness.

### Responsibilities
- Define test strategies, coverage expectations, and quality gates for planned work
- Review requirements and designs with Product Managers and Developers to identify ambiguities and risks early
- Execute or coordinate functional, regression, exploratory, and release validation
- Track defects, confirm fixes, and communicate release impact to Project Managers and stakeholders as needed
- Support final acceptance decisions by providing objective quality and readiness signals

### Goals
- Catch defects early and reduce escaped issues
- Make release readiness visible and evidence-based
- Strengthen confidence that delivered work meets customer and business expectations

### Typical Communication
- Test planning and bug triage with Developers and Product Managers
- Release-readiness updates and risk escalation with Project Managers
- Quality summaries for stakeholders when issues affect scope, timing, or acceptance decisions

---

## Site Reliability/DevOps Engineers

### Role Summary
Site Reliability and DevOps Engineers own delivery pipelines, environments, observability, and operational readiness. They work with Developers and Technical Leads to ensure new capabilities can be deployed, monitored, and supported reliably from implementation through production operations.

### Responsibilities
- Maintain deployment automation, environment consistency, and release processes
- Define monitoring, alerting, resilience, and rollback expectations with Developers and Technical Leads
- Identify operational dependencies and communicate release constraints to Project Managers
- Support incident readiness, change management, and post-release stabilization with stakeholders and support teams
- Hand operational insights back to Product Managers and engineering teams to improve future planning

### Goals
- Improve reliability, deployment safety, and recovery speed
- Reduce operational risk introduced during delivery
- Ensure production readiness is built into the lifecycle rather than deferred to release time

### Typical Communication
- Implementation and operability reviews with Developers and Technical Leads
- Release planning, dependency tracking, and incident coordination with Project Managers
- Readiness updates and service-impact communication for stakeholders and customer-facing teams

---

## Security/Privacy Partners

### Role Summary
Security and Privacy Partners help teams identify, prioritize, and address security, privacy, and compliance requirements throughout the lifecycle. They provide decision support on controls and risk acceptance while coordinating with Developers, Technical Leads, Product Managers, Project Managers, and stakeholders when sensitive trade-offs arise.

### Responsibilities
- Define security, privacy, and compliance expectations during planning and design
- Review proposed solutions with Developers and Technical Leads for threats, controls, and data-handling risks
- Advise Product Managers on requirement changes or scope adjustments needed to meet obligations
- Escalate unresolved risks, exceptions, or approval needs through Project Managers to stakeholders or decision makers
- Validate release readiness for high-risk changes and support post-incident follow-up when needed

### Goals
- Reduce security and privacy risk without slowing delivery unnecessarily
- Make risk decisions explicit, traceable, and appropriately owned
- Build security and privacy expectations into normal project planning and execution

### Typical Communication
- Risk reviews and control discussions with Developers and Technical Leads
- Planning and requirement alignment with Product Managers and Project Managers
- Escalation summaries for stakeholders when risk acceptance or compliance decisions are required

---

## Data/Analytics Partners

### Role Summary
Data and Analytics Partners ensure teams can measure whether delivered work creates the intended outcome. They define instrumentation and reporting needs early, coordinate implementation handoffs with Developers, and help Product Managers, Project Managers, and stakeholders interpret results after release.

### Responsibilities
- Define metrics, dashboards, and measurement plans with Product Managers
- Specify telemetry, event tracking, and reporting requirements for Developers
- Validate that analytics implementations support launch decisions and post-release learning
- Share performance insights with Project Managers and stakeholders during status reviews and retrospectives
- Recommend follow-up experiments or prioritization changes based on observed outcomes

### Goals
- Make product and project decisions more evidence-based
- Ensure success criteria can be measured in production
- Close the loop between delivery, adoption, and business impact

### Typical Communication
- Metric definition and outcome reviews with Product Managers
- Instrumentation handoffs and validation with Developers
- Status, adoption, and results reporting with Project Managers and stakeholders

---

## Customer Support/Operations Representatives

### Role Summary
Customer Support and Operations Representatives bring customer-impact, readiness, and workflow considerations into project delivery. They help teams plan for rollout, supportability, and feedback loops so Developers, Product Managers, Project Managers, and stakeholders understand downstream operational effects before decisions are finalized.

### Responsibilities
- Represent customer support workflows, operational constraints, and known pain points during planning
- Review proposed changes with Product Managers and Developers for supportability, documentation, and training needs
- Coordinate launch communications, readiness checklists, and escalation paths with Project Managers
- Surface production feedback, recurring issues, and adoption friction back to the product and engineering teams
- Support post-release monitoring and incident response handoffs with operations and reliability partners

### Goals
- Reduce customer disruption during rollout and change adoption
- Ensure internal teams are prepared to support what is delivered
- Improve the quality and speed of feedback from real-world operations

### Typical Communication
- Discovery and readiness discussions with Product Managers and Project Managers
- Supportability reviews with Developers and Technical Leads
- Launch updates, issue trends, and escalation feedback for stakeholders and customer-facing teams

---

## Business Sponsors/Decision Makers

### Role Summary
Business Sponsors and Decision Makers provide strategic direction, approve major trade-offs, and are accountable for business outcomes tied to the work. They participate at key decision points, relying on Product Managers, Project Managers, and other delivery roles to surface options, risks, and recommended actions.

### Responsibilities
- Confirm business goals, success criteria, funding, and priority decisions
- Resolve escalations when scope, timeline, risk, or resource trade-offs exceed team-level authority
- Review recommendations from Product Managers, Project Managers, Technical Leads, and other partners at major milestones
- Align stakeholders on go/no-go decisions, significant change requests, and acceptance of residual risk
- Sponsor cross-functional participation and remove organizational blockers when progress is at risk

### Goals
- Keep delivery aligned with strategic priorities and expected value
- Enable timely decisions when the team reaches escalation points
- Ensure accountability for business outcomes extends beyond implementation alone

### Typical Communication
- Milestone reviews and prioritization decisions with Product Managers and Project Managers
- Escalation and trade-off discussions with Technical Leads, Security, and other functional partners
- Stakeholder briefings that confirm direction, approvals, and next-step expectations

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
