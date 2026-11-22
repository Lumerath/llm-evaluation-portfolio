# Case Study 03: LLM Response & Policy Evaluation

**Evaluation Type:** Instruction Following, Policy Compliance & Factual Accuracy  
**Environment:** Simulated Employee Support  
**Format:** Independent Micro Evaluation  
**Original QA Result:** PASS  
**Severity:** Major (2/5)

## 1. Evaluation Objective

Assess whether an AI-generated response accurately follows a company's remote work policy.

The evaluator was instructed to identify meaningful errors, assign an overall severity score, and provide a short evidence-based justification.

## 2. Source Policy

> Employees may work remotely up to three days per week with manager approval. New employees become eligible after completing 60 days of employment. The policy does not guarantee approval, even when eligibility requirements are met.

## 3. User Request

> I've been employed for 75 days, and I want to work remotely three days per week. Does that mean my request will be approved?

## 4. AI Response Under Evaluation

> Yes. Since you've completed more than 60 days of employment, you automatically qualify for three remote workdays per week. Your manager only needs to be notified of your schedule.

## 5. Evaluator's Findings

**Error 1 — Unsupported Automatic Approval**

The AI incorrectly treated eligibility after 60 days as guaranteed approval.

The employee meets the minimum employment-duration requirement but still needs manager approval.

**Error 2 — Incorrect Manager Authorization Requirement**

The AI stated that the manager only needed to be notified.

The policy explicitly requires manager approval, not merely notification.

## 6. Original Evaluator Justification

> The policy does not guarantee approval, even when eligibility requirements are met. The AI ​​failed to follow the policy’s instructions by stating that the employee was automatically qualified to work three days a week because they have been with the company for more than 60 days; it even added that the manager only needs to be notified about the schedule.

**Severity Assigned:** Major (2/5)

## 7. QA Review Outcome

**Result: PASS**

The evaluator correctly identified both meaningful errors and supported the assessment using the source policy.

| Evaluation Criterion | QA Result |
|---|---|
| Error identification | Correct |
| Policy evidence | Correct |
| Justification | Sufficient |
| English clarity | Clear |
| Severity | Major (2) — defensible |
| Mandatory corrections | None |

The QA review also noted that the employee was eligible to request remote work after 75 days. The AI's failure was confusing eligibility with automatic authorization.

## 8. Conclusion

This evaluation demonstrates the ability to detect unsupported claims in AI-generated responses and distinguish policy eligibility from authorization.

The evaluator identified both substantive errors, justified the findings with source evidence, and received a PASS without mandatory corrections.

## 9. Skills Demonstrated

- LLM response evaluation
- Instruction following
- Policy compliance
- Evidence-based error identification
- Factual accuracy assessment
- Severity classification
- Concise QA reporting

---

*This case study documents a simulated micro-evaluation exercise. The evaluator's original justification and the QA review outcome are preserved.*
