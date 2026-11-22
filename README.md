# Palak Namdev

**AI/ML Engineer — Agentic AI · Generative AI · LLM Infrastructure**

I build production LLM systems: multi-agent orchestration, enterprise RAG, and the
infrastructure that keeps both auditable and cheap to run.

### Selected work

**[RM-Copilot](https://github.com/palak178/RM-Copilot)** — agentic copilot for retail banking
> The LLM plans, selects tools and explains. It never computes a score or asserts a fact —
> all scoring, eligibility and compliance stay deterministic. That split is what makes
> every recommendation auditable and reproducible, which is the only way an AI
> recommendation survives a regulated review.

`FastAPI + SSE` · `typed tool registry` · `versioned prompts` · `guardrails` · `120 tests`

**[audio-transcription-pipeline](https://github.com/palak178/audio-transcription-pipeline)** — offline speech-to-text
> Memory stays bounded independent of audio length, by windowing at silence rather than at
> fixed intervals. Content-probes with ffprobe instead of trusting file extensions, and
> enables VAD by default because Whisper hallucinates on silence.

`faster-whisper` · `CTranslate2` · `Typer CLI` · `queue-backed async` · `CPU-only`

**[LLM_Chatbot](https://github.com/palak178/LLM_Chatbot)** — RAG over uploaded documents
> Answers grounded strictly in retrieved passages, with embeddings persisted to a vector
> store so the same corpus isn't re-embedded on every session.

`SentenceTransformer` · `Qdrant` · `Streamlit`

### Working with

`Python` `FastAPI` `AutoGen GraphFlow` `LangGraph` `MCP` `LiteLLM`
`Celery` `RabbitMQ` `Redis` `PostgreSQL / pgvector` `Pinecone` `Qdrant` `Weaviate` `Neo4j`
`Docker` `Azure` `AWS`

### Interests

Stateful agent graphs · retrieval quality you can actually measure · multi-tenant
isolation · keeping token cost bounded under concurrency

📫 **palak.namdev1701@gmail.com** · [LinkedIn](https://www.linkedin.com/in/palak-namdev)
