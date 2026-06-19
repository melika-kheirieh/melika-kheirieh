## Hi, I'm Melika 👋

I build **Python backend systems for AI and data workflows**.

My focus is turning uncertain model or data behavior into controlled software: explicit contracts, safety checks, database-backed state, retries, tests, and observable failure modes.

I am especially interested in backend systems where LLMs are not treated as magic boxes, but as components inside safer, testable, and debuggable workflows.

---

## 🚀 Featured Systems

### NL2SQL Copilot

Safety-first NL→SQL backend for converting natural-language questions into validated SQL through a staged pipeline.

**What it demonstrates**

- schema-aware context construction
- LLM-generated SQL treated as a proposal, not blindly executed
- SELECT-only and single-statement safety checks before database access
- verification and bounded repair
- structured failure contracts
- evaluation workflows, metrics, and observability

**Stack:** Python, FastAPI, SQL, PostgreSQL/SQLite, Docker, Prometheus, Grafana, tests

https://github.com/melika-kheirieh/nl2sql-copilot

---

### Async Job API

Backend reliability project for asynchronous job processing with inspectable job state and explicit failure handling.

**What it demonstrates**

- FastAPI API layer for job creation and status tracking
- Celery + Redis background processing
- PostgreSQL-backed job lifecycle state
- retry handling, terminal failures, and stuck-job recovery
- idempotency keys to avoid duplicate job creation
- service/repository boundaries, Docker Compose, tests, and CI

**Stack:** Python, FastAPI, Celery, Redis, PostgreSQL, SQLAlchemy, Alembic, Docker Compose, pytest, GitHub Actions

https://github.com/melika-kheirieh/async-job-api

---

### LLM Agent API

Small LLM-backed API focused on clean boundaries and testability rather than agent hype.

**What it demonstrates**

- FastAPI request/response contracts
- isolated agent orchestration
- pluggable LLM provider layer
- persistence boundary
- structured HTTP errors
- dependency injection and fake components for tests without live LLM calls

**Stack:** Python, FastAPI, Pydantic, SQLite, provider abstraction, pytest

https://github.com/melika-kheirieh/llm-agent-api

---

## 🧱 Engineering Style

I care about:

- clear API and service boundaries
- fail-closed behavior before risky execution
- database-backed state for inspectability
- explicit error contracts
- tests that do not depend on live external services
- logs, metrics, traces, or evaluation artifacts that make failures visible

I like building systems that are small enough to reason about, but structured enough to grow.

---

## 🎓 Background

- Former Business Data Analyst at Divar, working with SQL-heavy analytics, Airflow, PySpark, metrics, and data quality workflows
- M.Sc. in Artificial Intelligence from the University of Tehran
- Focused on Python backend engineering, LLM systems, evaluation workflows, and reliability-minded AI applications

---

## 🔗 Links

- LinkedIn: https://www.linkedin.com/in/melika-kheirieh-03a7b5176/
