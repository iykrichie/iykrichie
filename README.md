# Richard Ikechukwu Mbaliri

<div align="center">
  <a href="https://github.com/iykrichie">
    <img src="https://img.shields.io/badge/AI_Architect-Private_AI_Systems-blue?style=for-the-badge" alt="AI Architect" />
  </a>
  <a href="https://github.com/iykrichie">
    <img src="https://img.shields.io/badge/Fintech-Data_Engineering-ff69b4?style=for-the-badge" alt="Fintech" />
  </a>
  <a href="https://github.com/iykrichie">
    <img src="https://img.shields.io/badge/Cloud_&_On-Prem-Trusted_Infrastructure-success?style=for-the-badge" alt="Cloud and On-Prem" />
  </a>
</div>

### Building secure, high-impact AI and data systems for regulated industries

> I design private, scalable, and production-ready AI infrastructure that helps organizations move from experimentation to dependable business value.

I work at the intersection of strategy, software engineering, and applied AI. My niche is helping teams move from cloud-dependent experimentation to robust, governable systems that run efficiently in-house—especially in finance, insurance, and data-heavy operations. I focus on making AI practical, safe, and valuable—especially where privacy, compliance, and operational reliability matter most.

## 🧠 Core Competencies & Tech Stack

| Domain | Skills & Technologies |
| :--- | :--- |
| **Enterprise AI Architecture** | Local LLM Orchestration, RAG-style Workflows, Agentic Systems (Ollama, LlamaIndex), Multi-Agent Pipelines |
| **Software Engineering** | TypeScript, Node.js, Python, React (Next.js/Vite), WebSockets |
| **Data & Infrastructure** | Data Centralization, Docker, AWS, Azure, GCP, Nginx, PostgreSQL, Web Workers |
| **Business Value Delivery** | Financial Reconciliation, Risk Workflows, Document Processing (OCR), Data Quality Systems |

---

## ✨ Featured Architecture & Systems

### 🔍 [AIMatch: High-Performance Reconciliation Engine](https://github.com/iykrichie/ai_recon_match_local)
**Automated full-stack financial reconciliation combining deterministic matching with local AI semantic fallbacks.**
* **Problem:** Manual matching of Bank vs. General Ledger entries is prone to error and time-consuming, while financial data is too sensitive for cloud LLMs.
* **Approach:** Designed a strict two-phase matching architecture. Phase 1 enforces exact 1-to-1 matches and extracts patterns from noisy narratives. Phase 2 applies a circuit-breaker aggregation algorithm for M:1 / 1:M matching. Fallback to a local `llama3.1:8b` model for semantic matching of ambiguous records.
* **Skills/Tools:** React 19, TypeScript, Node.js, Web Workers (background processing), Local Ollama, Fuzzball.

### 📄 [Coronation OCR: Intelligent Claims Processing](https://github.com/iykrichie/claimscan_ai_local)
**Multimodal agentic pipeline automating data extraction, reporting, and risk assessment for insurance claims.**
* **Problem:** Slow, manual processing of handwritten and printed insurance forms with high overhead and compliance risks.
* **Approach:** Built a multi-agent system defaulting to `qwen2.5:3b` and `minicpm-v` for local, 100% offline document parsing and reasoning. Implemented Human-in-the-Loop (HITL) RBAC portals for customers and handlers.
* **Skills/Tools:** Local AI Orchestration, OCR, Prompt Engineering (Personas), LlamaIndex RAG, Docker, WebSockets.

### 🌍 [CleanAddress: Enterprise Address Standardizer](https://github.com/iykrichie/CleanAddress)
**Production-grade API and web app for bulk-processing, standardizing, and geocoding unstructured addresses.**
* **Problem:** Messy Nigerian address data (PO Boxes, Plots) limits operational efficiency and geographic insights.
* **Approach:** Engineered a hybrid pipeline using Google's Enterprise APIs paired with deep Nigerian domain logic (custom PO Box guards, district-to-LGA fuzzy matching). Scaled throughput 5-10x using a concurrent asynchronous worker pool and an in-memory cache layer.
* **Skills/Tools:** REST API Design, Concurrent Worker Pools, Caching Strategies, Regex, Google Maps/Places APIs.

---

## 🏆 Experience Highlights

* **Head of Data Management & Analytics | Coronation Technologies**
  * Led data centralization efforts and engineered private AI infrastructure to streamline operations in the insurance sector.
* **Pioneer, AI & Insights Department | Union Bank**
  * Established the AI function from the ground up, delivering measurable execution within a highly regulated financial environment.
* **Data & Analytics Lead | Sterling Bank**
  * Built a real-time fraud monitoring capability and delivered strategic analytics that created direct business value.
* **Data Lead | VBank MFB**
  * Architected cloud-enabled data platforms and fostered a high-performance engineering culture from inception.

## 🔗 Connect

* **LinkedIn:** [ikechukwumbaliri](https://www.linkedin.com/in/ikechukwumbaliri/)
* **GitHub:** [iykrichie](https://github.com/iykrichie)

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=iykrichie&label=Profile%20Views&color=brightgreen&style=flat" alt="Profile views" />
</div>
