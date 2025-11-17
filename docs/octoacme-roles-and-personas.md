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

## QA Engineers

### Role Summary
QA Engineers validate product quality, ensure acceptance criteria are met, and help teams prevent defects before production. They design test strategies, execute manual and automated tests, and report issues.

### Responsibilities
- Create test plans and test cases based on requirements
- Execute manual and automated tests
- Report bugs with clear reproduction steps
- Validate fixes and verify acceptance criteria
- Contribute to test automation and CI pipeline

### Goals
- Ensure high product quality and reliability
- Catch defects early in the development cycle
- Improve test coverage and automation

### Typical Communication
- Bug reports and test results
- Test plan reviews with PM and developers
- Daily standups and sprint planning
- Sign-off on release readiness

### Interactions with Other Roles
- **Developers**: Collaborate on testability, review test results, clarify bug reports
- **Product Manager**: Validate acceptance criteria, provide quality feedback
- **Project Manager**: Report on testing status, identify quality risks
- **Release Manager**: Provide test sign-off for releases

### Lifecycle Involvement
Most involved during Execution and Release phases; participates in Planning for test strategy.

---

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and coach teams on agile practices. They ensure the team follows agreed processes and continuously improves.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Remove blockers and impediments for the team
- Coach team members on agile and scrum practices
- Protect the team from external disruptions
- Track team metrics and identify improvement opportunities

### Goals
- Maximize team productivity and velocity
- Foster a culture of continuous improvement
- Maintain healthy team dynamics and collaboration

### Typical Communication
- Facilitation of all scrum ceremonies
- Blocker escalation and resolution tracking
- Retrospective insights and action items
- Team health metrics and observations

### Interactions with Other Roles
- **Developers**: Remove impediments, facilitate collaboration
- **Product Manager**: Ensure backlog clarity and priority alignment
- **Project Manager**: Coordinate on dependencies and timeline risks
- **QA Engineers**: Support testing processes and quality gates
- **Stakeholders**: Shield team from unplanned requests

### Lifecycle Involvement
Most involved during Execution phase; facilitates ceremonies throughout all phases.

---

## UX Designer

### Role Summary
UX Designers research user needs, design intuitive interfaces, and ensure products are usable and delightful. They create wireframes, prototypes, and design systems that guide implementation.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and prototypes
- Design user flows and interaction patterns
- Maintain design system and style guides
- Collaborate with developers on implementation feasibility

### Goals
- Deliver intuitive, accessible user experiences
- Validate designs through user feedback and testing
- Ensure design consistency across products

### Typical Communication
- Design reviews and critiques
- User research findings and insights
- Design specs and handoff documentation
- Usability testing results

### Interactions with Other Roles
- **Product Manager**: Align on user needs and feature priorities
- **Developers**: Collaborate on implementation and feasibility
- **QA Engineers**: Define acceptance criteria for UI/UX
- **Business Analyst**: Incorporate user workflows into requirements
- **Stakeholders**: Present design concepts and gather feedback

### Lifecycle Involvement
Most involved during Planning and early Execution; provides design guidance throughout.

---

## Business Analyst

### Role Summary
Business Analysts bridge business needs and technical solutions. They gather requirements, analyze processes, and ensure solutions align with business objectives and user needs.

### Responsibilities
- Elicit and document business requirements
- Analyze current processes and identify improvements
- Create functional specifications and user stories
- Validate solutions meet business needs
- Support data analysis and reporting requirements

### Goals
- Ensure clear, actionable requirements
- Align technical solutions with business value
- Reduce ambiguity and rework

### Typical Communication
- Requirements documents and user stories
- Process flow diagrams and analysis
- Stakeholder interviews and workshops
- Requirements clarification sessions

### Interactions with Other Roles
- **Product Manager**: Collaborate on requirements and priorities
- **Project Manager**: Define scope and acceptance criteria
- **Developers**: Clarify requirements and answer questions
- **UX Designer**: Align on user workflows and needs
- **QA Engineers**: Define test scenarios and success criteria
- **Stakeholders**: Gather requirements and validate solutions

### Lifecycle Involvement
Most involved during Initiation and Planning phases; supports clarifications during Execution.

---

## Release Manager

### Role Summary
Release Managers coordinate release activities, ensure readiness criteria are met, and orchestrate deployments. They manage release schedules, dependencies, and communication to ensure smooth production rollouts.

### Responsibilities
- Plan and coordinate release schedules
- Verify release readiness (tests, documentation, approvals)
- Manage deployment process and rollback plans
- Coordinate cross-team dependencies for releases
- Track release metrics and post-release health

### Goals
- Deliver releases on time with minimal risk
- Ensure zero-downtime deployments when possible
- Maintain clear release communication

### Typical Communication
- Release schedules and go/no-go decisions
- Release notes and deployment plans
- Post-release status reports
- Coordination with support and operations teams

### Interactions with Other Roles
- **Project Manager**: Coordinate release timing and scope
- **Developers**: Verify code freeze and deployment readiness
- **QA Engineers**: Confirm test completion and sign-off
- **Support Lead**: Hand off release notes and known issues
- **Scrum Master**: Align release schedule with sprint cadence
- **Stakeholders**: Communicate release plans and changes

### Lifecycle Involvement
Most involved during Release phase; begins coordination during late Execution.

---

## Support Lead

### Role Summary
Support Leads manage customer-facing support operations, triage incidents, and coordinate post-release monitoring. They ensure issues are resolved quickly and feedback reaches product teams.

### Responsibilities
- Triage and prioritize support tickets
- Coordinate incident response and escalations
- Monitor post-release product health
- Gather and communicate customer feedback
- Maintain support documentation and runbooks

### Goals
- Minimize customer impact and resolution time
- Provide actionable feedback to product teams
- Build knowledge base for self-service support

### Typical Communication
- Incident reports and escalations
- Customer feedback summaries
- Support metrics and trends
- Post-release monitoring reports

### Interactions with Other Roles
- **Release Manager**: Receive handoff and release notes
- **Developers**: Escalate bugs and request hotfixes
- **Product Manager**: Share customer feedback and pain points
- **QA Engineers**: Report production issues for regression testing
- **Stakeholders**: Communicate customer impact and satisfaction

### Lifecycle Involvement
Most involved during Release and post-release monitoring; provides feedback during Planning.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

