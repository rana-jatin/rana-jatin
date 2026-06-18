<!--
========================================================================
  TODO BEFORE PUSHING - fill these 4 placeholders:
  1. LinkedIn URL        → search "YOUR-LINKEDIN-HANDLE"
  2. WhatsApp number     → search "91XXXXXXXXXX"
  3. MindMitra live URL  → search "MINDMITRA-LIVE-URL"
  4. Confirm the JSTQE paper title matches your FINAL published title
  Also: PIN MindMitra + Prompt2Mesh repos so they show on your profile,
  and update each project's repo/demo links below.
========================================================================
-->

<div align="center">

[![Header](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&pause=1000&color=58A6FF&center=true&vCenter=true&width=680&lines=Jatin+Rana;Founder+%7C+AI+Engineer+%7C+IEEE+Researcher;I+ship+AI+to+production%2C+then+publish+the+research)](https://github.com/rana-jatin)

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jatin.20234073@mnnit.ac.in)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jatin-rana-340726251/)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/917055184188)

![IEEE](https://img.shields.io/badge/IEEE-Q1_First--Author-00629B?style=flat-square&logo=ieee&logoColor=white)
![Production](https://img.shields.io/badge/MindMitra-Live_in_Production-2ea043?style=flat-square)
![JEE](https://img.shields.io/badge/JEE_2023-99.34_%25ile-orange?style=flat-square)

</div>

---

## `> whoami`

**B.Tech ECE @ MNNIT Allahabad** (2023–27) · **Co-founder, [MindMitra](#-mindmitra--ai-mental-health-companion)** · **First-author IEEE (Q1) researcher** · Robotics Club Coordinator

Most people building AI ship a demo. I ship to **production** - a culturally-grounded mental-health platform serving real users in Hindi - and then publish **peer-reviewed research** on the methods underneath it. My work sits at the intersection of **explainable AI**, **novel neural architectures (KANs)**, and **agentic 3D pipelines**. Off-screen, I play competitive field hockey at the inter-NIT/IIT level.

---

## 🚀 Featured Work

### 🧠 MindMitra - AI Mental-Health Companion &nbsp; [![Live](https://img.shields.io/badge/▲-Live-2ea043?style=flat-square)](https://MINDMITRA-LIVE-URL)
> Hindi-first, culturally-grounded mental-health support. **In production. Serving real users.**

- **Live**, not a prototype - Railway (backend) + Vercel (frontend). **~21K LOC** (6K Python · 15K+ React/TS).
- **Intent-routed 4-path pipeline across 5 LLM providers** - contextual analysis + empathetic response generation.
- **3-layer crisis-detection gate** + **PHQ-9 / GAD-7** clinical screening, advised by an **NABH-accredited MD**.
- **3D lip-synced avatar** - TalkingHead v1.7 + a custom **MindMitraBridge (893 lines)**.
- **Persistent memory** - mem0 + Qdrant (semantic / episodic / procedural) over a **12-table Supabase Postgres** with row-level security.
- **5 companion personas**, **7 therapeutic games**.
- Built with co-founder **Harshit Mathur** (IIT ISM Dhanbad · ex-Zepto SDE).

`React` · `TypeScript` · `Python` · `Supabase` · `Qdrant` · `mem0` · `Three.js` · `Railway`

&nbsp;&nbsp;&nbsp;[**→ Live Demo**](https://mindmmitra.co.in/) &nbsp;|&nbsp; [**→ Architecture**](https://github.com/rana-jatin/mindmitra)

<br>

### 🦀 raeth - Deterministic CLOB Matching Engine (Rust)
> A central-limit-order-book matching engine built for what exchanges actually care about: correctness, determinism, and predictable latency - not feature breadth.

- **~14.4M orders/sec at ~70 ns/order** on a laptop CPU - *measured* (criterion + HDR histograms), not asserted.
- **Zero heap allocation** on the steady-state hot path · **no `unsafe`** · **no floating point** anywhere.
- Strict price-time priority, never crosses the book, conserves shares exactly, replays **bit-for-bit deterministically**.
- Correctness proven with **property tests** over hundreds of randomized command streams.

`Rust` · `zero-alloc` · `property-testing` · `criterion` &nbsp;&nbsp; [**→ Repo**](https://github.com/rana-jatin/raeth-matching-engine)

<br>

### 🎮 Prompt2Mesh - Agentic Text-to-3D
> Presented at the **Sankalp Innovation Challenge 2026**, MNNIT.

- **6-stage agentic pipeline**: prompt → scene graph → 3D generation → optimization.
- Groq NLP · FAISS semantic retrieval · Gaussian Splatting reconstruction.
- **Blender MCP integration** for automated mesh post-processing.

`Groq` · `FAISS` · `Gaussian Splatting` · `Blender` · `Python` &nbsp;&nbsp; [**→ Repo**](https://github.com/vanshika-0305/Prompt2Mesh/tree/main)

<br>

**Also on GitHub:** [Multi-agent code optimizer](https://github.com/rana-jatin/aiquest) · [Ayurvedic AI prognosis](https://github.com/rana-jatin/classifi) · [full repo list →](https://github.com/rana-jatin?tab=repositories)

---

## 🔬 Research-Grade Builds

*Focused, reproducible artifacts - each extends a specific paper or lab's line of work, built to be read, run, and verified (CI, real benchmarks, honest null results).*

- **[affect-equity-audit](https://github.com/rana-jatin/affect-equity-audit)** - Cross-lingual fairness + interpretability audit of text affect recognition (EN vs TR). Extends Cambridge **AFAR Lab**'s subgroup-fairness line to a *language* axis; from-scratch KAN + SHAP + U-Fair metrics against an XLM-R baseline. &nbsp; `Python` · `fairness` · `KAN` · `SHAP`
- **[int4-ssm-scan](https://github.com/rana-jatin/int4-ssm-scan)** - Fused **INT4-dequant + Triton associative-scan** for a diagonal linear SSM (LRU-style), benchmarked vs an fp16 baseline for latency *and* quality - the weight-quantization axis complementary to CompreSSM's state truncation. &nbsp; `Triton` · `GPU` · `quantization` · `SSM`
- **[kan-orbital-free-functionals](https://github.com/rana-jatin/kan-orbital-free-functionals)** - Learning the 1D kinetic-energy density functional `T[n]` with a **KAN** vs KRR/MLP: an orbital-free-DFT proof-of-concept with interpretable splines and a smooth functional derivative `δT/δn`. &nbsp; `Python` · `DFT` · `KAN` · `scientific-ML`
- **[reservoir-vaccinomics](https://github.com/rana-jatin/reservoir-vaccinomics)** - **Reservoir computing** (Echo State Networks) for longitudinal systems-vaccinology transcriptomics; temporal ML on real yellow-fever vaccine-trial data, benchmarked against ridge and LSTM. &nbsp; `Python` · `reservoir-computing` · `time-series` · `bioinformatics`

---

## 🔬 Research & Publications

| Paper | Venue | Year |
| ----- | ----- | ---- |
| *Ultralow Prediction Error in SPR-Based PCF Sensor Using KAN and ANN* - **first author** | **IEEE J. Selected Topics in Quantum Electronics (Q1)** | 2026 |
| *Intervention of ML & Explainable AI in Fiber-Optic Sensor Data for Systematic Performance Optimization* | **IEEE Sensors Letters** | 2024 |

**Headline results:** A Kolmogorov-Arnold Network cuts confinement-loss prediction error to **MAPE 0.02193** - roughly **half** the ANN baseline (0.04327) - on gold-coated PCF-SPR sensors. A CatBoost + SHAP explainability pipeline reaches **R² 0.9997** on fiber-optic figure-of-merit prediction.

**Focus:** explainable AI for photonic-crystal-fiber sensors · KAN vs ANN benchmarking with rigorous statistical validation · ML-driven confinement-loss prediction.

---

## 🏆 Selected Achievements

```text
🔬  IEEE Publication (Q1)   →  J. Selected Topics in Quantum Electronics, 2026   [first author]
🔬  IEEE Publication        →  IEEE Sensors Letters, 2024
🥈  IIT Bombay AI Eduthon   →  National Rank 2   (ML hackathon)
🏅  HackQuest               →  Winner, 2023 & 2024
🤖  MNNIT Robotics Club     →  Coordinator · led BotRush 4.0 (₹40K pool, 3LC.ai-sponsored)
🧊  IBM Quantum             →  Certified - Quantum Foundational
🎓  JEE 2023                →  99.34 percentile
```

---

## 🛠️ Tech Stack

**Languages**
&nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**AI / ML**
&nbsp;
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Unsloth](https://img.shields.io/badge/Unsloth-FF6F00?style=flat-square&logoColor=white)

**Robotics & 3D**
&nbsp;
![ROS](https://img.shields.io/badge/ROS-22314E?style=flat-square&logo=ros&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo-000000?style=flat-square&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-F5792A?style=flat-square&logo=blender&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)

**Cloud & Data**
&nbsp;
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 🗣️ Languages

`English` (Fluent) · `Hindi` (Native) · `German` (Conversational)

---

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=rana-jatin&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117)
![Streak](https://streak-stats.demolab.com?user=rana-jatin&theme=tokyonight&hide_border=true&background=0D1117)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=rana-jatin&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117)

<br>

***Production before funding. Ship first, publish second, talk last.***

![Profile views](https://komarev.com/ghpvc/?username=rana-jatin&style=flat-square&color=58a6ff)

</div>
