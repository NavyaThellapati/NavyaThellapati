# Navya Thellapati

## Building reliable backend systems, financial platforms, distributed workflows, and data-driven applications

Software Engineer with 4+ years of experience designing Python backend applications, REST APIs, microservice-style services, relational data models, ETL pipelines, and automated delivery workflows. My professional work spans banking and enterprise systems, with a focus on transactional correctness, SQL performance, data validation, and maintainable service architecture.

[Portfolio](https://navya-portfolio-sable.vercel.app) · [LinkedIn](https://www.linkedin.com/in/navya-thellapati/) · [Email](mailto:navyachowdary.thellapati@gmail.com) · [Resume](https://navya-portfolio-sable.vercel.app/Navya-Thellapati-Resume.pdf)

<table>
  <tr>
    <td align="center"><strong>30+</strong><br><sub>backend services and APIs across two roles</sub></td>
    <td align="center"><strong>5K+</strong><br><sub>daily banking records supported</sub></td>
    <td align="center"><strong>40%</strong><br><sub>deployment-time reduction</sub></td>
    <td align="center"><strong>30%</strong><br><sub>SQL query-runtime reduction</sub></td>
  </tr>
</table>

## About Me

```yaml
role: Software Engineer / Backend Engineer
experience: 4+ years
core_stack:
  - Python
  - FastAPI
  - PostgreSQL
  - SQL
  - Docker
  - REST APIs
engineering_focus:
  - Backend systems and microservices
  - Financial transaction processing
  - Distributed job execution
  - Relational database design
  - ETL and workflow automation
  - CI/CD-driven delivery
currently_exploring:
  - Retrieval-augmented generation
  - LLM-integrated applications
  - Vector databases and semantic search
mobility: Open to relocation
```

## Current Focus

- Building production-style Python services with FastAPI, explicit service boundaries, validation, and tested APIs.
- Designing transaction-processing workflows around data consistency, traceability, and safe concurrent operations.
- Developing asynchronous and distributed background-processing systems with retry and recovery paths.
- Improving PostgreSQL schema design, query performance, and data-quality controls.
- Integrating RAG, LangChain, and vector retrieval into secure, source-grounded applications.

## Experience Highlights

### Truist — Software Engineer III

<sub>May 2025 - June 2026</sub>

- Designed and maintained 10+ Python services and REST APIs supporting banking integrations and account and transaction workflows processing 5K+ daily records.
- Structured microservice-style components around clear API, business-logic, and data-access boundaries, reducing new-feature development time by 20%.
- Modeled relational schemas and optimized complex validation, reconciliation, and reporting queries, reducing query runtime by 30%.
- Automated packaging, testing, and deployment pipelines, reducing deployment time by 40% and improving release consistency.

### Accenture Solutions — Software Engineer

<sub>June 2021 - July 2024</sub>

- Built Python and SQL automation for account provisioning, workflow orchestration, and data validation, removing 300+ recurring manual checks and improving processing efficiency by 28%.
- Developed and integrated 20+ backend services using Python, REST APIs, and JSON/XML integrations, supporting 6K+ daily account, billing, and platform records.
- Built Python/SQL ETL pipelines for validated reporting data, reducing recurring load errors by 22%.
- Packaged and deployed Python services through Jenkins and Azure DevOps, supporting 12+ releases with repeatable CI/CD workflows.

## Tech Stack

| Area | Technologies |
| --- | --- |
| **Languages** | Python, JavaScript, TypeScript, SQL, Bash |
| **Backend** | FastAPI, Flask, REST APIs, microservices, SQLAlchemy, OpenAPI, JWT, JSON/XML integration |
| **Frontend** | React, HTML5, CSS3, responsive and component-based UI development |
| **Databases** | PostgreSQL, SQL Server, relational modeling, query optimization |
| **Cloud and delivery** | Docker, Jenkins, GitHub Actions, Azure DevOps, Linux, Git, CI/CD |
| **Testing** | Unit testing, API testing, integration testing, Postman, regression testing, test-data validation |
| **Data and AI** | Pandas, NumPy, TensorFlow, scikit-learn, LangChain, OpenAI API, Llama 3, ChromaDB, RAG, semantic search |

## Selected Projects

### [DocuMind — Document-Grounded AI Assistant](https://github.com/NavyaThellapati/documind-ai-document-qa-assistant)

**What it does:** Lets authenticated users upload PDF, TXT, and DOCX files and ask questions whose answers are grounded in retrieved document passages with source citations.

**Engineering highlights**

- Separates React presentation, FastAPI endpoints, relational metadata, document processing, retrieval, and LLM orchestration.
- Enforces user-scoped document and conversation access with JWT authentication and refresh-token rotation.
- Validates uploads, processes documents asynchronously, and preserves page and chunk metadata for attributable answers.
- Includes Alembic migrations, backend and frontend tests, Docker Compose, API documentation, and GitHub Actions CI.

**Architecture:** `React + TypeScript → FastAPI → SQLAlchemy / PostgreSQL → document pipeline → ChromaDB → grounded LLM response`

**Engineering decisions:** Uploaded content is treated as untrusted reference data; retrieval is filtered by user and document ownership; unsupported answers use an explicit fallback instead of inventing information.

**Stack:** `Python` `FastAPI` `React` `TypeScript` `PostgreSQL` `ChromaDB` `Docker`

### [Patient Portal Platform](https://github.com/NavyaThellapati/mychart---homepage)

**What it does:** Provides authenticated appointment, medication, test-result, billing, messaging, and guided-navigation workflows over a React client and PostgreSQL-backed Express API.

**Engineering highlights**

- Implements registration, JWT authentication, optional email MFA, password recovery, role-aware authorization, and audit logging.
- Applies user-level ownership checks, parameterized SQL, input validation, rate limits, and appointment-conflict detection.
- Exercises authentication and appointment workflows with PostgreSQL integration tests in GitHub Actions.
- Documents security boundaries, deployment tradeoffs, and remaining requirements for a real healthcare environment.

**Architecture:** `React + TypeScript → Express REST API → authentication / service logic → PostgreSQL → SMTP provider`

**Engineering decisions:** Sensitive actions create audit records; password-reset and MFA secrets are hashed and expire; generic recovery responses reduce account enumeration risk.

**Stack:** `React` `TypeScript` `Node.js` `Express` `PostgreSQL` `JWT` `GitHub Actions`

### [Developer Portfolio](https://github.com/NavyaThellapati/navya_portfolio) · [Live site](https://navya-portfolio-sable.vercel.app)

A responsive engineering portfolio with technical case studies, accessible motion, persistent light/dark themes, and route-aware Vercel deployment.

**Architecture:** `React components → typed portfolio data → case-study routes → Vite build → Vercel`

**Stack:** `React` `TypeScript` `Vite` `Tailwind CSS` `Framer Motion` `Vercel`

> The banking reconciliation and distributed workflow repositories will be featured here after their résumé-listed implementations are available publicly. Empty repositories are not presented as completed engineering evidence.

## AI-Integrated Software Engineering

My primary focus is backend engineering. I also build AI-enabled application layers using retrieval-augmented generation, LangChain, OpenAI-compatible APIs, Llama 3, ChromaDB, vector databases, semantic search, Sentence Transformers, prompt design, and source attribution. I treat model integration as a software reliability problem: constrain inputs, preserve provenance, handle unavailable evidence, and test the surrounding application behavior.

## GitHub Analytics

<p>
  <img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=NavyaThellapati&theme=transparent" alt="Navya Thellapati's public GitHub repository statistics">
  <img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=NavyaThellapati&theme=transparent" alt="Navya Thellapati's public repositories by language">
</p>

<sub>Language distribution reflects public repository composition, not proficiency.</sub>

## Education

### University of South Florida

**Master of Science in Computer Science**<br>
August 2024 - May 2026 · Tampa, Florida

## Let's Connect

I am interested in software engineering and backend engineering opportunities involving scalable APIs, distributed systems, financial technology, cloud delivery, and data-intensive applications.

[LinkedIn](https://www.linkedin.com/in/navya-thellapati/) · [Email](mailto:navyachowdary.thellapati@gmail.com) · [GitHub](https://github.com/NavyaThellapati) · [Portfolio](https://navya-portfolio-sable.vercel.app) · [Resume](https://navya-portfolio-sable.vercel.app/Navya-Thellapati-Resume.pdf)

Open to relocation.
