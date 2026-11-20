# Abdelouahed Tahri: Machine Learning Engineer (LLMs, Time-Series Forecasting, NLP)

**MSc Artificial Intelligence @ CentraleSupélec (Paris) · Engineering @ École Centrale Casablanca**

I build and evaluate ML systems end to end: **LLM agents and RAG**, **time-series forecasting**, **low-resource NLP** (Moroccan Darija, Arabic, French) and **graph learning**. My habit is to fix the evaluation protocol before running experiments: out-of-sample tests, leakage checks, honest baselines.

🎯 **Open to a 5–6 month research / R&D internship from May 2027** · 🏁 Hackathons welcome

[![Website](https://img.shields.io/badge/Website-qudotcom.github.io-222222?logo=githubpages&logoColor=white)](https://qudotcom.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-abdelouahed--tahri--ai-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdelouahed-tahri-ai)
[![Email](https://img.shields.io/badge/Email-abdelouahed.tahri%40student--cs.fr-D14836?logo=gmail&logoColor=white)](mailto:abdelouahed.tahri@student-cs.fr)
[![SSRN](https://img.shields.io/badge/SSRN-preprint-1F4E79)](https://ssrn.com/abstract=7677118)

---

### ⚡ What I bring to a build

| | |
|---|---|
| 📈 **Forecasting** | GDP **nowcasting** at the Central Bank of Morocco (Reservoir Computing RNN, **+25% accuracy** over statistical baselines) and a **leakage-safe backtesting engine** evaluated out of sample across 121 cohorts ([SSRN preprint](https://ssrn.com/abstract=7677118)) |
| 🤖 **LLM apps & agents** | Hybrid **RAG** with persistent memory and a live monitoring agent ([Zelig](https://github.com/qudotcom/tourism-ai)), and **on-device LLM inference** with llama.cpp on Android ([Macaroon](https://github.com/qudotcom/macaroon-app)) |
| 🗣️ **Multilingual NLP** | Owned the **Moroccan Darija** component of a production voice-AI system: heavy code-switching and no standard spelling |
| 🧮 **Optimization** | CP-SAT combined with genetic algorithms, **optimal on the FT06/FT10** job-shop benchmarks ([live demo](https://jsp-eta.vercel.app)) |
| 🚀 **Shipping fast** | Hackathon MVP ([ExoVision AI](https://github.com/qudotcom/exovision-ai)), Dockerized APIs, deployed demos, tested code (1,200+ tests in Macaroon) |

### 🔬 Current research

**Self-supervised learning on dynamic (temporal) graphs**, CVN lab, CentraleSupélec (2026–2027)
- A reproducible benchmark for contrastive and generative dynamic-graph SSL models, with the evaluation protocol fixed before any experiment
- A synthetic graph generator with tunable temporal heterophily, smoothness, feature noise, sparsity and unseen nodes, to isolate what drives each performance gap
- Node classification and link prediction with PyTorch Geometric on Slurm · target venue: NeurIPS / ICLR

### 💼 Experience

- **ML Intern, Conversational AI: CRSC (deployed at BMCI Bank)** · May–Aug 2026
  Owned the Moroccan Darija language component of a voice AI system that trains bank sales teams.
- **Data Science & Modelling Intern: Bank Al-Maghrib (Central Bank of Morocco)** · Jul–Aug 2025
  GDP nowcasting with Reservoir Computing: preprocessing, feature engineering, tuning and evaluation. **+25% accuracy** over classical baselines; dashboard and results presented to senior management.
- **President: Centrale Quanta Club, École Centrale Casablanca** · 2025–present
  Leading student research projects, technical conferences and ML workshops.

### 🔭 Featured projects

| Project | What it does | Stack |
|---|---|---|
| [**Zelig: tourism-ai**](https://github.com/qudotcom/tourism-ai) | Hybrid RAG assistant: grounded answers over a curated knowledge base, persistent vector memory, and a live news-monitoring safety agent with risk scoring. REST API, Dockerized | LangChain · HuggingFace · Gemini · ChromaDB · FastAPI · React |
| [**macaroon-app**](https://github.com/qudotcom/macaroon-app) | Offline-first companion running an **on-device LLM** (llama.cpp via JNI on Android). AES-GCM encrypted backups, EN/FR/AR with RTL, 1,200+ tests | JavaScript · Capacitor · Kotlin · C++ |
| [**job-shop-scheduler**](https://github.com/qudotcom/job-shop-scheduler) · [demo](https://jsp-eta.vercel.app) | Exact **CP-SAT** model combined with a **genetic algorithm**: optimal on FT06 and FT10, with interactive Gantt charts | OR-Tools · Flask · Plotly |
| [**exovision-ai**](https://github.com/qudotcom/exovision-ai) | Hackathon MVP: classifies Kepler exoplanet candidates and fine-tunes on user-labelled data in the app | LightGBM · Flask |
| [**QLP-SOLVER**](https://github.com/qudotcom/QLP-SOLVER) | Quantum linear solvers (**HHL, VQLS, adiabatic**) for elasticity problems, benchmarked against a classical LU solver | Qiskit · FastAPI · Docker |
| [**quantum-chess-arena**](https://github.com/qudotcom/quantum-chess-arena) | Centrale Quanta club platform: multiplayer quantum chess with superposition, entanglement, an AI opponent and tournament brackets | FastAPI · SQLAlchemy · JS |
| [**quantum-ml-notebooks**](https://github.com/qudotcom/quantum-ml-notebooks) | Variational quantum classifier vs. a classical neural-network baseline | PennyLane · PyTorch |

### 📄 Publications

- **Systematic strategy backtesting and validation framework**: a reproducible Python backtesting engine with explicit data-leakage protection and out-of-sample evaluation across 121 cohorts. Preprint on [SSRN](https://ssrn.com/abstract=7677118); submitted to the *Journal of Asset Management*.

### 🛠️ Skills

**LLMs & NLP:** RAG · agents · LangChain · HuggingFace Transformers · ChromaDB · llama.cpp / GGUF · low-resource & multilingual NLP
**Forecasting & ML:** time-series forecasting · nowcasting · backtesting · out-of-sample validation · PyTorch · PyTorch Geometric · TensorFlow · scikit-learn · LightGBM · pandas · NumPy
**Optimization:** Google OR-Tools (CP-SAT) · genetic algorithms · Qiskit · PennyLane
**Engineering:** Python · FastAPI · Docker · REST APIs · Slurm · Git · JavaScript

### 🎓 Education

- **MSc Artificial Intelligence**: CentraleSupélec, Université Paris-Saclay · 2026–2027
- **Diplôme d'Ingénieur, AI & Digital Transformation**: École Centrale Casablanca · 2024–2027
- **CPGE MP**: Lycée Omar Ibn Al-Khattab, Meknès · 2022–2024

🌍 Arabic (native) · French (C1) · English (professional) · 🏆 Pre-Plancks physics competition: 4th (2024) and 8th (2025) nationally
