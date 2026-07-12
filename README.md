# 👋 Hey — I’m Utkarsh Singh

**AI Engineer specializing in local LLMOps and production RAG architectures.**

I bridge the gap between cutting-edge AI research and secure, stable software engineering. I build autonomous, tool-capable systems that focus deeply on production-grade resilience, strict input validation, and zero-hallucination constraints. 

---

### 🔭 What I do right now

* **Multi-Agent Orchestration & Tool-Use:** Developing lightweight, secure execution environments utilizing the Model Context Protocol (MCP) to connect local and cloud LLMs securely to live system tools (Stripe, Gmail, CRMs).
* **Local & Privacy-Preserving AI:** Architecting resource-optimized inference pipelines on consumer edge hardware to process high-stakes data without external cloud API dependencies.
---

### 🛠️ Featured Open-Source & R&D Work

#### 🎙️ [Voice-Enabled Invoice Agent](https://github.com/Hustple/Voice_Agent) | [Live Video Demo](https://youtu.be/hl1az0yU5tc)
*An end-to-end autonomous accounts receivable system with real-time bidirectional voice I/O.*
* **The Stack:** Groq LLaMA 3.1, local OpenAI Whisper (zero inference cost), gTTS, Pydantic, Tenacity.
* **Production Engineering:** Built with an explicit custom exception hierarchy, automated regex constraints blocking injection/XSS attempts, and structured logging. Implemented modular data mocking allowing an instant environment-variable toggle to live Stripe/Gmail production tools.

#### 📈 [Agentic RAG Optimization Pipeline (B.Tech Research)](https://github.com/Hustple/Thesis/blob/main/README.md#factuality%E2%80%93helpfulness-trade-off)
*An empirical research project proving hallucination reduction via local, iterative self-critique loops.*
* **The Stack:** Python, LangChain, Ollama (Llama 3.2 3B), ChromaDB, RAGAS Framework.
* **The Core Insight:** Engineered a structured Natural Language Inference (NLI) claim-verification backend running entirely offline on consumer hardware. Rigorously evaluated 300 generated answers against the **FinanceBench** benchmark, mathematically validating a **4.2% relative gain in RAGAS Faithfulness** and completely eliminating cross-document entity contamination.

#### 🐝 [Open-Source AI Framework Contributor (Model Context Protocol)](https://github.com/aden-hive/hive/pull/5136)
* **The Work:** Engineered production-ready Brevo API integrations for a high-scale open-source AI agent framework.
* **The Engineering:** Penned 34 asynchronous python unit tests covering success paths, schema validations, network backoff timeouts, and API authentication exceptions to secure framework stability.

---

### 🧰 Tech & Tools

* **Languages:** Python, SQL, C/C++, Java, JavaScript, HTML/CSS
* **AI & Agentic Frameworks:** LangChain, LangGraph, LlamaIndex, Model Context Protocol (MCP), RAGAS, Ollama, Prompt Engineering
* **Machine Learning & Audio:** Fine-tuning (LoRA / QLoRA), OpenAI Whisper, gTTS, PyTorch, Transformers, KerasNLP
* **Cloud & Infrastructure:** AWS (Bedrock, Kendra, SageMaker, S3, Lambda, IAM), Docker, Git, Linux, PostgreSQL, PyPDF

---

### 📈 Startup Quick Wins: How I bring immediate value

* **Hardening Agent Safety:** Restructuring unstable agentic codebases into resilient architectures protected by custom exception hierarchies, robust schema validation, and exponential backoff retry rules (`Tenacity`).
* **Benchmarking and Evaluation:** Moving pipelines away from superficial "vibes-based" prompting to rigorous mathematical tracking using automated LLM-as-a-judge frameworks (`RAGAS`) and strict token-level F1 scoring.
* **Slashing API & Latency Overhead:** Transitioning expensive, slow cloud dependency layers over to hyper-optimized, privacy-preserving, local-first models paired with low-latency tool-calling paradigms (`Groq` / `Ollama`).
