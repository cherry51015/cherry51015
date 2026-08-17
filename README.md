<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:05070A,35:0D1B2A,70:123B63,100:05070A&height=240&section=header&text=CHARANI&fontSize=72&fontColor=E6EDF3&fontAlignY=38&desc=AI%20ENGINEERING%20%C2%B7%20RETRIEVAL%20%C2%B7%20EVALUATION%20%C2%B7%20ML%20SYSTEMS&descSize=15&descAlignY=62&descColor=79C0FF&animation=fadeIn" width="100%"/>

<br>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=16&duration=2800&pause=900&color=79C0FF&center=true&vCenter=true&width=780&lines=I+build+systems+around+models%2C+not+just+models.;Retrieval+that+knows+where+it+came+from.;Models+that+are+tested+before+they+are+trusted.;AI+%C3%97+Neuroscience+%C3%97+Explainability;Currently+building+LLM+evaluation+systems+at+Ethara+AI." />

<br><br>

<a href="mailto:charani51015@gmail.com">
<img src="https://img.shields.io/badge/EMAIL-0D1117?style=for-the-badge&logo=gmail&logoColor=EA4335&labelColor=0D1117"/>
</a>
&nbsp;
<a href="https://linkedin.com/in/sri-naga-charani">
<img src="https://img.shields.io/badge/LINKEDIN-0D1117?style=for-the-badge&logo=linkedin&logoColor=0A66C2&labelColor=0D1117"/>
</a>
&nbsp;
<a href="https://github.com/cherry51015">
<img src="https://img.shields.io/badge/GITHUB-0D1117?style=for-the-badge&logo=github&logoColor=FFFFFF&labelColor=0D1117"/>
</a>
&nbsp;
<a href="https://github.com/cherry51015/Levi-legal_AI_assistant">
<img src="https://img.shields.io/badge/FLAGSHIP%20PROJECT-LEVI-0D1117?style=for-the-badge&logo=readthedocs&logoColor=79C0FF&labelColor=0D1117"/>
</a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=cherry51015&label=PROFILE%20VIEWS&color=1f6feb&style=flat-square"/>

</div>

---

## `~/about`

> **I don't just build models. I build the systems around them.**

I'm **Sri Naga Charani**, a Computer Science undergraduate at **IIIT Kota** working at the intersection of **LLM engineering, retrieval systems, evaluation, backend systems, and applied ML research**.

Currently at **Ethara AI**, working on LLM evaluation and generative-output benchmarking — building systematic ways to identify **hallucination, instruction drift, grounding failures, relevance issues, and other failure modes** that don't appear in a happy-path demo.

Alongside engineering, I'm researching **ASD classification from resting-state fMRI** under **Dr. Bhavna Bajpai**, combining graph-based deep learning, explainability, and LLM-assisted interpretation.

The common thread across my work:

```text
                    ┌─────────────────┐
                    │      DATA       │
                    └────────┬────────┘
                             ↓
                    ┌─────────────────┐
                    │      MODEL      │
                    └────────┬────────┘
                             ↓
                    ┌─────────────────┐
                    │    RETRIEVAL    │
                    └────────┬────────┘
                             ↓
                    ┌─────────────────┐
                    │   EVALUATION    │
                    └────────┬────────┘
                             ↓
                    ┌─────────────────┐
                    │   DEPLOYMENT    │
                    └────────┬────────┘
                             ↓
                    ┌─────────────────┐
                    │   OBSERVATION   │
                    └────────┬────────┘
                             │
                             └──→ improve → repeat
```

**The goal isn't a model that works once.
The goal is a system that still works when nobody is watching.**

---

<div align="center">

## `SYSTEM SIGNALS`

<table>
<tr>

<td align="center" width="20%">

### 153K+

<sub>LEGAL CLAUSES<br>LEVI</sub>

</td>

<td align="center" width="20%">

### 570

<sub>ABIDE-I<br>SUBJECTS</sub>

</td>

<td align="center" width="20%">

### 0.793

<sub>MEAN AUC<br>ASD CLASSIFIER</sub>

</td>

<td align="center" width="20%">

### 17+

<sub>PUBLIC<br>REPOSITORIES</sub>

</td>

<td align="center" width="20%">

### 46

<sub>SOURCES<br>PRISMA REVIEW</sub>

</td>

</tr>
</table>

</div>

---

<div align="center">

# `01 / FEATURED SYSTEMS`

</div>

<table>
<tr>

<td width="50%" valign="top">

<h3>🔎 Levi</h3>

### Legal Document Intelligence

A retrieval-grounded legal assistant built around a simple principle:

> **If the system cannot ground an answer in the documents, it shouldn't confidently answer.**

```text
Documents
    ↓
Chunking / Indexing
    ↓
┌─────────┬─────────┐
│  BM25   │  FAISS  │
└────┬────┴────┬────┘
     └─────┬───┘
           ↓
    Hybrid Retrieval
           ↓
         Gemini
           ↓
    Grounding Check
           ↓
   ┌───────┴───────┐
   ↓               ↓
Briefing          Chat
```

**Highlights**

* 153K+ legal clauses
* BM25 + FAISS hybrid retrieval
* LLM-as-judge evaluation
* Document-grounding guardrails
* Modular verifier / briefing / chat modes
* FastAPI backend
* GCP Cloud Run deployment

`FASTAPI` `FAISS` `BM25` `GEMINI` `GCP`

<br>

<a href="https://github.com/cherry51015/Levi-legal_AI_assistant">
<img src="https://img.shields.io/badge/VIEW%20REPOSITORY-1F6FEB?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</td>

<td width="50%" valign="top">

<h3>🌐 Agent-Translator</h3>

### Structure-Aware Document Translation

Not:

```text
PDF → text → LLM → PDF
```

Instead:

```text
Input Document
      ↓
Structure Analysis
      ↓
Agent Routing
      ↓
Translation
      ↓
Equation / Table / Layout
Preservation
      ↓
Independent QA
      ↓
Self-Correction
      ↓
Reconstructed Document
```

Supports academic documents across:

`DOCX` · `PDF` · `TXT`

Uses hierarchical agents and a self-correcting QA loop.

`PYTHON` `CREWAI` `MULTI-AGENT` `AWS ECS`

<br>

<a href="https://github.com/cherry51015/Agent-Translator">
<img src="https://img.shields.io/badge/VIEW%20REPOSITORY-1F6FEB?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</td>

</tr>

<tr>

<td width="50%" valign="top">

<h3>📖 NarrativeForge</h3>

### Human-in-the-Loop Generation

A publication workflow where generation isn't the endpoint.

```text
Web
 ↓
Research
 ↓
Draft
 ↓
Human Review
 ↓
Feedback
 ↓
Refinement
 ↓
Improved Output
```

The interesting part isn't just the generator.

**It's the feedback loop around it.**

`LANGCHAIN` `PYTHON` `RL`

<br>

<a href="https://github.com/cherry51015/NarrativeForge">
<img src="https://img.shields.io/badge/VIEW%20REPOSITORY-1F6FEB?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</td>

<td width="50%" valign="top">

<h3>📋 Trello Clone</h3>

### Full-Stack Systems Engineering

Built end-to-end under a two-day SDE assignment window.

```text
React / Vite
     ↕
REST APIs
     ↕
FastAPI
     ↕
SQLAlchemy
     ↕
PostgreSQL
```

**Highlights**

* Fractional indexing
* Optimistic UI updates
* Drag-and-drop ordering
* Custom React hooks
* Card / checklist / label workflows
* Production deployment

`REACT` `FASTAPI` `POSTGRESQL` `VITE`

<br>

<a href="https://github.com/cherry51015/trello-clone">
<img src="https://img.shields.io/badge/VIEW%20REPOSITORY-1F6FEB?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</td>

</tr>
</table>

---

<div align="center">

# `02 / RESEARCH`

</div>

## 🧠 LLM-Assisted Neuroimaging Explainability

### ASD Prediction & Individual Biomarker Identification from Resting-State fMRI

Research with **Renu Rawal, Kunja Anusri, and Dr. Bhavna Bajpai**.

A pipeline connecting neuroimaging, graph-based deep learning, explainability, and language models:

```text
                    ABIDE-I
                       │
                       ▼
               Resting-state fMRI
                       │
                       ▼
            Functional Connectivity
                       │
                       ▼
                  Schaefer-400
                       │
                       ▼
                  BrainNetCNN
                       │
                       ▼
                  ASD Prediction
                       │
                       ▼
                  GradientSHAP
                       │
                       ▼
                Yeo-7 Networks
                       │
                       ▼
             Biomarker Representation
                       │
                       ▼
                  Llama-3.3-70B
                       │
                       ▼
           Natural-Language Explanation
```

### Research Snapshot

| Signal            |            Result |
| ----------------- | ----------------: |
| Subjects          |           **570** |
| Atlas             |  **Schaefer-400** |
| Model             |   **BrainNetCNN** |
| Mean AUC          |         **0.793** |
| Attribution       |  **GradientSHAP** |
| Network mapping   |         **Yeo-7** |
| Explanation layer | **Llama-3.3-70B** |

`fMRI` `BRAINNETCNN` `GRADIENTSHAP` `XAI` `GRAPH LEARNING` `LLM`

---

<div align="center">

# `03 / CURRENTLY`

</div>

<table>

<tr>

<td width="33%" valign="top">

### 🧪 EVALUATION

**Ethara AI**

Working on LLM evaluation frameworks and generative-output benchmarking.

Focus areas:

* Human-preference signals
* Rubric-based evaluation
* Faithfulness
* Grounding
* Relevance
* Instruction following
* Adversarial testing
* Failure-mode discovery

</td>

<td width="33%" valign="top">

### 🔬 RESEARCH

**AI × Neuroscience**

Exploring:

* Functional connectivity
* Graph-based learning
* Explainability
* Biomarker discovery
* LLM-assisted interpretation

> Can a black-box prediction become an understandable scientific hypothesis?

</td>

<td width="33%" valign="top">

### 🛠️ ENGINEERING

**Systems over demos**

Interested in:

* RAG architectures
* Agentic workflows
* LLM evaluation
* Model serving
* Cloud infrastructure
* Retrieval quality
* Observability
* Reliable AI systems

</td>

</tr>

</table>

---

<div align="center">

# `04 / ENGINEERING STACK`

</div>

### `LANGUAGES`

<div align="center">

<img src="https://skillicons.dev/icons?i=python,cpp,javascript,typescript&theme=dark"/>

</div>

### `AI / ML`

<div align="center">

<img src="https://skillicons.dev/icons?i=pytorch,tensorflow&theme=dark"/>

<br><br>

<img src="https://img.shields.io/badge/Transformers-161B22?style=flat-square&logo=huggingface&logoColor=FFD21E"/>
<img src="https://img.shields.io/badge/LangChain-161B22?style=flat-square&logoColor=79C0FF"/>
<img src="https://img.shields.io/badge/LangGraph-161B22?style=flat-square&logoColor=79C0FF"/>
<img src="https://img.shields.io/badge/CrewAI-161B22?style=flat-square&logoColor=79C0FF"/>
<img src="https://img.shields.io/badge/LlamaIndex-161B22?style=flat-square&logoColor=79C0FF"/>
<img src="https://img.shields.io/badge/FAISS-161B22?style=flat-square&logoColor=79C0FF"/>
<img src="https://img.shields.io/badge/BM25-161B22?style=flat-square&logoColor=79C0FF"/>
<img src="https://img.shields.io/badge/RAG-161B22?style=flat-square&logoColor=79C0FF"/>
<img src="https://img.shields.io/badge/MCP-161B22?style=flat-square&logoColor=79C0FF"/>

</div>

### `BACKEND / DATA`

<div align="center">

<img src="https://skillicons.dev/icons?i=fastapi,react,postgres,redis&theme=dark"/>

</div>

### `CLOUD / INFRA`

<div align="center">

<img src="https://skillicons.dev/icons?i=docker,aws,gcp,git,githubactions&theme=dark"/>

<br><br>

<img src="https://img.shields.io/badge/Amazon_Bedrock-161B22?style=flat-square&logo=amazonaws&logoColor=FF9900"/>
<img src="https://img.shields.io/badge/AWS_ECS-161B22?style=flat-square&logo=amazonaws&logoColor=FF9900"/>
<img src="https://img.shields.io/badge/Cloud_Run-161B22?style=flat-square&logo=googlecloud&logoColor=4285F4"/>
<img src="https://img.shields.io/badge/CI%2FCD-161B22?style=flat-square&logo=githubactions&logoColor=79C0FF"/>

</div>

---

<div align="center">

# `05 / EXPERIENCE`

</div>

```text
2026 ───────────────────────────────────────────────────────── NOW

ETHARA AI
LLM Post-Training / Evaluation Intern

├── LLM evaluation frameworks
├── Generative-output benchmarking
├── Adversarial stress testing
├── Failure-mode analysis
└── Faithfulness / grounding / relevance


ONGOING ─────────────────────────────────────────────────────────

RESEARCH
ASD Classification from Resting-State fMRI

├── BrainNetCNN
├── Functional connectivity
├── GradientSHAP
├── Yeo-7 network aggregation
└── LLM-assisted explanations


2024 ───────────────────────────────────────────────────────────

FOX TRADING
ML Engineer

├── Forex feature engineering
├── LSTM
├── XGBoost
└── Walk-forward validation


OPEN SOURCE ───────────────────────────────────────────────────

LANGCHAIN ECOSYSTEM

└── RAG guardrails / retrieval refinement
```

---

<div align="center">

# `06 / SIGNALS`

<table>

<tr>

<td align="center" width="25%">

### 🏆

**Google GenAI Hackathon**

Top 15 Finalist

National

</td>

<td align="center" width="25%">

### 🏦

**Goldman Sachs Hackathon**

Builder

</td>

<td align="center" width="25%">

### 🎓

**McKinsey Forward**

Scholar

</td>

<td align="center" width="25%">

### 📚

**Systematic Review**

46-source PRISMA study

</td>

</tr>

</table>

</div>

---

<div align="center">

# `07 / ENGINEERING PHILOSOPHY`

</div>

<table>

<tr>

<td width="50%" valign="top">

### `01` — RELIABILITY

A beautiful demo is easy.

A system that survives:

* noisy retrieval
* adversarial prompts
* hallucinations
* malformed inputs
* model changes
* production traffic

is much harder.

**That's the interesting part.**

</td>

<td width="50%" valign="top">

### `02` — EVALUATION

If you cannot measure failure,

**you don't really know whether the system works.**

I'm interested in evaluation that goes beyond a single benchmark number.

</td>

</tr>

<tr>

<td width="50%" valign="top">

### `03` — EXPLAINABILITY

Prediction is only half the problem.

For scientific and high-stakes applications:

```text
prediction
    ↓
attribution
    ↓
structure
    ↓
explanation
    ↓
human understanding
```

</td>

<td width="50%" valign="top">

### `04` — SYSTEMS

I like the layer between:

```text
"the model works"
```

and

```text
"the product works."
```

APIs · Retrieval · Evaluation · Deployment · Observability · Failure Handling

</td>

</tr>

</table>

---

<div align="center">

# `08 / GITHUB TELEMETRY`

<br>

<img src="https://github-readme-stats.vercel.app/api?username=cherry51015&show_icons=true&hide_border=true&bg_color=0D1117&title_color=E6EDF3&icon_color=79C0FF&text_color=8B949E&rank_icon=github&hide=contribs&include_all_commits=true" height="170"/>

  

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=cherry51015&layout=compact&hide_border=true&bg_color=0D1117&title_color=E6EDF3&text_color=8B949E&langs_count=8" height="170"/>

<br><br>

<img src="https://streak-stats.demolab.com/?user=cherry51015&theme=github-dark-blue&hide_border=true&background=0D1117&stroke=1F6FEB&ring=79C0FF&fire=79C0FF&currStreakLabel=E6EDF3" height="170"/>

<br><br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=cherry51015&bg_color=0D1117&color=79C0FF&line=1F6FEB&point=FFFFFF&area=true&hide_border=true" width="95%"/>

</div>

---

<div align="center">

# `09 / CONTRIBUTIONS`

<img src="https://raw.githubusercontent.com/cherry51015/cherry51015/output/github-contribution-grid-snake-dark.svg" width="95%"/>

</div>

---

<div align="center">

## `CURRENTLY BUILDING`

### Reliable AI systems where retrieval, reasoning and evaluation meet.

<br>

`RAG` · `LLM EVALUATION` · `AGENTS` · `ML SYSTEMS` · `XAI`

<br><br>

<a href="mailto:charani51015@gmail.com">
<img src="https://img.shields.io/badge/LET'S_BUILD_SOMETHING_INTERESTING-1F6FEB?style=for-the-badge&logoColor=white"/>
</a>

<br><br>

<sub>

IIIT Kota · Computer Science · Batch '27

</sub>

</div>

<br>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:05070A,35:0D1B2A,70:123B63,100:05070A&height=130&section=footer" width="100%"/>

</div>
