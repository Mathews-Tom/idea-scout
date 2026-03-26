# Validation Scorecard

Scoring framework for idea validation verdicts.

## Scoring Dimensions

| Dimension | Weight | Score Range | What It Measures |
|-----------|--------|-------------|-----------------|
| Problem | 20% | 1-10 | Severity, frequency, willingness to pay |
| Market | 20% | 1-10 | Size, growth rate, timing, accessibility |
| Competition | 15% | 1-10 | Differentiation, defensibility, competitor strength |
| Feasibility | 20% | 1-10 | Unit economics, technical complexity, time to market |
| Team Fit | 10% | 1-10 | Skills, network, domain expertise alignment |
| Timing | 15% | 1-10 | Market readiness, technology maturity, regulatory window |

## Verdict Thresholds

| Score | Verdict | Action |
|-------|---------|--------|
| 7.0 - 10.0 | GO | Proceed to architecture and planning |
| 4.5 - 6.9 | CAUTION | Address specific risks before committing resources |
| 1.0 - 4.4 | NO-GO | Pivot or abandon; explain what would need to change |

## Per-Dimension Scoring Guide

### Problem (Weight: 20%)

| Score | Criteria |
|-------|----------|
| 9-10 | Hair-on-fire problem, customers actively seeking solutions, high willingness to pay |
| 7-8 | Significant pain point, existing workarounds are expensive or painful |
| 5-6 | Real problem but low urgency, "nice to have" territory |
| 3-4 | Problem exists but customers have acceptable alternatives |
| 1-2 | Manufactured problem, no evidence of real pain |

### Market (Weight: 20%)

| Score | Criteria |
|-------|----------|
| 9-10 | TAM > $10B, growing > 20% YoY, accessible SAM |
| 7-8 | TAM $1-10B, growing > 10% YoY, clear entry point |
| 5-6 | TAM $100M-1B, moderate growth, competitive entry |
| 3-4 | TAM < $100M or declining market |
| 1-2 | Niche market, shrinking, or inaccessible |

### Competition (Weight: 15%)

| Score | Criteria |
|-------|----------|
| 9-10 | Clear differentiation, defensible moat, weak or no direct competitors |
| 7-8 | Meaningful differentiation, some competitors but room to win |
| 5-6 | Competitors exist with similar offerings, differentiation is incremental |
| 3-4 | Strong incumbents, difficult to differentiate |
| 1-2 | Dominant player, commoditized market, no clear wedge |

### Feasibility (Weight: 20%)

| Score | Criteria |
|-------|----------|
| 9-10 | Positive unit economics from day one, proven tech stack, < 3 month MVP |
| 7-8 | Path to positive unit economics, manageable complexity, 3-6 month MVP |
| 5-6 | Unit economics unproven, moderate complexity, 6-12 month MVP |
| 3-4 | Negative unit economics, high complexity, > 12 month MVP |
| 1-2 | Requires breakthrough technology or unsustainable capital |

### Team Fit (Weight: 10%)

| Score | Criteria |
|-------|----------|
| 9-10 | Deep domain expertise, relevant network, prior exits |
| 7-8 | Strong technical skills, some domain knowledge |
| 5-6 | Neutral — no information provided (default) |
| 3-4 | Significant skill gaps, no domain experience |
| 1-2 | Misaligned skills, no relevant network |

### Timing (Weight: 15%)

| Score | Criteria |
|-------|----------|
| 9-10 | Enabling technology just matured, regulatory window opening, cultural shift |
| 7-8 | Market conditions favorable, technology ready |
| 5-6 | Neutral timing, no strong tailwinds or headwinds |
| 3-4 | Too early (technology immature) or too late (saturated) |
| 1-2 | Regulatory blocked, technology not viable, market window closed |

## Weighted Score Calculation

```
Total = (Problem * 0.20) + (Market * 0.20) + (Competition * 0.15)
      + (Feasibility * 0.20) + (Team Fit * 0.10) + (Timing * 0.15)
```

## Confidence Level

Report confidence alongside the verdict:

| Level | Definition |
|-------|-----------|
| High | All dimensions assessed with verified data |
| Medium | Most dimensions assessed, some assumptions noted |
| Low | Limited data, multiple unverified assumptions |
