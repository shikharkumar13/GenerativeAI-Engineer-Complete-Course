## Generative AI Engineer Series
 
A practical, code-first curriculum for becoming a Generative AI Engineer; from transformers and embeddings through LangChain, RAG, and LangGraph agents, in 42 articles across 7 phases, each paired with a short companion video.
 
![Articles](https://img.shields.io/badge/articles-42-2F6FED)
![Phases](https://img.shields.io/badge/phases-7-7C3AED)
![Format](https://img.shields.io/badge/format-article%20%2B%20video-0F9D58)
![Status](https://img.shields.io/badge/status-in%20progress-F4B400)
 
---
 
## Contents
 
- [What this is](#what-this-is)
- [Who it's for](#who-its-for)
- [How this series works](#how-this-series-works)
- [Curriculum](#curriculum)
  - [Phase 1: Foundations of Generative AI](#phase-1-foundations-of-generative-ai)
  - [Phase 2: Working with LLMs](#phase-2-working-with-llms)
  - [Phase 3: Vector Databases & Embeddings](#phase-3-vector-databases--embeddings)
  - [Phase 4: LangChain](#phase-4-langchain)
  - [Phase 5: Retrieval Augmented Generation (RAG)](#phase-5-retrieval-augmented-generation-rag)
  - [Phase 6: LangGraph & Agentic AI](#phase-6-langgraph--agentic-ai)
  - [Phase 7: Deployment & Capstone Projects](#phase-7-deployment--capstone-projects)
  - [Bonus capstone projects](#bonus-capstone-projects)
- [Repository layout](#repository-layout)
- [Where to go next](#where-to-go-next)
- [Notes](#notes)
---
 
## What this is
 
42 articles, organized into 7 phases, taking a reader from "what is generative AI" to shipping a deployed, agentic RAG application. Every phase builds on the one before it for example, embeddings before vector databases, vector databases before RAG, chains before agents, so the series is meant to be read in order rather than sampled topic by topic.
 
Each article follows the same shape: the concept explained in plain language first, then a full, runnable implementation. Nothing is left as "an exercise for the reader"; every idea introduced gets code that actually produces it.
 
### Who it's for
 
New data science and machine learning learners moving into generative AI engineering. It assumes the basic knowledge of Python, Machine Learning, Model training but no prior exposure to LLMs, LangChain, or vector databases.
 
### What you need
 
- Python 3.9+
- A free-tier account with an LLM provider (OpenAI and/or Anthropic) from Phase 2 onward
- A Google Colab account (or a local GPU) for the hands-on fine-tuning article in Phase 2
- No prior LangChain, vector database, or agent experience required
---
 
## How this series works
 
Every numbered article in the tables below ships as:
 
- a **written article** (theory plus a complete, working implementation), and
- a **video** covering the same material.
Each article also carries a format tag:
 
| Tag | Meaning |
| --- | --- |
| `Theory` | Concept-first, light or no code — builds the mental model the next articles depend on |
| `Hands-on` | A full, runnable implementation of the concept |
| `Project` | Multiple concepts assembled into one larger, portfolio-ready build |
 
---
 
## Curriculum
 
### Phase 1: Foundations of Generative AI
 
Bridging machine learning into generative AI — the concepts every later phase depends on.
 
| # | Topic | Format | Article | Video |
| --- | --- | --- | --- | --- |
| 01 | **What is Generative AI**<br>Discriminative vs. generative models, types of GenAI, real-world use cases | `Theory` | [Article 1](https://shikharkumar13.github.io/GenerativeAI-Engineer-Complete-Course/1.%20What%20is%20Generative%20Ai.html) | *Coming soon* |
| 02 | **The Transformer architecture**<br>Why transformers replaced RNNs, self-attention intuition, encoder vs. decoder | `Theory` | [Article 2](https://shikharkumar13.github.io/GenerativeAI-Engineer-Complete-Course/2.%20Transformers%20(Architecture%20behind%20every%20LLM)%20.html) | *Coming soon* |
| 03 | **Tokenization explained**<br>BPE, WordPiece, SentencePiece, building a tokenizer from scratch, token costs | `Hands-on` | [Article 3](https://shikharkumar13.github.io/GenerativeAI-Engineer-Complete-Course/3.%20Tokenization%20-%20How%20text%20becomes%20numbers.html) | *Coming soon* |
| 04 | **Embeddings from scratch**<br>Word2Vec intuition, sentence embeddings, visualizing embedding space | `Hands-on` | [Article 4](https://shikharkumar13.github.io/GenerativeAI-Engineer-Complete-Course/4.%20Embeddings%20from%20scratch.html) | *Coming soon* |
| 05 | **Attention mechanism deep dive**<br>Query/Key/Value, multi-head attention, positional encoding | `Theory` | *Coming soon* | *Coming soon* |
| 06 | **Prompt engineering basics**<br>Zero-shot vs. few-shot, chain-of-thought, temperature/top-p/top-k | `Hands-on` | *Coming soon* | *Coming soon* |
 
### Phase 2: Working with LLMs
 
Moving from theory to building — calling, running, evaluating, and adapting real LLMs.
 
| # | Topic | Format | Article | Video |
| --- | --- | --- | --- | --- |
| 07 | **LLM APIs: OpenAI & Anthropic**<br>Chat completions, streaming responses, rate limits and error handling | `Hands-on` | *Coming soon* | *Coming soon* |
| 08 | **Open-source LLMs with HuggingFace**<br>Model hub, `transformers` pipelines, 4-bit quantization, running models locally | `Hands-on` | *Coming soon* | *Coming soon* |
| 09 | **Advanced prompt engineering with Instructor and Pydantic**<br>Structured output, validation and retries, ReAct prompting | `Hands-on` | *Coming soon* | *Coming soon* |
| 10 | **LLM evaluation strategies**<br>BLEU/ROUGE/BERTScore, LLM-as-a-judge, building an evaluation harness | `Hands-on` | *Coming soon* | *Coming soon* |
| 11 | **Fine-tuning an LLM (theory)**<br>Full fine-tuning vs. PEFT, LoRA and QLoRA explained, fine-tuning vs. RAG | `Theory` | *Coming soon* | *Coming soon* |
| 12 | **Fine-tuning in practice with LoRA**<br>Dataset preparation, training with PEFT/TRL on a free GPU, saving and merging adapters | `Hands-on` | *Coming soon* | *Coming soon* |
| 13 | **LLM safety & responsible use**<br>Hallucination mitigation, prompt injection, guardrails | `Theory` | *Coming soon* | *Coming soon* |
 
### Phase 3: Vector Databases & Embeddings
 
The storage and retrieval layer every RAG system in Phase 5 is built on.
 
| # | Topic | Format | Article | Video |
| --- | --- | --- | --- | --- |
| 14 | **Vector databases explained**<br>Approximate nearest neighbor search, HNSW and IVF indexes, why traditional databases fall short | `Theory` | *Coming soon* | *Coming soon* |
| 15 | **Embedding models deep dive**<br>Reading the MTEB leaderboard, benchmarking models on your own data, OpenAI vs. open-source | `Hands-on` | *Coming soon* | *Coming soon* |
| 16 | **ChromaDB hands-on**<br>Local persistent vector store, metadata filtering, a reusable retrieval class | `Hands-on` | *Coming soon* | *Coming soon* |
| 17 | **Pinecone for production**<br>Serverless indexes, namespaces for multi-tenancy, sparse-dense hybrid search | `Hands-on` | *Coming soon* | *Coming soon* |
| 18 | **FAISS for custom pipelines**<br>Index types (Flat, IVF, HNSW, IVF-PQ), GPU acceleration, offline deployment | `Hands-on` | *Coming soon* | *Coming soon* |
 
### Phase 4: LangChain
 
The orchestration framework that connects every component built so far.
 
| # | Topic | Format | Article | Video |
| --- | --- | --- | --- | --- |
| 19 | **LangChain core concepts**<br>The Runnable interface, six core components, your first LCEL pipeline | `Theory` | *Coming soon* | *Coming soon* |
| 20 | **Prompt templates and output parsers**<br>`ChatPromptTemplate`, `with_structured_output`, handling parsing failures | `Hands-on` | *Coming soon* | *Coming soon* |
| 21 | **Chains with LCEL**<br>Parallel branches, conditional routing, fallbacks between models | `Hands-on` | *Coming soon* | *Coming soon* |
| 22 | **Memory and conversation history**<br>Memory types compared, `RunnableWithMessageHistory`, Redis-backed persistence | `Hands-on` | *Coming soon* | *Coming soon* |
| 23 | **Document loaders & text splitters**<br>PDF/web/CSV loaders, chunking strategy, splitting for retrieval | `Hands-on` | *Coming soon* | *Coming soon* |
| 24 | **Tools and function calling**<br>Custom tools, the `@tool` decorator, native function calling | `Hands-on` | *Coming soon* | *Coming soon* |
| 25 | **LangChain agents**<br>ReAct agents from scratch, prebuilt tool-calling agents | `Hands-on` | *Coming soon* | *Coming soon* |
| 26 | **LangSmith for observability**<br>Tracing chains and agents, datasets and evaluators, CI for prompts | `Hands-on` | *Coming soon* | *Coming soon* |
 
### Phase 5: Retrieval Augmented Generation (RAG)
 
The single most important pattern in production generative AI.
 
| # | Topic | Format | Article | Video |
| --- | --- | --- | --- | --- |
| 27 | **RAG architecture fundamentals**<br>Indexing vs. retrieval vs. generation, the naive RAG pipeline | `Theory` | *Coming soon* | *Coming soon* |
| 28 | **Build your first RAG pipeline**<br>PDF ingestion to vector store, query → retrieve → generate, end-to-end with LangChain | `Hands-on` | *Coming soon* | *Coming soon* |
| 29 | **Advanced retrieval techniques**<br>Hybrid search, maximum marginal relevance, parent-document retriever | `Hands-on` | *Coming soon* | *Coming soon* |
| 30 | **Query transformation strategies**<br>HyDE, multi-query retrieval, step-back prompting | `Hands-on` | *Coming soon* | *Coming soon* |
| 31 | **Reranking and post-retrieval**<br>Cross-encoder reranking, Cohere Rerank, contextual compression | `Hands-on` | *Coming soon* | *Coming soon* |
| 32 | **Evaluating RAG systems**<br>Faithfulness, relevance and recall, the RAGAS framework | `Hands-on` | *Coming soon* | *Coming soon* |
| 33 | **Production RAG patterns**<br>Chunking tables and code, multi-modal RAG, caching and cost optimization | `Project` | *Coming soon* | *Coming soon* |
 
### Phase 6: LangGraph & Agentic AI
 
Stateful, multi-step agents that plan, reason, and self-correct.
 
| # | Topic | Format | Article | Video |
| --- | --- | --- | --- | --- |
| 34 | **Why LangGraph? Agents vs. chains**<br>Limitations of linear chains, graphs/nodes/state, when to reach for LangGraph | `Theory` | *Coming soon* | *Coming soon* |
| 35 | **LangGraph core: state & nodes**<br>State schema, adding nodes and edges, conditional routing | `Hands-on` | *Coming soon* | *Coming soon* |
| 36 | **Building a ReAct agent in LangGraph**<br>Tool-calling loop, human-in-the-loop checkpoints, persistence | `Hands-on` | *Coming soon* | *Coming soon* |
| 37 | **Multi-agent systems**<br>Supervisor pattern, hierarchical agent teams, parallel execution | `Hands-on` | *Coming soon* | *Coming soon* |
| 38 | **Long-running agents & interrupts**<br>Streaming agent events, interrupt-and-approve patterns | `Hands-on` | *Coming soon* | *Coming soon* |
| 39 | **Agentic RAG with LangGraph**<br>Self-corrective RAG loop, routing between retrievers, hallucination detection | `Project` | *Coming soon* | *Coming soon* |
 
### Phase 7: Deployment & Capstone Projects
 
Shipping real applications and building a portfolio that proves the skill.
 
| # | Topic | Format | Article | Video |
| --- | --- | --- | --- | --- |
| 40 | **Deploying GenAI apps**<br>FastAPI + LangServe, Docker, monitoring with LangSmith and Prometheus | `Hands-on` | *Coming soon* | *Coming soon* |
| 41 | **Cost, latency & reliability**<br>Semantic caching, model fallback patterns, token budgeting | `Theory` | *Coming soon* | *Coming soon* |
| 42 | **Capstone: full-stack GenAI app**<br>Agentic RAG chatbot with memory, a frontend, end-to-end deployment | `Project` | *Coming soon* | *Coming soon* |
 
### Bonus capstone projects
 
Three additional, self-contained projects — not counted in the 42 core articles —
for extra portfolio pieces once Phase 7 is complete.
 
| # | Topic | Format | Article | Video |
| --- | --- | --- | --- | --- |
| P1 | **Document QA system**<br>Multi-format ingestion, hybrid retrieval, source citation | `Project` | *Coming soon* | *Coming soon* |
| P2 | **AI coding assistant**<br>GitHub repo ingestion, code-aware chunking, an agent with a code execution tool | `Project` | *Coming soon* | *Coming soon* |
| P3 | **Research agent**<br>Web search and scraping tools, report synthesis loop, export to PDF | `Project` | *Coming soon* | *Coming soon* |
 
---
 
## Progress
 
- [ ] **Phase 1** — Foundations of Generative AI (0/6)
- [ ] **Phase 2** — Working with LLMs (0/7)
- [ ] **Phase 3** — Vector Databases & Embeddings (0/5)
- [ ] **Phase 4** — LangChain (0/8)
- [ ] **Phase 5** — Retrieval Augmented Generation (RAG) (0/7)
- [ ] **Phase 6** — LangGraph & Agentic AI (0/6)
- [ ] **Phase 7** — Deployment & Capstone Projects (0/3, + 0/3 bonus projects)
---
 
## Repository layout
 
A suggested layout — adjust folder names to match however the articles end up
hosted (this repo directly, GitHub Pages, or an external blog):
 
```
.
├── phase-1-foundations/
│   ├── 01-what-is-generative-ai.html
│   ├── 02-transformer-architecture.html
│   └── ...
├── phase-2-working-with-llms/
├── phase-3-vector-databases/
├── phase-4-langchain/
├── phase-5-rag/
├── phase-6-langgraph/
├── phase-7-deployment-capstone/
├── bonus-projects/
│   ├── document-qa-system/
│   ├── ai-coding-assistant/
│   └── research-agent/
└── README.md
```
 
Each article folder is meant to hold the article itself alongside any notebook,
script, or dataset it references, so a reader can clone the repo and run the
code for that article without hunting for dependencies elsewhere.
 
---
 
## Where to go next
 
This series assumes a prior Machine Learning series as its foundation and ends
with a deployed, agentic RAG application. If you know basic fundamentals of Machine Learning and Deep Learning, natural next steps are:
 
1. **This series.** Generative AI fundamentals through LangChain, RAG, and LangGraph.
2. **The bonus capstone projects.** Three additional builds to round out a portfolio.
3. **Specialized production topics.** Evaluation at scale, multi-agent orchestration,
   and MLOps for LLM-powered systems.
---
 
## Notes
 
- Articles are added to the tables above as they are published.
- The series is meant to be followed in phase order: later phases assume the
  vocabulary and code from earlier ones (Phase 5's RAG pipeline reuses the vector
  stores from Phase 3 and the chains from Phase 4, for example).
- Phase 2 onward requires API access to at least one LLM provider (OpenAI and/or
  Anthropic); Phase 2's fine-tuning article additionally needs a GPU, available
  for free through Google Colab.
