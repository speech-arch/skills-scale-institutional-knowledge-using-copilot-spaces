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
QA/Testing Leads own quality assurance strategy and ensure all deliverables meet acceptance criteria and quality standards. They collaborate with product, engineering, and stakeholders to define testing approaches and validate release readiness.

### Responsibilities
- Define and maintain test strategy aligned with project scope and risk profile
- Create and maintain test plans, test cases, and acceptance criteria validation
- Coordinate automated and manual testing efforts
- Participate in sprint planning to identify testability requirements early
- Conduct exploratory testing and identify edge cases and usability issues
- Validate acceptance criteria are met before code review approval
- Coordinate smoke testing and post-deployment verification
- Track and report defect trends and quality metrics
- Assist in incident triage and root cause analysis

### Goals
- Deliver high-quality, reliable features that meet user expectations
- Catch defects early to reduce production incidents
- Provide confidence in release readiness through comprehensive testing

### Typical Communication
- Sprint planning and backlog refinement (testability discussion)
- Daily standups (blockers, test progress)
- Pre-release QA sign-off meetings
- Defect reports and quality metrics in weekly syncs

### How QA/Testing Lead interacts with other roles
- **Developers**: Collaborate on testability of features and review test results
- **Product Managers**: Validate acceptance criteria and test approach alignment with user needs
- **Project Managers**: Report quality metrics and readiness status for release gates
- **Release Manager**: Coordinate pre-release testing and smoke test execution

---

## Technical Lead/Architect

### Role Summary
Technical Leads provide technical guidance, design system components, and identify technical risks. They collaborate with developers on implementation approaches, mentor junior team members, and ensure architectural consistency across the project.

### Responsibilities
- Design system architecture and technical approach for features
- Conduct technical design reviews and code reviews
- Identify technical risks and propose mitigation strategies
- Mentor and guide developers on implementation best practices
- Evaluate technology choices and trade-offs
- Ensure adherence to coding standards and architectural patterns
- Participate in estimation and planning to assess technical feasibility
- Champion technical debt reduction and refactoring initiatives

### Goals
- Ensure scalable, maintainable technical solutions
- Reduce technical risk and prevent architectural debt
- Build team capability and technical expertise
- Enable faster, more confident development

### Typical Communication
- Technical design discussions and RFC reviews
- Code review comments and architectural guidance
- One-on-ones with developers for mentoring
- Technical risk escalations to Project Manager

### How Technical Lead/Architect interacts with other roles
- **Developers**: Guide implementation, review code, and provide mentoring
- **Project Managers**: Flag technical risks and feasibility concerns
- **QA/Testing Lead**: Advise on testing strategy for complex technical components
- **Security Lead**: Collaborate on security architecture and threat mitigation

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies and coach teams on continuous improvement. They remove impediments, ensure process adherence, and help teams optimize their delivery practices.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Remove blockers and impediments that slow team progress
- Ensure adherence to agreed agile practices and ceremonies
- Coach team on agile principles and practices
- Track and report sprint metrics (velocity, burn-down, cycle time)
- Facilitate resolution of team conflicts or process issues
- Champion continuous improvement and retrospective action items
- Help Product Manager maintain and groom the backlog

### Goals
- Enable team autonomy and self-organization
- Improve team velocity and predictability over time
- Foster psychological safety and continuous learning
- Reduce waste and improve delivery flow

### Typical Communication
- Facilitation of all agile ceremonies
- One-on-ones with team members
- Process improvement discussions
- Metrics and velocity reporting

### How Scrum Master/Agile Coach interacts with other roles
- **Project Managers**: Coordinate on ceremony scheduling and escalations
- **Product Managers**: Support backlog refinement and prioritization
- **All team members**: Coach on agile practices and remove impediments
- **Stakeholders**: Communicate sprint progress and cadence

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, approve scope and timeline, and participate in key decision gates. They champion the project, secure necessary resources, and ensure alignment with organizational strategy.

### Responsibilities
- Provide business context and rationale for the project
- Approve scope, timeline, and resource allocation
- Participate in key decision gates (initiation, planning, release)
- Champion the project within the organization
- Secure and allocate necessary resources and budget
- Review and approve major milestone deliverables
- Communicate project status to executive leadership
- Provide feedback on solution alignment with business needs

### Goals
- Ensure project delivers business value and ROI
- Maintain stakeholder confidence and support
- Align project outcomes with organizational strategy
- Enable team to deliver with appropriate resources

### Typical Communication
- Milestone gate reviews and approvals
- Monthly or quarterly stakeholder updates
- Executive steering committee meetings
- Decision and approval sign-offs

### How Stakeholder/Sponsor interacts with other roles
- **Project Manager**: Primary communication partner for status and decisions
- **Product Manager**: Provide business priorities and success metrics
- **Technical Lead**: Review feasibility and resource implications
- **Release Manager**: Approve release timing and go/no-go decisions

---

## Release Manager

### Role Summary
Release Managers coordinate all activities related to planning, executing, and verifying software releases. They work across engineering, QA, operations, and stakeholders to ensure smooth, low-risk deployments.

### Responsibilities
- Plan and schedule release windows in coordination with operations and support
- Ensure all pre-release requirements are met (tests passing, security scans, release notes)
- Coordinate staging and production deployment activities
- Execute or coordinate deployment pipelines and verify post-deploy health checks
- Manage rollback decisions and procedures if issues arise
- Communicate release status to stakeholders and support teams
- Maintain release notes and known issues documentation
- Track metrics on deployment frequency, lead time, and incident rates
- Coordinate post-release verification and monitoring

### Goals
- Reduce deployment risk through standardized, repeatable processes
- Minimize time to recover from deployment issues
- Maintain predictable, reliable releases
- Improve deployment velocity over time

### Typical Communication
- Release planning meetings with PM, engineering leads, ops
- Deployment window announcements and status updates
- Post-release retrospectives and metrics reviews
- Incident response coordination during deployments

### How Release Manager interacts with other roles
- **QA/Testing Lead**: Coordinate pre-release testing and smoke tests
- **Technical Lead**: Review deployment plan and rollback procedures
- **Project Manager**: Coordinate release timing and stakeholder communication
- **Security Lead**: Ensure security validation and incident response readiness
- **Operations/Infrastructure**: Coordinate deployment execution and monitoring

---

## Security Lead

### Role Summary
Security Leads provide security guidance, conduct threat assessments, and ensure compliance. They respond to security incidents, review security-sensitive code, and champion security best practices throughout the project lifecycle.

### Responsibilities
- Provide security guidance and threat modeling during design phase
- Conduct threat assessments and identify security risks
- Review security-sensitive code and designs
- Ensure compliance with security policies and standards
- Coordinate security scanning and penetration testing
- Respond to and triage security incidents
- Advise on secure deployment and operational security practices
- Track and report security metrics and compliance status
- Mentor team on secure coding practices

### Goals
- Prevent security vulnerabilities and breaches
- Ensure compliance with regulatory and organizational requirements
- Build security awareness and best practices across the team
- Minimize security incident impact through rapid response

### Typical Communication
- Security design reviews and threat assessment meetings
- Code review comments on security-sensitive changes
- Security incident notifications and response coordination
- Security metrics and compliance reporting
- Risk escalations to Project Manager and Stakeholders

### How Security Lead interacts with other roles
- **Developers**: Review security-sensitive code and advise on secure practices
- **Technical Lead/Architect**: Collaborate on security architecture and threat models
- **Project Managers**: Escalate security risks and compliance requirements
- **QA/Testing Lead**: Coordinate security testing and validation
- **Release Manager**: Ensure security validation before deployment
- **Stakeholders**: Report security risks and compliance status

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When developing exercises, consider inter-persona scenarios that reflect real cross-functional collaboration patterns (e.g., QA coordinating with Technical Lead on testing strategy for complex features).
