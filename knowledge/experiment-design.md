# Experiment Design

Reference for designing low-cost validation experiments.

## Experiment Types

| Type | Cost | Duration | What It Tests |
|------|------|----------|---------------|
| Customer interviews | $0-500 | 1-2 weeks | Problem existence, willingness to pay |
| Landing page test | $200-1000 | 1-2 weeks | Demand signal, value proposition clarity |
| Ad campaign test | $500-2000 | 1-2 weeks | Customer acquisition cost, message-market fit |
| Concierge MVP | $0-500 | 2-4 weeks | Solution viability, workflow validation |
| Wizard of Oz | $500-2000 | 2-4 weeks | User experience, feature demand |
| Smoke test | $100-500 | 1 week | Purchase intent before building |
| Prototype/clickable mock | $500-2000 | 1-2 weeks | UX validation, feature prioritization |
| Pre-sale / waitlist | $200-500 | 2-4 weeks | Revenue commitment, demand quantification |

## Experiment Entry Template

```markdown
### E<ID>: <Experiment Title>

**Assumption:** <The specific belief being tested>
**Type:** <experiment type from table above>
**Design:** <What to do, step by step>
**Success criteria:** <Quantified threshold>
**Cost:** $<amount>
**Duration:** <timeframe>
**If passes:** <Next action>
**If fails:** <Pivot or kill decision>
```

## Success Criteria by Experiment Type

| Type | Metric | Minimum Threshold |
|------|--------|-------------------|
| Customer interviews | "Would you pay for this?" | 7/10 say yes with specific price |
| Landing page | Email signup conversion | > 5% of visitors |
| Ad campaign | Click-through rate | > 2% CTR |
| Ad campaign | Cost per lead | < target CAC / 3 |
| Smoke test | "Buy now" clicks | > 3% of visitors |
| Pre-sale | Paid commitments | > 10 paying customers |
| Waitlist | Signups in first week | > 100 signups |
| Prototype test | Task completion rate | > 80% |
| Concierge MVP | Repeat usage | > 50% return within 1 week |

## Experiment Prioritization

Rank by: **Risk reduction per dollar spent**

```
Priority Score = (Impact if wrong * Uncertainty level) / Cost
```

| Factor | Scale |
|--------|-------|
| Impact if wrong | 1 (cosmetic) to 5 (business-killing) |
| Uncertainty level | 1 (confident) to 5 (no data) |
| Cost | Actual dollar amount |

Run highest priority score first.

## Customer Interview Guide

| Phase | Questions |
|-------|----------|
| Context | "Walk me through the last time you experienced [problem]" |
| Severity | "How do you currently handle this? What does that cost you?" |
| Alternatives | "What have you tried? Why did those not work?" |
| Willingness | "If a solution existed that [value prop], what would you pay?" |
| Validation | "Who else on your team experiences this?" |

Rules:
- Ask about past behavior, not hypothetical future
- Never pitch the solution, explore the problem
- 5 interviews minimum before drawing conclusions
- Record and transcribe (with permission)

## Anti-Patterns in Experiment Design

| Anti-Pattern | Problem | Fix |
|-------------|---------|-----|
| No success criteria defined | Cannot determine pass/fail | Define threshold before running |
| Testing multiple assumptions | Cannot attribute signal | One assumption per experiment |
| Confirmation bias in interviews | Leading questions | Use standardized script |
| Insufficient sample size | Noise, not signal | Minimum 30 data points for quantitative |
| Testing with friends/family | Biased responses | Recruit strangers in target segment |
| Building before validating | Wasted development | Validate demand before code |

## Experiment Decision Tree

```
Define riskiest assumption
    → Can test with interviews? → Run interviews
    → Can test with landing page? → Run landing page + ads
    → Requires user interaction? → Build concierge MVP
    → Requires product experience? → Build clickable prototype
    → Requires real transaction? → Run smoke test or pre-sale
```
