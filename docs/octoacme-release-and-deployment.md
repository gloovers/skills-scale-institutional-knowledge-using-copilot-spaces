# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted by Technical Writer and reviewed with PdM
- Rollback / mitigation plan documented (owned by DevOps Engineer)
- Smoke tests prepared by QA Lead

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - DevOps Engineer triggers incident response and notifies on-call
  - Rollback to last known-good release if necessary (owned by DevOps Engineer)
  - Triage root cause and capture action items
  - PM communicates incident status to stakeholders

For a full pre-release and post-release verification checklist, see the [Cross-Functional Handoffs Checklist](./octoacme-cross-functional-handoffs-checklist.md).

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
