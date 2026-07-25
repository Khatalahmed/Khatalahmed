<!-- ====================== ANIMATED HEADER ====================== -->
<a href="https://github.com/Khatalahmed">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2E86FF,50:6E56CF,100:0F1021&height=220&section=header&text=Ahmed%20Khatal&fontSize=58&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=AI%20%C2%B7%20GenAI%20%C2%B7%20Agentic%20AI%20%C2%B7%20Data%20Science&descSize=20&descAlignY=58" width="100%" />
</a>

<div align="center">

<!-- Typing animation -->
<a href="https://github.com/Khatalahmed">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=2E86FF&center=true&vCenter=true&width=820&lines=Building+production-grade+AI+systems+%F0%9F%A4%96;Agentic+AI+%C2%B7+Multi-Agent+Orchestration+%E2%9A%99%EF%B8%8F;RAG+%C2%B7+LLM+Fine-Tuning+%C2%B7+NL-to-SQL+%F0%9F%A7%A0;Grounded.+Guarded.+Evaluated.+%E2%9C%85" alt="Typing SVG" />
</a>

<!-- Live badges -->
<p>
  <img src="https://komarev.com/ghpvc/?username=Khatalahmed&label=Profile+Views&color=2E86FF&style=for-the-badge" alt="views" />
  <a href="https://github.com/Khatalahmed?tab=followers"><img src="https://img.shields.io/github/followers/Khatalahmed?label=Follow&style=for-the-badge&logo=github&color=181717" alt="followers" /></a>
  <img src="https://img.shields.io/badge/Open%20to-AI%20%2F%20GenAI%20%2F%20Agentic%20Roles-6E56CF?style=for-the-badge" alt="open to work" />
</p>

<p>
  <a href="mailto:ahmedkhatal22@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/khatalahmed/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/Khatalahmed"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:2E86FF,100:6E56CF&height=3" width="100%" />

## 🧭 About Me

I turn open-ended business problems into **reliable AI systems**. My work shares the same production DNA: **typed tools, retrieval grounded in real data, multi-agent orchestration, safety guardrails, and automated evaluation (RAGAS / LLM-as-judge)** — end-to-end from data modeling and fine-tuning to **GCP Cloud Run with keyless CI/CD.**

```python
class AhmedKhatal:
    roles      = ["AI/GenAI Engineer", "Agentic AI Builder", "Data Scientist"]
    core       = ["RAG", "Multi-Agent Systems", "LLM Fine-Tuning (QLoRA)", "NL-to-SQL", "Classical ML"]
    llm_stack  = ["Vertex AI · Gemini", "Groq · Llama-3.3", "Qwen3", "Ollama (local)"]
    frameworks = ["LangGraph", "LangChain", "DeepAgents", "FastMCP / MCP", "FastAPI"]
    ships_with = ["Guardrails", "RAGAS / LLM-as-Judge Eval", "Observability", "Docker", "GCP CI/CD"]
    philosophy = "Fine-tuning teaches how to speak. RAG teaches what's true. Agents decide what to do."
```

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:2E86FF,100:6E56CF&height=3" width="100%" />

## 🌟 Featured Projects

> Six systems spanning **Agentic AI · GenAI/RAG · LLM Fine-Tuning · Applied ML** — each built production-first with evaluation and guardrails.

### 🤖 Agentic AI & Autonomous Systems

<table>
<tr>
<td width="50%" valign="top">

#### 🏠 [AI Operating System for PG Hostels](https://github.com/Khatalahmed/AI-operating-system-for-PG-hostels)
**Manage an entire hostel by chatting with an AI.**

- **~90 typed MCP tools** exposed via FastMCP
- **Gemini function-calling agent** — NL → correct tool sequence
- **Role-scoped safety**: owner / tenant / guest toolsets; destructive tools hard-blocked
- **Multi-channel** (Telegram live + WhatsApp) + Next.js dashboard
- **5 background agents**, RAG knowledge base, 50+ table Postgres schema

`FastMCP` `Gemini` `asyncpg` `PostgreSQL` `LangGraph` `Next.js`

</td>
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
</tr>
<tr>
<td colspan="2" valign="top">

#### 🎯 Why these stand out
Not demos — each ships with the hard parts: ✅ **Guardrails** before the LLM ever runs · ✅ **Automated evaluation** (RAGAS, LLM-as-judge) · ✅ **Verification layers** that fact-check the model · ✅ **Human-in-the-loop** on risky actions · ✅ **Observability** + cost/latency awareness

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
- **RAGAS + LLM-as-judge** eval; local RapidOCR (no external API)
- **Keyless CI/CD** (WIF), image 5GB→runtime, **83s builds**

`LangGraph` `Qdrant` `FlashRank` `NeMo` `Portkey` `RAGAS` `Cloud Run`

</td>
<td width="50%" valign="top">

#### ✈️ [ACME Airlines Support AI](https://github.com/Khatalahmed/acme-ai-support)
**Fine-tuning + RAG + tool-calling in one support agent.**

- **Qwen3-4B** fine-tuned with **QLoRA/Unsloth** (33M params, 0.81%)
- **RAG (ChromaDB)** pins answers to canon policy — no hallucinated refunds
- **GGUF Q5_K_M** quant (2.7GB) → **Ollama local, zero API cost**
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
- API-key auth, rate limiting, **RAGAS governance reports**
- CI-tested endpoints (pytest)

`FastAPI` `Gemini` `pgvector` `PostgreSQL` `RAGAS`

</td>
<td width="50%" valign="top">

#### 📈 Plus Applied Data Science
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

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:2E86FF,100:6E56CF&height=3" width="100%" />

## 🛠️ Tech Stack

<div align="center">

**Languages & Data**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

**GenAI · LLM · Agentic**<br>
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-FastMCP-6E56CF?style=for-the-badge)
![Gemini](https://img.shields.io/badge/Gemini_Vertex_AI-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white)
![Groq](https://img.shields.io/badge/Groq_Llama_3.3-F55036?style=for-the-badge&logo=meta&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)

**RAG · Vector · Fine-Tuning**<br>
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=for-the-badge)
![QLoRA](https://img.shields.io/badge/QLoRA_Unsloth-6E56CF?style=for-the-badge)
![RAGAS](https://img.shields.io/badge/RAGAS_Eval-2E86FF?style=for-the-badge)

**ML · Backend · MLOps**<br>
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge)
![SHAP](https://img.shields.io/badge/SHAP-000000?style=for-the-badge)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GCP](https://img.shields.io/badge/GCP_Cloud_Run-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:2E86FF,100:6E56CF&height=3" width="100%" />

## 🐍 Watch My Commits Come Alive

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Khatalahmed/Khatalahmed/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Khatalahmed/Khatalahmed/output/github-contribution-grid-snake.svg" />
  <img alt="snake eating my contributions" src="https://raw.githubusercontent.com/Khatalahmed/Khatalahmed/output/github-contribution-grid-snake.svg" />
</picture>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:2E86FF,100:6E56CF&height=3" width="100%" />

## 🎯 What I Bring to a Team

| | |
|---|---|
| **🤖 Agentic AI** | Multi-agent orchestration (LangGraph, DeepAgents, MCP) with planners, verifiers, and human-in-the-loop |
| **🧠 GenAI & RAG** | Advanced retrieval (HyDE, RAG Fusion, rerank), guardrails, and RAGAS/LLM-judge evaluation |
| **🔧 LLM Fine-Tuning** | QLoRA fine-tuning, GGUF quantization, and local serving at zero API cost |
| **📊 Data Science** | Leakage-safe modeling, XGBoost, SHAP explainability, forecasting & classification |
| **⚙️ Production Mindset** | Docker, GCP Cloud Run, keyless CI/CD, observability, and cost/latency awareness |

<div align="center">

### 💡 Quote I Build By

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" />

</div>

<!-- ====================== ANIMATED FOOTER ====================== -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F1021,50:6E56CF,100:2E86FF&height=140&section=footer&text=From%20notebooks%20to%20production%20%E2%80%94%20grounded%2C%20guarded%2C%20evaluated.&fontSize=17&fontColor=ffffff&fontAlignY=72" width="100%" />
