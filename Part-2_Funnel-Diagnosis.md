**PART 2 — Funnel Debugging via Prompt-Based Diagnosis**

**Step 1 - Create Mock Funnel Dataset (3 Rows)**

| Campaign   | Persona      | Funnel Movement      | Response Rate | Drop-Off Reason           | Message Summary                |
| ---------- | ------------ | -------------------- | ------------- | ------------------------- | ------------------------------ |
| Campaign A | D2C CTO      | 1000 → 420 → 60 → 6  | 8% reply      | “Need proof before call”  | Feature-heavy automation email |
| Campaign B | Pharma COO   | 700 → 280 → 210 → 25 | 18% reply     | “Not urgent currently”    | Compliance efficiency pitch    |
| Campaign C | SaaS Founder | 1200 → 150 → 20 → 2  | 3% reply      | “Didn’t understand value” | Generic growth email           |

**Step 2 — Diagnose Using MMF Logic**

MMF = Message–Market Fit

It means: Does the message actually match buyer expectations?

**Campaign A Analysis (D2C CTO)**

**Funnel Pattern**

High MQL → Very Low SQL

Meaning:

People show interest
But avoid booking calls

**Failure Layer:**

Lack of proof

Over-engineered messaging

Feature focus instead of outcome focus

**Step 3 — Fix It With New Prompt**

Fix Prompt — Trust Injection

Target AIDCA Stage:

[D — Desire] + [C — Conviction]

**New Prompt**

Generate an outbound email focusing on real business outcomes instead of product features.
Include one short case example and one measurable improvement range.
Keep tone technical and outcome-driven.

**Cialdini Principle Added:**

Authority + Social Proof

**Campaign B Analysis (Pharma COO)**

**Funnel Pattern:**

High SQL → Low Client Conversion

**Meaning:**

Calls are happening
Deals not closing

**Diagnosis:**

**Urgency problem**

They like solution
But don’t act fast.

**Failure Layer:**

Weak CTA
No timing pressure

**Fix Prompt — Urgency Creation**

**Target AIDCA Stage:**

[A — Action]

**New Prompt**

Rewrite the CTA to include operational urgency related to audits, compliance deadlines, or production cycles.
Make delay feel costly but professional.

**Cialdini Principle Added:**

Scarcity + Loss Aversion

**Campaign C Analysis (SaaS Founder)**

**Funnel Pattern:**

High leads → Very low engagement

**Meaning:**

People open less
Reply less

**Diagnosis:**

Message relevance problem

**Failure Layer:**

Wrong tone
Weak headline

**Fix Prompt — Attention Repair**

**Target AIDCA Stage:**

[A — Attention] + [I — Interest]

**New Prompt**

Generate a personalized opening referencing one real founder pain such as CAC, churn, or burn rate.
Avoid generic growth claims.
Make first two lines highly specific.

**Cialdini Principle Added:**

Relevance Bias (Similarity Effect)
