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

### Interactions with Other Roles
- Work with **QA / Testing Leads** to understand test requirements and implement testable code
- Receive technical guidance and mentorship from **Technical Leads / Architects** on design and standards
- Collaborate with **Project Managers** on scheduling and dependency management
- Implement features defined by **Product Managers** and work toward their success metrics
- Support **DevOps / Infrastructure Engineers** by providing code optimized for CI/CD pipelines
- Receive facilitation and blocker removal support from **Scrum Masters / Agile Coaches**

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

### Interactions with Other Roles
- Define acceptance criteria for **Developers** to implement
- Work with **Technical Leads / Architects** to understand technical feasibility and trade-offs
- Collaborate with **Project Managers** on release planning and timeline management
- Review quality metrics and test coverage reports from **QA / Testing Leads**
- Align business objectives with **Executive Sponsors / Stakeholders** to ensure prioritization
- Provide feature and success criteria information to **Scrum Masters** for sprint planning
- Work with **DevOps / Infrastructure Engineers** to understand deployment and release capabilities

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

### Interactions with Other Roles
- Work with **Developers** to track progress and identify schedule risks
- Collaborate with **Product Managers** on scope management and milestone definition
- Partner with **QA / Testing Leads** to integrate quality gates into the release timeline
- Escalate technical risks identified by **Technical Leads / Architects** to stakeholders
- Coordinate with **DevOps / Infrastructure Engineers** on deployment windows and release readiness
- Support **Scrum Masters / Agile Coaches** in maintaining project cadence
- Report status and escalate blockers to **Executive Sponsors / Stakeholders**

---

## QA / Testing Lead

### Role Summary
QA and Testing Leads ensure product quality through comprehensive test planning, test execution, and acceptance validation. They collaborate with product and development teams to define quality standards and acceptance criteria, and track quality metrics throughout the project lifecycle.

### Responsibilities
- Create and maintain test plans aligned with acceptance criteria
- Define test strategies (unit, integration, end-to-end, performance, security)
- Execute or coordinate test execution and defect tracking
- Validate acceptance criteria and sign off on feature readiness
- Participate in sprint planning to understand requirements and scope
- Mentor developers on testing best practices
- Report quality metrics and trends to PM and stakeholders

### Goals
- Ensure features meet acceptance criteria before release
- Minimize critical bugs reaching production
- Provide confidence through comprehensive test coverage
- Improve team's testing maturity and practices

### Typical Communication
- Test plan and strategy documents
- Daily standup updates on test progress and blockers
- Defect reports and quality dashboards
- Acceptance sign-off comments in PRs and release gates

### Interactions with Other Roles
- Work closely with **Developers** to define testable requirements and mentor them on testing best practices
- Collaborate with **Product Managers** to validate acceptance criteria and measure quality against success metrics
- Coordinate with **Project Managers** to integrate quality gates into release timelines
- Support **Technical Leads / Architects** by testing architectural components and identifying quality risks
- Work with **DevOps / Infrastructure Engineers** to automate test execution in CI/CD pipelines
- Provide quality status updates to **Scrum Masters / Agile Coaches** for sprint retrospectives
- Report quality metrics and release readiness assessments to **Executive Sponsors / Stakeholders**

---

## Technical Lead / Architect

### Role Summary
Technical Leads guide architectural and design decisions, mentor developers, and ensure technical excellence. They balance delivery velocity with code quality, maintainability, and scalability.

### Responsibilities
- Define technical architecture and design patterns
- Conduct code reviews and provide technical guidance
- Identify technical risks and propose mitigation strategies
- Collaborate on estimating and planning technical work
- Mentor junior developers and foster technical growth
- Drive technical standards, testing, and documentation practices
- Coordinate with other technical teams on dependencies and integrations

### Goals
- Deliver maintainable, scalable, well-tested code
- Reduce technical debt and improve code quality
- Enable fast, confident deployments
- Build team capability and technical resilience

### Typical Communication
- Technical design documents and architecture review sessions
- Code review feedback and recommendations
- Risk and dependency escalations
- Technical decision logs and ADRs (Architecture Decision Records)

### Interactions with Other Roles
- Mentor and guide **Developers** on technical standards, design patterns, and best practices
- Advise **Product Managers** on technical feasibility, trade-offs, and architectural implications of features
- Escalate technical risks and dependencies to **Project Managers** for timeline impact assessment
- Work with **QA / Testing Leads** to define testable architecture and quality standards
- Collaborate with **DevOps / Infrastructure Engineers** on deployment architecture and scalability requirements
- Support **Scrum Masters / Agile Coaches** by providing technical context for sprint planning
- Communicate technical risks and mitigation plans to **Executive Sponsors / Stakeholders**

---

## DevOps / Infrastructure Engineer

### Role Summary
DevOps and Infrastructure Engineers own the deployment pipeline, infrastructure setup, and production operations. They enable teams to release reliably, monitor systems, and respond to incidents.

### Responsibilities
- Design and maintain CI/CD pipelines
- Provision and manage infrastructure (development, staging, production)
- Automate deployment and testing processes
- Monitor production systems and respond to incidents
- Implement security scanning and compliance controls
- Support incident response and post-mortems
- Document runbooks and operational procedures

### Goals
- Enable fast, safe deployments with minimal manual effort
- Ensure systems are reliable, secure, and observable
- Reduce time-to-recovery for production issues
- Continuously improve deployment and operational processes

### Typical Communication
- Deployment runbooks and CI/CD documentation
- Infrastructure and security requirements in sprint planning
- Post-deployment verification and incident reports
- On-call escalations and incident timelines

### Interactions with Other Roles
- Work with **Developers** to integrate code into CI/CD pipelines and provide deployment feedback
- Collaborate with **Product Managers** to ensure infrastructure supports feature requirements and scale
- Coordinate with **Project Managers** on deployment windows, release readiness, and go/no-go decisions
- Automate **QA / Testing Leads'** test execution and provide infrastructure for testing environments
- Support **Technical Leads / Architects** on infrastructure architecture and scalability design
- Partner with **Scrum Masters / Agile Coaches** to understand deployment dependencies for sprint planning
- Report infrastructure status, deployment readiness, and operational risks to **Executive Sponsors / Stakeholders**

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate agile ceremonies, remove blockers, and foster a culture of continuous improvement. They ensure the team follows agreed processes, maintains psychological safety, and continuously refines their delivery approach.

### Responsibilities
- Facilitate sprint ceremonies (planning, standups, reviews, retrospectives)
- Identify and help remove team blockers and impediments
- Coach the team on agile practices and continuous improvement
- Ensure Definition of Done and team agreements are followed
- Foster psychological safety and encourage team feedback
- Facilitate retrospectives and track action items
- Support team productivity and well-being

### Goals
- Smooth process execution and team cadence
- Maximize team productivity and velocity
- Foster continuous learning and improvement culture
- Maintain psychological safety and team engagement

### Typical Communication
- Sprint planning and backlog grooming sessions
- Daily standup facilitation
- Retrospective facilitation and action item tracking
- Blocker escalations and process improvement proposals

### Interactions with Other Roles
- Support **Developers** by removing impediments and facilitating collaboration
- Work with **Product Managers** on sprint planning and backlog clarity
- Coordinate with **Project Managers** on ceremony scheduling and escalation protocols
- Facilitate **QA / Testing Leads'** participation in sprint planning and retrospectives
- Help **Technical Leads / Architects** communicate technical decisions and risks to the team
- Coordinate with **DevOps / Infrastructure Engineers** on deployment readiness for sprints
- Escalate team-level blockers to **Executive Sponsors / Stakeholders** via Project Managers

---

## Executive Sponsor / Stakeholder

### Role Summary
Executive Sponsors provide strategic oversight, secure funding and resources, and ensure business alignment. They are the decision authority for go/no-go decisions and major trade-offs.

### Responsibilities
- Approve project charter and business case
- Secure budget, resources, and executive support
- Make go/no-go decisions at key gates (Initiation, Planning, Release)
- Escalate blockers and resolve business constraints
- Communicate project status to broader leadership
- Align project objectives with business strategy
- Support team during challenges and risks

### Goals
- Ensure project delivers measurable business value
- Remove organizational barriers and constraints
- Maintain alignment between project and business strategy
- Achieve project outcomes on time and within budget

### Typical Communication
- Monthly stakeholder briefings
- Gate review meetings
- Escalation and risk updates
- Go/no-go decision discussions

### Interactions with Other Roles
- Approve project charter and success metrics defined by **Product Managers**
- Make resource and prioritization decisions impacting all team members (**Developers**, **Technical Leads**, **DevOps Engineers**)
- Escalate and resolve blockers escalated by **Project Managers**
- Review quality and readiness assessments from **QA / Testing Leads** before release decisions
- Support team initiatives proposed by **Scrum Masters / Agile Coaches** for process improvement
- Provide executive air cover and resolve organizational constraints affecting the entire delivery team
- Communicate project status and business outcomes to broader leadership

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Understand cross-functional dependencies and interactions when planning projects and managing delivery.
