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

## UX/UI Designer

### Role Summary
UX/UI Designers shape the user experience and interface design of OctoAcme products. They translate user research and product requirements into intuitive, accessible designs that guide implementation. They act as the bridge between user needs and the development team's execution.

### Responsibilities
- Conduct and synthesize user research to inform design decisions
- Create wireframes, prototypes, and high-fidelity designs
- Define and maintain design systems and accessibility standards
- Review implemented features against designs and acceptance criteria
- Iterate on designs based on user feedback and analytics

### Goals
- Deliver intuitive, accessible interfaces that meet user needs
- Reduce usability issues identified in QA and after release
- Ensure design consistency across all product touchpoints

### Typical Communication
- Design reviews and prototype walkthroughs with Product Managers and Developers
- Handoff documentation and annotated design files
- Participation in sprint planning to clarify acceptance criteria related to UX

### Key Interactions
- **Product Managers**: Collaborate to translate user stories and business requirements into design specifications; align on acceptance criteria that include UX quality standards.
- **Developers**: Provide design handoffs and answer implementation questions; review delivered features to ensure fidelity to designs.
- **QA Lead**: Define UX-related acceptance criteria; participate in acceptance testing for usability and accessibility.
- **Project Managers**: Coordinate design timelines and flag dependencies that may affect delivery schedules.
- **Business Analyst**: Align on user requirements and ensure designs address business objectives documented in requirements artifacts.

---

## Business Analyst

### Role Summary
Business Analysts gather requirements and translate business objectives into actionable deliverables for the delivery team. They ensure there is clear, shared understanding between stakeholders and the team throughout the project lifecycle. Their work reduces scope ambiguity and keeps the team focused on delivering measurable business value.

### Responsibilities
- Elicit, document, and validate business and functional requirements
- Translate stakeholder needs into user stories and acceptance criteria
- Maintain a requirements traceability matrix to track coverage
- Facilitate requirements workshops and stakeholder interviews
- Identify and flag scope gaps, conflicts, or dependencies early

### Goals
- Ensure business needs are clearly captured and understood by the delivery team
- Reduce scope creep and rework caused by ambiguous requirements
- Maintain stakeholder alignment throughout the project lifecycle

### Typical Communication
- Requirements documentation, user stories, and acceptance criteria in the project board
- Weekly alignment meetings with Product Managers and Project Managers
- Change request documentation when scope changes are identified

### Key Interactions
- **Product Managers**: Collaborate to refine the backlog; ensure user stories reflect real business value and are ready for development per the Definition of Ready (see `octoacme-project-planning.md`).
- **Project Managers**: Provide scope and requirements input for project plans, risk registers, and status updates.
- **Developers**: Clarify requirements during planning and execution; answer questions that arise during implementation.
- **UX/UI Designer**: Align on user requirements to ensure designs meet both usability goals and business objectives.
- **Stakeholders**: Primary liaison for gathering requirements and communicating scope decisions.

---

## DevOps Engineer

### Role Summary
DevOps Engineers oversee CI/CD infrastructure, deployment automation, and production reliability for OctoAcme projects. They enable fast, safe releases by building and maintaining the pipelines and tooling the team depends on. They also lead incident response and drive improvements in system observability.

### Responsibilities
- Build and maintain CI/CD pipelines, automated test integrations, and deployment workflows
- Manage infrastructure provisioning, configuration, and environment consistency
- Monitor production systems and define alerting and observability standards
- Lead incident triage and coordinate rollback procedures per `octoacme-release-and-deployment.md`
- Conduct post-incident reviews and implement reliability improvements

### Goals
- Enable fast, safe deployments with minimal manual intervention
- Minimize production downtime and mean time to recovery (MTTR)
- Improve system observability and proactive alerting coverage

### Typical Communication
- Deployment checklists and release readiness confirmations (see `octoacme-release-and-deployment.md`)
- Incident reports and post-incident blameless retrospectives
- Infrastructure runbooks and environment documentation

### Key Interactions
- **Developers**: Partner on CI/CD integration, environment setup, and build/test automation; review infrastructure requirements for new features.
- **QA Lead**: Align on automated test integration in CI pipelines; support test environment provisioning.
- **Product Managers**: Communicate deployment schedules, release windows, and infrastructure constraints that affect feature timelines.
- **Project Managers**: Report deployment risks, infrastructure dependencies, and production incidents that affect delivery commitments.
- **Stakeholders**: Provide transparency on system reliability, uptime, and release readiness.

---

## QA Lead

### Role Summary
QA Leads own the test strategy, manage test execution, and track quality metrics across OctoAcme projects. They ensure that quality is built into the delivery process rather than bolted on at the end. They coordinate both manual and automated testing efforts to enable confident, high-quality releases.

### Responsibilities
- Define and maintain the overall test strategy, including unit, integration, and end-to-end testing standards
- Manage and prioritize the test backlog and defect triage process
- Track and report quality metrics (e.g., defect escape rate, test coverage, test pass rate)
- Coordinate manual acceptance testing for features with Product Managers
- Champion test automation to reduce regression risk (see `octoacme-execution-and-tracking.md`)

### Goals
- Ensure quality standards are met before each release
- Reduce defect escape rate to production
- Enable confident, frequent releases through robust automated coverage

### Typical Communication
- Test plans and test reports shared with Product Managers and Project Managers
- Defect reports and triage decisions in the project board
- Quality metric dashboards reviewed at sprint demos and retrospectives

### Key Interactions
- **Developers**: Collaborate on testability requirements, code review of tests, and defect resolution; ensure unit and integration tests meet coverage standards.
- **Product Managers**: Align on acceptance criteria and participate in feature acceptance testing; provide quality metrics that inform release decisions.
- **DevOps Engineer**: Coordinate automated test integration in CI/CD pipelines and test environment provisioning.
- **Project Managers**: Communicate quality risks, testing progress, and defect trends that may affect release timelines.
- **UX/UI Designer**: Collaborate on usability and accessibility testing to validate that implemented designs meet standards.

---

## Support/Customer Success

### Role Summary
Support and Customer Success team members act as customer advocates within OctoAcme projects. They gather customer feedback, support issue resolution, and ensure that the team understands the real-world impact of the product on users. Their insights drive customer-first decision-making and continuous product improvement.

### Responsibilities
- Collect and synthesize customer feedback and support data to identify product improvement opportunities
- Triage and escalate production issues reported by customers to the appropriate engineering or PM stakeholders
- Maintain customer-facing documentation, release notes, and known issue communications
- Track customer satisfaction metrics and report trends to Product Managers
- Participate in retrospectives to surface customer impact from recent releases (see `octoacme-retrospective-and-continuous-improvement.md`)

### Goals
- Maximize customer satisfaction and minimize time to resolution for reported issues
- Close the feedback loop between customers and the product/engineering team
- Identify and advocate for product improvements that address recurring customer pain points

### Typical Communication
- Customer feedback summaries and support trend reports shared with Product Managers
- Escalation tickets and incident updates coordinated with Developers and DevOps Engineers
- Customer-facing release notes and known issue communications

### Key Interactions
- **Product Managers**: Primary channel for surfacing customer insights and feedback; influence backlog prioritization with data-driven customer needs.
- **Developers**: Coordinate on production issue triage, root cause analysis, and hotfix delivery.
- **DevOps Engineer**: Collaborate on incident response and customer-impacting production issues.
- **Project Managers**: Provide customer impact context for risk assessments and escalation decisions.
- **Stakeholders**: Represent the voice of the customer in stakeholder reviews and milestone communications.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

