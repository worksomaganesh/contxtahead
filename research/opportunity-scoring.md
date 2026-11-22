# CONTXT AHEAD Opportunity Scoring Model

**Model:** Context Opportunity Score (COS)  
**Range:** 0–100  
**Purpose:** Rank topic candidates by audience demand, competitive gap, relevance, storytelling value, evidence, and durability.

The score is a decision aid, not an automatic publishing approval.

## 1. Weighted dimensions

Rate each dimension from 1 (weak) to 5 (strong).

| Dimension | Weight | What a high score means |
|---|---:|---|
| Demand strength | 25 | Multiple independent signals show that the audience cares or is actively asking |
| Competitive gap | 25 | Existing coverage leaves a meaningful question unresolved or provides weak context |
| Audience relevance | 20 | The issue materially affects the primary audience's understanding or decisions |
| Storytelling potential | 15 | The topic supports a compelling question, narrative progression, and visual explanation |
| Evidence availability | 10 | Credible, inspectable evidence is available for the material claims |
| Long-term value | 5 | The explanation will remain useful beyond a short news cycle |
| **Total** | **100** | |

Formula:

COS = sum((rating / 5) × weight)

## 2. Rating guidance

### Demand strength (25)
- 1: One weak or incidental signal.
- 2: Some isolated interest, little repetition.
- 3: Repeated questions or at least two credible demand signals.
- 4: Strong signals across multiple channels or markets.
- 5: Consistent, repeated demand with clear audience urgency.

### Competitive gap (25)
- 1: Numerous strong, recent explanations already answer the same question.
- 2: Existing coverage is mostly adequate; our difference is cosmetic.
- 3: Some useful coverage exists, but a meaningful audience question remains.
- 4: Repeated coverage gaps, outdated explanations, weak evidence, or poor audience translation.
- 5: Strong evidence of an underserved question with a defensible, specific angle.

### Audience relevance (20)
- 1: Weak relationship to the primary audience.
- 2: Peripheral interest.
- 3: Relevant to one meaningful audience segment.
- 4: Important to the primary audience's learning or career decisions.
- 5: High-stakes or recurring question for a large part of the primary audience.

### Storytelling potential (15)
- 1: A list or announcement with little narrative.
- 2: Limited development or visual explanation.
- 3: Clear question and a few supporting insights.
- 4: Strong narrative, comparison, timeline, or visual evidence.
- 5: Distinctive story with compelling tension, context, evidence, and payoff.

### Evidence availability (10)
- 1: Material claims cannot be verified.
- 2: Mostly secondary or promotional claims.
- 3: At least one credible primary source and sufficient corroboration for the scope.
- 4: Strong primary sources and independent cross-checks.
- 5: Multiple high-quality, directly inspectable sources with clear limitations.

### Long-term value (5)
- 1: Very short-lived and little reusable insight.
- 2: Mostly tied to a moment.
- 3: Useful for a defined period.
- 4: Evergreen explanation with current relevance.
- 5: Foundational understanding likely to remain useful for years.

## 3. Decision bands

| Score | Decision |
|---:|---|
| 80–100 | High-priority candidate |
| 70–79 | Produce/test if capacity allows |
| 55–69 | Reframe or gather more evidence |
| Below 55 | Monitor or reject |

## 4. Hard gates

A high total score cannot override a critical failure.

- Demand strength must be at least 3/5.
- Evidence availability must be at least 3/5.
- Audience and brand fit must be clear.
- Material claims must be verifiable or narrowed.
- Rights, privacy, and platform risks must be acceptable.

If evidence quality is below 3, do not publish a factual explainer with unsupported central claims. Reframe as a clearly labelled question or wait for evidence.

## 5. Scorecard record

For every idea, store:
- Candidate ID and working title.
- Exact audience question.
- Demand sources and capture dates.
- Competitor coverage sample.
- Evidence gap and proposed differentiation.
- Six ratings and weighted score.
- Evidence links and unresolved uncertainty.
- Production estimate.
- Decision, reviewer, and reason.

## 6. Calibration

After the first 8–12 published videos:
- Compare predicted scores with actual audience response.
- Check whether high-gap topics were genuinely underserved.
- Inspect whether the scoring model overvalues trend spikes.
- Adjust weights only when repeated evidence supports the change.
- Preserve the previous scoring version so historical scores remain interpretable.

Do not optimise COS only for views. Also track meaningful comments, saves/shares where available, returning viewers, subscriber conversion, and whether the audience reports better understanding.
