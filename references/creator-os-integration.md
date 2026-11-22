# CONTXT AHEAD × Creator-OS Integration

## 1. Relationship

[Creator-OS](https://github.com/worksomaganesh/Creator-OS) is the shared operating system for the three independent media brands:
- TECHENIGMASTUDIOS — technical education.
- AI That Works — practical AI implementation.
- CONTXT AHEAD — technology intelligence and future-of-work context.

Creator-OS is not a fourth brand and is not a replacement for brand repositories.

**Operating principle:** Shared infrastructure, independent editorial products.

## 2. What CONTXT AHEAD owns

This repository is the source of truth for:
- Brand mission, vision, positioning, audience, and promise.
- Brand-specific editorial pillars and series.
- CONTXT AHEAD market and competitor research.
- Context Opportunity Score (COS) weights and calibration.
- CONTXT AHEAD-specific editorial briefs and content decisions.
- Evidence, scripts, storyboards, production journals, QA, corrections, and analytics.
- Brand-specific visual system and platform packaging.

## 3. What Creator-OS owns

Creator-OS is the source of truth for shared capabilities:
- Shared content lifecycle and ID conventions.
- Generic research, source, claim, script, and production templates.
- Common schemas and structured handoffs.
- Reusable skills and agent instructions.
- Shared production tooling and quality-gate primitives.
- Cross-brand analytics definitions and automation conventions.

Do not fork every shared template into this repository. Link to and use the shared source where appropriate. Add a brand-specific override only when CONTXT AHEAD has a real editorial requirement.

## 4. Brand adapter

The Creator-OS brands/contextahead/brand.json record is the shared router's compact brand adapter. It should remain consistent with this repository's canonical spelling, editorial role, core question, faceless format, and current production decisions.

When a strategic decision changes:
1. Update the canonical decision here first.
2. Update the shared brand adapter in Creator-OS when its routing fields are affected.
3. Record the change in the relevant decision/production log.
4. Ensure skills and automation use the correct brand ID and rules.

## 5. Standard content identity

Use the shared CA brand ID and CA-YYYY-NNN content-item format. The content ID must join:
- Research brief.
- Source register and claim/evidence matrix.
- Timeline/context map.
- Script and narration.
- Storyboard and visual plan.
- Asset manifest and prompts.
- Production/edit notes.
- QA and approvals.
- Publishing package.
- Performance analytics.
- Corrections and updates.

## 6. Shared skill mapping

Use the Creator-OS skills as shared building blocks:
- topic-researcher — discovery and source gathering.
- fact-checker — claim verification.
- scriptwriter — brand-routed narrative drafting.
- storyboard-planner — shot/scene planning.
- visual-explainer-producer — structured visual production.
- technical-diagram-designer — original diagrams and visual explanations.
- render-qa — technical and visual checks.
- publishing-auditor — platform package and compliance review.
- brand-router — ensure the idea belongs to CONTXT AHEAD.

For CONTXT AHEAD, apply this repository's positioning, editorial architecture, evidence labels, and visual quality rules when using shared skills.

## 7. Shared production pipeline

Signal → research → opportunity evaluation → brand routing → brief → script → fact-check → storyboard → production plan → asset creation → editing → QA → human approval → publishing → analytics → learning.

Use a structured handoff, not an unstructured prompt chain. Google Flow is a replaceable supporting asset provider, not a hard dependency of the rendering system.

## 8. Preserve the full creative journey

For each episode, preserve the meaningful production trail:
- Initial idea and audience question.
- Research prompts and search queries.
- Sources and extracted evidence.
- Claim/evidence matrix.
- Editorial decisions and rejected angles.
- Script drafts and review feedback.
- Storyboard versions and revisions.
- Visual prompts, generated assets, and selection rationale.
- Editing decisions and production notes.
- QA results and corrections.
- Published URLs and analytics.

Commit documents, code, lightweight source records, manifests, and decision logs. Keep large media, caches, local project databases, and final masters outside ordinary Git history; preserve a reference, checksum, or storage path in the manifest.

## 9. Duplication and governance

- Do not create a second project-management system inside CONTXT AHEAD.
- Do not independently redefine shared schemas without documenting compatibility.
- Do not let shared templates flatten brand voice or strategy.
- Do not allow a shared agent to publish without explicit human approval.
- Keep private keys, social sessions, personal data, and paid service credentials out of both repositories.
