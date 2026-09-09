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

### Interaction with Other Roles
- **With QA/Testing Lead**: Collaborate on test strategy, accept feedback on code quality and testability
- **With Technical Architect**: Follow architectural guidance and design patterns, escalate technical decisions
- **With Security Lead**: Implement security requirements, participate in security reviews
- **With Scrum Master**: Report progress and blockers in standups, participate in ceremonies

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

### Interaction with Other Roles
- **With QA/Testing Lead**: Define acceptance criteria, validate quality standards align with customer expectations
- **With Stakeholder/Executive Sponsor**: Report progress against success metrics, seek approval on scope changes
- **With Project Manager**: Collaborate on timeline and resource planning
- **With Scrum Master**: Refine backlog priorities during planning ceremonies

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

### Interaction with Other Roles
- **With Stakeholder/Executive Sponsor**: Report progress, escalate blockers, request resource allocation
- **With Product Manager**: Align on timeline and scope trade-offs
- **With Scrum Master**: Coordinate ceremony scheduling and process improvements
- **With QA/Testing Lead**: Track quality metrics and release readiness
- **With Security Lead**: Integrate security review timelines into project plan

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality strategy, test planning, and acceptance criteria validation. They work with product and engineering to define what "done" means and ensure quality standards are met before release.

### Responsibilities
- Define and maintain test plans and QA strategy
- Validate acceptance criteria with Product Managers
- Coordinate manual and automated testing
- Report quality metrics and identify test gaps
- Participate in release readiness reviews
- Define Definition of Done (DoD) in collaboration with Product and Project Managers

### Goals
- Ensure quality standards are met consistently
- Reduce defects reaching production
- Enable fast, confident deployments
- Support team velocity with efficient testing practices

### Typical Communication
- Sprint planning and refinement meetings
- Daily updates on test execution and blockers
- Quality dashboards and metrics reporting
- Release readiness assessments

### Interaction with Other Roles
- **With Developers**: Collaborate on test strategy, provide feedback on code quality and testability, participate in code reviews
- **With Product Managers**: Validate acceptance criteria clarity, confirm quality expectations
- **With Project Managers**: Report on quality status, identify quality-related risks
- **With Technical Architect**: Align testing strategy with architectural decisions
- **With Security Lead**: Execute security testing and coordinate penetration testing activities

---

## Security Lead

### Role Summary
Security Leads integrate security into all phases of project delivery. They conduct threat analysis, security reviews, and ensure compliance with organizational security standards.

### Responsibilities
- Review security requirements and threat models
- Participate in design reviews for security implications
- Execute security testing and code scanning
- Manage security incidents and vulnerability remediation
- Provide security training and awareness
- Ensure compliance with regulatory and organizational security standards

### Goals
- Minimize security vulnerabilities in production
- Enable compliance with regulatory requirements
- Foster security-first culture across the organization
- Reduce remediation time for vulnerabilities

### Typical Communication
- Security design reviews and threat modeling sessions
- Vulnerability reports and remediation tracking
- Security incident communications
- Compliance and audit documentation

### Interaction with Other Roles
- **With Developers**: Review code and architecture for security implications, provide guidance on secure coding practices
- **With Technical Architect**: Collaborate on secure system design, review technology selections for security posture
- **With QA/Testing Lead**: Coordinate security testing strategy and penetration testing
- **With Project Managers**: Escalate security risks, communicate security review timelines
- **With Stakeholder/Executive Sponsor**: Report on security posture and compliance status

---

## Technical Architect

### Role Summary
Technical Architects provide technical strategy and design guidance. They ensure architectural decisions align with long-term technical vision, scalability, and maintainability.

### Responsibilities
- Review technical designs for alignment with architecture standards
- Identify technical risks and propose mitigations
- Guide technology selection decisions
- Mentor developers on architectural patterns
- Document key design decisions and rationale
- Ensure system scalability, performance, and maintainability

### Goals
- Maintain technical excellence and system health
- Enable scalability and performance
- Reduce technical debt
- Support sustainable long-term product growth

### Typical Communication
- Technical design reviews and RFC (Request for Comments) discussions
- Architecture documentation and decision logs
- Mentoring sessions with development team
- Technology evaluation workshops

### Interaction with Other Roles
- **With Developers**: Provide guidance on design patterns, conduct design reviews, mentor on architectural best practices
- **With Product Managers**: Advise on technical feasibility and timeline implications of feature requests
- **With Project Managers**: Identify architectural risks and integration points with other systems
- **With Security Lead**: Collaborate on secure architecture design and threat modeling
- **With QA/Testing Lead**: Define test strategy for complex architectural components

---

## Stakeholder/Executive Sponsor

### Role Summary
Stakeholder/Executive Sponsors represent business interests and provide strategic direction. They approve scope, resources, and timeline while removing organizational blockers.

### Responsibilities
- Approve project charter and scope
- Allocate budget and resources
- Remove organizational and political blockers
- Provide executive visibility and status reporting
- Make trade-off decisions between scope, time, and quality
- Communicate project value to broader organization

### Goals
- Ensure project delivers business value
- Secure resources and priority for project execution
- Enable fast decision-making and escalation resolution
- Support organizational strategic objectives

### Typical Communication
- Project approval and go/no-go decisions
- Monthly or milestone-based status updates
- Executive steering committee briefings
- Budget and resource approval meetings

### Interaction with Other Roles
- **With Project Manager**: Receive regular status updates, approve scope and timeline changes, resolve blockers
- **With Product Manager**: Align on business metrics and strategic value, approve major scope trade-offs
- **With Developers and Technical Architect**: Understand technical constraints and feasibility
- **With QA/Testing Lead**: Understand quality standards and release readiness

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters/Agile Coaches facilitate agile processes and remove impediments to team productivity. They coach the team on agile practices and continuous improvement.

### Responsibilities
- Facilitate sprint ceremonies (planning, standup, review, retrospective)
- Identify and help remove blockers and impediments
- Coach team on agile practices and ceremonies
- Track metrics and highlight process improvements
- Shield team from organizational distractions
- Ensure psychological safety and team retrospective effectiveness

### Goals
- Maximize team productivity and velocity
- Foster continuous improvement culture
- Enable sustainable pace of delivery
- Improve team collaboration and communication

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospective facilitation and action item tracking
- Velocity and burn-down metrics
- Team coaching and one-on-ones

### Interaction with Other Roles
- **With Project Manager**: Coordinate ceremony scheduling, escalate blockers, provide team metrics
- **With Product Manager**: Facilitate backlog refinement, communicate team capacity constraints
- **With Developers**: Facilitate standups, remove blockers, coach on agile practices
- **With QA/Testing Lead**: Ensure testing is integrated into sprint planning and ceremonies
- **With all team members**: Foster psychological safety and continuous improvement mindset

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference interactions between roles to understand dependencies and communication patterns in project workflows.
