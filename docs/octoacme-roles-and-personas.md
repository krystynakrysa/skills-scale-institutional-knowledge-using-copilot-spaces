# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. It covers all roles referenced across the project lifecycle — from initiation through retrospective — to ensure clarity, accountability, and consistent collaboration.

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

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies, remove team impediments, and protect the team's ability to deliver. They serve as coaches for continuous improvement and ensure the team adheres to agreed agile practices.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Identify and remove blockers and cross-team dependencies
- Shield the team from unplanned interruptions and scope creep during a sprint
- Coach the team on agile principles and promote continuous improvement
- Track team velocity and flag delivery risks to the Project Manager

### Goals
- Maintain a healthy, productive team rhythm
- Reduce impediments and increase predictable delivery
- Foster a culture of transparency and continuous improvement

### Typical Communication
- Daily standups and sprint ceremonies
- Impediment logs and retrospective action items
- Coordination with Project Manager on risks and resource constraints

### Interactions with Other Roles
- **Project Manager:** Collaborates on risk escalation, resource planning, and milestone tracking; Scrum Master focuses on team-level health while PM focuses on cross-team coordination.
- **Product Manager:** Coordinates backlog readiness and ensures stories are well-defined before sprint planning.
- **Developers:** Shields them from distractions, facilitates their retrospective input, and removes blockers they surface in standups.
- **QA Lead:** Ensures QA activities are accounted for in sprint capacity and Definition of Done.
- **Business Analyst:** Confirms acceptance criteria are clear before sprint commitment.

---

## UX Designer

### Role Summary
UX Designers advocate for user experience throughout the product lifecycle. They conduct research, create designs, and validate that solutions meet user needs before and during development.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define interaction patterns and contribute to the design system
- Collaborate on acceptance criteria with the Product Manager
- Work with Developers to ensure implementation matches design intent
- Participate in sprint reviews to validate UX quality of delivered features

### Goals
- Deliver intuitive, accessible, and user-validated experiences
- Reduce rework caused by late-stage UX issues
- Align design work with product roadmap and technical constraints

### Typical Communication
- Design reviews and prototype walkthroughs
- Usability test reports and design specifications
- Async feedback on pull requests touching UI components

### Interactions with Other Roles
- **Product Manager:** Collaborates on problem framing, success metrics, and feature prioritization; UX Designer provides user research to support data-driven decisions.
- **Developers:** Provides design specifications, reviews implemented UI, and clarifies intent during development; participates in design-in-code reviews.
- **Business Analyst:** Aligns on requirements to ensure designs address business and user needs.
- **QA Lead:** Coordinates on UX acceptance criteria and participates in usability-focused test scenarios.
- **Stakeholders:** Presents design concepts and user research findings to gather feedback and alignment.

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business needs and technical solutions. They elicit and document requirements, model processes, and validate that delivered solutions meet the intended business outcomes.

### Responsibilities
- Gather, document, and validate functional and non-functional requirements
- Facilitate requirements workshops with stakeholders and subject matter experts
- Map current and future-state business processes
- Translate business needs into user stories and acceptance criteria
- Support User Acceptance Testing (UAT) by defining test scenarios
- Maintain the requirements traceability matrix

### Goals
- Ensure delivered solutions address real business problems
- Reduce ambiguity and misalignment before development begins
- Validate that acceptance criteria are testable and agreed upon

### Typical Communication
- Requirements workshops and stakeholder interviews
- User stories, acceptance criteria, and process diagrams
- UAT plans and sign-off documentation

### Interactions with Other Roles
- **Product Manager:** Supports backlog refinement by detailing requirements and translating strategic priorities into actionable stories.
- **Project Manager:** Provides requirements status and flags scope changes that affect timeline or resources.
- **Developers:** Clarifies requirements ambiguity during sprint execution; reviews implemented features against acceptance criteria.
- **QA Lead:** Collaborates on test scenarios derived from acceptance criteria; supports UAT coordination.
- **UX Designer:** Aligns on user needs to ensure requirements reflect both business and user-experience goals.
- **Stakeholders:** Conducts interviews, facilitates workshops, and validates that requirements accurately reflect business intent.

---

## QA Lead

### Role Summary
The QA Lead owns the overall quality strategy and testing practices for the project. They define standards, coordinate testing activities across the team, and act as the final quality gate before releases.

### Responsibilities
- Define and maintain the test strategy (unit, integration, end-to-end, regression, performance)
- Coordinate manual and automated testing activities across the team
- Review and approve acceptance criteria for testability
- Maintain defect tracking, triage, and resolution processes
- Enforce Definition of Done quality standards in collaboration with the Scrum Master
- Validate release readiness and sign off on pre-release checklists
- Lead root-cause analysis for critical defects

### Goals
- Deliver high-confidence releases with minimal post-release defects
- Shift quality left by embedding testing earlier in the development process
- Build and maintain automated test coverage to accelerate delivery

### Typical Communication
- Test plans, defect reports, and release quality summaries
- Sprint ceremony participation (planning, review, retrospective)
- Async review of PR test coverage and CI results

### Interactions with Other Roles
- **Project Manager:** Provides testing status, flags quality risks, and reports on release readiness.
- **Product Manager:** Validates acceptance criteria are testable and aligned with quality expectations.
- **Developers:** Collaborates on test automation, code coverage standards, and defect resolution.
- **Scrum Master:** Ensures testing is accounted for in sprint capacity and that quality blockers are escalated promptly.
- **Business Analyst:** Reviews acceptance criteria together to define test scenarios; coordinates UAT.
- **Stakeholders:** Reports quality metrics and communicates release readiness in stakeholder reviews.

---

## Stakeholders

### Role Summary
Stakeholders are individuals or groups with a vested interest in project outcomes. They provide strategic inputs, approve key decisions, and receive regular communication on project progress.

### Responsibilities
- Provide business context, priorities, and approval at key decision gates
- Review and sign off on project scope, requirements, and deliverables
- Escalate business-critical constraints or changes to the Project Manager
- Participate in milestone demos and User Acceptance Testing as appropriate
- Champion the project within their organizational area

### Goals
- Ensure the project delivers intended business value
- Stay informed of progress, risks, and decisions that affect their area
- Provide timely approvals to avoid delivery delays

### Typical Communication
- Monthly or milestone-based status updates
- Milestone demos and UAT sessions
- Decision-gate reviews (initiation, release sign-off)

### Interactions with Other Roles
- **Project Manager:** Primary point of contact for status updates, escalations, and decision-gate approvals.
- **Product Manager:** Collaborates on roadmap priorities, feature trade-offs, and success metrics.
- **Business Analyst:** Participates in requirements workshops and validates that documented requirements reflect business needs.
- **UX Designer:** Reviews design concepts and provides feedback on user-facing features.
- **QA Lead:** Receives release quality summaries and participates in UAT sign-off.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [`octoacme-raci-matrix.md`](octoacme-raci-matrix.md) for a cross-role responsibility matrix across the project lifecycle.
- See [`octoacme-role-handoffs-checklist.md`](octoacme-role-handoffs-checklist.md) for handoff checkpoints between lifecycle phases.

