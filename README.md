# Palak Namdev

**AI/ML Engineer — Agentic AI · Generative AI · LLM Infrastructure**

I build production LLM systems: multi-agent orchestration, enterprise RAG, and the
infrastructure that keeps both auditable and cheap to run.

---

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

---

### Tech

| Area | |
|---|---|
| **Agentic AI & Orchestration** | LangGraph · AutoGen GraphFlow · Multi-Agent Systems · Stateful Graph Execution · DAG Scheduling · Conditional Routing · Tool Calling · MCP · Human-in-the-Loop · State Management |
| **Generative AI & LLM** | LangChain · LlamaIndex · LiteLLM · Prompt & Context Engineering · Guardrails · LLM & Agent Evaluation · Model Benchmarking · Prompt Caching · Token & Cost Optimization |
| **RAG & Retrieval** | VectorRAG · GraphRAG · Agentic RAG · Hybrid Search · Reranking · Chunking Strategies · Metadata Filtering · Embeddings · Knowledge Graphs |
| **Document & Multimodal** | Intelligent Document Processing · OCR · Table Parsing · Image / Audio / Video Ingestion · Speech-to-Text · Web Scraping |
| **ML & NLP** | Machine Learning · NLP · Transformers · Hugging Face · PyTorch · TensorFlow · Scikit-learn · Pandas · NumPy |
| **Backend & Distributed** | Python · FastAPI · Django · Flask · Pydantic · REST APIs · Celery · RabbitMQ · Redis · Microservices · Async Processing · Horizontal Scaling |
| **Models** | GPT · Claude · Gemini · LLaMA · Mistral · Qwen · DeepSeek · Whisper |
| **Data & Vector Stores** | PostgreSQL / pgvector · MongoDB · SQLite · Pinecone · Qdrant · Weaviate · ChromaDB · Neo4j |
| **Cloud & DevOps** | Azure · AWS · Docker · CI/CD · Git · Linux · GPU Inference · Grafana · LangSmith |

---

### Certifications

- **Claude Certified Architect — Foundation**, Anthropic
- **Claude Code in Action**, Anthropic
- AI Agentic Design Patterns with AutoGen — Microsoft / DeepLearning.AI
- Building Multimodal Search and RAG — Weaviate / DeepLearning.AI

---

### Interests

Stateful agent graphs · retrieval quality you can actually measure · multi-tenant
isolation · keeping token cost bounded under concurrency

📫 **palak.namdev1701@gmail.com** · [LinkedIn](https://www.linkedin.com/in/palak-namdev)
