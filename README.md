<div align="center">

# Chinmay Shivratriwar

**Backend engineer · Distributed systems · Building toward agentic AI**

Java / Spring Boot · Kafka · LangGraph · Pune, India

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/TODO-your-handle)
[![LeetCode](https://img.shields.io/badge/LeetCode-TODO-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/TODO)
[![Codeforces](https://img.shields.io/badge/Codeforces-TODO-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white)](https://codeforces.com/profile/TODO)

</div>

---

## About

I'm a Software Development Engineer at **Tata Consultancy Services**, with about three years of backend experience in payments-scale systems: high-throughput Kafka pipelines, batch processing, and the failure modes that only show up in production. I care about correctness under load, observability, and systems that degrade gracefully.

I'm now moving toward **agentic AI and product-focused engineering**. I build agent systems the way I build backend services: deterministic where it matters, with LLMs only where they add value, and with guardrails, human-in-the-loop controls, and failure handling designed in from the start.

---

## Experience

### Software Development Engineer · Tata Consultancy Services
*Pune, India · TODO: start month/year – Present*

- Backend engineer on a large-scale payments client account, working in Java/Spring Boot and Kafka-based event pipelines.
- Solo-built a PR-triggered AI agent that generates SQL for schema changes, cutting turnaround from **~2 hours to ~30 seconds**.
- Diagnosed an out-of-memory production issue end to end, from heap analysis to root cause to fix.
- Closed PCI/PII compliance gaps in data-handling paths.
- Implemented SAGA choreography replay for recovering failed distributed transactions.
- Worked directly with business stakeholders on requirements, rollout, and incident follow-up.
- TODO: add 1–2 bullets with real scale numbers (TPS, P99 latency, message volume, data size).

---

## Technical Depth

| Area | What I've worked with |
|---|---|
| **Languages** | Java 21, Python, SQL, TypeScript |
| **Backend** | Spring Boot, Spring Batch, Spring AI, Hibernate/JPA, REST |
| **Distributed systems** | Kafka, Transactional Outbox, SAGA, ShedLock, idempotency, retry/DLQ patterns |
| **Performance** | HikariCP tuning, Caffeine caching, virtual threads, JVM memory diagnosis |
| **Data** | PostgreSQL, pgvector, ChromaDB, Supabase, Neon |
| **AI / Agents** | LangGraph, LangChain, LangSmith, RAG, GraphRAG, MCP, Groq, Cohere, NVIDIA NIM |
| **Infra / Tools** | Docker, Render, Vercel, Git, GitHub Actions |

---

## Projects


### 🔎 NL-SQL Engine
Production natural-language-to-SQL service. Replaced full-schema prompt injection with **GraphRAG schema retrieval**: table embeddings, foreign-key edges, cosine-similarity retrieval, and bidirectional BFS over FK relationships to pull in only the relevant subgraph.
`Java 21` `Spring Boot 3.5` `Spring AI` `Cohere` `PostgreSQL` `React` · Render + Vercel + Supabase

### 🛠️ cns-devintel
MCP server that performs **static AST analysis** of Spring Boot codebases, with no LLM server-side. It detects N+1 queries, transactional pitfalls, security misconfigurations, and volatile in-memory queue anti-patterns, and maps endpoints. It runs bounded-concurrency repo analysis through JGit and StaticJavaParser, and works with agent-mode IDE clients.
`Java` `Spring Boot` `MCP` `JGit` `StaticJavaParser`

### 📚 Ask HR
Agentic RAG chatbot over real HR policy documents. The graph covers routing, retrieval, relevance grading, a query-rewrite retry loop, and a Presidio PII scrub as the final node, traced end to end with LangSmith.
`LangGraph` `FastAPI` `pgvector` `NVIDIA NIM` `Presidio`

---

## Education

**TODO: College / University name**
TODO: Degree, branch · TODO: start year – end year · CGPA/percentage (optional)
TODO: relevant coursework, clubs, or notable academic work (optional)

---

## Competitive Programming

| Platform | Handle | Rating / Rank | Problems solved |
|---|---|---|---|
| LeetCode | TODO | TODO | TODO |
| Codeforces | TODO | TODO | TODO |
| CodeChef | TODO | TODO | TODO |

- TODO: notable contest results (e.g., "Top X% in LeetCode Weekly Contest N")
- TODO: strongest topics (DP, graphs, etc.)

<div align="center">

[![LeetCode Stats](https://leetcard.jacoblin.cool/TODO?theme=dark&font=Inter&ext=heatmap)](https://leetcode.com/u/TODO)

</div>

---

## GitHub Stats

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=ChinmayShivratriwar&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ChinmayShivratriwar&layout=compact&theme=tokyonight&hide_border=true)

![Streak](https://streak-stats.demolab.com?user=ChinmayShivratriwar&theme=tokyonight&hide_border=true)

</div>

---

## Currently

- 🔭 Building **NLSQL**, a production-minded multi-agent reliability suite
- 🌱 Going deeper on agent guardrails, evaluation, and token-efficient multi-agent design
- 💬 Open to talking about distributed systems, agent architecture, and backend reliability

## Collaborate

I'm interested in agentic AI infrastructure, developer tooling (MCP servers, static analysis), and fintech/payments engineering.

## Reach me

📫 **[LinkedIn](https://www.linkedin.com/in/TODO-your-handle)** is the best way to reach me.

<!---
ChinmayShivratriwar/ChinmayShivratriwar is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
--->
