

# Chaitanya Chollangi

**AI engineer — I build multi-agent systems that have to be right, not just fluent.**

Most LLM demos are impressive until you ask them for a number. My work is about the layer
that makes agent output trustworthy: grounded retrieval, critic loops that reject unsupported
claims, deterministic verification, and eval harnesses that put a score on it.

B.Tech CS, VIT Bhopal (2026) · Hyderabad, open to Bengaluru · Looking for AI/ML engineering roles

[Portfolio](https://riishii21.github.io) ·
[LinkedIn](https://www.linkedin.com/in/chollangi-chaitanya/) ·
[chollangichaitanya04@gmail.com](mailto:chollangichaitanya04@gmail.com)

---

## What I'm building

**[VERITAS — Equity Research Swarm](https://github.com/Riishii21/equity-research-swarm)** · [live demo](https://equity-research-swarm.onrender.com)
Six-agent LangGraph swarm that turns a ticker into a fully-cited research brief from SEC EDGAR
filings. Hybrid BM25 + semantic retrieval, a Critic agent that flags any claim without a source,
and an eval harness that scores groundedness. Async FastAPI + SSE backend, WebGL frontend.
`LangGraph` `RAG` `FastAPI` `Groq` `SEC EDGAR`

**[TaxLens](https://github.com/Riishii21/taxlens)**
Prototype that makes Indian Income Tax notices legible: verify the message, understand it, draft a
response, submit through a mocked gov adapter. AI orchestrates data only — a deterministic state
machine owns every consequential step, and the citizen approves before anything moves.
`Next.js` `FastAPI` `Safety validation` `25 tests, ruff + mypy`

**[AI Translator](https://github.com/Riishii21/AI_Translator_Project)**
Document translation pipeline pairing EasyOCR vision with Llama 3.2 — layout-aware extraction
through to translated output.
`EasyOCR` `Llama 3.2` `Python`

**[Smart Expense Tracker](https://github.com/Riishii21/smart-expense-tracker)**
FastAPI REST API with concurrency-safe writes and 47 pytest cases — the unglamorous half of the
job, done properly.
`FastAPI` `pytest` `SQLite`

---

## Stack

**Core** Python · FastAPI · LangGraph / LangChain · PyTorch
**Retrieval** Hybrid RAG (BM25 + dense) · ChromaDB · SEC EDGAR / FMP ingestion
**Serving** Docker · AWS · Render · Streamlit · SSE / async
**Data** SQL · Pandas · NumPy
**Vision** YOLO · OpenCV · EasyOCR

---

## How I work

- Every agent system ships with an eval harness. If I can't score it, I don't claim it.
- Deterministic checks wrap non-deterministic components — LLMs propose, code verifies.
- Sources or it didn't happen: citation-linked output, and a critic pass that kills the rest.

![Chaitanya's GitHub stats](https://github-readme-stats.vercel.app/api?username=Riishii21&show_icons=true&hide_border=true&theme=transparent&hide=issues)
