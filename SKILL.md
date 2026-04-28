        ---
        name: "r00-BehiSecc-awesome-claude-skills--datascience"
        description: >
          🤖 Data Science & AI/ML skill suite derived from BehiSecc/awesome-claude-skills.
          Data pipelines, model training, evaluation, MLOps and analytical reporting.
          Provides 10 specialised commands for data-science, machine-learning, analytics workflows.
        version: "1.0.0"
        domain: datascience
        tags: ["data-science", "machine-learning", "analytics", "pandas", "mlops"]
        source: "https://github.com/BehiSecc/awesome-claude-skills"
        license: MIT
        ---

        # 🤖 Data Science & AI/ML Skill Suite

        > Derived from **BehiSecc/awesome-claude-skills** · Focus: _curated list of Claude Skills_

        ## Overview

        This skill provides 10 production-ready commands tailored for
        **Data Science & AI/ML** workflows. All commands follow a consistent
        interaction pattern with structured output, progress tracking and
        actionable recommendations.

        ## Available Commands

        - `/data-profiling` — Automated EDA report: distributions, nulls, outliers, correlations and drift
- `/feature-engineer` — Feature importance analysis with SHAP values and automated encoding recipes
- `/model-evaluate` — Model performance dashboard: ROC, PR curves, confusion matrix and bias check
- `/pipeline-scaffold` — Modular ML pipeline scaffold with versioning, logging and registry hooks
- `/ab-test-design` — Statistical A/B test design: sample size, power, MDE and sequential testing
- `/sql-optimize` — Query plan analysis, index recommendations and cost estimation
- `/dashboard-spec` — BI dashboard specification from KPI list with chart types and data sources
- `/data-contract` — Schema validation, SLA definition and data quality contract generation
- `/llm-eval` — LLM output evaluation harness: hallucination rate, faithfulness and latency
- `/anomaly-detect` — Time-series anomaly detection with root-cause attribution and alert tuning

        ## Interaction Pattern

        Every command follows this structured response format:

        ```
        1. CONTEXT CHECK   — Verify inputs and confirm scope with user
        2. ANALYSIS        — Deep analysis with live progress display
        3. FINDINGS TABLE  — Structured results with severity / priority
        4. RECOMMENDATIONS — Prioritised action list (quick wins first)
        5. NEXT STEPS      — Suggested follow-up commands
        ```

        ## UI Conventions

        | Symbol | Meaning              |
        |--------|----------------------|
        | ✓      | Passed / complete    |
        | ✗      | Failed / critical    |
        | ⚠      | Warning / review     |
        | ⟳      | In progress          |
        | ░      | Pending              |
        | 🔴     | Critical severity    |
        | 🟠     | High severity        |
        | 🟡     | Medium severity      |
        | 🟢     | Low / informational  |

        Progress bars use block characters:
        `[████████░░] 80%`

        ## Quick Start

        ```bash
        # Install this skill
        cp -r . ~/.claude/skills/r00-BehiSecc-awesome-claude-skills--datascience/

        # In Claude Code
        /read ~/.claude/skills/r00-BehiSecc-awesome-claude-skills--datascience/SKILL.md
        ```

        Then simply describe your task and Claude will route to the
        appropriate command automatically.
