# 🤖 Data Science & AI/ML Skills Suite
### Derived from [BehiSecc/awesome-claude-skills](https://github.com/BehiSecc/awesome-claude-skills)

![Domain](https://img.shields.io/badge/Domain-Data%20Science%20&%20AI/ML-purple?style=for-the-badge)
![Commands](https://img.shields.io/badge/Commands-10-blue?style=for-the-badge)
![Workflows](https://img.shields.io/badge/Workflows-5-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

> **Adaptation of `BehiSecc/awesome-claude-skills` for Data Science & AI/ML use cases.**
> Source focus: _curated list of Claude Skills_

---

## What This Skill Suite Does

Data pipelines, model training, evaluation, MLOps and analytical reporting.

This collection provides **10 specialised commands** and
**5 multi-step workflows**, all with a consistent
structured-output UI so you always know exactly where you are and what to do next.

---

## Quick Install

```bash
# Clone this skill
cp -r . ~/.claude/skills/r00-BehiSecc-awesome-claude-skills--datascience/

# Register in Claude Code
# In a Claude Code session:
/read ~/.claude/skills/r00-BehiSecc-awesome-claude-skills--datascience/SKILL.md
```

---

## Commands

| Command | Description |
|---------|-------------|
| `/data-profiling` | Automated EDA report: distributions, nulls, outliers, correlations and drift |
| `/feature-engineer` | Feature importance analysis with SHAP values and automated encoding recipes |
| `/model-evaluate` | Model performance dashboard: ROC, PR curves, confusion matrix and bias check |
| `/pipeline-scaffold` | Modular ML pipeline scaffold with versioning, logging and registry hooks |
| `/ab-test-design` | Statistical A/B test design: sample size, power, MDE and sequential testing |
| `/sql-optimize` | Query plan analysis, index recommendations and cost estimation |
| `/dashboard-spec` | BI dashboard specification from KPI list with chart types and data sources |
| `/data-contract` | Schema validation, SLA definition and data quality contract generation |
| `/llm-eval` | LLM output evaluation harness: hallucination rate, faithfulness and latency |
| `/anomaly-detect` | Time-series anomaly detection with root-cause attribution and alert tuning |

**Usage:**
```bash
/data-profiling <target>
/feature-engineer --scope full --output md
```

---

## Workflows (Multi-step)

| Workflow | Description |
|----------|-------------|
| `ml-project-init` | End-to-end ML project: EDA → baseline → feature engineering → model → deploy |
| `data-migration` | Data warehouse migration: audit → schema map → ETL → validation → cutover |
| `reporting-pipeline` | Automated reporting pipeline: source → transform → validate → visualise → deliver |
| `model-retraining` | Scheduled model retraining: drift detect → retrain → shadow → promote → monitor |
| `analytics-sprint` | 2-week analytics sprint: question → data → analysis → insight → recommendation |

**Usage:**
```bash
/workflows:ml-project-init <target> --scope full
```

---

## UI Design

All commands display structured output with:

- **Progress panels** — real-time step tracking
- **Findings tables** — sorted by severity (🔴🟠🟡🟢)
- **Action checklists** — quick wins → medium-term → strategic
- **Summary cards** — at-a-glance metrics after each command


## Progress Display Example

```
╔══════════════════════════════════════════════════╗
║  ML Pipeline  —  churn_prediction_v3             ║
╠══════════════════════════════════════════════════╣
║  Data ingestion   ✓   1.2M rows loaded            ║
║  Profiling        ✓   12 features, 3 issues found ║
║  Feature eng.     ✓   47 features created          ║
║  Training         ⟳   Epoch 18/50  [███████░░░]   ║
║  Evaluation       ░   Pending                      ║
║  Registry push    ░   Pending                      ║
╚══════════════════════════════════════════════════╝

DATA QUALITY ISSUES
  ✗  customer_age   → 847 nulls (0.07%)  → Impute with median
  ⚠  last_purchase  → 12 future dates    → Clip to today
  ⚠  revenue        → 3σ outliers: 214   → Review before drop
```


---

## Interaction Pattern

Every command follows this 5-step structure:

```
① Scope Confirmation  — verify target and options with user
② Live Analysis       — progress bar while working
③ Findings Table      — structured results sorted by impact
④ Action Plan         — prioritised, time-boxed recommendations
⑤ Next Steps          — suggested follow-up commands
```

---

## Source Repository

This suite is derived from
**[BehiSecc/awesome-claude-skills](https://github.com/BehiSecc/awesome-claude-skills)**
which focuses on: _curated list of Claude Skills_.

Improvements in this adaptation:
- Domain-specific command vocabulary for Data Science & AI/ML
- Enhanced structured output with visual progress tracking
- Prioritised action plans with time estimates
- Workflow orchestration for end-to-end processes
- Consistent UI conventions across all commands

---

## License

MIT — free to use, modify and distribute.
