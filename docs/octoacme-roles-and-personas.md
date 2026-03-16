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

## QA/Testing Lead

### Role Summary
QA/Testing Leads design and implement quality assurance strategies, establish testing standards, and ensure that delivered features meet acceptance criteria and quality benchmarks before release.

### Responsibilities
- Define QA strategy and testing approaches for the project
- Establish and maintain acceptance criteria standards
- Execute testing across all levels (unit, integration, end-to-end, performance)
- Track defects, manage triage, and report quality metrics
- Design test cases and automation frameworks
- Validate product readiness for release
- Conduct smoke tests and regression testing before deployments

### Goals
- Ensure all released features meet quality standards
- Identify and prevent defects before production
- Reduce post-release incidents and customer issues
- Enable fast, confident releases through automation

### Typical Communication
- Acceptance criteria review with Product Managers
- Test plan and QA approach alignment with Developers
- Quality blockers and risk escalation to Project Managers
- Release readiness sign-off before deployment
- Defect reports and test summary reports

### Interactions
- **With Developers**: Define test requirements, clarify acceptance criteria, provide feedback on testability
- **With Product Managers**: Validate feature completeness against acceptance criteria
- **With Project Managers**: Escalate quality blockers, report readiness status, coordinate testing timelines
- **With Release Managers**: Approve go/no-go for production deployment

---

## Technical Lead / Architect

### Role Summary
Technical Leads design technical solutions, review architectures for scalability and maintainability, identify technical risks, and mentor developers on best practices and design patterns.

### Responsibilities
- Design technical solutions and system architectures
- Review code and architectural decisions for scalability, security, and maintainability
- Identify and mitigate technical risks and dependencies
- Mentor developers on best practices, design patterns, and code quality
- Enforce coding standards and architectural consistency
- Participate in technical due diligence and technology selection
- Guide performance optimization and infrastructure decisions

### Goals
- Build scalable, maintainable, secure technical solutions
- Reduce technical debt and long-term maintenance costs
- Accelerate developer productivity through mentoring and standards
- Prevent costly technical mistakes and re-work

### Typical Communication
- Technical design reviews and architecture discussions
- Code review guidance and design feedback
- Risk identification during planning and execution
- Feasibility assessments with Product Managers
- Technical decisions and trade-off analysis

### Interactions
- **With Developers**: Provide design guidance, review code and architecture, mentor on best practices
- **With Product Managers**: Assess feasibility, discuss technology trade-offs, inform scope decisions
- **With Project Managers**: Escalate technical risks, provide effort estimates, identify dependencies
- **With QA/Testing Lead**: Ensure testability and quality standards are built into design

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide strategic business context and decision-making authority, approve major decisions, remove organizational barriers, and ensure business alignment throughout the project.

### Responsibilities
- Define the business case and strategic context for the project
- Approve scope, budget, timeline, and major milestones
- Make go/no-go decisions at key gates
- Remove organizational blockers and secure resources
- Provide executive visibility and escalation authority
- Align project with business strategy and priorities
- Review and approve major decisions and trade-offs

### Goals
- Ensure projects deliver strategic business value
- Maintain organizational alignment and support
- Make timely, informed decisions
- Remove obstacles to successful delivery

### Typical Communication
- Project charter and business case review
- Milestone and phase gate approvals
- Escalated risk and decision requests
- Executive status updates and reviews
- Resource and priority alignment

### Interactions
- **With Project Managers**: Primary interface for escalations, approvals, and status updates
- **With Product Managers**: Align on priorities, strategic fit, and business outcomes
- **With Development Team**: Occasional deep-dives on technical feasibility or critical decisions
- **As final decision authority**: Approve go/no-go, scope changes, and major trade-offs

---

## Release Manager / DevOps Engineer

### Role Summary
Release Managers and DevOps Engineers manage release planning and coordination, maintain CI/CD infrastructure and deployment pipelines, execute deployments with quality controls, and ensure system reliability and performance in production.

### Responsibilities
- Plan and schedule releases with clear communication and coordination
- Maintain and evolve CI/CD pipelines and automation infrastructure
- Execute deployments to staging and production environments
- Manage rollback procedures and incident response for deployments
- Establish deployment quality controls and pre/post-deployment verification
- Monitor system health and performance metrics post-deployment
- Document release procedures, runbooks, and deployment checklists
- Coordinate with on-call and incident response teams

### Goals
- Enable fast, safe, reliable deployments to production
- Minimize deployment risk and post-release incidents
- Maintain system stability and uptime
- Reduce time-to-recovery from deployment issues

### Typical Communication
- Release schedules and deployment windows
- CI/CD pipeline status and improvements
- Deployment checklists and pre-flight verification
- Post-deployment verification and smoke test results
- Incident response and rollback decisions
- Infrastructure and performance metrics

### Interactions
- **With Developers**: Collaborate on CI/CD improvements, pipeline troubleshooting, test automation
- **With Project Managers**: Coordinate release scheduling and deployment windows
- **With QA/Testing Lead**: Verify post-deployment quality and conduct release verification
- **With Technical Lead**: Optimize infrastructure, performance, and deployment automation
- **With Stakeholders**: Provide release status and downtime notifications

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
