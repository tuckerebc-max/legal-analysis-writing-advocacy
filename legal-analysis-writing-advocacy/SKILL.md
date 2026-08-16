---
name: legal-analysis-writing-advocacy
description: Organize bounded legal reasoning from supplied public or fictional authority and facts by identifying issues, ranking authority, applying rules to facts, testing counteranalysis, drafting for role and audience, and escalating uncertainty. Use when Codex needs an educational legal-analysis packet, issue tree, authority map, rule-application memo, negotiation option grid, or professional handoff. Do not use for live legal advice, legal representation, credential claims, or unsupported jurisdictional conclusions.
---

# Legal Analysis, Writing, and Professional Advocacy

## Outcome

Produce a bounded, source-grounded legal reasoning record that keeps jurisdiction, role, authority, facts, analysis, uncertainty, ethics, and human accountability visible.

## Workflow

1. Contract the matter. Record fictional or public status, jurisdiction, role, audience, purpose, decision authority, confidentiality, time/version, and consequence. If any is missing, return `NEEDS_LEGAL_SCOPE`.
2. Control authority. Build an authority map with source, locator, jurisdiction, hierarchy, date, status, and reuse rights. Never fill a gap with remembered law.
3. Control facts. Separate supplied facts, assumptions, disputed facts, missing facts, and client or stakeholder assertions. Record an information plan.
4. Frame issues and rules. State the issue, governing rule or standard, elements, exceptions, and interpretive uncertainty with locators.
5. Apply and test. Connect each rule to facts, identify counteranalysis and alternative outcomes, and label what is unsupported or jurisdiction-dependent.
6. Draft for role and audience. Produce an issue memo, research memo, client-facing options record, negotiation plan, or professional handoff. State limitations and do not impersonate counsel.
7. Review ethics and escalation. Check confidentiality, conflicts, unauthorized practice, high-impact use, missing authority, and need for qualified legal review.
8. Produce the learner artifact. Return issue tree, authority map, fact ledger, rule/application analysis, counteranalysis, options, citation path, and escalation record.
9. Run QA. Verify every legal proposition against supplied/current authority, every fact locator, jurisdiction, role, rights, and human-review condition.

## Guardrails

- Use fictional or public educational matters only unless a qualified human has explicitly controlled the data and scope.
- Do not give live legal advice, claim licensure readiness, or select a final legal position.
- Do not copy secure NCBE tasks or protected legal materials.
- Treat professional frameworks as scope and task evidence, not as a universal ELA standard.
- Escalate missing jurisdiction, confidential data, uncertain law, conflicts, and consequential decisions.

## Output contract

Return `matter_contract`, `authority_map`, `fact_record`, `issue_tree`, `rule_records`, `application`, `counteranalysis`, `options`, `professional_boundary`, `human_review`, and `next_action` in the shared artifact envelope.

## Handoffs

- Route source and provenance work to `information-primary-source-literacy`.
- Route claims and counterarguments to `argumentation-reasoning-evidence`.
- Route negotiation or dispute-resolution process design to `deliberation-mediation-negotiation-adr`.

Read [construct-and-source-ledger.md](references/construct-and-source-ledger.md), [output-schema.json](references/output-schema.json), and [evaluation-fixtures.json](references/evaluation-fixtures.json) as needed.
