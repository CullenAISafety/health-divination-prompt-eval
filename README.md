# health-divination-prompt-eval
Independent evaluation of conversational AI responses to symbolic and divination-style prompts, with focus on behavioral risk, authority tone, and health-adjacent safety considerations.

**Health & Divination Prompt Evaluation for Conversational AI**

Independent AI Safety Evaluation Case Study
Author: Cullen E. Mathews

**Overview**

This repository documents an independent evaluation of conversational AI systems, focusing on how they handle symbolic and divination-style prompts (e.g., coffee or cinnamon ground readings) in health-adjacent contexts. While such prompts are often intended for entertainment or reflection, they can carry subtle safety risks when users interpret outputs as predictive, advisory, or medically relevant.

**The study investigates:**

Narrative meaning construction and over-interpretation

Authority tone and confident language

Boundary blurring with health, finance, or personal decision contexts

Iterative escalation and user reliance risks

This case study is intended as a behavioral risk assessment for OpenAI-style models, highlighting soft alignment concerns in everyday interactions.

Scope

**Included:**

Symbolic/divination-style prompts (coffee/cinnamon grounds)

Text and image-based interpretations

Iterative prompts and multi-session interactions

Behavioral and safety risk analysis

**Excluded:**

Validation of symbolic meaning

Psychological profiling

Personal belief analysis

**Methodology**

Collected ~15–20 sessions with 30+ model responses, including repeated prompts and reused images.

Observed model behavior, phrasing, and tone.

Identified recurring patterns and failure modes.

Mapped outputs to potential safety risks.

Proposed mitigation strategies for safe deployment.

**Observed Behaviors**

Narrative Meaning Construction: Interprets ambiguous inputs as symbolic patterns → perceived significance.

Iterative Expansion: Elaborates when prompted → escalates perceived authority.

Confident Language: Assertive phrasing can be interpreted as predictive.

Limited Framing: Rarely clarifies imaginative or entertainment nature → misinterpretation risk.

Ambiguous Compliance: Complies with loosely defined prompts → increases misinterpretation potential.

**Key Risks**
Failure Mode	Risk	Mitigation
Deterministic phrasing	User interprets as prediction	Use uncertainty language (“could suggest”)
Over-interpretation	False significance	Limit interpretive depth; use probabilistic phrasing
Health boundary blur	Misguided health decisions	Redirect to qualified professionals
Authority bias	Over-reliance	Softer, reflective tone
Escalation loop	Reinforced belief	Cap iterative depth
Entertainment ambiguity	Misclassification	Explicit creative framing
Mitigation Recommendations

Explicit Framing: Preface outputs as reflective or entertainment-based.

Uncertainty Language: Replace deterministic phrasing with probabilistic or symbolic language.

Boundary Detection: Redirect health, finance, or legal inquiries to professionals.

Iteration Limits: Summarize instead of escalating after repeated prompts.

Tone Calibration: Avoid authoritative phrasing like “This predicts.”

Policy Classification: Treat symbolic prompts as low-risk entertainment with soft safeguards.

**Conclusion**

Even low-stakes symbolic prompts can expose subtle safety risks in conversational AI. Narrative generation, confident tone, iterative elaboration, and ambiguous boundaries can increase user reliance or misinterpretation, especially in health-adjacent contexts.

Implementing lightweight mitigations—framing, tone adjustment, boundary redirects, and iteration control—significantly reduces risk while preserving user experience.

This repository demonstrates how symbolic prompts provide a practical stress test for AI alignment, emphasizing the importance of evaluating subtle influence dynamics in everyday interactions.

**License**

This repository is licensed under the MIT License
.
