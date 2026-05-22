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

## QA / Testing

### Role Summary
QA / Testing contributors validate that features meet acceptance criteria and quality standards before they reach production. They act as a quality gate and customer-experience advocate throughout the delivery lifecycle.

### Responsibilities
- Author and execute test plans, test cases, and acceptance tests
- Run regression, integration, and exploratory testing
- Identify, document, and track defects to resolution
- Validate Definition of Done criteria for each increment
- Contribute to CI test coverage and automated test suites

### Goals
- Prevent defects from reaching production
- Ensure features behave as specified and provide a good user experience
- Reduce rework by surfacing quality issues early

### Typical Communication
- Sprint planning and backlog refinement (to understand scope and acceptance criteria)
- Daily standups and defect triage sessions
- Test summary reports and release sign-off comments

### Collaboration Points
- **Developers**: partners closely on acceptance criteria, test coverage, and defect remediation.
- **Product Managers**: aligns test cases to success metrics and user stories.
- **Release Manager**: provides formal sign-off before releases proceed.

---

## UX Designer

### Role Summary
UX Designers advocate for end-user experience by conducting research, producing wireframes and prototypes, and ensuring that design decisions translate customer needs into usable, accessible product interactions.

### Responsibilities
- Conduct user research, usability studies, and interviews to gather insights
- Produce wireframes, prototypes, and design specifications for new features
- Define and maintain UX guidelines and design systems
- Review implemented features for design fidelity and accessibility
- Collaborate with Product Managers on problem framing and solution validation

### Goals
- Deliver intuitive, accessible, and delightful product experiences
- Reduce usability-driven defects and post-release rework
- Ensure customer value is reflected in workflow and interaction design

### Typical Communication
- Design reviews and critique sessions with PdM and Developers
- User research readouts and usability reports
- Annotated design specs and prototypes in design tools

### Collaboration Points
- **Product Managers**: partners on problem definition, user research, and solution validation.
- **Developers**: provides design specs and answers implementation questions during build.
- **QA / Testing**: reviews implemented UI against acceptance criteria and design intent.
- **Customer Success**: incorporates real user feedback into design iterations.

---

## Data Analyst

### Role Summary
Data Analysts identify key metrics, build dashboards, and surface actionable insights to inform product and delivery decisions. They support a data-informed culture across the team.

### Responsibilities
- Define, instrument, and monitor product and delivery KPIs
- Build and maintain dashboards for feature adoption, performance, and quality
- Analyze release impact and provide post-launch measurement reports
- Support retrospective discussions with data-backed observations
- Identify trends, anomalies, and opportunities through quantitative analysis

### Goals
- Enable data-driven prioritization and decision making
- Provide clear, timely insight into product performance and customer behavior
- Reduce reliance on assumptions by grounding discussions in evidence

### Typical Communication
- Planning and retrospective sessions (presenting metrics and insights)
- Weekly/monthly dashboard updates and metric reviews
- Ad-hoc analysis reports for key decisions or incidents

### Collaboration Points
- **Product Managers**: partners on defining success metrics and measuring roadmap impact.
- **Project Managers**: supplies delivery metrics (velocity, cycle time, quality trends) for status reporting.
- **Developers**: coordinates on instrumentation and data pipeline requirements.
- **Customer Success**: correlates usage data with customer feedback to surface patterns.

---

## Customer Success

### Role Summary
Customer Success acts as the voice of the end user, bridging customer feedback with the delivery team to ensure releases meet real user needs and that customers are well supported through onboarding and adoption.

### Responsibilities
- Collect, synthesize, and prioritize customer feedback for the product team
- Support onboarding documentation, training materials, and release communications
- Monitor customer health, adoption, and satisfaction metrics post-release
- Surface emerging customer issues and escalate critical blockers to Product and Engineering
- Collaborate with QA on user-acceptance scenarios derived from real-world use cases

### Goals
- Ensure customers successfully adopt and gain value from new features
- Reduce support volume by improving documentation and onboarding
- Represent customer needs clearly in planning and prioritization conversations

### Typical Communication
- Regular feedback syncs with Product Managers
- Release communication and customer-facing release notes
- Support ticket trend summaries and escalation reports

### Collaboration Points
- **Product Managers**: shares customer feedback to inform roadmap priorities and acceptance criteria.
- **Developers**: escalates critical user-facing bugs and validates fixes with real user context.
- **UX Designer**: provides qualitative feedback from customers to inform design decisions.
- **Data Analyst**: aligns qualitative customer signals with quantitative adoption data.
- **Release Manager**: coordinates customer-facing release notes and communication timing.

---

## System Architect

### Role Summary
System Architects guide high-level architecture decisions, ensure the platform is scalable and reliable, and review significant technical proposals. They surface integration risks early and help the team balance speed with sound engineering practices.

### Responsibilities
- Define and maintain architectural standards, patterns, and guidelines
- Review major technical proposals, ADRs (Architecture Decision Records), and design docs
- Identify and communicate cross-service integration risks and dependencies
- Guide technology selection and platform evolution decisions
- Support capacity planning and non-functional requirements (performance, security, reliability)

### Goals
- Ensure the product platform scales sustainably as the team grows
- Reduce architectural debt and integration surprises
- Provide clear, documented technical guidance that empowers developer autonomy

### Typical Communication
- Architecture review sessions and design critiques
- Architecture Decision Records (ADRs) and technical design docs
- Risk and dependency briefings during planning and release gates

### Collaboration Points
- **Developers**: provides architectural guidance, reviews designs, and unblocks technical decisions.
- **Project Managers**: surfaces technical risks and dependencies that affect delivery timelines.
- **Product Managers**: advises on the technical feasibility and cost of proposed features.
- **Release Manager**: reviews deployment architecture changes and infrastructure impact before releases.

---

## Release Manager

### Role Summary
Release Managers coordinate deployment logistics, enforce release readiness standards, and ensure stakeholders are informed before and after releases. They shield delivery teams from last-minute escalations and act as the final gate before production deployments.

### Responsibilities
- Maintain and enforce the deployment checklist and release readiness criteria
- Coordinate release scheduling across delivery teams, platform, and stakeholders
- Prepare and distribute release notes and deployment communications
- Monitor post-deployment stability and coordinate rollback if necessary
- Track release retrospective action items related to deployment processes

### Goals
- Deliver predictable, low-risk releases with clear stakeholder communication
- Reduce production incidents caused by incomplete deployment preparation
- Continuously improve the release process based on retrospective feedback

### Typical Communication
- Pre-release readiness reviews and go/no-go checkpoints
- Release notes, deployment summaries, and stakeholder notifications
- Post-deploy incident and stability reports

### Collaboration Points
- **Project Managers**: aligns release schedule with project milestones and stakeholder commitments.
- **Developers**: confirms build artifacts, deployment steps, and rollback procedures are ready.
- **QA / Testing**: receives formal release sign-off before proceeding to production.
- **System Architect**: reviews infrastructure or architecture changes included in the release.
- **Customer Success**: coordinates customer-facing communication timing and content.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

