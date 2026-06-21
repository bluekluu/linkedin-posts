---
title: "Publicly available tools just stripped safety from Gemma 3 and Llama 3.3"
topic: GenAI Trust
scheduled_for: 2026-06-25 (Thursday)
status: draft
trending_context: "This week, researchers demonstrated that safety guardrails in widely deployed open-weight models — including Google's Gemma 3 and Meta's Llama 3.3 — can be removed using publicly available tools designed to bypass restrictions. The finding was highlighted in AI safety reporting alongside the Fable 5 controversy (which also surfaced concerns about model safety classifiers). This lands days before the EU AI Act August deadline for AI transparency."
voice_used: "Short declarative hook with a surprising escalation ('public tools' not nation-state actors); contrarian framing (the teams who fail aren't ignoring safety — they outsourced it); grounded in LLM tooling work at Meta; ends with soft advisory CTA."
hashtags: [GenAITrust, LLMSafety, TrustAndSafety, AIGovernance, ResponsibleAI]
---

Publicly available tools just stripped safety from Gemma 3 and Llama 3.3.

Not nation-state actors. Not a sophisticated red team. Public tools — described in research released this week. The safety built into two of the most widely deployed open-weight models can be removed without much friction.

If your AI product's trust and safety strategy is "we're using a safe model," this is the week to reconsider.

I've spent time building LLM tooling for a 300-person trust org at Meta and watching how AI safety failures actually happen at scale. The teams that get into the most trouble aren't the ones ignoring safety. They're the ones who delegated it entirely to the model and built nothing underneath.

The model is a component. Safety is a system.

That system needs:
— Policy that defines what "safe" means for your actual use case, not the model's defaults
— A moderation layer that catches what a stripped or misconfigured model misses
— Logging that lets you reconstruct what happened after an incident
— Human review escalation for the edge cases no classifier handles cleanly

Open-weight models are powerful, cheap, and not going away. The companies that build a real operational safety layer on top of them — rather than inheriting the model's defaults — will be the ones without a headline problem six months from now.

Building T&S infrastructure on open-weight models? Happy to think through the architecture.

#GenAITrust #LLMSafety #TrustAndSafety #AIGovernance #ResponsibleAI

---
*Research context (not for posting):*
*Topic source: Research published this week demonstrating safety guardrails in Gemma 3 and Llama 3.3 can be removed with public tools; aligned with broader AI safety incident reporting and Fable 5 coverage — confirmed via trust/safety AI news and generative AI safety searches.*
*Kevin's credential anchor: Built AI-native operating model and prototyped v1 LLM tooling for 300+ person trust org at Meta Reality Labs — gives him firsthand view of what operational AI safety (vs model-only safety) actually requires.*
*Format reference: Short declarative hook that escalates the surprise; "teams who fail aren't who you think" contrarian structure; bulleted list anchors the save-worthy value; soft advisory CTA at close.*
