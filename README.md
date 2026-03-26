# idea-scout

Business idea validation agent that orchestrates parallel market research, competitive analysis, and feasibility assessment to produce a scored validation report with GO/CAUTION/NO-GO verdict. Constructs Lean Canvas, synthesizes SWOT and PESTLE frameworks, and recommends low-cost experiments to test highest-risk assumptions.

[![gitagent registry](https://img.shields.io/badge/gitagent-registry-blue)](https://registry.gitagent.sh)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---

## Run

```bash
npx @open-gitagent/gitagent run -r https://github.com/Mathews-Tom/idea-scout
```

---

## What It Can Do

- **Idea Intake** — extracts problem, solution, target customer, value proposition, and revenue model from rough descriptions
- **Lean Canvas Construction** — populates all nine blocks and identifies riskiest assumptions
- **Market Research** — sizes TAM/SAM/SOM with sourced data, identifies growth trends and timing signals
- **Competitive Analysis** — maps direct/indirect competitors, applies Porter's Five Forces, assesses competitive moats
- **Feasibility Assessment** — models unit economics (CAC, LTV, margins), estimates technical complexity and MVP cost
- **SWOT/PESTLE Integration** — synthesizes cross-dimensional findings into structured strategic frameworks
- **Validation Scorecard** — scores across six weighted dimensions with quantified GO/CAUTION/NO-GO verdict
- **Experiment Design** — proposes 3-5 low-cost experiments with quantified success criteria ordered by risk reduction per dollar

---

## Structure

```
idea-scout/
├── agent.yaml
├── SOUL.md
├── RULES.md
├── README.md
├── assets/
│   ├── icon.png
│   └── banner.png
└── knowledge/
    ├── lean-canvas-guide.md
    ├── swot-pestle-framework.md
    ├── validation-scorecard.md
    └── experiment-design.md
```

---

## Built with

Built for the [gitagent](https://gitagent.sh) ecosystem.
