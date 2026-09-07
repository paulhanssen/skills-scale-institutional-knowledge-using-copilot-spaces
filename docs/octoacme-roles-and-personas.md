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

## Technical Leads / Architects

### Role Summary
Technical Leads define technical strategy, oversee architectural decisions, and mentor developers on complex implementations. They bridge product requirements with technical feasibility and guide the team toward scalable, maintainable solutions.

### Responsibilities
- Design technical solutions that align with product goals and organizational standards
- Review and approve architectural decisions and major design changes
- Mentor and guide developers on best practices and complex problem-solving
- Identify and escalate technical risks and propose mitigation strategies
- Ensure code quality, test coverage, and maintainability standards are met
- Collaborate with DevOps and QA on deployment and testing strategies

### Goals
- Deliver scalable, maintainable technical solutions
- Build team capability and reduce technical debt
- Enable faster delivery through clear technical direction

### Interactions with Existing Roles
- **With Developers**: Provide technical guidance, conduct design reviews, mentor on complex implementations
- **With Product Managers**: Validate technical feasibility of features, inform roadmap trade-offs with architectural considerations
- **With Project Managers**: Identify and communicate technical risks, dependencies, and timeline impacts
- **With QA / Test Engineers**: Define quality standards and testability requirements
- **With Release Managers**: Review deployment strategies and architectural impacts on rollout plans
- **With DevOps / Infrastructure Engineers**: Design solutions compatible with infrastructure capabilities and deployment strategies

### Typical Communication
- Technical design reviews and architecture discussions
- Code review guidance and mentoring sessions
- Technical risk assessments and mitigation plans
- Architecture decision records (ADRs)

---

## QA / Test Engineers

### Role Summary
QA and Test Engineers develop test strategies, ensure quality standards are met, and validate product readiness for release. They are champions of user experience and system reliability.

### Responsibilities
- Develop and maintain test plans and test cases
- Execute manual and automated testing across feature and regression scenarios
- Identify and document defects with clear reproduction steps
- Validate acceptance criteria are met before release
- Define quality metrics and monitor test coverage
- Collaborate with developers and product on quality standards

### Goals
- Ensure high-quality releases that meet user expectations
- Reduce production defects and support burden
- Provide confidence and transparency on product readiness

### Interactions with Existing Roles
- **With Developers**: Collaborate on test strategy, provide defect feedback, validate fixes
- **With Product Managers**: Ensure features meet acceptance criteria, validate user-facing quality
- **With Project Managers**: Track quality metrics, report release readiness status
- **With Technical Leads / Architects**: Align test strategies with architectural decisions and quality standards
- **With Release Managers**: Provide quality sign-off and defect trend analysis for release decisions
- **With DevOps / Infrastructure Engineers**: Test deployment procedures and infrastructure readiness

### Typical Communication
- Test plans and quality dashboards
- Defect reports and release readiness assessments
- Quality metrics and trend analysis
- Test execution reports and acceptance validation

---

## Release Managers

### Role Summary
Release Managers coordinate deployment schedules, manage release documentation, and ensure smooth production rollouts. They minimize risk and enable predictable releases while maintaining clear communication across all stakeholders.

### Responsibilities
- Plan and schedule releases aligned with business and product goals
- Coordinate with developers, QA, DevOps, and stakeholders on release timelines
- Maintain release notes, runbooks, and deployment procedures
- Manage release communications and stakeholder notifications
- Oversee deployment execution and rollback procedures
- Track release metrics and post-release health

### Goals
- Deliver releases on schedule with minimal disruption
- Maintain clear visibility and communication throughout release cycle
- Enable rapid, safe rollbacks if issues are detected

### Interactions with Existing Roles
- **With Developers**: Coordinate code freeze, manage cherry-picks, communicate deployment windows
- **With Product Managers**: Align release timing with business priorities, manage feature delivery expectations
- **With Project Managers**: Synchronize release schedules with project timelines and dependencies
- **With Technical Leads / Architects**: Review deployment strategies, validate technical readiness
- **With QA / Test Engineers**: Confirm quality gate completion, coordinate pre-release testing
- **With DevOps / Infrastructure Engineers**: Execute deployments, coordinate infrastructure changes, manage rollbacks

### Typical Communication
- Release schedules and deployment plans
- Release notes and stakeholder notifications
- Go/no-go decisions and deployment checklists
- Post-release health reports and retrospectives

---

## Stakeholders / Business Sponsors

### Role Summary
Stakeholders and Business Sponsors provide business context, approve scope changes, and ensure alignment with organizational goals. They represent customer needs and business value drivers in decision-making.

### Responsibilities
- Define business goals and success criteria for projects
- Approve scope changes and prioritize trade-offs
- Provide business context and market insights
- Review project progress against business objectives
- Approve budget, resource allocation, and timeline decisions
- Communicate project status to executive leadership

### Goals
- Ensure projects deliver business value and ROI
- Maintain alignment between delivery and organizational strategy
- Manage stakeholder expectations and governance

### Interactions with Existing Roles
- **With Product Managers**: Provide business requirements and prioritization guidance
- **With Project Managers**: Approve scope, timeline, and resource decisions; receive status updates
- **With Developers**: Communicate business context in sprint reviews
- **With Technical Leads / Architects**: Understand technical trade-offs and architectural implications
- **With QA / Test Engineers**: Approve release readiness based on quality metrics
- **With Release Managers**: Authorize release decisions and manage executive communications

### Typical Communication
- Executive steering committee meetings
- Business requirements and success metrics
- Approval of scope changes and trade-off decisions
- Project health reports and risk escalations
- Post-release business impact reviews

---

## DevOps / Infrastructure Engineers

### Role Summary
DevOps and Infrastructure Engineers manage deployment infrastructure, monitor system health, and support operational excellence. They enable reliable, scalable delivery and ensure production environments are secure, performant, and maintainable.

### Responsibilities
- Design and maintain deployment infrastructure and pipelines
- Manage environments (development, staging, production)
- Monitor system health, performance, and security
- Automate deployment, testing, and operations workflows
- Respond to incidents and support troubleshooting
- Ensure infrastructure scalability and reliability

### Goals
- Enable fast, reliable deployments with minimal manual effort
- Maintain high system availability and performance
- Reduce operational overhead and incident response time

### Interactions with Existing Roles
- **With Developers**: Support local development environment setup, manage deployment pipelines, assist in debugging production issues
- **With Technical Leads / Architects**: Design infrastructure supporting architectural requirements, ensure deployment compatibility
- **With QA / Test Engineers**: Provision test environments, support test automation infrastructure
- **With Release Managers**: Execute deployments, coordinate infrastructure changes with release schedules
- **With Project Managers**: Communicate infrastructure constraints and dependencies affecting timelines

### Typical Communication
- Infrastructure design and deployment pipeline documentation
- System health dashboards and incident reports
- Deployment runbooks and operational procedures
- Capacity planning and infrastructure roadmaps

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the "Interactions with Existing Roles" sections to understand cross-functional collaboration patterns.
