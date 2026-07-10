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

## Quality Assurance Lead

### Role Summary
The QA Lead owns the quality strategy and testing approach for projects. They define acceptance criteria framework, plan testing activities, and ensure that quality standards are met before release. They work closely with Product Managers to validate requirements and with Developers to design testable solutions.

### Responsibilities
- Define quality strategy and acceptance criteria framework
- Plan and oversee testing activities (unit, integration, end-to-end, security)
- Validate features meet acceptance criteria before release
- Mentor QA team members and establish testing best practices
- Identify quality risks and propose mitigations
- Collaborate with developers on test automation and CI/CD integration
- Track quality metrics and defect trends

### Goals
- Ensure high-quality releases that meet or exceed customer expectations
- Reduce post-release defects and support burden
- Continuously improve testing efficiency and coverage
- Foster a quality-first culture across the team

### Typical Communication
- Acceptance criteria definition workshops
- Test plan reviews and test case documentation
- Quality metrics reporting in weekly syncs
- Escalation of quality blockers in standups
- Test coverage and defect reports

### Interaction with Other Roles
- Works with **Developers** to design testable code and plan test automation
- Collaborates with **Product Managers** to validate acceptance criteria and feature requirements
- Coordinates with **Project Managers** on testing timelines and quality gates
- Guides the **Technical Architect** on testability implications of design decisions

---

## Technical Architect

### Role Summary
The Technical Architect defines the technical vision and direction for projects. They evaluate technical trade-offs, ensure system scalability and maintainability, and guide design decisions that have long-term implications. They act as a technical authority while fostering collaboration with developers and product leaders.

### Responsibilities
- Define system architecture and technical standards
- Review and approve technical designs for major features
- Evaluate technology choices and propose architectural improvements
- Identify technical risks and propose mitigation strategies
- Mentor developers on architecture patterns and best practices
- Ensure designs are scalable, maintainable, and aligned with long-term vision
- Collaborate with Product Managers on feasibility and trade-offs
- Document architectural decisions via Architecture Decision Records (ADRs)

### Goals
- Build systems that are scalable, maintainable, and extensible
- Make informed technical decisions that balance innovation with stability
- Reduce technical debt and architectural fragmentation
- Foster knowledge sharing and architectural consistency

### Typical Communication
- Technical design review meetings
- Architecture decision records (ADRs) and documentation
- Technical risk assessments in planning and retrospectives
- Code review commentary and architectural guidance
- Design pattern workshops and knowledge transfer sessions

### Interaction with Other Roles
- Guides **Developers** on design decisions and architectural patterns
- Works with **Product Managers** on feasibility trade-offs and technical constraints
- Collaborates with **Project Managers** on technical risk mitigation
- Partners with **QA Lead** to ensure architectures support testability
- Supports **Scrum Master** with technical impediment resolution

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, strategic alignment, and resource support for projects. They represent business interests, user needs, and organizational priorities. Sponsors hold decision-making authority for go/no-go decisions and resource allocation.

### Responsibilities
- Provide business context and strategic alignment
- Approve project charters and major scope changes
- Make go/no-go decisions at key gates
- Allocate resources and remove organizational blockers
- Review and approve release decisions
- Communicate project impact and outcomes to broader organization
- Escalate issues that require executive intervention

### Goals
- Ensure projects deliver business value and strategic objectives
- Remove organizational barriers to project success
- Make informed decisions about resource prioritization
- Maximize return on investment (ROI)

### Typical Communication
- Project initiation and approval meetings
- Monthly stakeholder status briefings
- Gate review meetings at major milestones
- Escalation communications for critical blockers
- Executive-level outcome reporting

### Interaction with Other Roles
- Approves initiatives proposed by **Product Managers**
- Receives status updates and escalations from **Project Managers**
- Makes resource allocation decisions affecting all team members
- Reviews business value delivered by the team

---

## Scrum Master / Agile Coach

### Role Summary
The Scrum Master facilitates agile processes and coaching for the team. They remove impediments to progress, coach the team on agile practices and values, and foster a culture of continuous improvement. They act as a servant leader rather than a traditional manager.

### Responsibilities
- Facilitate daily standups, planning, review, and retrospective meetings
- Remove impediments and blockers that prevent team progress
- Coach team members on agile principles and practices
- Protect the team from external disruptions
- Track velocity and health metrics
- Foster psychological safety and continuous improvement culture
- Escalate organizational impediments that block team effectiveness
- Mentor team on process improvements and time management

### Goals
- Maximize team velocity and delivery predictability
- Build a high-performing, self-organizing team
- Create a culture of continuous learning and improvement
- Remove barriers to team autonomy and empowerment

### Typical Communication
- Meeting facilitation and timekeeping
- Impediment tracking and status updates
- Retrospective action item follow-up
- Metrics and velocity reporting
- Coaching and mentoring sessions

### Interaction with Other Roles
- Supports all roles by facilitating process and removing impediments
- Works with **Project Managers** on schedule and coordination
- Coaches **Developers** on agile practices and self-organization
- Supports **Product Managers** with backlog refinement facilitation
- Partners with **QA Lead** on sprint quality metrics
- Assists **Technical Architect** in communicating technical constraints

---

## Role Interaction Matrix

| Role | Collaborates With | Key Interface | Frequency |
|------|-------------------|----------------|-----------|
| **Developer** | QA Lead, Technical Architect, PM | Code reviews, design discussions, acceptance criteria | Daily |
| **Product Manager** | Technical Architect, Stakeholder, QA Lead | Feasibility discussions, requirements refinement | 2-3x weekly |
| **Project Manager** | All roles | Status, risks, blockers, schedules | Daily/Weekly |
| **QA Lead** | Developers, Product Managers, Scrum Master | Quality gates, test plans, metrics | Daily/Weekly |
| **Technical Architect** | Developers, Product Managers, QA Lead | Design reviews, technical decisions, ADRs | Weekly |
| **Stakeholder/Sponsor** | Project Manager, Product Manager | Approvals, resource decisions, outcomes | Monthly/Gate events |
| **Scrum Master** | All roles | Facilitation, impediments, metrics | Daily |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the Role Interaction Matrix to understand cross-functional dependencies and communication patterns.
