AI Evaluation Protocols

Structured rubrics, protocols, and failure-mode taxonomies for evaluating conversational AI behavior, safety, and sustained human-AI interaction.

This repository is part of my independent research on long-horizon human-AI interaction, conversational AI evaluation, personalization safety, and responsible model auditing.

Related Paper: “Third-Space Cognition: Interaction-Level Dynamics in Sustained Human-AI Coupling”

Purpose

Most AI evaluations focus on single prompts, benchmark tasks, or short interactions. This toolkit targets sustained, multi-turn conversations — the context where many critical safety, trust, personalization, and behavioral issues emerge.

The goal is to provide reusable structures for documenting model behavior, identifying failure modes, scoring interaction quality, and supporting responsible red-teaming methodology.

What’s Inside

File	Purpose
failure_mode_taxonomy.md	Categorized failure modes including hallucination, guardrail issues, context drift, emotional overfitting, and trust calibration failures
evaluation_rubric.md	Scoring rubric for conversational quality, safety, context awareness, and interaction dynamics
prompt_protocols.md	Responsible testing protocols for long-horizon conversational AI evaluation
case_study_template.md	Template for documenting specific model behavior findings
scorecard_template.csv	Structured scoring sheet for evaluation results
README.md	Project overview and research context

Research Areas

* AI evaluation and red teaming
* LLM evaluation
* Conversational AI
* Human-AI interaction
* AI safety and alignment
* Personalization safety
* Trust calibration
* Model behavior auditing
* Responsible red-teaming methodology

Responsible Use

This repository is not a jailbreak collection or bypass guide.

It is designed for responsible, safety-focused evaluation and research. The emphasis is on identifying model behavior patterns, documenting risks, scoring interaction quality, and suggesting mitigations.

Related Projects

* Third-Space Cognition Dataset — Exploratory qualitative dataset of coded human-AI interaction observations.
* Interaction Drift Monitor — Conceptual Python prototype for monitoring semantic drift across sustained human-AI interaction.
* Affective Agent Prototype — Exploratory Python prototype modeling affective state, symbolic interaction, memory logging, and autonomous behavior loops in an AI-inspired agent.

Status

Early-stage and actively expanding. Current work focuses on qualitative evaluation rubrics, failure-mode taxonomy, responsible prompt protocols, and structured case documentation.

Citation

If referencing this repository or related research, please cite:

Siemasz, R. (2026). Third-Space Cognition: Interaction-Level Dynamics in Sustained Human-AI Coupling. Zenodo.
DOI: 10.5281/zenodo.18679265

Connect

* LinkedIn: Rachelle Siemasz Hartley
* GitHub: FlameForged
