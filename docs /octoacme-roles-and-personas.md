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

## UX Designer

### Role Summary
UX Designers research user needs, design intuitive interfaces, and advocate for user experience throughout the product lifecycle. They collaborate with Product Managers to translate business goals into user-centered solutions and with Developers to ensure design feasibility.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Collaborate with Product Managers to ensure designs meet customer needs and business requirements
- Work with Developers on design feasibility, implementation details, and responsive behavior
- Participate in design reviews and iterate based on feedback
- Document design systems, patterns, and accessibility guidelines
- Support QA in defining user-centric acceptance criteria

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Minimize user friction and support task completion
- Build and maintain design consistency across products
- Advocate for user needs in prioritization decisions

### Typical Interactions
- **With Product Managers**: Align on user personas, feature priorities, and success metrics
- **With Developers**: Discuss implementation constraints, design handoff, and responsive design
- **With QA Lead**: Define visual acceptance criteria and usability testing scenarios
- **With Project Managers**: Communicate design timelines and dependencies

### Typical Communication
- Design kick-off meetings and design review sessions
- Prototypes, wireframes, and design specifications in shared design tools
- Accessibility checklists and design system documentation
- User research summaries and usability test findings

---

## QA Lead

### Role Summary
QA Leads own the quality strategy and test planning for projects. They coordinate test execution, establish quality standards, and partner with Developers to embed testing practices throughout the delivery process.

### Responsibilities
- Define quality standards, testing strategy, and test coverage goals
- Create and maintain test plans and test cases
- Coordinate test execution (automated and manual) and defect triage
- Report on test status, quality metrics, and quality risks
- Work with Developers to ensure robust automated test practices and CI/CD integration
- Collaborate with Product Managers to clarify acceptance criteria and edge cases
- Coach team members on quality best practices
- Support release readiness validation

### Goals
- Ensure products meet acceptance criteria and quality standards before release
- Reduce defects in production and cycle time for bug fixes
- Build a culture of quality ownership across the team
- Enable rapid, confident releases through test automation

### Typical Interactions
- **With Developers**: Establish automated test practices, CI/CD quality gates, and test coverage targets
- **With Product Managers**: Clarify acceptance criteria, prioritize testing efforts, and validate feature completeness
- **With Project Managers**: Report on quality risks and test status for release readiness
- **With UX Designer**: Define visual and usability acceptance criteria and test scenarios

### Typical Communication
- Test plans and test case documentation
- Quality status reports and metrics dashboards
- Defect reports and regression test summaries
- Release readiness checklists and go/no-go recommendations

---

## DevOps Engineer

### Role Summary
DevOps Engineers manage CI/CD pipelines, infrastructure, and deployment automation. They ensure system reliability, observability, and operational efficiency, partnering with Developers to enable rapid, safe releases.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment automation
- Manage infrastructure, scaling, and resource optimization
- Implement monitoring, alerting, and observability solutions
- Support incident response and troubleshooting
- Partner with Developers on build/deploy process improvements and dependency management
- Advise on operational requirements, performance, and security
- Document runbooks, deployment procedures, and incident playbooks
- Ensure environment parity and configuration management

### Goals
- Enable fast, safe, and repeatable deployments
- Maximize system reliability and uptime
- Reduce mean time to resolution (MTTR) for incidents
- Minimize operational overhead and manual toil

### Typical Interactions
- **With Developers**: Collaborate on CI/CD improvements, dependency management, and deployment testing
- **With Project Managers**: Advise on operational risks, deployment windows, and infrastructure readiness
- **With QA Lead**: Integrate quality gates into CI/CD, support performance and load testing
- **With Product Managers**: Communicate on capacity planning and operational constraints

### Typical Communication
- CI/CD pipeline status and deployment logs
- Infrastructure and performance metrics
- Incident retrospectives and root cause analysis
- Runbooks and operational documentation

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and technical teams. They capture functional requirements, clarify business needs, and support requirement management throughout the project lifecycle.

### Responsibilities
- Gather and document functional requirements from stakeholders
- Create use cases, user stories, and acceptance criteria
- Facilitate requirements workshops and clarification sessions
- Work with Product Managers to refine backlog and ensure story clarity
- Support change management and impact analysis for scope changes
- Validate solutions against requirements during testing and delivery
- Document business rules, workflows, and data requirements
- Communicate requirements to technical teams in clear, testable language

### Goals
- Ensure business needs are correctly understood and implemented
- Minimize rework due to requirement ambiguity or misalignment
- Support efficient, requirement-driven delivery
- Enable clear communication between business and technical stakeholders

### Typical Interactions
- **With Product Managers**: Refine product vision into detailed requirements and user stories
- **With Developers**: Clarify functional requirements and support technical feasibility discussions
- **With Project Managers**: Support backlog prioritization and requirement traceability
- **With QA Lead**: Define acceptance criteria, test scenarios, and validation approaches
- **With Stakeholders**: Gather and validate business requirements and constraints

### Typical Communication
- Requirements documentation and user story specifications
- Acceptance criteria and definition of done checklists
- Requirements traceability matrices
- Change impact analysis and scope management documents

---

## Cross-Role Interaction Matrix

| Role | Primary Partners | Key Dependencies | Communication Frequency |
|------|------------------|------------------|--------------------------|
| **Developer** | QA Lead, DevOps Engineer, UX Designer | Design specs, acceptance criteria, build tools | Daily standups, PR reviews |
| **Product Manager** | Business Analyst, Project Manager, Stakeholders | Requirements, prioritization, metrics | Weekly syncs, roadmap reviews |
| **Project Manager** | All roles | Schedules, risks, dependencies, status | Weekly status, standups, retrospectives |
| **UX Designer** | Product Manager, Developers, QA Lead | User research, design systems, feasibility | Design reviews, kickoffs, feedback loops |
| **QA Lead** | Developers, Product Manager, Project Manager | Test infrastructure, acceptance criteria, release readiness | Daily standups, test reports |
| **DevOps Engineer** | Developers, QA Lead, Project Manager | Build requirements, deployment strategy, monitoring | As-needed, CI/CD reviews, incident response |
| **Business Analyst** | Product Manager, Stakeholders, All delivery teams | Requirements, business rules, acceptance criteria | Requirements workshops, clarifications, reviews |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the Cross-Role Interaction Matrix to understand dependencies and communication patterns.
- New team members should review their role definition and interaction patterns during onboarding.
