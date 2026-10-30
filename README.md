# Hi, I'm Abdul Rahman 

**Computer Science & IoT graduate | GenAI Engineering · AI Agents · AI Security**

I build Python-based AI applications and explore how to make LLM-powered systems more useful, testable, and secure. My current focus is backend engineering for AI products: API design, retrieval-augmented generation (RAG), tool calling, evaluation, and security regression testing.

📍 Hyderabad, India  
🔗 [LinkedIn](https://www.linkedin.com/in/abdul-rahman-221128258) · 📧 [Email](mailto:nextomate22@gmail.com)

---

## Featured Projects

### 1. [Cognis — AI Agent Evaluation & Security](https://github.com/Xatreus/cognis)

An actively developed platform for running quality evaluations and security-regression checks against AI agents and model endpoints.

- Runs deterministic evaluation cases and records per-case assertions, pass rates, and latency metrics.
- Includes baseline probes for prompt injection and related response-level security regressions.
- Supports compatible model APIs and existing HTTP-agent endpoints through adapters.
- Produces JSON and Markdown reports, with a FastAPI API and local dashboard.
- Uses SQLite for local evaluation history, with optional PostgreSQL configuration.

**Engineering focus:** evaluation design, API contracts, adapter boundaries, security regression testing, reporting, and reproducibility.

> Cognis provides regression signals, not a guarantee of security or a production security certification. Its adversarial coverage and deployment hardening remain ongoing work.

### 2. [Invoice Buddy — AI Invoice Intelligence](https://github.com/Xatreus/invoice-buddy)

A Python and FastAPI application for extracting structured data from PDF invoices and answering questions about invoice records.

- Ingests PDF invoices and extracts structured fields using an LLM.
- Combines SQL-backed queries with RAG over invoice-document text.
- Uses tool-calling workflows to answer questions grounded in invoice data.
- Includes invoice lookup, spending summaries, duplicate checks, and anomaly-reporting modules.
- Provides REST endpoints, API documentation, and automated tests.

**Engineering focus:** LLM integration, document processing, data validation, retrieval, persistence, and backend API design.

> Personal engineering project intended for local use and demonstration. Review security, privacy, and operational controls before using sensitive financial data or deploying publicly.

### 3. [NexPilot Mini — Agent Engineering Prototype](https://github.com/Xatreus/nexpilot-mini)

An experimental Python prototype exploring the foundations of a repository and documentation assistant.

- Pydantic models for typed tasks and task results.
- Asynchronous service orchestration and structured logging.
- Explicit service boundaries and custom exceptions.
- A starting point for validated repository inspection, documentation retrieval, and tool contracts.

**Engineering focus:** async Python, typed interfaces, task orchestration, error handling, and maintainable architecture.

> This is an early scaffold: repository analysis and documentation retrieval are currently placeholder services, not a functioning autonomous coding agent.

---

## Technical Focus

| Area | Technologies and concepts |
|---|---|
| **AI engineering** | LLM APIs, RAG, embeddings, tool/function calling, agent workflows, AI evaluation |
| **Backend development** | Python, FastAPI, REST APIs, Pydantic, SQLAlchemy, SQLite |
| **Testing & reliability** | pytest, regression tests, validation, structured errors, evaluation metrics |
| **AI application security** | Prompt-injection testing, API security, security regression cases, web application security |
| **Tools & infrastructure** | Git, GitHub, Docker / Docker Compose, Linux |

This list reflects my current learning and project work; depth and implementation vary by technology.

## Certifications

- [Oracle Cloud Infrastructure Certified AI Foundations Associate](https://catalog-education.oracle.com/pls/certview/sharebadge?id=FFF3BB90ADA78034EB70717DB0EE92C2640D9AC4F3572540C55C171B53200A20)
- [Oracle Agentic AI Certified Foundations Associate](https://catalog-education.oracle.com/pls/certview/sharebadge?id=D5F89B27F403077F3625D83FB1F6940A54DA55BFD8CFD0B1586F8D0AC7580E58)

---

## What I'm Working Toward

I'm strengthening my software engineering and system-design skills while developing practical GenAI and agentic AI applications. I'm especially interested in building systems that are observable, testable, secure, and maintainable—not just demos that produce a plausible answer.

I'm open to opportunities and collaboration in **junior GenAI engineering, AI agent development, Python backend development, and AI application security**.

