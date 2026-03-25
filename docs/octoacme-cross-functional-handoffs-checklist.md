# OctoAcme — Cross-Functional Handoffs Checklist

## Purpose
Provide actionable checklists for key handoff points across the project lifecycle. Use these to reduce gaps, miscommunications, and rework when work moves between roles.

For role definitions, see [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md).

---

## Discovery → Planning Handoff

**From:** Product Manager (PdM), UX Designer  
**To:** Project Manager (PM), Developers, QA Lead, Technical Writer

### Checklist
- [ ] Problem statement and user research findings shared with the full team
- [ ] High-level solution direction and UX wireframes/prototypes reviewed
- [ ] Success metrics and acceptance criteria drafted by PdM
- [ ] Initial scope documented in the [Project One-pager / Charter](./octoacme-project-initiation.md)
- [ ] Key risks and dependencies identified and added to the [Risk Register](./octoacme-risks-and-communication.md)
- [ ] Technical Writer briefed on scope of documentation changes
- [ ] DevOps Engineer flagged for any infrastructure or environment prerequisites
- [ ] QA Lead engaged to review acceptance criteria for testability

---

## Planning → Execution Handoff

**From:** Project Manager (PM), Product Manager (PdM)  
**To:** Developers, QA Lead, UX Designer, DevOps Engineer, Technical Writer

### Checklist
- [ ] Sprint or iteration backlog finalized with acceptance criteria on each item
- [ ] Definition of Done agreed and communicated to all contributors
- [ ] Test plan or test strategy shared by QA Lead with Developers
- [ ] Design specifications and assets shared by UX Designer with Developers
- [ ] CI/CD pipeline and test environments confirmed ready by DevOps Engineer
- [ ] Technical Writer has a list of features requiring documentation updates
- [ ] Milestones, delivery dates, and dependencies communicated via the project board
- [ ] Risk Register reviewed and updated by PM

---

## Pre-Release Readiness

**From:** Developers, QA Lead, DevOps Engineer, Technical Writer  
**To:** Project Manager (PM), Product Manager (PdM), Stakeholders

### Checklist
- [ ] All acceptance criteria met and PRs merged to release branch
- [ ] CI passing: automated tests, linting, and security scans green
- [ ] QA Lead sign-off: test plan executed, critical defects resolved or risk-accepted
- [ ] Release notes drafted and reviewed (Technical Writer + PdM)
- [ ] Rollback / mitigation plan documented by DevOps Engineer
- [ ] Deployment window confirmed and stakeholders notified by PM
- [ ] Smoke tests prepared and ready to execute post-deploy
- [ ] Known issues documented in release notes by Technical Writer
- [ ] Final go/no-go confirmed by PM, PdM, and QA Lead

See also: [Release & Deployment Guide](./octoacme-release-and-deployment.md)

---

## Post-Release Verification & Comms

**From:** DevOps Engineer, QA Lead  
**To:** Project Manager (PM), Product Manager (PdM), Stakeholders, Technical Writer

### Checklist
- [ ] Post-deploy smoke tests executed and results shared with PM and QA Lead
- [ ] Production monitoring dashboards reviewed (DevOps Engineer)
- [ ] Release announced to stakeholders and support teams (PM)
- [ ] Release notes published and linked from project README or changelog (Technical Writer)
- [ ] Any post-release defects logged and triaged by QA Lead
- [ ] Rollback triggered if critical issues detected (DevOps Engineer + PM decision)
- [ ] Incident communication sent if an outage or degradation occurred (PM)
- [ ] Retrospective scheduled to capture learnings (PM)

See also: [Risk Management & Communication](./octoacme-risks-and-communication.md)
