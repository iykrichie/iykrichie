# Richard Ikechukwu Mbaliri

<div align="center">
  <img src="https://img.shields.io/badge/AI_Architect-Private_AI_Systems-0052CC?style=for-the-badge&logo=openai&logoColor=white" alt="AI Architect" />
  <img src="https://img.shields.io/badge/Fintech-Data_Engineering-8A2BE2?style=for-the-badge&logo=apachespark&logoColor=white" alt="Fintech" />
  <img src="https://img.shields.io/badge/Cloud_%26_On--Prem-Trusted_Infrastructure-108A00?style=for-the-badge&logo=docker&logoColor=white" alt="Cloud and On-Prem" />
</div>

<br/>

> **Building secure, high-impact AI and data systems for regulated industries.** <br/>
> I design private, scalable, and production-ready AI infrastructure that helps organizations move from experimentation to dependable business value.

I work at the intersection of strategy, software engineering, and applied AI. My niche is helping teams move from cloud-dependent experimentation to robust, governable systems that run efficiently in-house—especially in finance, insurance, and data-heavy operations. I focus on making AI practical, safe, and valuable—especially where privacy, compliance, and operational reliability matter most.

---

## 🧠 Core Competencies & Tech Stack

| Domain | Skills & Technologies |
| :--- | :--- |
| **🤖 Enterprise AI Architecture** | Local LLM Orchestration, RAG Workflows, Agentic Systems (Ollama, LlamaIndex) |
| **💻 Software Engineering** | TypeScript, Node.js, Python, React (Next.js/Vite), WebSockets, REST APIs |
| **☁️ Data & Infrastructure** | Data Centralization, Docker, AWS, Azure, GCP, Nginx, PostgreSQL, Web Workers |
| **📈 Business Value Delivery** | Financial Reconciliation, Risk Workflows, Document Processing (OCR), Data Quality |

---

## ✨ Featured Architecture & Systems

### 🔍 [AIMatch: High-Performance Reconciliation Engine](https://github.com/iykrichie/ai_recon_match_local)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=nodedotjs&logoColor=white) ![Ollama](https://img.shields.io/badge/Local_AI-Ollama-black?style=flat-square&logo=ollama&logoColor=white)

**Automated full-stack financial reconciliation combining deterministic matching with local AI semantic fallbacks.**
* **Problem:** Manual matching of Bank vs. General Ledger entries is prone to error and time-consuming, while financial data is too sensitive for cloud LLMs.
* **Approach:** Designed a strict two-phase matching architecture. Phase 1 enforces exact 1-to-1 matches and extracts patterns from noisy narratives. Phase 2 applies a circuit-breaker aggregation algorithm for M:1 / 1:M matching. Fallback to a local `llama3.1:8b` model for semantic matching of ambiguous records.

### 📄 [Coronation OCR: Intelligent Claims Processing](https://github.com/iykrichie/claimscan_ai_local)
![Python](https://img.shields.io/badge/Python-14354C?style=flat-square&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![LlamaIndex](https://img.shields.io/badge/RAG-LlamaIndex-blueviolet?style=flat-square) ![AI](https://img.shields.io/badge/Multi--Agent-Qwen%20%7C%20MiniCPM-darkred?style=flat-square)

**Multimodal agentic pipeline automating data extraction, reporting, and risk assessment for insurance claims.**
* **Problem:** Slow, manual processing of handwritten and printed insurance forms with high overhead and compliance risks.
* **Approach:** Built a multi-agent system defaulting to `qwen2.5:3b` and `minicpm-v` for local, 100% offline document parsing and reasoning. Implemented Human-in-the-Loop (HITL) RBAC portals for customers and handlers.

### 🌍 [CleanAddress: Enterprise Address Standardizer](https://github.com/iykrichie/CleanAddress)
![API](https://img.shields.io/badge/REST-API_Design-0052CC?style=flat-square) ![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white) ![Caching](https://img.shields.io/badge/Architecture-In--Memory_Cache-ff69b4?style=flat-square)

**Production-grade API and web app for bulk-processing, standardizing, and geocoding unstructured addresses.**
* **Problem:** Messy Nigerian address data (PO Boxes, Plots) limits operational efficiency and geographic insights.
* **Approach:** Engineered a hybrid pipeline using Google's Enterprise APIs paired with deep Nigerian domain logic (custom PO Box guards, district-to-LGA fuzzy matching). Scaled throughput 5-10x using a concurrent asynchronous worker pool and an in-memory cache layer.

### 📊 Data Science & Analytics Projects

#### 💨 [Lagos Air Quality Monitoring System](https://github.com/iykrichie/AirQualityMonitoringSystem)
![Python](https://img.shields.io/badge/Python-14354C?style=flat-square&logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![Cassandra](https://img.shields.io/badge/Cassandra-1287B1?style=flat-square&logo=apachecassandra&logoColor=white) ![Tkinter](https://img.shields.io/badge/GUI-Tkinter-lightgrey?style=flat-square)

**A desktop application that retrieves, analyzes, and visualizes air quality data from the Astra database or local CSV files.**
* **Problem:** Air quality data was siloed in remote databases and difficult for non-technical stakeholders to quickly visualize and analyze.
* **Approach:** Built an interactive Python GUI using `tkinter` connected to a remote Cassandra-based Astra DB via custom drivers. Used `pandas` and `matplotlib` to dynamically query and plot real-time metrics, giving users instant visual feedback.

#### 🎯 [RFM Customer Segmentation Model](https://github.com/iykrichie/rfmSegmentation)
![Python](https://img.shields.io/badge/Python-14354C?style=flat-square&logo=python&logoColor=white) ![Machine Learning](https://img.shields.io/badge/Machine_Learning-Clustering-ff69b4?style=flat-square) ![Analytics](https://img.shields.io/badge/Customer_Analytics-Data_Science-0052CC?style=flat-square)

**A supervised clustering pipeline that scores and segments customers based on Recency, Frequency, and Monetary value.**
* **Problem:** E-commerce businesses struggle to identify their most valuable customers, leading to inefficient and generic marketing campaigns.
* **Approach:** Implemented an RFM analysis model that quantitatively ranks customer purchase behavior. Engineered features to compute individual scores and mapped them into discrete, actionable segment groups (e.g., "Champions", "At Risk"), enabling targeted ROI-focused campaigns.
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

---

## 🔗 Connect

<div align="center">
  <a href="https://www.linkedin.com/in/ikechukwumbaliri/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/iykrichie">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</div>

<br/>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=iykrichie&show_icons=true&theme=radical&hide_border=true" alt="iykrichie's GitHub stats" />
</div>

<br/>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=iykrichie&label=Profile%20Views&color=brightgreen&style=flat" alt="Profile views" />
</div>
