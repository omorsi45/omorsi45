# Omar Morsi

GenAI Developer at Ericsson. Computer Science at Concordia University.

I build applied ML and LLM systems: evaluation pipelines, agent reliability tooling, and production-oriented AI APIs. At Ericsson I work on generative AI engineering and AI-enabled software workflows.

---

## Agent reliability and tooling

- **[Hazard](https://github.com/omorsi45/hazard)**: Test harness for coding agents. Avoids running the full suite on every change by ranking impacted tests from dependency, coverage, and semantic signals, with calibrated recall guarantees and automatic full-suite fallback when confidence is low.
- **[Twinwright](https://github.com/omorsi45/twinwright)**: Executable digital twins for testing autonomous agents before they touch production. Stateful tools, durable execution, deterministic evaluation, fault injection, replay, checkpointing, counterfactual forks, and OpenTelemetry traces.
- **[Evolve Skills](https://github.com/omorsi45/evolve-skills)**: Open-source skill evolution system inspired by Google's WikiSkill research. Real execution traces feed a persistent wiki, which produces targeted `SKILL.md` proposals gated by human approval and benchmarks.

## LLM evaluation

- **[HalluciScope](https://github.com/omorsi45/HalluciScope)**: Detects RAG answers that look right but are not grounded in the source. Claim-level ensemble of NLI, self-consistency, and semantic similarity, with a per-claim hallucination score and HaluEval ablation. FastAPI, React, FAISS, Ollama.

## Applied ML and backend

- **[NOVA](https://github.com/omorsi45/nova-network-failure-prediction)**: Predicts node outages from telemetry and syslog. Windowed features into a supervised MLP and an autoencoder. Public-data reimplementation of internship work.
- **[Surgical Workflow Analysis](https://github.com/omorsi45/surgical-workflow-analysis)**: Joint phase recognition and tool tracking in laparoscopic video. Multi-task MS-TCN on frozen ResNet-50 features, plus a correlation loss for impossible tool-phase pairs. Four-model comparison, 64 tests, Cholec80 subset.
- **[Distributed Task API](https://github.com/omorsi45/distributed-task-api)**: Java 21 / Spring Boot task API that survives duplicate writes and concurrent updates. Idempotency keys, optimistic locking, Flyway, Testcontainers, Docker Compose.
- **[Medical Insurance Regression](https://github.com/omorsi45/medical-insurance-linear-regression)**: Ridge regression with feature engineering, preprocessing, and cross-validation to predict insurance charges.
