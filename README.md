# Hi, I'm Priya

### Full-stack engineer building applied AI products

Based in **Dubai, UAE**. My background is in full-stack software development with **React, TypeScript and Node.js**, with recent work focused on **Python, FastAPI and LLM applications**.

I build across the frontend, APIs and cloud infrastructure. My personal AI projects explore retrieval quality, structured answers, evaluation and observability.

**Open to:** Full Stack Engineer (AI products), Applied AI / LLM Application Engineer, and Python Backend Engineer roles. Interested in UAE opportunities, international remote roles where location eligibility permits, and opportunities in Bengaluru or Singapore.

[LinkedIn](https://www.linkedin.com/in/priya-raja-web/) · [Email](mailto:priya.thevar89@gmail.com)

---

## Featured projects

### AeroNova — airline knowledge assistant

A RAG application built around a **fictional airline corpus**, covering questions such as baggage policies and cabin menus.

- Combines **BM25 and Qdrant vector retrieval** with topic and policy-year filtering.
- Produces **Pydantic-structured answers** with source chunk citations and citation validation.
- Checks document content hashes to detect an outdated index.
- Explores **JEV routing**, versioned prompts and **Phoenix tracing** to understand quality and latency tradeoffs.

**Stack:** Python · LangChain · Qdrant · OpenAI · BM25 · Pydantic · Phoenix

[Explore AeroNova](https://github.com/Priya-raja/Agentic_System_Design/tree/main/rag_airlines) · [Retrieval implementation](https://github.com/Priya-raja/Agentic_System_Design/blob/main/rag_airlines/retrieve.py) · [Answer and citation validation](https://github.com/Priya-raja/Agentic_System_Design/blob/main/rag_airlines/answer.py)

### Digital Twin — AI portfolio assistant

A personal portfolio chatbot that answers questions using supplied professional background and communication context.

- **Next.js frontend** connected to a **FastAPI backend**.
- Uses **AWS Bedrock** for responses and **S3** for conversation storage.
- Includes **Terraform infrastructure** for Lambda, API Gateway, S3 and CloudFront, plus GitHub Actions deployment workflows.

**Stack:** Next.js · React · TypeScript · FastAPI · AWS Bedrock · S3 · Lambda · Terraform

[Explore Digital Twin](https://github.com/Priya-raja/digital-twin) · [Backend](https://github.com/Priya-raja/digital-twin/blob/main/backend/server.py) · [Infrastructure](https://github.com/Priya-raja/digital-twin/blob/main/terraform/main.tf)

### Educosys Claude — code assistant foundations

**Work in progress.** A Python project exploring code context and a CLI for a RAG-powered coding assistant. The public CLI currently scaffolds the `/ask` flow; retrieval-to-LLM integration remains a TODO.

[Explore the project](https://github.com/Priya-raja/Agentic_System_Design/tree/main/educosys_claude)

---

## Merged open-source contributions

I contributed a phonetic similarity comparator and corresponding SDK support to **FutureAGI**.

| Contribution | Implementation | Status |
| --- | --- | --- |
| [FutureAGI #617](https://github.com/future-agi/future-agi/pull/617) | Pure-Python Soundex-based phonetic similarity comparator integrated with the grounded evaluator interface | Merged |
| [Agent Learning Kit #48](https://github.com/future-agi/agent-learning-kit/pull/48) | Python and TypeScript SDK comparator support, with test updates | Merged |

---

## Core technologies

| Area | Technologies |
| --- | --- |
| Frontend | React, Next.js, TypeScript, Tailwind CSS |
| Backend | Python, FastAPI, Node.js, PostgreSQL, MongoDB |
| Applied AI | LangChain, OpenAI API, AWS Bedrock, Qdrant, BM25, Pydantic |
| Cloud and tooling | AWS, Docker, Terraform, GitHub Actions, Phoenix |

## Engineering interests

- Grounded answers and retrieval quality
- Evaluation datasets and regression checks
- Agent tracing, latency and cost tradeoffs
- Shipping usable AI features across frontend, backend and cloud

My repositories include both personal applications and learning exercises. The featured projects above are the best starting point for reviewing my work.
