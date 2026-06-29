## Hi, I'm Melika

I build **Python backend systems where AI, data, and automation workflows need clear contracts, durable state, tests, and observable failure modes**.

My focus is turning uncertain or failure-prone behavior into controlled software: explicit service boundaries, database-backed state, retries, safety checks, evaluation workflows, and debuggable failure paths.

I am especially interested in systems where LLMs, background workers, search projections, and data pipelines are treated as reliable components inside testable software.

---

## Featured Systems

### NL2SQL Copilot

Safety-first NL-to-SQL backend for converting natural-language questions into validated SQL through a staged pipeline.

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

### FastAPI Ticket Search Service

Backend service for managing support tickets in PostgreSQL and making them searchable through an Elasticsearch projection.

**What it demonstrates**

- PostgreSQL as the durable source of truth
- Elasticsearch as a rebuildable search projection
- transactional outbox events for ticket-to-search synchronization
- Celery worker and beat scheduler for async outbox processing
- Redis-backed background runtime
- reindex flow for projection recovery
- request IDs, structured logs, health checks, Docker Compose, tests, and CI

**Stack:** Python, FastAPI, PostgreSQL, SQLAlchemy, Alembic, Elasticsearch, Celery, Redis, Docker Compose, pytest, GitHub Actions

https://github.com/melika-kheirieh/fastapi-ticket-search-service

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

## Engineering Style

I care about:

- clear API and service boundaries
- fail-closed behavior before risky execution
- database-backed state for inspectability
- explicit error contracts
- tests that do not depend on live external services
- logs, metrics, traces, or evaluation artifacts that make failures visible

I like building systems that are small enough to reason about, but structured enough to grow.

---

## Background

- Former Business Data Analyst at Divar, working with SQL-heavy analytics, Airflow, PySpark, metrics, and data quality workflows
- M.Sc. in Artificial Intelligence from the University of Tehran
- Focused on Python backend engineering, LLM systems, data workflows, async processing, and reliability-minded AI applications

---

## Links

LinkedIn: https://www.linkedin.com/in/melika-kheirieh-03a7b5176/
