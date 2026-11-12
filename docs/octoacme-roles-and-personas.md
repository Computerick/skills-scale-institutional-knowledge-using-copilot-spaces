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

### Collaboration
- **Developers:** Pair on implementation details, estimates, and technical trade-offs.
- **Product Managers:** Clarify user needs, scope, priorities, and acceptance criteria.
- **Project Managers:** Share progress, estimates, blockers, and delivery risks.
- **QA/Test:** Agree on testability, coverage, defect triage, and release readiness.
- **Stakeholders:** Explain technical impact and demonstrate completed work.

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

### Collaboration
- **Developers:** Explain product intent, answer questions, and make scope trade-offs.
- **Project Managers:** Align priorities, milestones, dependencies, and status updates.
- **QA/Test:** Confirm acceptance criteria and review validation results.
- **Stakeholders:** Gather needs, communicate decisions, and report product outcomes.
- **UX/Product Design:** Align research, usability goals, and solution direction.

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

### Collaboration
- **Developers:** Coordinate capacity, sequencing, dependencies, and blockers.
- **Product Managers:** Align scope, priorities, milestones, and changes.
- **QA/Test:** Include quality activities and readiness in the delivery plan.
- **Stakeholders:** Provide clear status, surface risks, and coordinate decisions.

---

## QA / Test Leads

### Role Summary
QA/Test Leads guide the team's quality strategy throughout delivery, helping the team verify acceptance criteria early and identify risks before release.

### Responsibilities
- Define test approaches, coverage, and quality checkpoints
- Coordinate functional, integration, and regression testing
- Track defects and facilitate triage with the team
- Identify quality risks and recommend mitigations
- Communicate test results and release readiness

### Goals
- Catch important issues early and reduce escaped defects
- Make coverage, defects, and quality risks visible throughout delivery
- Support predictable, evidence-based release decisions

### Typical Communication
- Test plans, test cases, and quality dashboards
- Defect reports and triage discussions
- Readiness updates during planning and release reviews

### Collaboration
- **Developers:** Review testability, reproduce defects, and coordinate fixes and verification.
- **Product Managers:** Clarify acceptance criteria and communicate user-impacting quality trade-offs.
- **Project Managers:** Plan testing time, report progress, and flag quality risks to milestones.
- **QA/Test:** Coordinate coverage, responsibilities, peer reviews, and consistent reporting.
- **Stakeholders:** Summarize validation evidence, known issues, and readiness in clear terms.

---

## UX / Product Designers

### Role Summary
UX/Product Designers shape usable and coherent experiences by connecting user needs with product goals. They research, design, and validate workflows and interfaces.

### Responsibilities
- Conduct user research and synthesize findings
- Create user flows, wireframes, prototypes, and interface designs
- Define usability and accessibility considerations
- Validate designs with users and incorporate feedback
- Provide implementation-ready design specifications and support handoff

### Goals
- Make products useful, intuitive, and accessible
- Reduce uncertainty about user needs before implementation
- Deliver consistent experiences that support product outcomes

### Typical Communication
- Research summaries and usability findings
- Design reviews, prototypes, and annotated specifications
- Ongoing feedback with product and engineering teams

### Collaboration
- **Developers:** Explain interaction details, review implementation, and resolve design trade-offs.
- **Product Managers:** Align user problems, product goals, priorities, and success measures.
- **Project Managers:** Share research and design dependencies, estimates, and review timelines.
- **QA/Test:** Identify usability and accessibility scenarios and review behavior against designs.
- **Stakeholders:** Present research, explain design rationale, and gather feedback.

---

## Technical Leads / Architects

### Role Summary
Technical Leads/Architects guide technical direction and system design. They help teams make sound architectural decisions while balancing reliability, maintainability, and delivery needs.

### Responsibilities
- Define and communicate architecture and technical standards
- Evaluate technical options, constraints, and system-wide risks
- Guide design and code reviews for complex changes
- Coordinate technical dependencies across teams
- Support developers with implementation decisions and technical blockers

### Goals
- Keep systems secure, reliable, scalable, and maintainable
- Enable teams to deliver without avoidable technical rework
- Make architectural decisions transparent and appropriately documented

### Typical Communication
- Architecture diagrams and decision records
- Design reviews and technical guidance
- Risk and dependency discussions with engineering and delivery leads

### Collaboration
- **Developers:** Provide design guidance, review proposed changes, and unblock implementation.
- **Product Managers:** Explain technical options, constraints, and implications for product scope.
- **Project Managers:** Identify dependencies, estimate technical work, and communicate risks.
- **QA/Test:** Align on system behavior, non-functional requirements, and test environments.
- **Stakeholders:** Explain architectural decisions and their impact on cost, risk, and delivery.

---

## DevOps / Release Engineers

### Role Summary
DevOps/Release Engineers enable reliable software delivery through automation, deployment infrastructure, and operational practices. They help teams release and operate changes safely.

### Responsibilities
- Maintain CI/CD pipelines and deployment automation
- Manage environments, infrastructure, and release tooling
- Define deployment, monitoring, rollback, and recovery practices
- Support release coordination and production verification
- Identify reliability and operational risks

### Goals
- Make releases repeatable, observable, and low risk
- Reduce manual delivery effort and time to recover
- Improve service reliability and operational readiness

### Typical Communication
- Pipeline and deployment status updates
- Release checklists, runbooks, and incident communications
- Operational reviews and infrastructure change discussions

### Collaboration
- **Developers:** Integrate build and deployment workflows and resolve pipeline or runtime issues.
- **Product Managers:** Align release timing and communicate deployment constraints that affect scope.
- **Project Managers:** Coordinate release dependencies, readiness milestones, and change windows.
- **QA/Test:** Provide stable test environments and coordinate deployment validation.
- **Stakeholders:** Communicate release timing, operational impact, and service health.

---

## Business Analysts

### Role Summary
Business Analysts connect business needs to clear, actionable requirements. They help teams understand current processes, define desired outcomes, and resolve ambiguity before and during delivery.

### Responsibilities
- Elicit and document business needs and requirements
- Map workflows, rules, and dependencies
- Translate business needs into testable requirements and acceptance criteria
- Validate proposed solutions with users and business stakeholders
- Track requirement changes and clarify their impact

### Goals
- Ensure the team solves the right business problem
- Reduce ambiguity and rework through shared understanding
- Make requirements traceable to measurable outcomes

### Typical Communication
- Requirements, process maps, and decision logs
- Workshops and clarification sessions
- Change-impact summaries and acceptance reviews

### Collaboration
- **Developers:** Clarify rules, edge cases, and expected behavior during implementation.
- **Product Managers:** Align business needs with product goals, priorities, and scope.
- **Project Managers:** Communicate dependencies, requirement changes, and analysis milestones.
- **QA/Test:** Review testable acceptance criteria and confirm coverage of business rules.
- **Stakeholders:** Elicit needs, validate workflows, and confirm that requirements reflect business intent.

---

## Customer Support / Operations Representatives

### Role Summary
Customer Support/Operations Representatives bring frontline knowledge of customer issues and day-to-day service operations. They help teams anticipate user impact and prepare for changes and incidents.

### Responsibilities
- Share recurring customer questions, pain points, and operational patterns
- Help assess the impact and urgency of reported issues
- Review support readiness, customer-facing documentation, and escalation paths
- Communicate customer-facing changes and known issues
- Provide feedback from post-release support and operations

### Goals
- Resolve customer issues effectively and consistently
- Reduce avoidable support demand through clearer products and guidance
- Ensure operational teams are prepared for releases and incidents

### Typical Communication
- Support tickets, issue summaries, and escalation updates
- Knowledge-base articles, FAQs, and release communications
- Feedback in launch-readiness and post-release reviews

### Collaboration
- **Developers:** Share reproducible issue details and verify fixes against real customer scenarios.
- **Product Managers:** Surface customer trends and help prioritize user-impacting problems.
- **Project Managers:** Coordinate support preparation, escalation paths, and release communications.
- **QA/Test:** Contribute real-world scenarios and help validate fixes for reported issues.
- **Stakeholders:** Report customer impact, service trends, and operational readiness.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

