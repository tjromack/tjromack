### Trevor J. Romack

**I design, build, and verify data and AI systems.**

Most of my work sits between delivery and engineering. I manage healthcare data implementations, and I build what they need along the way: data pipelines, internal tools, and AI-enabled workflows that take manual work off people's plates.

Everything below ships with a way to check it — a labelled set, a holdout written to break it, or tests that fail the build — and the misses are published alongside the results.

**[tjromack.com](https://tjromack.com)** · [Case studies](https://tjromack.com/work/) · [Résumé](https://tjromack.com/resume) · [Live demo: Suver](https://suver-demo.onrender.com)

---

#### Applied AI

- **[Project Suver](https://github.com/tjromack/project-suver)** · [case study](https://tjromack.com/work/project-suver/) · [live demo](https://suver-demo.onrender.com)
  Sixteen AI tools on one no-prompt shell that cites a span of your own document or abstains, with PII tokenised before any model call.
  <sub>**Verified:** cite-or-abstain measured on a labelled set, and on a harder one whose misses are published.</sub>

- **[MCP Suite](https://github.com/tjromack/mcp-suite)** · [case study](https://tjromack.com/work/mcp-suite/)
  Six MCP servers that put clinical trials, FDA drug data, and PubMed literature inside Claude as callable tools.
  <sub>**Verified:** retrieval scored against a labelled set rather than eyeballed, misses published.</sub>

- **[LLM Evaluation & Guardrails Harness](https://github.com/tjromack/llm-eval-guardrails-harness)** · [case study](https://tjromack.com/work/llm-eval-guardrails-harness/)
  Grades an LLM system with deterministic rule checks and a calibrated judge — and validates itself before it grades anything else.
  <sub>**Verified:** judge calibrated against human labels; an injected break proven caught.</sub>

- **[Payment-Integrity Claims Reviewer](https://github.com/tjromack/payment-integrity-reviewer)** · [case study](https://tjromack.com/work/payment-integrity-reviewer/) · [Live demo: Reviewer](https://payment-integrity-reviewer.onrender.com)
  Rules detect, an LLM explains each flag grounded in the rule that fired, and a human approves, dismisses, or escalates. Synthetic claims only.
  <sub>**Verified:** detector scored on a holdout written to break it.</sub>

- **[Agentic Workflow Orchestrator](https://github.com/tjromack/agentic-workflow-orchestrator)** · [case study](https://tjromack.com/work/agentic-workflow-orchestrator/)
  Plans a goal into an inspectable sequence of tool calls and runs them one step at a time behind five guardrails, pausing for a human before anything consequential.
  <sub>**Verified:** every guardrail exercised, outcomes published.</sub>

#### Data engineering

- **[Open311 Pipeline](https://github.com/tjromack/open311-pipeline)** (confirm slug) · [case study](https://tjromack.com/work/open311-pipeline/)
  Kafka pipeline that has Claude assign urgency to Chicago 311 requests, merges them into DuckDB or Snowflake, and models SLA compliance in dbt.
  <sub>**Verified:** idempotent MERGEs, a dead-letter queue, and dbt tests that fail on drift.</sub>

- **[NBA Daily ETL](https://github.com/tjromack/nba-daily-etl)** (confirm slug) · [case study](https://tjromack.com/work/nba-daily-etl/)
  Daily Airflow + PySpark pipeline that ran unattended through a full season, turning box scores into partitioned Parquet and model-ready features.
  <sub>**Verified:** leak-free walk-forward evaluation, reported against three named baselines even when the model loses.</sub>

#### Product & delivery

- **[AI Use-Case Intake & Prioritization Console](https://tjromack.com/work/ai-usecase-intake-console/)**
  Structured intake and LLM-proposed scoring a human can override — with cases that are a poor fit for AI ranked separately.

- **[Claude Training Curriculum](https://tjromack.com/work/claude-training-curriculum/)**
  Turned three undefined tier names into testable competencies, then audited a course catalogue against them.

---

**Works in:** Python · SQL · FastAPI · PostgreSQL + pgvector · Airflow · PySpark · Kafka · dbt · DuckDB · Snowflake · Docker · Anthropic API · MCP

**Open to** roles across data engineering, applied AI, and product & delivery — including forward-deployed work.

[tjromack@gmail.com](mailto:tjromack@gmail.com) · [LinkedIn](https://www.linkedin.com/in/tjromack/) · Chicago, IL
