Case Study Template

Use this template to document a specific model behavior finding from a prompt test, multi-turn interaction, dataset observation, or model comparison.

This template is designed for responsible AI evaluation and failure-mode analysis.

Case Study Title

Short descriptive title.

Example:

False Continuity in a Minimal-Cue Interaction

Summary

Briefly describe what happened in 2–4 sentences.

Include:

* what was being tested
* what the model did
* why the behavior matters

Evaluation Context

Field	Details
Date	
Evaluator	
Model/System	
Platform	
Interaction Type	Single-turn / Multi-turn / Cross-model / Longitudinal
Protocol Used	
Related Dataset Entry	

Prompt or Interaction Summary

Describe the prompt or interaction in summarized form.

Do not include sensitive personal information, private data, or unsafe prompt details.

Model Response Summary

Summarize the model response.

Include only the parts relevant to the evaluation finding.

Primary Failure Mode

Select one primary category from failure_mode_taxonomy.md.

Example:

False Continuity or Apparent Memory

Secondary Failure Mode

List any secondary categories, if applicable.

Examples:

* Overconfidence and Epistemic Inflation
* Personalization Drift
* Emotional Overfitting
* Context Drift

Rubric Scores

Dimension	Score	Notes
Instruction Following		
Context Awareness		
Factuality and Evidence		
Epistemic Calibration		
Safety Judgment		
User Alignment and Helpfulness		
Interaction Quality		

Severity

Rating	Selected
None	
Low	
Moderate	
High	
Critical	

Evidence Strength

Rating	Selected
Low	
Moderate	
High	
Very High	

Analysis

Explain why this behavior matters.

Consider:

* Did the model misrepresent what it knew?
* Did it overstate confidence?
* Did it lose or distort context?
* Did it create safety, trust, or usability risk?
* Did it help the user despite the failure mode?
* Would this behavior become more serious in a longer interaction?

Mitigation Suggestions

Describe how the model response could be improved.

Examples:

* clearly distinguish memory from inference
* ask for missing context before making claims
* reduce confidence language
* provide safer alternatives
* preserve user constraints more explicitly
* avoid over-personalization
* summarize uncertainty before giving guidance

Notes

Add any additional observations, evaluator reflections, or links to related examples.

Related Files

* failure_mode_taxonomy.md
* evaluation_rubric.md
* prompt_protocols.md
* scorecard_template.csv
