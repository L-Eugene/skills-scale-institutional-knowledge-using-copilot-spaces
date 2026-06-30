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

## Engineering Manager / Tech Lead

### Role Summary
Engineering Managers and Tech Leads are accountable for technical direction, delivery feasibility, and team execution quality.

### Responsibilities
- Translate roadmap goals into technical plans and milestones
- Guide architecture and implementation decisions
- Balance delivery speed with reliability, maintainability, and security
- Remove technical blockers and coordinate cross-team engineering dependencies

### Goals
- Deliver technically sound solutions on predictable timelines
- Improve engineering quality, team productivity, and incident prevention
- Reduce rework through early technical alignment

### Typical Communication
- Technical design reviews and implementation plans
- Capacity and risk discussions with PM and PdM
- Escalation updates for architectural blockers

### Interaction Model (with existing roles)
- **PM:** Aligns schedule, sequencing, and dependency mitigation plans.
- **PdM:** Shapes scope trade-offs based on technical complexity and risk.
- **Developers:** Provides direction, mentoring, and architecture guardrails.
- **QA/Testing:** Aligns test strategy with technical design and risk areas.
- **Stakeholders:** Explains technical constraints, options, and delivery impact.

---

## UX Designer / Researcher

### Role Summary
UX Designers and Researchers ensure the team builds usable solutions that map to validated user needs.

### Responsibilities
- Conduct user research and synthesize findings into actionable insights
- Define user journeys, wireframes, and interaction patterns
- Validate prototypes and feature usability before release
- Collaborate on accessibility and content clarity requirements

### Goals
- Increase task success, usability, and customer satisfaction
- Reduce feature rework caused by late usability findings
- Ensure customer needs are represented in planning and prioritization

### Typical Communication
- Research readouts and usability findings
- Design reviews and acceptance criteria clarifications
- Customer journey walkthroughs with delivery teams

### Interaction Model (with existing roles)
- **PM:** Aligns research and design milestones with project timeline.
- **PdM:** Refines problem statements and prioritization with user evidence.
- **Developers:** Clarifies interaction intent and implementation details.
- **QA/Testing:** Defines usability and accessibility validation criteria.
- **Stakeholders:** Shares customer insights to support trade-off decisions.

---

## Security / Compliance

### Role Summary
Security and Compliance partners reduce risk by embedding security, privacy, and policy controls into delivery.

### Responsibilities
- Define security and compliance requirements for scope and design
- Review high-risk changes and threat-model critical workflows
- Ensure required controls, audits, and evidence are tracked
- Support incident response and remediation planning

### Goals
- Prevent avoidable security incidents and compliance gaps
- Shift security checks earlier into planning and delivery
- Maintain audit readiness with clear ownership and evidence

### Typical Communication
- Security risk reviews and control checklists
- Compliance sign-off criteria and remediation tracking
- Incident escalation and post-incident recommendations

### Interaction Model (with existing roles)
- **PM:** Aligns security gates, risk owners, and escalation paths.
- **PdM:** Balances customer value with policy and regulatory requirements.
- **Developers:** Provides secure coding guidance and remediation support.
- **QA/Testing:** Aligns security test coverage and release readiness criteria.
- **Stakeholders:** Communicates risk posture and control status.

---

## SRE / Operations

### Role Summary
SRE and Operations ensure production readiness, reliability, and operational resilience across releases.

### Responsibilities
- Define SLOs/SLIs and operational readiness requirements
- Review deployment, rollback, and observability plans
- Lead incident triage and post-incident follow-through
- Improve runbooks, alerting quality, and on-call effectiveness

### Goals
- Improve availability, performance, and mean time to recovery
- Reduce release risk through strong operational readiness
- Strengthen confidence in production changes

### Typical Communication
- Release readiness and go/no-go checkpoints
- Incident updates and reliability trend reporting
- Runbook and alerting review sessions

### Interaction Model (with existing roles)
- **PM:** Coordinates readiness checkpoints, change windows, and incident comms.
- **PdM:** Aligns reliability targets with product expectations and trade-offs.
- **Developers:** Supports instrumentation, operational fixes, and runbook updates.
- **QA/Testing:** Aligns pre-release verification with reliability risk areas.
- **Stakeholders:** Reports reliability posture and incident outcomes.

---

## Customer Support / Success

### Role Summary
Customer Support and Success teams represent customer reality by surfacing operational pain points and adoption risks.

### Responsibilities
- Provide customer issue trends and high-impact feedback
- Validate release messaging and known issue communication
- Contribute customer readiness and enablement requirements
- Track post-release customer impact and escalation patterns

### Goals
- Reduce customer-facing incidents and confusion
- Improve onboarding, adoption, and retention outcomes
- Ensure customer impact informs prioritization decisions

### Typical Communication
- Support trend summaries and escalation reports
- Release readiness feedback and launch communication reviews
- Post-release impact summaries

### Interaction Model (with existing roles)
- **PM:** Aligns customer-impact risks, communication timing, and escalation handling.
- **PdM:** Prioritizes roadmap adjustments based on support signal data.
- **Developers:** Shares reproducible issues and customer-context details.
- **QA/Testing:** Provides real-world edge cases and regression patterns.
- **Stakeholders:** Brings customer impact evidence into decision forums.

---

## Data Analyst

### Role Summary
Data Analysts provide measurement clarity by defining metrics, validating experiment outcomes, and supporting evidence-based decisions.

### Responsibilities
- Define success metrics, baselines, and instrumentation needs
- Build and maintain dashboards for delivery and product outcomes
- Analyze experiments, launches, and operational trends
- Surface decision-ready insights and confidence levels

### Goals
- Improve decision quality through trustworthy measurement
- Detect negative trends early and guide corrective actions
- Connect delivery outputs to customer and business outcomes

### Typical Communication
- KPI dashboards and metric health snapshots
- Experiment analysis readouts
- Decision support notes for planning and retrospective sessions

### Interaction Model (with existing roles)
- **PM:** Tracks delivery health metrics and dependency impact trends.
- **PdM:** Validates product outcomes against success criteria.
- **Developers:** Aligns instrumentation requirements and data quality checks.
- **QA/Testing:** Confirms measurement coverage for critical user flows.
- **Stakeholders:** Communicates performance trends and recommendation confidence.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
