# Ashi Malaiya

**Backend & Full-Stack Software Engineer** — I build production-grade distributed systems: fault-tolerant Spring Boot microservices, cloud infrastructure on AWS, and REST APIs that handle real-time financial data at scale.

Currently architecting a 9-service equity intelligence platform in production. Previously debugged carrier-grade telecom infrastructure at **Nokia** (Docker, Kubernetes, Kafka) and shipped full-stack products at **Reliance Jio** and **SDC-MUJ**.

B.Tech Computer Science, CGPA 9.43 · Manipal University · AIR 34 (top 0.03%), National Creativity Olympiad

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/ashi-malaiya)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:ashimalaiya.official@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/Ashi777)

---

## What I Work On

I focus on the backend: designing services, modeling data, and making systems resilient under real-world failure.

- **Distributed systems & microservices** — multi-service architectures with independent, well-bounded REST APIs
- **Reliability engineering** — circuit breakers, retries, and graceful degradation for third-party data dependencies
- **Cloud & deployment** — provisioning and running services on AWS (EC2, RDS, Route 53) with Docker
- **Data pipelines** — scheduled, timezone-aware ingestion and deduplication of high-volume market and news data
- **API design** — authentication (JWT + OTP), role-based access, and clean contracts between services

---

## Areas of Expertise

| Domain | Focus |
|---|---|
| **Backend Engineering** | Java / Spring Boot, Python / Flask & FastAPI, REST API design, microservices |
| **Databases** | PostgreSQL, MySQL, Qdrant (vector search), schema and query design |
| **Cloud & DevOps** | AWS (EC2, RDS, Route 53), Docker, Kubernetes, CI/CD, GitHub Actions, Linux |
| **Distributed Systems** | Resilience4j (circuit breakers, retry), scheduled jobs, Kafka, fault tolerance |
| **Testing & Quality** | pytest, Robot Framework, mypy `--strict`, root-cause analysis |

---

## Technical Skills

**Languages** · Java · Python · JavaScript · TypeScript · SQL · C

**Backend** · Spring Boot · Flask · FastAPI · Node.js · REST APIs · Microservices · JWT / OTP Auth

**Databases** · PostgreSQL · MySQL · Qdrant (Vector DB)

**Cloud & DevOps** · AWS (EC2, RDS, Route 53) · Docker · Docker Compose · Kubernetes · CI/CD · GitHub Actions · Linux

**Messaging & Reliability** · Apache Kafka · Resilience4j · Scheduled Cron Jobs

**Testing** · pytest · Robot Framework · mypy · RAGAS

**AI / ML** · RAG Pipelines · Vector Embeddings · Semantic Search · BM25 · sentence-transformers · Gemini & Groq APIs

**Frontend** · Next.js · D3.js · HTML · CSS

**Tools** · Git · Postman · Prometheus · Grafana · Wireshark · JIRA · Figma

---

## Featured Projects

### PyGit — A Git Version Control Engine, Built from Scratch
`Python` · `Flask` · `REST API` · `D3.js` · `pytest` · `mypy` · `GitHub Actions`

A working reimplementation of Git in **pure Python with zero dependencies** — built to understand version control from first principles.

- **Core engine:** SHA-1 content-addressable storage, zlib compression, Myers O(ND) diff, three-way merge with BFS-based lowest-common-ancestor resolution, and packfile delta decoding.
- **20+ CLI commands** byte-compatible with native Git, validated by **316 pytest tests** and `mypy --strict` in a GitHub Actions CI pipeline.
- **Full-stack visualizer:** a 4-endpoint REST API and D3.js v7 single-page app rendering an interactive topological commit graph, branch overlays, and an in-browser file viewer.
- **Benchmarked at 1.3–1.7× native C Git speed** for staging operations — in interpreted Python.

**→ [github.com/Ashi777/pygit](https://github.com/Ashi777/pygit)**

---

### DocuRetrieve — Production Retrieval-Augmented Generation Engine
`Python` · `FastAPI` · `Next.js` · `TypeScript` · `Qdrant` · `Docker Compose` · `Gemini / Groq`

A full-stack, production-grade RAG platform delivering **sub-second semantic search** over multi-format documents (PDF, HTML, Markdown, images).

- **Hybrid retrieval:** BM25 + `sentence-transformers` with Reciprocal Rank Fusion and cross-encoder reranking, backed by a Dockerized **Qdrant** vector database — running at **$0 infrastructure cost**.
- **Pluggable LLM layer** (Gemini, Groq) with inline citations and token-streaming REST APIs.
- **Test-driven:** 200+ pytest cases and a CI pipeline, plus a **RAGAS** evaluation suite for hallucination detection.
- **Next.js 14 + TypeScript** dashboard front end.

**→ [Live Demo](https://rag-framework-theta.vercel.app/)**

---

## Experience Highlights

**Full Stack Developer — Inboundcy IT Solutions** *(Feb 2026 – Present, Remote)*
- Architecting and leading the AWS cloud deployment of **NiveshFlow**, a **9-service Spring Boot + PostgreSQL** equity intelligence platform with modular REST APIs for real-time NSE announcement ingestion, RSS news aggregation, JWT + OTP auth, and role-based subscription tiers.
- Engineered a fault-tolerant financial data pipeline aggregating live market data across **70+ market and 2,200+ company keywords** via IST-aware scheduled cron jobs — with **Resilience4j** circuit breakers and retries, a **4-layer news deduplication engine** (URL match + Jaccard similarity), a 24-hour rolling retention system, and Python Flask microservices for Yahoo Finance integration.

**Student Intern — Nokia Solutions Network** *(Jul 2024 – May 2025, Gurugram)*
- Built automated test suites in **Robot Framework** across Nokia's Converged Charging (NCC) CI/CD pipelines — a carrier-grade billing platform — surfacing **50+ defects** and strengthening release quality.
- Diagnosed and resolved **60+ production issues** on containerized cloud infrastructure (**Docker, Kubernetes, Kafka, Linux**), performing root-cause analysis with Wireshark, Postman, Prometheus, and Grafana, and reducing MTTR.

**Summer Intern — Reliance Jio** *(Jun 2024 – Jul 2024, Jaipur)*
- Built an internal onboarding knowledge portal that **reduced new-joiner orientation time by 30%**, replacing fragmented department-siloed docs with a unified platform.

**Software Developer Intern — SDC-MUJ** *(Jan 2024 – May 2024, Jaipur)*
- Shipped the full-stack official website (**Next.js, Node.js**) with an Agile/Scrum team of 4 — driving a **40% rise in student outreach** and **25% growth in industry-sponsored collaborations**.

---

## Achievements

- **All India Rank 34 (top 0.03%)** — National Creativity Olympiad, among 100,000+ participants
- **Co-authored a peer-reviewed book chapter** on AI/ML for climate data analysis (Taylor & Francis)
- **Dean's List** for 6 consecutive semesters
- **TGELF Mentor** — CS/math education to 50+ children and entrepreneurship training to 70+ women

---

## Let's Connect

I'm open to **SDE, backend, full-stack (backend-leaning), and software engineering roles**.

📫 **[ashimalaiya.official@gmail.com](mailto:ashimalaiya.official@gmail.com)** · 💼 **[LinkedIn](https://linkedin.com/in/ashi-malaiya)**
