<!--
  Abdul Rahman | GitHub Profile
  Built with GitHub-flavoured Markdown, HTML details, Mermaid and Shields.io.
-->

<div align="center">

  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=25&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=850&lines=Building+useful+AI+systems%2C+not+just+demos.;GenAI+Engineering+%7C+AI+Agents+%7C+AI+Security;Python+Backend+%7C+RAG+%7C+Evaluation+%7C+AppSec" alt="Typing introduction" />

  <h1>Hi, I'm Abdul Rahman 👋</h1>
  <h3>GenAI Engineering · AI Agents · AI Application Security</h3>

  <p>
    <a href="https://github.com/Xatreus"><img src="https://img.shields.io/badge/GitHub-Xatreus-181717?style=for-the-badge&logo=github" alt="GitHub" /></a>
    <a href="https://www.linkedin.com/in/abdul-rahman-221128258"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn" /></a>
    <a href="mailto:abdulrahmandev22@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  </p>

  <p><b>Computer Science & IoT Graduate</b> · Hyderabad, India</p>
  <p><i>I build Python-based AI applications and explore how to make LLM-powered systems useful, testable, observable and secure.</i></p>

</div>

---

## 🧭 About Me

I'm interested in the engineering behind reliable AI products — from backend APIs and retrieval pipelines to agent workflows, evaluation and application security.

My current focus is on:

- **GenAI applications:** LLM integration, RAG, embeddings and tool/function calling.
- **Agent engineering:** task orchestration, typed tool contracts, workflows and reliable execution.
- **AI quality & security:** evaluation harnesses, regression testing, prompt-injection probes and API security.
- **Backend engineering:** Python, FastAPI, REST APIs, persistence, testing and maintainable architecture.

I care about the parts beyond a successful demo: clear boundaries, useful failure modes, reproducible tests and honest documentation.

## 🗺️ Engineering Focus

<div align="center">

| AI Application Engineering | Agent Systems | AI Security |
|:---:|:---:|:---:|
| RAG · Embeddings · LLM APIs | Tool calling · Orchestration | Prompt injection · LLM testing |
| Document intelligence | Typed tasks · Async workflows | API security · Threat modeling |
| Evaluation · Grounding | Service boundaries · Observability | Security regression checks |

</div>

### How I think about an AI application

```mermaid
flowchart TD
    A["User / Application"] --> B["FastAPI · API Contracts"]
    B --> C["Application Orchestration"]
    C --> D["LLM / Model Provider"]
    C --> E["Retrieval · Tools · Data"]
    D --> F["Validation & Evaluation"]
    E --> F
    F --> G["Response · Trace · Report"]
    H["Security & Regression Tests"] -.-> B
    H -.-> C
    H -.-> F
```

<sub>Conceptual view of the engineering concerns I work with — not a claim that every project implements every component.</sub>

---

## 🚀 Featured Projects

A selection of projects where I'm applying AI engineering, backend development and security concepts.

<details open>
<summary><b>01 · Cognis — AI Agent Evaluation & Security</b> <sup>Active development</sup></summary>

<br/>

<a href="https://github.com/Xatreus/cognis"><img src="https://img.shields.io/badge/Explore-Cognis-7C3AED?style=for-the-badge&logo=github" alt="Explore Cognis" /></a>

A platform for running quality evaluations and security-regression checks against AI agents and model endpoints.

**What it does**
- Runs deterministic evaluation cases and records assertions, pass rates and latency.
- Includes baseline probes for prompt injection and related response-level security regressions.
- Connects to compatible model APIs and existing HTTP-agent endpoints through adapters.
- Produces JSON and Markdown reports, with a FastAPI API and local dashboard.
- Stores local evaluation history in SQLite, with optional PostgreSQL configuration.

**Engineering themes:** evaluation design · adapter boundaries · API contracts · security regression testing · reproducibility

> Cognis provides regression signals, not a guarantee of security or a production security certification. Adversarial coverage and deployment hardening remain ongoing work.

</details>

<details>
<summary><b>02 · Invoice Buddy — AI Invoice Intelligence</b></summary>

<br/>

<a href="https://github.com/Xatreus/invoice-buddy"><img src="https://img.shields.io/badge/Explore-Invoice_Buddy-0D9488?style=for-the-badge&logo=github" alt="Explore Invoice Buddy" /></a>

A Python and FastAPI application for extracting structured data from PDF invoices and answering questions about invoice records.

**What it does**
- Extracts structured invoice fields from PDFs using an LLM.
- Combines SQL-backed queries with RAG over invoice-document text.
- Uses tool-calling workflows to answer questions grounded in invoice data.
- Includes invoice lookup, spending summaries, duplicate checks and anomaly-reporting modules.
- Provides REST endpoints, API documentation and automated tests.

**Engineering themes:** document processing · LLM integration · retrieval · persistence · data validation · backend API design

> A personal engineering project intended for local use and demonstration. Review security, privacy and operational controls before using sensitive financial data or deploying publicly.

</details>

<details>
<summary><b>03 · NexPilot Mini — Agent Engineering Prototype</b></summary>

<br/>

<a href="https://github.com/Xatreus/nexpilot-mini"><img src="https://img.shields.io/badge/Explore-NexPilot_Mini-2563EB?style=for-the-badge&logo=github" alt="Explore NexPilot Mini" /></a>

An experimental Python prototype exploring the foundations of a repository and documentation assistant.

- Pydantic models for typed tasks and task results.
- Asynchronous service orchestration and structured logging.
- Explicit service boundaries and custom exceptions.
- A starting point for validated repository inspection, documentation retrieval and tool contracts.

**Engineering themes:** async Python · typed interfaces · task orchestration · error handling · maintainable architecture

> This is an early scaffold: repository analysis and documentation retrieval are currently placeholder services, not a functioning autonomous coding agent.

</details>

---

## 🧰 Technology & Tools

I organize my stack by the engineering problems I'm working to solve, rather than treating every tool as an equal level of expertise.

| Domain | Technologies & concepts |
|---|---|
| **Languages** | Python, SQL |
| **AI / GenAI** | LLM APIs, RAG, embeddings, vector search, tool/function calling, agent workflows |
| **Backend** | FastAPI, REST APIs, Pydantic, SQLAlchemy |
| **Data & storage** | PostgreSQL, SQLite, ChromaDB, document processing |
| **Testing & quality** | pytest, evaluation metrics, regression testing, validation |
| **AI & application security** | Prompt-injection testing, LLM security, API testing, OWASP concepts |
| **Web security** | SQL injection, XSS, IDOR, SSRF, SSTI, path traversal, file-upload flaws, OS command injection |
| **Developer tools** | Git, GitHub, VS Code, Linux, Docker / Docker Compose |

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
</p>

<sub>Skills reflect a mix of hands-on project implementation, practical study and ongoing learning; depth varies by topic.</sub>

---

## 🔐 Security Learning & Practice

I have studied and practiced common web and API vulnerability classes through hands-on labs and security testing.

<details>
<summary><b>View areas explored</b></summary>

- **Injection:** SQL injection, OS command injection, server-side template injection (SSTI)
- **Browser-side:** reflected XSS, DOM-based XSS
- **Access control:** IDOR and authorization weaknesses
- **Server-side requests & files:** SSRF, path traversal, file-upload vulnerabilities
- **API security:** authentication, authorization, input validation and API testing
- **AI security:** prompt injection, tool misuse and LLM application attack surfaces

</details>

---

## 🎓 Certifications

| Certification | Issuer |
|---|---|
| [Oracle Cloud Infrastructure Certified AI Foundations Associate](https://catalog-education.oracle.com/pls/certview/sharebadge?id=FFF3BB90ADA78034EB70717DB0EE92C2640D9AC4F3572540C55C171B53200A20) | Oracle |
| [Oracle Agentic AI Certified Foundations Associate](https://catalog-education.oracle.com/pls/certview/sharebadge?id=D5F89B27F403077F3625D83FB1F6940A54DA55BFD8CFD0B1586F8D0AC7580E58) | Oracle |

---

## 📚 Currently Exploring

- Designing agent workflows with clear tool contracts and failure handling.
- Improving RAG quality, retrieval evaluation and grounded responses.
- Building repeatable AI evaluation and security regression suites.
- Strengthening software architecture, testing and deployment practices.

## 🤝 Let's Connect

I'm open to connecting with engineers and teams working on **GenAI engineering, AI agent development, Python backend systems and AI application security**.

<div align="center">

  <a href="https://www.linkedin.com/in/abdul-rahman-221128258"><img src="https://img.shields.io/badge/LinkedIn-Abdul_Rahman-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn" /></a>
  <a href="mailto:abdulrahmandev22@gmail.com"><img src="https://img.shields.io/badge/Email-Say_Hello-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

  <br/><br/>
  <i>Build thoughtfully. Test relentlessly. Secure by design.</i>

</div>
