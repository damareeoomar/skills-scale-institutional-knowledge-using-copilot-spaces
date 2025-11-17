# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability. The Release Manager coordinates all release activities and ensures readiness criteria are met.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Release Manager Responsibilities
- Coordinate release schedule and communicate to all stakeholders
- Verify all pre-release requirements are met
- Facilitate go/no-go decision with PM, QA, and technical leads
- Execute deployment checklist and monitor deployment health
- Coordinate handoff to Support Lead with release notes and known issues
- Track release metrics and retrospective items

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- QA sign-off on test completion
- Release notes drafted (see template below)
- Rollback / mitigation plan documented
- Smoke tests prepared
- Deployment window scheduled and communicated
- Support team briefed on changes and known issues

## Deployment Checklist
Release Manager uses this checklist for every deployment:
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] All stakeholders notified of deployment
- [ ] Deploy to staging and run smoke tests
- [ ] QA sign-off received
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Monitor error rates and key metrics for 30 minutes
- [ ] Announce release to stakeholders and support
- [ ] Hand off to Support Lead with release notes and escalation contact

For a comprehensive, reusable checklist, see [release-checklist.md](release-checklist.md).

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Release Manager coordinates with technical leads on rollback decision
  - Rollback to last known-good release if necessary
  - Support Lead communicates impact to affected customers
  - Triage root cause and capture action items

## Support Handoff
After successful deployment, Release Manager hands off to Support Lead:
- Share release notes and deployment summary
- Review known issues and workarounds
- Provide escalation contacts for engineering team
- Brief on monitoring dashboards and key metrics to watch
- Set expectations for post-release verification period

Support Lead responsibilities post-handoff:
- Monitor support channels for release-related issues
- Triage and escalate incidents per severity
- Track customer feedback and report trends to Product team
- Verify post-release success criteria (error rates, performance, adoption)

## Release Notes Template
- Release name / number:
- Date:
- Owner: (Release Manager name)
- Support contact: (Support Lead or escalation channel)
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
