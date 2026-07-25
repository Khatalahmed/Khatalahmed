<div align="center">

<!-- ====================== HEADER ====================== -->

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1000&color=2E86FF&center=true&vCenter=true&width=760&lines=AI+%2F+GenAI+Engineer+%7C+Agentic+AI+Builder;Data+Scientist+%7C+ML+%2B+LLM+Systems;RAG+%C2%B7+Multi-Agent+%C2%B7+Fine-Tuning+%C2%B7+MLOps" alt="typing banner" />

# Hi, I'm Ahmed Khatal 👋

### 🚀 AI / GenAI Engineer · Agentic AI Builder · Data Scientist

I build **production-grade AI systems** — agentic pipelines, RAG platforms, fine-tuned LLMs, and classical ML — that ship with **guardrails, evaluation, and observability**, not just notebooks.

<p>
<a href="https://github.com/Khatalahmed"><img src="https://img.shields.io/badge/Focus-Agentic%20AI%20%7C%20GenAI%20%7C%20RAG-2E86FF?style=for-the-badge" /></a>
<a href="mailto:ahmedkhatal22@gmail.com"><img src="https://img.shields.io/badge/Email-ahmedkhatal22-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/khatalahmed/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
</p>

</div>

---

## 🧭 What I Do

I turn open-ended business problems into **reliable AI systems**. Across my projects you'll find the same production DNA: **typed tools, retrieval grounded in real data, multi-agent orchestration, safety guardrails, and automated evaluation (RAGAS / LLM-as-judge).** I work end-to-end — from data modeling and fine-tuning to deployment on **GCP Cloud Run with keyless CI/CD.**

```python
class AhmedKhatal:
    roles      = ["AI/GenAI Engineer", "Agentic AI Builder", "Data Scientist"]
    core       = ["RAG", "Multi-Agent Systems", "LLM Fine-Tuning (QLoRA)", "NL-to-SQL", "Classical ML"]
    llm_stack  = ["Vertex AI · Gemini", "Groq · Llama-3.3", "Qwen3", "Ollama (local)"]
    frameworks = ["LangGraph", "LangChain", "DeepAgents", "FastMCP / MCP", "FastAPI"]
    ships_with = ["Guardrails", "RAGAS / LLM-as-Judge Eval", "Observability", "Docker", "GCP CI/CD"]
    philosophy = "Fine-tuning teaches how to speak. RAG teaches what's true. Agents decide what to do."
```

---

## 🌟 Featured Projects

> Six systems spanning **Agentic AI · GenAI/RAG · LLM Fine-Tuning · Applied ML** — each built production-first with evaluation and guardrails.

### 🤖 Agentic AI & Autonomous Systems

<table>
<tr>
<td width="50%" valign="top">

#### 📊 Pattern Platform
**Production AI analytics platform** — ask your database questions in plain English.

- **NL-to-SQL** with read-only validation + human-in-the-loop approval
- **Advanced RAG** over DB schemas: pgvector + **HyDE + RAG Fusion**
- **LangGraph** multi-agent pipeline + **MCP server** for tool access
- **Sandboxed ML execution** (Docker) with SHAP explanations
- **RBAC**, Fernet encryption, LLMOps eval, GCP Cloud Run

`FastAPI` `LangGraph` `pgvector` `Vertex AI` `MCP` `XGBoost` `SHAP` `GCP`

</td>
<td width="50%" valign="top">

#### 🏠 [AI Operating System for PG Hostels](https://github.com/Khatalahmed/AI-operating-system-for-PG-hostels)
**Manage an entire hostel by chatting with an AI.**

- **~90 typed MCP tools** exposed via FastMCP
- **Gemini function-calling agent** — NL → correct tool sequence
- **Role-scoped safety**: owner / tenant / guest toolsets, destructive tools hard-blocked
- **Multi-channel** (Telegram live + WhatsApp) + Next.js dashboard
- **5 background agents**, RAG knowledge base, 50+ table Postgres schema

`FastMCP` `Gemini` `asyncpg` `PostgreSQL` `LangGraph` `Next.js`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🔔 [Customer Churn Early-Warning Agent](https://github.com/Khatalahmed/customer_churn_alert_agent)
**ML ranks the risk; agents investigate and verify it.**

- **XGBoost** with *leakage-safe* features — honest **ROC-AUC 0.731**
- **DeepAgents** hierarchical multi-agent investigation
- **Evidence verifier** re-queries DB → **100% evidence fidelity**
- **Precision @ top-15 = 1.00**, per-archetype recall 88–91%
- Agent can *override* the model on benign evidence

`DeepAgents` `LangGraph` `XGBoost` `SHAP` `Vertex AI`

</td>
<td width="50%" valign="top">

#### 🎯 Why these stand out
Not demos — each ships with the hard parts:

- ✅ **Guardrails** before the LLM ever runs
- ✅ **Automated evaluation** (RAGAS, LLM-as-judge)
- ✅ **Verification layers** that fact-check the model
- ✅ **Human-in-the-loop** on risky actions
- ✅ **Observability** + cost/latency awareness

</td>
</tr>
</table>

### 🧠 GenAI · RAG · LLM Fine-Tuning

<table>
<tr>
<td width="50%" valign="top">

#### 🛡️ [Enterprise Agentic RAG — K8s Assistant](https://github.com/Khatalahmed/enterprise-rag)
**Production RAG that stays accurate on noisy corpora (~40% irrelevant).**

- **LangGraph planner** + **NeMo Guardrails** (jailbreak/off-topic block)
- **Two-stage retrieval**: Qdrant bi-encoder → **FlashRank** rerank (15→5)
- **Portkey LLM gateway**: fallback, caching, rate-limit resilience
- **RAGAS + LLM-as-judge** evaluation; local RapidOCR (no external API)
- **Keyless CI/CD** (Workload Identity Federation), image 5GB→runtime, **83s builds**

`LangGraph` `Qdrant` `FlashRank` `NeMo` `Portkey` `RAGAS` `Cloud Run`

</td>
<td width="50%" valign="top">

#### ✈️ [ACME Airlines Support AI](https://github.com/Khatalahmed/acme-ai-support)
**Fine-tuning + RAG + tool-calling in one support agent.**

- **Qwen3-4B** fine-tuned with **QLoRA/Unsloth** (33M params, 0.81%)
- **RAG (ChromaDB)** pins answers to canon policy — no hallucinated refunds
- **GGUF Q5_K_M** quantization (2.7GB) → **Ollama local, zero API cost**
- **Tool-calling** for live flight status / cancellation
- **Gemini LLM-as-judge** eval on 5 calibrated criteria

`Qwen3` `QLoRA` `Unsloth` `ChromaDB` `llama.cpp` `Ollama`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 👥 [HR Helpdesk RAG API](https://github.com/Khatalahmed/HR_helpdesk)
**Privacy-first RAG API for HR policy Q&A.**

- **FastAPI** + **Gemini** embeddings & generation + **pgvector**
- Heading-aware chunking; `/ask`, `/retrieve-debug`, `/feedback`
- **Privacy by design**: feedback stores metadata hashes, not raw text
- API-key auth, configurable rate limiting, **RAGAS governance reports**
- CI-tested endpoints (pytest)

`FastAPI` `Gemini` `pgvector` `PostgreSQL` `RAGAS`

</td>
<td width="50%" valign="top">

#### 📈 Plus applied Data Science
Classical ML foundation behind the GenAI work:

- 🍕 **Domino's** — demand forecasting (ARIMA/SARIMA)
- 🚗 **Car Dheko** — used-car price prediction + Streamlit
- 🛡️ **Microsoft** — cybersecurity incident classification
- 😀 **Emotion Detection** — ResNet34 vision app
- 💡 **DataSpark** — global electronics analytics

*Forecasting · classification · CV · EDA & dashboards*

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

**Languages & Data**
<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**GenAI · LLM · Agentic**
<br>
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-FastMCP-6E56CF?style=flat-square)
![Gemini](https://img.shields.io/badge/Gemini_Vertex_AI-4285F4?style=flat-square&logo=googlegemini&logoColor=white)
![Groq](https://img.shields.io/badge/Groq_Llama_3.3-F55036?style=flat-square&logo=meta&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

**RAG · Vector · Fine-Tuning**
<br>
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=flat-square)
![QLoRA](https://img.shields.io/badge/QLoRA_Unsloth-6E56CF?style=flat-square)
![RAGAS](https://img.shields.io/badge/RAGAS_Eval-2E86FF?style=flat-square)

**ML & Explainability**
<br>
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square)
![SHAP](https://img.shields.io/badge/SHAP-000000?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

**Backend · Serving · MLOps**
<br>
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![GCP](https://img.shields.io/badge/GCP_Cloud_Run-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Khatalahmed&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Khatalahmed&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Khatalahmed&theme=tokyonight&hide_border=true" />

</div>

---

## 🎯 What I Bring to a Team

| | |
|---|---|
| **🤖 Agentic AI** | Multi-agent orchestration (LangGraph, DeepAgents, MCP) with planners, verifiers, and human-in-the-loop |
| **🧠 GenAI & RAG** | Advanced retrieval (HyDE, RAG Fusion, rerank), guardrails, and RAGAS/LLM-judge evaluation |
| **🔧 LLM Fine-Tuning** | QLoRA fine-tuning, GGUF quantization, and local serving at zero API cost |
| **📊 Data Science** | Leakage-safe modeling, XGBoost, SHAP explainability, forecasting & classification |
| **⚙️ Production Mindset** | Docker, GCP Cloud Run, keyless CI/CD, observability, and cost/latency awareness |

---

<div align="center">

### 🤝 Let's Build Something Intelligent

<a href="mailto:ahmedkhatal22@gmail.com"><img src="https://img.shields.io/badge/Email-ahmedkhatal22@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/khatalahmed/"><img src="https://img.shields.io/badge/LinkedIn-Ahmed_Khatal-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/Khatalahmed"><img src="https://img.shields.io/badge/GitHub-Khatalahmed-181717?style=for-the-badge&logo=github&logoColor=white" /></a>

<sub>⭐ From notebooks to production — grounded, guarded, and evaluated.</sub>

</div>
