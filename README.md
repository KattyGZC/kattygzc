# Hi, I'm Kathy Zambrano

**Senior Software Engineer · Backend & Full-Stack**
Python · TypeScript · Node.js · Go · FastAPI · Django · React · PostgreSQL · AWS
Remote from Ecuador (UTC-5) · Spanish (native) · English (B2)

I've spent six years building APIs, microservices and the products on top of them for teams in the US, Mexico, Argentina, Chile and Spain. Most of my work is backend: designing services, modeling data in PostgreSQL, wiring third-party integrations, and finding out why production broke. I also build the React screens those services need.

> **Open to work:** senior backend or full-stack roles, remote, full-time or contract.
> [LinkedIn](https://www.linkedin.com/in/kathy-gzc) · [katherine.zambrano.tech@gmail.com](mailto:katherine.zambrano.tech@gmail.com)

---

## What I've worked on

- **Multi-tenant SaaS platform** (Simbe Family, 2026). TypeScript, Supabase edge functions, PostgreSQL and React. I moved legacy automation to an event-driven model, built CRM export pipelines with retries (HubSpot, Zoho, Monday.com, Salesforce), and traced production incidents to their cause with SQL.
- **Growth for a consumer mobile app** (Belozfi, YC W22, 2025–2026). A/B testing across mobile and web, a support ticketing service in Go and PostgreSQL, a growth data warehouse that pulls attribution data from Meta, Google and TikTok, and containerized services on AWS ECS.
- **API performance** (N5 Now, 2024–2025). FastAPI, SQLAlchemy and MongoDB. I cut responses that took several minutes to under one minute.
- **Legacy migration and ETL** (Vigigo, 2022–2024). I moved legacy systems to Django and Oracle and reworked an ETL process, which cut data loss by up to 40%.

## Projects

| Project | What it is | Stack |
|---|---|---|
| [**Alba**](https://github.com/jael0x/alba) | Credit pre-qualification assistant for a LATAM bank, built with a teammate for the Factored AI & Data Hackathon 2026. A versioned policy makes the decision, the LLM only interprets what the customer writes, and borderline cases go to a human consultant. | Python, FastAPI, PostgreSQL, React, Claude API, Docker |
| [**Job Hunter**](https://github.com/jael0x/job-hunter) | A local-first job search tracker with a CLI, an MCP server that lets an AI agent work the pipeline, and a live dashboard. Co-author. | Node.js, MCP |
| [**Loan Simulator**](https://github.com/KattyGZC/loan-simulator) | Chrome extension that simulates loans from any bank or credit union in Ecuador: French and German amortization, insurance, extra payments. Everything runs in the browser. *In development.* | TypeScript, Chrome Extensions |
| [**F1 Strategy Agent**](https://github.com/KattyGZC/f1-strategy-agent) | Natural-language assistant for Formula 1 data: telemetry, results and FIA regulations, with streamed answers. *In progress.* | Python, FastAPI, LangGraph, pgvector |
| [**Multi-tenant Applicant Pipeline**](https://github.com/KattyGZC/multi-tenant-simple-pipeline) | Hiring pipeline where each organization configures its own stages and allowed transitions, with webhooks and emails processed asynchronously. Runs with one `docker-compose up`. | TypeScript, Express, Prisma, React |

## Tech

| | |
|---|---|
| **Languages** | Python, TypeScript, JavaScript, Go, SQL |
| **Backend** | FastAPI, Django, Express.js, Node.js, REST, OpenAPI, microservices, event-driven workflows |
| **Frontend** | React, Next.js, React Native |
| **Data** | PostgreSQL, SQL Server, Oracle, MongoDB, Supabase, pgvector |
| **Cloud & tooling** | AWS (ECS), Docker, CI, unit testing, BDD, Git |
| **AI** | Claude API, LangGraph, RAG, MCP; Claude Code and Cursor in my daily work |

## How I work

- I start incidents from the data. I query what actually happened before I touch any code.
- I write down decisions where the next person will find them, in a README, an ADR or the PR description.
- I keep AI where it's useful and keep it away from decisions that have to be deterministic and auditable.
