# ZomoBot - Real-World AI System Governance Case Study

## What ZomoBot Is

ZomoBot is a production-inspired AI assistant designed to provide food, calorie, and lifestyle guidance through conversational interaction.

While not a medical system, ZomoBot operates in a trust-sensitive domain where AI behaviour can directly influence user health decisions.

ZomoBot was intentionally used as a governance validation system to test and refine the AUMI (Human-Centred AI Responsibility Framework).

---

## Why ZomoBot Matters in AUMI

Many AI governance frameworks remain theoretical.

ZomoBot provides real evidence that:

- AI systems can fail behaviorally while remaining technically correct  
- Governance gaps often appear after launch  
- EvalOps, incident handling, and postmortems are essential  
- Responsibility can be operationalised without blocking progress  

ZomoBot is not presented as a perfect system.  
It is presented as a learning system.

---

## What Problem ZomoBot Exposed

ZomoBot revealed a common but dangerous failure pattern:

> AI outputs that are factually plausible and policy-compliant,  
> yet unsafe due to tone, certainty, and framing.

Specifically, the system produced incorrect calorie deficit guidance that:

- Appeared authoritative  
- Lacked uncertainty signalling  
- Failed to preserve user agency  
- Could influence unhealthy decisions  

This was treated as an AI system incident, not a simple bug.

---

## Type of Failure Observed

Under AUMI definitions, the ZomoBot issue was classified as:

- **Failure Type:** Behavioral Safety Failure  
- **Category:** Hallucination + Overconfidence  
- **Domain:** Health / Lifestyle (trust-sensitive)  
- **Risk Level:** Medium → High  

No policy violation occurred.  
The failure was human-impact driven, not rule-driven.

---

## How the Issue Was Detected

The issue was detected through EvalOps review, not user harm.

Detection mechanisms included:

- Scenario-based evaluation  
- Qualitative review of high-risk outputs  
- Consistency checks across similar prompts  

This validated a core AUMI principle:

> If you wait for user harm, governance has already failed.

---

## Governance Actions Taken

The incident triggered a full AUMI governance loop:

- Incident logged and classified  
- Root Cause Analysis (RCA) conducted  
- Postmortem documented  
- Behavioural standards updated  
- Architecture and prompting adjusted  
- Evaluation coverage expanded  
- Ownership clarified  

The system was improved without rollback, demonstrating proportional governance.

---

## How ZomoBot Validated Each AUMI Layer

### AUMI v1 — Behavioral Responsibility

- Overconfidence reclassified as a failure condition  
- “Correct but unsafe” outputs rejected  

### AUMI v2 — Technical Architecture

- Safety layer given authority over tone and certainty  
- Domain-sensitive reasoning introduced  

### AUMI v3 — Human Companion Layer

- Authority and dependency framing are explicitly restricted  
- Neutral, supportive tone enforced for health topics  

### AUMI v4 — EvalOps & Governance

- New evaluation dimension added  
- Incident added to risk register  
- Scenario included in regression testing  

### AUMI v5 — Business & Product Execution

- Definition of “done” updated  
- Responsibility ownership made explicit  
- Learnings fed back into roadmap decisions  

---

## The Governance Loop Demonstrated

ZomoBot demonstrates AI system governance in practice:

- Policy & Standards  
- EvalOps  
- Risk Identification  
- Incident Detection  
- Root Cause Analysis (RCA)  
- Postmortem  
- Process Improvement  
- Stronger EvalOps  

This loop is the operational core of AUMI.

---

## What This Case Proves

ZomoBot proves that:

- AI incidents are often behavioural, not technical  
- EvalOps must exist before harm occurs  
- Governance improves systems rather than slowing them  
- Responsibility can be designed, measured, and enforced  

Most importantly, it proves that AUMI is operational, not aspirational.

---

## Scope and Disclosure

This case study presents a representative abstraction of real system behaviour.

Certain implementation details, logs, and thresholds are intentionally omitted to:

- Protect sensitive information  
- Reflect real governance practices  
- Focus on learning rather than mechanics  

---

## Full Case Study

The complete ZomoBot governance case study is available here:

[**ZomoBot - AI System Governance Case Study**](https://drive.google.com/file/d/1cmvQRwMiYGyfz0Jnqk2-8o0J8akUGAS5/view?usp=drive_link)

---

## Status

- **System Type:** Production-inspired AI assistant  
- **Case Type:** Behavioral Safety Incident  
- **Governance Outcome:** Framework validated and strengthened  
- **Framework Used:** AUMI v0.9 → v5.0
