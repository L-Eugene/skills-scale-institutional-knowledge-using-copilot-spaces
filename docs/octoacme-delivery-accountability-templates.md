# OctoAcme — Delivery Accountability Templates

Use these templates to improve ownership clarity across planning, execution, and release.

## 1) RACI Matrix Template (key deliverables)

Fill one row per deliverable or milestone.

| Deliverable / Decision | PM | PdM | Eng Mgr / Tech Lead | Developers | QA/Testing | UX | Security/Compliance | SRE/Ops | Support/Success | Data Analyst | Stakeholders |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Example: Finalize milestone scope | A | R | C | C | C | C | I | I | I | C | I |
| Example: Release readiness sign-off | A | C | R | C | R | I | C | R | C | C | I |
| Example: Launch communication | C | A | I | I | I | C | I | C | R | C | C |

Legend:
- **R** Responsible: does the work
- **A** Accountable: final owner and decision maker
- **C** Consulted: gives input before decision
- **I** Informed: notified of outcome

## 2) Planning → Execution → Release Handoff Checklist

### Planning to Execution
- [ ] Scope, acceptance criteria, and Definition of Done are documented
- [ ] RACI assignments are complete for current milestone
- [ ] Dependencies and owner commitments are confirmed
- [ ] Risks have owners, mitigations, and escalation triggers
- [ ] Instrumentation and success metrics are agreed
- [ ] Security/compliance requirements are captured

### Execution to Release
- [ ] All in-scope items meet acceptance criteria and DoD
- [ ] QA/Testing sign-off is complete for critical paths
- [ ] Release notes and stakeholder communication draft are ready
- [ ] Rollback plan and on-call ownership are confirmed
- [ ] Support team has launch context and known-issue guidance
- [ ] Go/no-go decision and accountable approver are documented

### Post-release to Continuous Improvement
- [ ] Production verification checks completed
- [ ] Customer impact and support ticket trends reviewed
- [ ] KPI dashboard reflects release metrics
- [ ] Follow-up actions are assigned with owners and dates

## 3) Dependency and Decision Log Template

### Dependency Log
| ID | Dependency | Owner | Needed By | Status | Risk if Late | Escalation Path |
| --- | --- | --- | --- | --- | --- | --- |
| DEP-001 |  |  |  |  |  |  |

### Decision Log
| ID | Date | Decision | Owner (A) | Consulted | Impact | Revisit Date |
| --- | --- | --- | --- | --- | --- | --- |
| DEC-001 |  |  |  |  |  |  |

## 4) Risk Ownership Checklist

- [ ] Each active risk has one accountable owner
- [ ] Probability and impact are current (last reviewed date recorded)
- [ ] Mitigation has an explicit next action and due date
- [ ] Trigger conditions and escalation route are defined
- [ ] Security/privacy risks include Security owner review
- [ ] Operational risks include SRE/Ops readiness checks
- [ ] Customer-impact risks are reviewed with Support/Success
- [ ] Open high-severity risks are included in weekly status updates

## Where to apply these templates
- During planning: pair with `octoacme-project-planning.md`
- During execution: pair with `octoacme-execution-and-tracking.md`
- Before launch: pair with `octoacme-release-and-deployment.md`
- For role expectations: pair with `octoacme-roles-and-personas.md`
