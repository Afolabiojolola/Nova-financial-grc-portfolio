AI Governance Gaps – One-Page Case Study
Overview

Over the past six months, companies across finance, healthcare, retail, and technology have rushed to adopt generative AI tools. However, the pace of adoption has outgrown internal governance capabilities. Organizations are now facing increasing risk exposure due to unclear accountability, unregulated model usage, and weak oversight. This case study outlines a realistic scenario of AI governance failure at a mid-size fintech company and demonstrates how GRC teams can intervene.

Case Study Scenario

Company: Nova Financial Services (Fintech)
Problem: Employees began using external AI tools (e.g., ChatGPT, Claude, GitHub Copilot) to automate tasks without clear policies or data boundaries. One analyst unknowingly uploaded sensitive customer data into an external LLM, causing a potential data leak.

What Happened:

No approved list of AI tools.

No data-classification restrictions for AI usage.

No review of generative-AI contracts (no DPAs, unclear data retention).

No LLM monitoring or access controls.

No awareness training for staff.

This triggered a near-breach incident when a third-party AI vendor stored the submitted data for “model improvement,” violating Nova’s compliance obligations (SOC 2, ISO 27001, PIPEDA/GLBA).

Root Cause Analysis (RCA)
Issue	Description	Control Gap
Shadow AI	Teams used AI tools without formal approval	Missing AI governance program
Data Leakage	Customer data uploaded externally	Weak data-handling controls
Vendor Risk	AI vendor retained submitted data	No AI vendor risk review
Lack of Policy	Employees unaware of what is allowed	No AI Acceptable Use Policy
Insufficient Controls	No monitoring or logging of AI interactions	No technical guardrails
NIST CSF Mapping
CSF Function	What Failed
Identify	Missing AI asset inventory, no risk assessment
Protect	No data-classification guardrails for AI
Detect	No alerting or monitoring for AI data misuse
Respond	Delayed response due to unclear ownership
Recover	No lessons learned, no AI governance playbook
Recommended Controls

Create an AI Acceptable Use Policy (AUP) – Define approved use cases, data restrictions, and user responsibilities.

Implement AI Vendor Risk Assessments – Review DPAs, data retention limits, model-training clauses.

Build an AI Tool Inventory – Track all LLMs, GenAI models, and integrations.

Deploy Technical Controls – DLP rules, PII redaction, and logging on AI inputs/outputs.

Training & Awareness – Teach employees “safe prompts,” data boundaries, and model risks.

Value for a Hiring Manager

This case study demonstrates:

Your understanding of current emerging GRC risks

Your ability to apply NIST CSF to real-world scenarios

Your capability to write, assess, and communicate technical risk clearly

Your readiness to join an AI governance, risk, or compliance team
