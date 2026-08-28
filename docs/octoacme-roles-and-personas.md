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

## Stakeholder / Executive Sponsor

### Role Summary
Stakeholders and Executive Sponsors provide strategic vision, set business priorities, and own escalation authority for projects. They ensure projects align with organizational goals and have the resources and support needed.

### Responsibilities
- Define and approve business objectives and success metrics
- Provide escalation path for high-impact decisions and blockers
- Ensure adequate budget and resource allocation
- Champion the project within the organization
- Review milestones and approve major scope changes
- Set organizational priorities and strategic context for projects

### Interaction with Other Roles
- **With Product Manager**: Aligns on strategic priorities, approves success metrics, and ensures business alignment
- **With Project Manager**: Reviews milestone progress, approves major scope changes, and provides escalation authority for blockers
- **With Development Team**: Provides business context and strategic rationale for decisions; communicates organizational priorities
- **With QA/Testing Lead**: Reviews quality standards and acceptance; approves release timelines
- **With Security Officer**: Approves risk tolerance and compliance investments

### Goals
- Ensure project delivers measurable business value
- Maintain stakeholder confidence and organizational alignment
- Enable rapid escalation resolution and decision-making
- Align project outcomes with organizational strategy

### Typical Communication
- Monthly or milestone-based status reviews
- Escalation-triggered urgent meetings
- Strategic planning and roadmap alignment sessions
- Executive briefings and board updates

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own the quality strategy and acceptance criteria validation. They ensure products meet quality standards and acceptance criteria before release.

### Responsibilities
- Define testing strategy (unit, integration, E2E, performance, security)
- Create and maintain test plans aligned with acceptance criteria
- Lead manual QA and acceptance testing
- Identify and track quality metrics and coverage
- Collaborate with developers on testability and test automation
- Escalate quality risks and blockers
- Establish quality standards and testing best practices

### Interaction with Other Roles
- **With Developers**: Pair on test automation, discuss testability of designs, collaborate on test strategy
- **With Product Manager**: Validate acceptance criteria are testable and measurable; ensure QA perspective in feature planning
- **With Project Manager**: Report quality metrics, flag risks, communicate testing timelines and dependencies
- **With Stakeholders**: Brief on quality metrics and release readiness; escalate critical quality issues
- **With Security Officer**: Coordinate security testing and compliance validation in QA process

### Goals
- Deliver high-quality products that meet acceptance criteria
- Enable fast, reliable releases through test automation
- Identify quality risks early in the project lifecycle
- Establish measurable quality metrics and continuous improvement

### Typical Communication
- Daily standups with development team
- Weekly quality metrics reviews
- Quality and test plan discussions during backlog refinement
- Pre-release QA sign-off meetings

---

## Security / Compliance Officer

### Role Summary
Security/Compliance Officers ensure projects meet security requirements, regulatory compliance, and organizational risk standards. They embed security into the project lifecycle from initiation through release.

### Responsibilities
- Define security and compliance requirements for projects
- Review architectural and design decisions for security implications
- Conduct or coordinate security assessments and testing
- Ensure incident response and escalation procedures are in place
- Track and mitigate security risks in the risk register
- Provide security training and guidance to the team
- Approve security testing and validation approaches
- Manage security dependencies and third-party assessments

### Interaction with Other Roles
- **With Developers**: Review code and design for security risks; provide security guidance and best practices; approve security approaches
- **With Technical Architect**: Collaborate on secure architecture decisions; review design trade-offs; ensure secure-by-default patterns
- **With Project Manager**: Track compliance and security risks; escalate issues; ensure security is built into timeline and dependencies
- **With QA/Testing Lead**: Coordinate security testing; define security test cases; validate compliance in acceptance testing
- **With Product Manager**: Ensure security requirements are captured in acceptance criteria; communicate security constraints

### Goals
- Ensure projects are secure and compliant with regulations
- Minimize security vulnerabilities and compliance breaches
- Enable secure, confidence-inspiring releases
- Build security expertise and awareness across the team

### Typical Communication
- Security design reviews during planning
- Weekly security risk assessments
- Code review feedback on security topics
- Pre-release security sign-off
- Incident response and escalation meetings

---

## Technical Architect

### Role Summary
Technical Architects define the technical vision and strategy for projects. They evaluate architectural trade-offs and ensure systems are scalable, maintainable, and aligned with organizational standards.

### Responsibilities
- Define technical architecture and design patterns
- Evaluate technical trade-offs and alternatives
- Review system design for scalability and maintainability
- Identify architectural risks and dependencies
- Guide design discussions and technical decisions
- Collaborate on technology choices and infrastructure strategy
- Ensure alignment with organizational technical standards
- Mentor developers on architectural patterns and best practices

### Interaction with Other Roles
- **With Developers**: Provide technical vision and guidance; review architectural decisions; mentor on design patterns and best practices
- **With Security Officer**: Collaborate on secure architecture; review security implications of technical decisions; ensure defense-in-depth
- **With DevOps/Release Engineer**: Align on infrastructure and deployment strategy; ensure architectural decisions support CI/CD pipeline
- **With Project Manager**: Communicate architectural risks and timeline impacts; identify technical dependencies and constraints
- **With QA/Testing Lead**: Discuss architectural implications for testing; ensure testability in design
- **With Product Manager**: Explain technical trade-offs affecting features and timelines

### Goals
- Deliver architecturally sound, scalable systems
- Reduce technical debt and future rework
- Enable long-term maintainability and evolution
- Build technical excellence and consistency across projects

### Typical Communication
- Architectural design reviews and discussions
- Technical decision documentation
- Design mentoring and code review feedback
- Cross-project architecture alignment meetings
- Risk and dependency discussions in planning

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate agile ceremonies, remove blockers, and coach teams on agile practices and continuous improvement. They enable high-performing, self-organizing teams.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Remove impediments and escalate blockers
- Coach team on agile practices and ceremonies
- Track team velocity and burndown
- Foster psychological safety and continuous improvement
- Protect team focus from external distractions
- Track action items from retrospectives
- Help teams improve velocity and predictability

### Interaction with Other Roles
- **With Developers**: Facilitate standups, remove blockers, support continuous improvement, coach on agile practices
- **With Project Manager**: Coordinate scheduling, provide team metrics and velocity data, identify risks early
- **With Product Manager**: Facilitate backlog refinement, story sizing, and product discovery sessions
- **With Stakeholders**: Communicate team capacity and velocity; manage expectations on delivery timelines
- **With QA/Testing Lead**: Ensure testing is integrated into sprint planning and ceremonies

### Goals
- Enable high-performing, self-organizing teams
- Maximize team velocity and delivery predictability
- Foster continuous improvement and learning culture
- Reduce cycle time and impediments

### Typical Communication
- Daily standups (15 minutes)
- Sprint planning and refinement sessions
- Retrospective facilitation and action tracking
- One-on-one coaching and feedback
- Metrics and velocity reporting

---

## DevOps / Release Engineer

### Role Summary
DevOps and Release Engineers manage CI/CD pipelines, deployment infrastructure, and release automation. They enable fast, reliable, and secure releases to production.

### Responsibilities
- Design and maintain CI/CD pipelines and automation
- Manage deployment infrastructure and environments (dev, staging, production)
- Automate testing, security scanning, and deployment processes
- Implement monitoring, logging, and observability
- Coordinate and execute production releases
- Manage rollback and incident response procedures
- Ensure infrastructure scalability and reliability
- Document deployment procedures and runbooks

### Interaction with Other Roles
- **With Developers**: Support code quality checks, testing automation, provide feedback on deployability; review deployment needs
- **With Technical Architect**: Align on infrastructure and deployment strategy; design for scalability and reliability; implement architectural patterns
- **With Project Manager**: Communicate release readiness and deployment timelines; identify infrastructure risks and dependencies
- **With Security Officer**: Implement security scanning and compliance checks in pipelines; manage secrets and access control
- **With QA/Testing Lead**: Support test automation infrastructure; coordinate smoke tests and post-deployment verification
- **With Stakeholders**: Communicate deployment windows and status; report on system reliability and performance

### Goals
- Enable fast, reliable, automated releases
- Minimize deployment risks and incidents
- Provide visibility into system health and performance
- Build a culture of infrastructure as code and continuous delivery

### Typical Communication
- Release planning and coordination meetings
- Deployment status and incident communications
- Infrastructure and pipeline reviews
- Performance and reliability metrics reporting
- On-call escalation and incident response

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Understand typical communication patterns and dependencies across roles for better project coordination.
- Reference interaction patterns when designing cross-functional workflows and decision-making processes.
