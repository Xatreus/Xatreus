<!-- Abdul Rahman | GitHub Profile README -->

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=25&duration=2800&pause=850&color=58A6FF&center=true&vCenter=true&width=900&lines=Engineering+AI+systems+with+purpose.;GenAI+%7C+Backend+Engineering+%7C+DevOps;Cloud+%7C+CI%2FCD+%7C+Infrastructure+as+Code" alt="Animated introduction" />

  <h1>Abdul Rahman</h1>
  <h3>AI & Backend Engineer · DevOps & Cloud Enthusiast</h3>

  <p>
    <a href="https://github.com/Xatreus"><img src="https://img.shields.io/badge/GitHub-Xatreus-181717?style=for-the-badge&logo=github" alt="GitHub profile" /></a>
    <a href="https://www.linkedin.com/in/abdul-rahman-221128258"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn profile" /></a>
  </p>

  <p><b>Computer Science & IoT Graduate</b> · Hyderabad, India</p>
  <p><i>Building AI-powered applications and backend systems, while developing practical skills in DevOps, cloud infrastructure and automation.</i></p>
</div>

---

## 🧑‍💻 Profile Overview

I'm interested in building and operating reliable software: from Python backend services and AI-powered applications to CI/CD pipelines, cloud infrastructure, containers and observability.

My work and learning currently center on four areas:

| Focus | What I'm building knowledge in |
|---|---|
| **Generative AI** | LLM integration, RAG, embeddings, hybrid retrieval and grounded responses |
| **Agentic systems** | Tool calling, task orchestration, typed interfaces and bounded agent workflows |
| **Backend engineering** | Python, FastAPI, REST APIs, async programming, persistence and system design |
| **DevOps & Cloud** | Linux, Docker, CI/CD, GitHub Actions, Kubernetes, Terraform, AWS and Azure |
| **Reliability & Security** | OpenTelemetry, monitoring, SLOs, testing, API security and application guardrails |

I value clear architecture, reproducible tests, explicit limitations and software that can be run and inspected by other developers.

## 🧭 Engineering Map

```mermaid
flowchart LR
    A["User / Product"] --> B["API Layer"]
    B --> C["Application & Agent Orchestration"]
    C --> D["Models"]
    C --> E["Retrieval · Tools · Data"]
    D --> F["Validation & Evaluation"]
    E --> F
    F --> G["Response · Evidence · Telemetry"]
    H["Security & Regression Testing"] -.-> B
    H -.-> C
    H -.-> F
```

<sub>A conceptual map of the engineering areas I explore. Individual repositories implement different subsets of this architecture.</sub>

---

## 🚀 Selected Projects

<div align="center">
  <h3>AI Engineering · Backend Systems · DevOps · Cloud & Reliability</h3>
  <p>Explore the repositories below for implementation details, setup instructions, architecture and current limitations.</p>
</div>

### 01 · <a href="https://github.com/Xatreus/cognis">Cognis</a>
**AI Agent Evaluation & Security Regression Platform**

<a href="https://github.com/Xatreus/cognis"><img src="https://img.shields.io/badge/VIEW_REPOSITORY-Cognis-7C3AED?style=for-the-badge&logo=github" alt="View Cognis" /></a>

Connect an AI model or agent endpoint, run repeatable quality and security cases, inspect individual failures and compare measurable results.

- Deterministic evaluation cases with assertions, pass rates and latency metrics.
- Baseline prompt-injection and response-level security regression probes.
- Adapters for compatible model APIs and existing HTTP-agent endpoints.
- JSON and Markdown reports, FastAPI API and local dashboard.
- SQLite evaluation history with optional PostgreSQL configuration.

**Core engineering:** evaluation design · adapters · API contracts · regression testing · reproducibility

<sub>Active portfolio project. It provides regression signals, not a security guarantee or certification; coverage and deployment hardening remain ongoing.</sub>

---

### 02 · <a href="https://github.com/Xatreus/Aetheris">Aetheris</a>
**AI Production Reliability & Observability Platform**

<a href="https://github.com/Xatreus/Aetheris"><img src="https://img.shields.io/badge/VIEW_REPOSITORY-Aetheris-0D9488?style=for-the-badge&logo=github" alt="View Aetheris" /></a>

An early-stage reliability engineering platform combining an application-side TypeScript OpenTelemetry SDK with a Python control plane.

- TypeScript SDK for application telemetry, traces and metrics over OTLP/HTTP.
- FastAPI control plane with typed reliability events and deterministic policies.
- Release evaluation gates with pass / warn / block outcomes.
- Evidence-preserving incident investigation reports and SLO / error-budget evaluation.
- PostgreSQL persistence path with SQLite as the local test default.
- Docker Compose, Kubernetes and Terraform deployment scaffolding.

**Core engineering:** OpenTelemetry · TypeScript SDKs · FastAPI · reliability policies · SLOs · platform engineering

<sub>Development baseline, not production-ready. Cloud manifests are starter scaffolding and have not been validated in a live cloud account.</sub>

---

### 03 · <a href="https://github.com/Xatreus/NexPilot">NexPilot</a>
**AI Software Engineering & DevOps Assistant**

<a href="https://github.com/Xatreus/NexPilot"><img src="https://img.shields.io/badge/VIEW_REPOSITORY-NexPilot-2563EB?style=for-the-badge&logo=github" alt="View NexPilot" /></a>

An engineering copilot prototype that turns software tasks into structured plans and inspects the delivery foundations of public GitHub repositories.

- Task planning across inspect, design, implement, test and deliver stages.
- Optional OpenRouter-compatible model assistance with deterministic fallback.
- Read-only repository intelligence for docs, tests, CI, dependencies and deployment signals.
- FastAPI backend, responsive dashboard and CLI.
- SQLAlchemy + SQLite activity history and Pydantic contracts.

**Core engineering:** AI-assisted planning · GitHub API integration · FastAPI · async HTTP · CLI · typed contracts

<sub>Early prototype. Repository checks inspect metadata and file-tree signals; they do not prove code quality, test success or deployment health. Autonomous code editing and deployment actions are not implemented.</sub>

---

### 04 · <a href="https://github.com/Xatreus/report-explainer">Report Explainer</a>
**Local-First Document Intelligence & RAG Workspace**

<a href="https://github.com/Xatreus/report-explainer"><img src="https://img.shields.io/badge/VIEW_REPOSITORY-Report_Explainer-D97706?style=for-the-badge&logo=github" alt="View Report Explainer" /></a>

A document workspace for exploring PDF and TXT reports, retrieving evidence, comparing findings and asking questions about source material.

- PDF/TXT ingestion with page-aware chunking and optional OCR.
- Hybrid retrieval combining local semantic embeddings and lexical search.
- Evidence-grounded Q&A with source passages and page-aware citations.
- Multi-report comparison, extracted metrics, entities and risk dashboards.
- Bounded read-only report analyst workflow.
- Streamlit UI with SQLite by default; optional PostgreSQL + pgvector and Redis/RQ paths.
- Provider-agnostic model selection through an OpenAI-compatible API configuration.

**Core engineering:** RAG · hybrid search · document processing · citations · retrieval evaluation · agent workflows

<sub>Local-first portfolio application. External model calls are optional; review provider data policies before processing confidential documents.</sub>

---

### 05 · <a href="https://github.com/Xatreus/lead-reviver-">Lead Reviver</a>
**Evidence-Aware AI Lead Management & Follow-Up Assistant**

<a href="https://github.com/Xatreus/lead-reviver-"><img src="https://img.shields.io/badge/VIEW_REPOSITORY-Lead_Reviver-0891B2?style=for-the-badge&logo=github" alt="View Lead Reviver" /></a>

An AI-assisted workspace that helps sales teams prioritize inactive leads and prepare context-aware follow-up drafts for human review.

- Lead management, search, status filtering and CSV import/export.
- Explainable heuristic revival scoring based on recency, due dates, deal value and pipeline stage.
- Gemini-powered email, SMS and LinkedIn draft generation with configurable tone and goal.
- RAG knowledge base for approved product information and sales playbooks.
- PostgreSQL + pgvector semantic retrieval, with SQLite local-development fallback.
- Consent guardrails prevent draft generation for opted-out and do-not-contact leads.

**Core engineering:** FastAPI · PostgreSQL · pgvector · RAG · embeddings · human-in-the-loop AI

<sub>Drafts are saved for human review and are never sent automatically. Authentication, tenant isolation and production hardening remain outstanding.</sub>

---

### 06 · <a href="https://github.com/Xatreus/invoice-buddy">Invoice Buddy</a>
**AI-Powered Invoice Intelligence API**

<a href="https://github.com/Xatreus/invoice-buddy"><img src="https://img.shields.io/badge/VIEW_REPOSITORY-Invoice_Buddy-16A34A?style=for-the-badge&logo=github" alt="View Invoice Buddy" /></a>

A Python API that extracts structured information from PDF invoices and answers questions about invoice records using database queries and retrieval.

- PDF invoice ingestion and LLM-based extraction of invoice fields and line items.
- Structured persistence and filtering with SQLAlchemy and SQLite.
- Tool-calling agent for invoice questions rather than relying on model-generated financial facts.
- Invoice lookup, spending summaries, vendor history and overdue-invoice queries.
- RAG over invoice-document content and API endpoints for application workflows.

**Core engineering:** Python · FastAPI · SQLAlchemy · LLM extraction · RAG · tool calling

<sub>Designed for local use and portfolio demonstration. Do not use sensitive production financial data without a security and privacy review.</sub>

---

## 📚 Learning Repository

### <a href="https://github.com/Xatreus/python-for-ai">Python for AI</a>
**Python Learning Notes & Mini Projects**

A learning archive covering Python fundamentals and small data-oriented exercises, including weather-data analysis with pandas and CSV-based sales calculations.

<a href="https://github.com/Xatreus/python-for-ai"><img src="https://img.shields.io/badge/VIEW_REPOSITORY-Python_for_AI-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="View Python for AI" /></a>

<sub>This is a learning repository rather than a polished application; some practice files are intentionally exploratory or incomplete.</sub>

---

## 🧰 Technology Stack

<div align="center">

**Languages & Backend**

<img src="https://skillicons.dev/icons?i=python,typescript,fastapi,postgres,docker,kubernetes,terraform,aws,azure,linux,git,githubactions,vscode" alt="Technology icons" />

**AI · Data · Quality**

<img src="https://img.shields.io/badge/LLM_APIs-Model_Integration-6D5BD0?style=for-the-badge" alt="LLM APIs" />
<img src="https://img.shields.io/badge/RAG-Hybrid_Retrieval-0F766E?style=for-the-badge" alt="RAG" />
<img src="https://img.shields.io/badge/AI_Agents-Tool_Calling-2563EB?style=for-the-badge" alt="AI agents" />
<img src="https://img.shields.io/badge/Testing-pytest-0A9EDC?style=for-the-badge" alt="pytest" />
<img src="https://img.shields.io/badge/Observability-OpenTelemetry-7C3AED?style=for-the-badge" alt="OpenTelemetry" />

</div>

| Area | Technologies & concepts |
|---|---|
| **Languages** | Python, SQL, TypeScript (SDK development) |
| **AI / GenAI** | LLM APIs, RAG, embeddings, vector search, hybrid retrieval, tool/function calling |
| **Agent engineering** | Agent workflows, adapters, orchestration, bounded tool use, evaluation |
| **Backend** | FastAPI, REST APIs, Pydantic, SQLAlchemy, Uvicorn, asynchronous programming, microservices |
| **Data & storage** | PostgreSQL, SQLite, pgvector, ChromaDB |
| **DevOps & Cloud** | Linux, Docker, Docker Compose, GitHub Actions, CI/CD, Kubernetes, Terraform, AWS, Azure, cloud-native deployment, infrastructure as code |
| **MLOps & Observability** | LLMOps, Langfuse (foundational), OpenTelemetry, monitoring, SLOs, model/agent evaluation |
| **Testing & Security** | pytest, Ruff, API/integration testing, secrets management, API security, OWASP concepts |
| **Developer tooling** | Git, GitHub, VS Code, async Python, HTTPX |

<sub>This stack spans hands-on implementation, project-specific use and ongoing learning; not every technology is used in every repository.</sub>

---

## 🔐 Security Knowledge & Practice

I have studied common web, API and AI application security topics through hands-on labs and project work. Security is one part of my broader engineering toolkit.

<details>
<summary><b>Explore security areas</b></summary>

| Category | Topics explored |
|---|---|
| **Injection** | SQL injection, OS command injection, server-side template injection (SSTI) |
| **Browser security** | Reflected XSS, DOM-based XSS |
| **Access control** | IDOR, authentication and authorization weaknesses |
| **Server-side** | SSRF, path traversal, file-upload vulnerabilities |
| **API security** | API testing, input validation, access control and OWASP API Security concepts |
| **AI security** | Prompt injection, tool misuse, LLM application attack surfaces and security regression testing |

</details>

---

## 🎓 Certifications

<div align="center">

<a href="https://catalog-education.oracle.com/pls/certview/sharebadge?id=FFF3BB90ADA78034EB70717DB0EE92C2640D9AC4F3572540C55C171B53200A20"><img src="https://img.shields.io/badge/Oracle-Cloud_Infrastructure_AI_Foundations-F80000?style=for-the-badge&logo=oracle&logoColor=white" alt="Oracle Cloud Infrastructure AI Foundations" /></a>

<a href="https://catalog-education.oracle.com/pls/certview/sharebadge?id=D5F89B27F403077F3625D83FB1F6940A54DA55BFD8CFD0B1586F8D0AC7580E58"><img src="https://img.shields.io/badge/Oracle-Agentic_AI_Foundations-F80000?style=for-the-badge&logo=oracle&logoColor=white" alt="Oracle Agentic AI Foundations" /></a>

</div>

---

## 📈 GitHub Activity

<div align="center">
  <img src="https://streak-stats.demolab.com?user=Xatreus&theme=tokyonight&hide_border=true" alt="GitHub contribution streak" />
</div>

---

## 🎯 What I'm Exploring Next

- Building dependable CI/CD workflows with GitHub Actions and automated quality gates.
- Deepening practical Kubernetes, Terraform, AWS and Azure deployment skills.
- Improving observability, monitoring, SLOs and production troubleshooting.
- Continuing to build AI applications, agent workflows and retrieval systems with strong backend foundations.

## 🤝 Connect

<div align="center">
  <a href="https://www.linkedin.com/in/abdul-rahman-221128258"><img src="https://img.shields.io/badge/LinkedIn-Connect_with_me-0A66C2?style=for-the-badge&logo=linkedin" alt="Connect on LinkedIn" /></a>
  <a href="https://github.com/Xatreus"><img src="https://img.shields.io/badge/GitHub-Follow_my_work-181717?style=for-the-badge&logo=github" alt="Follow on GitHub" /></a>
  <br/><br/>
  <i>Build reliable systems. Automate delivery. Keep learning.</i>
</div>
