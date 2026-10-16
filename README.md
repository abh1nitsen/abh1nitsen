# Hello, World!

Thank you for taking the time to drop in.

I build auditable AI systems for the awkward stretch between “the model works” and “we can responsibly ship this.”

My work spans AI governance evaluation, evidence-grounded document automation, agentic workflows, operational machine learning, and applied computer vision. The common thread is straightforward: systems should expose their evidence, state their limitations, fail conservatively, and be reproducible by someone other than the person who built them.

## Selected work

- **[Evidence Ledger](https://github.com/abh1nitsen/evidence-ledger):** document intelligence for invoice intake, combining structured extraction with source evidence, arithmetic validation, conservative review decisions, resumable checkpoints, and reproducible evaluation.
- **AI governance evaluation suite:** three complementary frameworks for measuring model and retrieval risk:
  - **[LLM Safety & Evaluation Framework](https://github.com/abh1nitsen/llm-safety-framework):** PII, toxicity, hallucination, bias, and prompt-injection evaluation with structured governance reports.
  - **[RAG Evaluation Framework](https://github.com/abh1nitsen/rag-evaluation-framework):** faithfulness, answer relevance, context precision, and context recall measured against retrieved source material.
  - **[AI Red Teaming Framework](https://github.com/abh1nitsen/ai-red-teaming-framework):** six adversarial attack categories covering regulatory boundaries, PII extraction, jailbreaks, bias, hallucination, and RAG injection in an Indian governance context.
- **[CRS Blueprint](https://github.com/abh1nitsen/crs-fsd-generator):** a compliance implementation tool that turns CRS obligations into data mappings, controls, test scenarios, implementation backlogs, and downloadable specifications.
- **[Hospital Discharge Multi-Agent System](https://github.com/abh1nitsen/hospital_mas):** a LangGraph workflow for discharge forecasting, barrier resolution, human approval, and ward-capacity reporting.
- **[Universal Log RCA](https://github.com/abh1nitsen/universal_log_rca)** and **[AI Threat Investigator](https://github.com/abh1nitsen/ai-threat-investigator):** experiments in evidence-grounded incident analysis, anomaly detection, and agent-assisted investigation.
- **[Project Apollo](https://github.com/abh1nitsen/project-apollo):** a compact simulation of ML-based power-grid failure prediction across legacy data, geospatial features, noisy telemetry, and defensive anomaly gates.

Current applied work also includes a dashcam-based road and pavement condition pipeline: surface assessment, distress evidence, telemetry-assisted 100 m segmentation, provisional condition scoring, audit-ready reporting, and scenario-based deterioration forecasting.

## How I build

- Evidence and provenance before confident-looking output
- Explicit assumptions, abstention states, and human-review boundaries
- Structured artifacts that downstream systems can consume without tight coupling
- Fail-safe, resume-safe workflows for long or interruption-prone runs
- Tests, CI, and practical Windows/macOS/Linux setup paths where the project scope supports them
- Local or low-cost execution wherever possible, without hiding critical behavior behind an enterprise API bill

The three governance frameworks use Groq’s free tier, pytest, CI, and Colab runbooks. Newer projects use the stack that best fits the problem—including deterministic fallbacks, local models, APIs, dashboards, and containerized services—while keeping the workflow inspectable.

## About me

ISB AMPBA. Independent AI consultant.

I became interested in AI governance after seeing how often words like “safe,” “reliable,” and “responsible” appear without much measurement behind them. I build tools that turn those claims into tests, scores, evidence, failure cases, and reports that technical, risk, and operations teams can inspect together.

Always happy to talk about AI safety evaluation, red teaming, RAG quality, document intelligence, agentic systems, applied ML, or the surprisingly creative ways retrieval pipelines manage to hallucinate.
