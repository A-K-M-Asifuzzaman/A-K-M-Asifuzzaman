<div align="center">

<a href="https://www.trinolit.com/">
  <img src="https://www.trinolit.com/email-logo.png" alt="TrinolIT" width="190" />
</a>

<br/>

# A.K.M. Asifuzzaman

### Founder, [TrinolIT](https://www.trinolit.com/) · AI / Machine Learning Engineer

**Production AI · RAG & Agents · Machine Learning · Backend Systems · Applied Research**

<em>I build AI systems and software products that are measurable, grounded, explainable, secure, and deployable.</em>

<br/>

<a href="https://www.trinolit.com/">
  <img src="https://img.shields.io/badge/TrinolIT-Founder-0D1117?style=for-the-badge&logoColor=white" />
</a>
<a href="https://www.asifzaman.online/">
  <img src="https://img.shields.io/badge/Portfolio-asifzaman.online-0D1117?style=for-the-badge&logo=firefoxbrowser&logoColor=white" />
</a>
<a href="https://www.linkedin.com/in/a-k-m-asifuzzaman-6027442a7/">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

<br/><br/>

<a href="https://github.com/A-K-M-Asifuzzaman">
  <img src="https://img.shields.io/github/followers/A-K-M-Asifuzzaman?style=flat-square&label=Followers&labelColor=0D1117" />
</a>
<img src="https://komarev.com/ghpvc/?username=A-K-M-Asifuzzaman&label=Profile%20Views&style=flat-square" />

</div>

---

## About Me

I am **A.K.M. Asifuzzaman**, Founder of **TrinolIT** and an **AI / Machine Learning Engineer** from Chattogram, Bangladesh.

I work across the complete AI product lifecycle: **data and experimentation → model development → retrieval and agentic systems → backend architecture → evaluation → deployment → product engineering**.

My strongest interests are:

- **Production AI systems** — RAG, CRAG, GraphRAG, agents, verification, citations, evaluation
- **Machine learning engineering** — model development, calibration, uncertainty, XAI, serving
- **LLM & NLP engineering** — low-resource NLP, fine-tuning, retrieval, multilingual systems
- **Computer vision** — classification, transfer learning, explainability, multimodal applications
- **Backend & SaaS systems** — FastAPI, PostgreSQL, Redis, multi-tenancy, RBAC, APIs, security
- **Applied research** — reproducible experiments, ablations, statistical evaluation, limitations

I am completing a **BSc in Computer Science & Engineering at East Delta University** while building research projects, production AI systems, and TrinolIT products.

```python
asif = {
    "role": "Founder, TrinolIT · AI / ML Engineer",
    "location": "Chattogram, Bangladesh",
    "education": "BSc in CSE — East Delta University",
    "focus": [
        "Production AI Systems",
        "RAG & Agentic AI",
        "Machine Learning Engineering",
        "Backend & SaaS Architecture",
        "Applied AI Research",
    ],
    "research": [
        "Low-Resource NLP",
        "Retrieval & Grounding",
        "Explainable AI",
        "Computer Vision",
        "LLM Evaluation",
    ],
    "principle": "Build systems that can be measured, explained, and trusted."
}
```

---

## Founder — TrinolIT

<div align="center">

<a href="https://www.trinolit.com/">
  <img src="https://raw.githubusercontent.com/A-K-M-Asifuzzaman/Startup-Website/main/public/email-logo.png" alt="TrinolIT logo" width="220" />
</a>

### [Visit TrinolIT →](https://www.trinolit.com/)

**AI Engineering · Custom Software · SaaS · Business Systems · Intelligent Automation**

</div>

I founded **TrinolIT** to build serious software and AI systems rather than one-off demos. My role spans product direction, architecture, AI/ML engineering, backend systems, technical decision-making, deployment strategy, and engineering quality.

Current TrinolIT engineering initiatives include:

- **Nexora AI** — multi-tenant ERP/POS and intelligent business platform
- **Trinol OS** — internal company operating system for projects, leads, clients, teams, finance, meetings, and documents
- **Trinol Payment** — transaction-confirmation and reconciliation infrastructure with deterministic matching, signed webhooks, Android device integration, and developer APIs
- **TrinolIT Web Platform** — immersive company website and technical showcase

> Trinol OS and Trinol Payment are currently maintained as private/internal repositories.

---

# Flagship Engineering Projects

These are the projects that best represent my current engineering level.

## 01 — NWP-Core
### Transformer from Scratch · ONNX · WASM · ML Systems

[Repository →](https://github.com/A-K-M-Asifuzzaman/Next-Word-Prediction-From-Scratch) · [Live App →](https://nwp-core.vercel.app)

A next-word prediction system built around a **19.47M-parameter decoder-only transformer trained from scratch**, rather than an external LLM API.

**Highlights**

- Trained on approximately **262M tokens**
- RMSNorm, RoPE, SwiGLU, grouped-query attention, tied embeddings
- PyTorch training pipeline with resumable telemetry
- ONNX export and dynamic int8 quantization
- Model size reduced from **103.5 MB to 26.6 MB**
- **58.53% test top-5 accuracy** after int8 quantization
- Browser-side inference using ONNX Runtime Web + WebAssembly
- Measured roughly **15–20 ms prediction latency**
- Tokenizer parity testing between Python training and browser inference

**What it demonstrates:** model architecture, training, benchmarking, quantization, deployment, ML systems engineering.

---

## 02 — DocFlow AI
### Production Document Intelligence · RAG · Provenance · Multi-Tenancy

[Repository →](https://github.com/A-K-M-Asifuzzaman/DocFlow-AI)

A production-oriented document intelligence platform designed around **traceable evidence rather than unverifiable LLM output**.

**Highlights**

- PDF/document ingestion and OCR
- Evidence-linked extraction
- RAG with citations and grounding checks
- Multi-tenant architecture
- Authorization and isolation testing
- Production-oriented security boundaries
- Backend + E2E test coverage
- Structured provenance from document to page/span/evidence
- Evaluation and failure analysis rather than demo-only output

**What it demonstrates:** production AI, retrieval, backend design, AI reliability, testing, security.

---

## 03 — FoodGenome AI
### Food-101 · Ensemble Vision · Conformal Prediction · RAG · GraphRAG

[Repository →](https://github.com/A-K-M-Asifuzzaman/Food) · [Live App →](https://food-red-omega.vercel.app/)

An end-to-end food intelligence system combining computer vision, uncertainty estimation, nutrition provenance, explainability, and grounded question answering.

**Measured results**

- **97.16%** Food-101 test top-1 accuracy
- **99.56%** conformal coverage
- Average candidate set: **1.54**
- **97.94%** accuracy on accepted predictions after abstention
- **98.6%** RAG correctness on a 76-case gold set
- 101-class nutrition knowledge base with USDA provenance

**Engineering**

- SigLIP-SO400M + EVA-02-L ensemble
- Temperature calibration
- Conformal candidate sets
- Abstention for uncertain predictions
- Grad-CAM explainability
- Hybrid retrieval + RRF + reranking
- CRAG-style evidence validation
- GraphRAG knowledge explorer
- Model benchmarking and McNemar significance testing

**What it demonstrates:** CV, uncertainty, XAI, RAG, evaluation, product engineering.

---

## 04 — Recurra
### Leakage-Aware ML · XAI · Calibration · Medical ML Research

[Repository →](https://github.com/A-K-M-Asifuzzaman/THYROID-ML-) · [Live App →](https://recurra-a-k-m-asifuzzamans-projects.vercel.app)

A thyroid-cancer recurrence research system built around an important finding: a commonly used post-treatment feature can create **target leakage** and artificially inflate performance.

**Highlights**

- Explicit feature tracks: post-treatment, at-diagnosis, raw-clinical
- Leakage-aware model registry that refuses unsafe feature tracks
- Test PR-AUC up to **0.892** on the at-diagnosis track
- SHAP explanations and constrained counterfactuals
- Calibration and threshold selection
- Explanation fidelity/stability measurement
- Model-randomization sanity checks
- **120 model configurations** benchmarked
- **284 Python tests**
- Explicit research/educational—not medical-device—boundary

**What it demonstrates:** rigorous applied ML, XAI, evaluation discipline, responsible ML engineering.

---

## 05 — Chatgaiya AI / ChatgaiyyaLM
### Low-Resource Chittagonian NLP

[Repository →](https://github.com/A-K-M-Asifuzzaman/Chatgaiya-AI)

Research and engineering for **Chittagonian**, a low-resource language where data scarcity is itself a central research problem.

**Research directions**

- Corpus construction and quality control
- Low-resource translation
- Sentiment analysis
- Question answering
- Named-entity recognition
- Summarization
- ASR
- Tokenizer fertility analysis
- Context-sensitive rewrite-rule mining
- Dialectness supervision and benchmark construction

**What it demonstrates:** original dataset work, low-resource NLP, multilingual AI, research design.

---

## 06 — Nexora AI
### Multi-Tenant ERP/POS · Enterprise SaaS · AI Systems

[Repository →](https://github.com/A-K-M-Asifuzzaman/Nexora-AI)

An enterprise-oriented multi-tenant business platform designed to demonstrate serious backend and SaaS architecture in addition to AI.

**Focus**

- Multi-tenant architecture
- ERP/POS workflows
- PostgreSQL data model
- FastAPI backend
- transactional business operations
- RBAC and tenant isolation
- AI-assisted business workflows
- production-oriented system design

**What it demonstrates:** backend engineering, SaaS architecture, business-domain modelling, technical-founder capability.

---

## 07 — BEACON AI
### Evidence-Attributed Audio Intelligence

[Repository →](https://github.com/A-K-M-Asifuzzaman/BEACON-AI) · [Live App →](https://beacon-ai-drab.vercel.app)

A meeting, lecture, and call intelligence system built around **attributed recall**.

Instead of presenting generated notes as unquestioned truth, Beacon links generated content back to the recording and classifies claims as supported, partial, or unsupported.

**Highlights**

- Transcription and speaker-aware sessions
- Sentence-level evidence attribution
- Timestamp-linked summaries
- Evidence-linked action items
- Grounded QA
- Retrieval score visibility
- Flashcards tied to source audio
- SSE-based AI streaming
- Live capture and session timeline

**What it demonstrates:** multimodal AI, grounding, product UX, evidence-aware generation.

---

## 08 — OmniMind
### Multi-Agent Multimodal Research Scientist

[Repository →](https://github.com/A-K-M-Asifuzzaman/CSE-466-Python-Project)

A research platform in which specialized agents plan, retrieve, reason, verify, critique, and generate evidence-backed research outputs.

**Highlights**

- 13 specialized agents
- typed blackboard coordination
- hybrid retrieval
- multimodal ingestion
- knowledge graph construction
- claim-by-claim evidence verification
- contradiction detection
- research-gap identification
- experiment proposal generation
- SSE agent telemetry
- clean/hexagonal architecture
- **119 passing tests**

**What it demonstrates:** agentic AI, architecture, orchestration, evaluation and research tooling.

---

## 09 — ShikkhaAI
### Grounded AI Tutor for Bangladesh

[Repository →](https://github.com/A-K-M-Asifuzzaman/ShikkhaAI) · [Live App →](https://shikkha-ai-lime.vercel.app)

A grounded AI tutor for SSC-level Bangladesh education using official NCTB textbooks.

**Highlights**

- 18 NCTB books / 4,551 pages
- Bangla, English and Banglish interaction
- hybrid dense + BM25 retrieval
- reciprocal-rank fusion
- reranking
- book/page citations
- specialist agent routing
- vision homework input
- Whisper voice input
- graph/diagram rendering
- Firebase authentication and student history

**What it demonstrates:** RAG, educational AI, multilingual systems, real product deployment.

---

## 10 — NeuraHub AI
### Multi-Tenant AI Workspace

[Repository →](https://github.com/A-K-M-Asifuzzaman/NeuralHub-AI)

A broad AI workspace combining codebase intelligence, data science, research assistance, education, agents, memory and collaboration.

**Architecture**

- Next.js application
- Flutter multi-platform client
- FastAPI microservices
- PostgreSQL RLS
- Qdrant
- Neo4j
- OpenTelemetry
- Prometheus/Grafana
- typed/tested Python services
- provider-agnostic LLM gateway

**What it demonstrates:** large-system architecture and integration across AI, backend, data and clients.

---

# Research & Academic Work

## Current Research

### ChatgaiyyaLM — Low-Resource Chittagonian AI
Building language resources and evaluation pipelines for translation, sentiment, QA, NER, summarization and speech tasks.

### Hybrid RAG for Bangladesh Secondary Education
Researching dense + sparse retrieval, reranking, grounded generation, faithfulness, abstention and retrieval evaluation for NCTB content.

### Bengali Physics LLM Evaluation
Evaluating multiple open LLM families on Bengali physics MCQs using zero/few-shot and reasoning-oriented prompting.

### Reasoning-Oriented Retrieval
Interested in temporal retrieval, conversational retrieval, evidence grounding, reranking, retrieval evaluation and SemEval-style benchmark systems.

---

# AI / ML Engineering Stack

### LLM · RAG · Agents

![OpenAI](https://img.shields.io/badge/OpenAI-0D1117?style=flat-square&logo=openai&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Hugging_Face-0D1117?style=flat-square&logo=huggingface&logoColor=FFD21E)
![LangChain](https://img.shields.io/badge/LangChain-0D1117?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-0D1117?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-0D1117?style=flat-square&logo=ollama&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0D1117?style=flat-square)
![Qdrant](https://img.shields.io/badge/Qdrant-0D1117?style=flat-square)
![Neo4j](https://img.shields.io/badge/Neo4j-0D1117?style=flat-square&logo=neo4j&logoColor=4581C3)

### Machine Learning · Deep Learning · XAI

![Python](https://img.shields.io/badge/Python-0D1117?style=flat-square&logo=python&logoColor=3776AB)
![PyTorch](https://img.shields.io/badge/PyTorch-0D1117?style=flat-square&logo=pytorch&logoColor=EE4C2C)
![TensorFlow](https://img.shields.io/badge/TensorFlow-0D1117?style=flat-square&logo=tensorflow&logoColor=FF6F00)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0D1117?style=flat-square&logo=scikitlearn&logoColor=F7931E)
![XGBoost](https://img.shields.io/badge/XGBoost-0D1117?style=flat-square)
![LightGBM](https://img.shields.io/badge/LightGBM-0D1117?style=flat-square)
![SHAP](https://img.shields.io/badge/SHAP-0D1117?style=flat-square)
![ONNX](https://img.shields.io/badge/ONNX-0D1117?style=flat-square&logo=onnx&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-0D1117?style=flat-square&logo=opencv&logoColor=5C3EE8)

### Backend · Data · Infrastructure

![FastAPI](https://img.shields.io/badge/FastAPI-0D1117?style=flat-square&logo=fastapi&logoColor=009688)
![Node.js](https://img.shields.io/badge/Node.js-0D1117?style=flat-square&logo=nodedotjs&logoColor=339933)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0D1117?style=flat-square&logo=postgresql&logoColor=4169E1)
![MongoDB](https://img.shields.io/badge/MongoDB-0D1117?style=flat-square&logo=mongodb&logoColor=47A248)
![Redis](https://img.shields.io/badge/Redis-0D1117?style=flat-square&logo=redis&logoColor=DC382D)
![Docker](https://img.shields.io/badge/Docker-0D1117?style=flat-square&logo=docker&logoColor=2496ED)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0D1117?style=flat-square&logo=githubactions&logoColor=2088FF)
![Linux](https://img.shields.io/badge/Linux-0D1117?style=flat-square&logo=linux&logoColor=FCC624)

### Frontend · Product Engineering

![Next.js](https://img.shields.io/badge/Next.js-0D1117?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-0D1117?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-0D1117?style=flat-square&logo=typescript&logoColor=3178C6)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-0D1117?style=flat-square&logo=tailwindcss&logoColor=06B6D4)
![Firebase](https://img.shields.io/badge/Firebase-0D1117?style=flat-square&logo=firebase&logoColor=FFCA28)

---

# Engineering Areas

| Area | Current Work |
|:---|:---|
| **Production RAG** | Hybrid dense + sparse retrieval, RRF, reranking, CRAG, citations, abstention, evaluation |
| **Agentic AI** | LangGraph workflows, routing, agent orchestration, verification, tool use |
| **ML Engineering** | Training, evaluation, calibration, feature engineering, benchmarking, deployment |
| **Explainability** | SHAP, LIME, Grad-CAM, Integrated Gradients, counterfactuals |
| **Computer Vision** | Classification, transfer learning, ensembles, uncertainty and visual attribution |
| **NLP** | Transformers, low-resource NLP, multilingual evaluation, QA, NER, sentiment |
| **Backend Systems** | FastAPI, APIs, async services, SSE/WebSockets, authentication, RBAC |
| **SaaS Architecture** | Multi-tenancy, organization isolation, PostgreSQL, business workflows |
| **AI Reliability** | Grounding, provenance, hallucination detection, confidence, reproducibility |
| **MLOps / Infra** | Docker, CI/CD, model serving, cloud deployment, monitoring |

---

# Education

### East Delta University
**BSc in Computer Science & Engineering**

- Focus: Artificial Intelligence, Machine Learning, Deep Learning, NLP, Computer Vision, Software Engineering
- Current academic/research work includes RAG, LLM evaluation, ML experimentation and intelligent systems
- CGPA: **3.78**

---

# Certifications

| Certification | Issuer | Year | Credential |
|:---|:---|:---:|:---:|
| **Docker for Machine Learning** | CampusX | 2026 | [View](https://i.ibb.co.com/60m73yNd/1786194080075-certificate.jpg) |
| **FastAPI for Machine Learning** | CampusX | 2026 | [View](https://i.ibb.co.com/wZSd1SDF/1782035825341-certificate.jpg) |
| Explainable AI (XAI) | CampusX | 2026 | [View](https://i.ibb.co.com/7t1QMwSd/1779017167687-certificate.jpg) |
| Deep Learning: Beginner to Advanced | Codebasics | 2026 | [View](https://codebasics.io/certificate/CB-85-637081) |
| AI Engineer Core: LLM, RAG, QLoRA, Agents | Udemy | 2025 | [View](https://www.udemy.com/certificate/UC-09849cd1-e3e9-4c62-bcdb-ad918f4bddcc/) |
| NLP with Python | Udemy | 2025 | [View](https://www.udemy.com/certificate/UC-2682647d-e413-4fb1-8292-5bd0073647de/) |
| Deep Learning A-Z | Udemy | 2025 | [View](https://www.udemy.com/certificate/UC-538a5c2d-5b67-43aa-836e-1940a7e48860/) |
| A Deep Understanding of Deep Learning | Udemy | 2025 | [View](https://www.udemy.com/certificate/UC-d544c779-689c-4225-971d-e0f72e7e760f/) |
| Machine Learning A-Z | Udemy | 2025 | [View](https://www.udemy.com/certificate/UC-f9047cf4-17a5-4106-b3e3-53980b7425b0/) |
| Master Machine Learning for Data Science | Codebasics | 2025 | [View](https://codebasics.io/certificate/CB-69-567414) |
| Supervised ML: Regression & Classification | DeepLearning.AI | 2025 | [View](https://www.coursera.org/account/accomplishments/records/6PVZE4V07XM8) |
| Python for Data Science, AI & Development | IBM | 2025 | [View](https://www.coursera.org/account/accomplishments/verify/L668YC8B8JK3) |
| Complete Web Development | Programming Hero | 2024 | [View](https://i.ibb.co.com/4R7kz8Jx/certificate-student.png) |

### Currently Learning

- **Advanced RAG — CampusX** *(ongoing)*
- **Deep Learning for Computer Vision — CampusX** *(ongoing)*

I also continuously study advanced retrieval, context engineering, agentic systems, multimodal AI, production ML, and system design.

---

# Professional Affiliation

**IEEE Student Member**

Interested in research collaboration, shared tasks, applied AI research, and research-oriented engineering.

---

# GitHub Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=A-K-M-Asifuzzaman&show_icons=true&count_private=true&hide_border=true&title_color=58a6ff&icon_color=58a6ff&text_color=8b949e&bg_color=0d1117" />

<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=A-K-M-Asifuzzaman&layout=compact&hide_border=true&title_color=58a6ff&text_color=8b949e&bg_color=0d1117&langs_count=8" />

<br/>

<img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=A-K-M-Asifuzzaman&hide_border=true&background=0d1117&stroke=21262d&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff&sideLabels=8b949e&dates=8b949e&currStreakNum=ffffff&sideNums=ffffff" />

<br/><br/>

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=A-K-M-Asifuzzaman&bg_color=0d1117&color=8b949e&line=58a6ff&point=ffffff&area=true&area_color=1f6feb&hide_border=true" />

</div>

---

# What I Care About

I am most interested in engineering work where AI is treated as a **system**, not simply an API call.

That means asking:

- Is the output grounded?
- Can a claim be traced back to evidence?
- Is the evaluation contaminated by leakage?
- What happens when the model is uncertain?
- Can the system refuse safely?
- Does the tenant boundary hold under attack?
- Are model and retrieval quality actually measured?
- Can another engineer reproduce the result?
- Is the product useful outside a notebook?

Those questions shape the systems I build.

---

# Current Direction

I am building toward a career that combines:

**AI / ML Engineering + Research + Technical Entrepreneurship**

My long-term areas of interest include:

- Production AI and LLM systems
- Retrieval and agentic architectures
- AI evaluation and reliability
- Multimodal intelligence
- Low-resource language technology
- Enterprise AI systems
- AI infrastructure and MLOps
- Graduate research and long-term PhD work
- Building TrinolIT into a serious AI and software engineering company

---

# Contact

<div align="center">

<a href="https://www.trinolit.com/">
  <img src="https://raw.githubusercontent.com/A-K-M-Asifuzzaman/Startup-Website/main/public/email-logo.png" alt="TrinolIT" width="150" />
</a>

<br/><br/>

### Engineering, research, collaboration, or building something ambitious?

[**TrinolIT**](https://www.trinolit.com/) ·
[**Portfolio**](https://www.asifzaman.online/) ·
[**LinkedIn**](https://www.linkedin.com/in/a-k-m-asifuzzaman-6027442a7/) ·
[**GitHub**](https://github.com/A-K-M-Asifuzzaman) ·
[**Email**](mailto:zasif855@gmail.com)

<br/>

**A.K.M. Asifuzzaman**  
Founder, TrinolIT · AI / Machine Learning Engineer

</div>
