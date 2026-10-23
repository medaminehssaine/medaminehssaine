<div align="center">

# Hi, I'm Mohammed Amine Hssaine 👋

### AI & Data Engineering student · ML research · Data platforms · Tech community lead

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/medaminehssaine/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://medaminehssaine.vercel.app)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:med.amine.hssaine@gmail.com)

</div>

---

I'm an engineering student in **AI & Data Technologies at ENSAM Meknès** (Morocco). I like problems where getting the measurement right matters as much as getting the model right, from 3D motion generation to production data pipelines.

- 🔬 **Research intern at AI Movement – UM6P**, Morocco's International Center for AI. I extended MotionCLIP to generate 3D human motion from text in **7 languages** → [multilingual-motionclip](https://github.com/medaminehssaine/multilingual-motionclip)
- 💼 **AI Software Engineer at AriMayi**: sales forecasting and recommendation systems for e-commerce
- 🧑‍🤝‍🧑 **President of Gadz'IT**, ENSAM Meknès' computer science club (member → sponsorship lead → VP → president)
- 🏁 Organised **AMPC3**, a national competitive programming contest with 40+ teams and 18,000 MAD in prizes

---

## ⭐ Featured work

### 🕺 [Multilingual MotionCLIP](https://github.com/medaminehssaine/multilingual-motionclip): text → 3D human motion in 7 languages

<a href="https://github.com/medaminehssaine/multilingual-motionclip"><img src="https://raw.githubusercontent.com/medaminehssaine/multilingual-motionclip/main/assets/gifs/languages/walk_7langs.gif" width="100%" alt="Same prompt in seven languages"></a>

A controlled research study, run during my internship at UM6P. Built on MotionCLIP and HumanML3D:

- Translated **24,844 motion captions** into 6 languages with NLLB-200, and swapped CLIP for **M-CLIP** or a **bank of 7 monolingual BERTs**
- Restored the **VAE objective** and replaced cosine alignment with **contrastive InfoNCE**, which turned a 0.0002 alignment gap into 0.0206
- Wrote the evaluation stack: **FID / R-precision** following the MoMask protocol, plus a 7-language latent-alignment benchmark; ~40 documented training runs
- **Result:** in a single-latent model, languages *divide* a fixed capacity. Each added language closes its own gap, and English retrieval halves.

`PyTorch` `Transformers` `VAE` `Contrastive learning` `M-CLIP` `NLLB-200` `HumanML3D` `SMPL`

---

### More projects

| Project | What it is | Stack |
|---|---|---|
| ☁️ [**Azure AdventureWorks Lakehouse**](https://github.com/medaminehssaine/azure-adventureworks-lakehouse) | End-to-end Azure data engineering: SQL Server → ADLS Gen2 bronze / silver / gold → Synapse → Power BI, with tested PySpark, data-quality gates, Bicep IaC and CI | PySpark · Azure · Bicep · Power BI |
| 🏭 [**Supply-Chain Kaizen Lakehouse**](https://github.com/medaminehssaine/supply-chain-kaizen-lakehouse) | Lean / Kaizen KPI pipeline (OTIF, OEE, defect PPM, inventory turns) with Pareto, SPC and PDCA analytics on a DuckDB medallion warehouse | Python · DuckDB · CI |
| ⚙️ [**APDA demo**](https://github.com/medaminehssaine/apda-demo) | Agentic product-development architecture demo on a DN100 butterfly valve: an agent chain with deterministic DFx scoring, in FR and EN | TypeScript · AI agents |
| 🌳 [**ID3 & C4.5**](https://github.com/medaminehssaine/ID3-C4.5) | Clean from-scratch implementation of the ID3 and C4.5 decision-tree algorithms | Python |
| ⚡ [**EnergyManager**](https://github.com/medaminehssaine/EnergyManager) | Data-driven district energy management | Python |
| 📊 [**OEE360**](https://github.com/medaminehssaine/OEE360) | Data analytics platform: dataset upload, model management and analysis | Python · Web |
| 🎙️ [**Live-Subtitles**](https://github.com/medaminehssaine/Live-Subtitles) | Desktop app that transcribes any live stream in 21 languages with Vosk, then translates it as live subtitles | Java · Vosk |
| 🗓️ [**ReservENSAM**](https://github.com/medaminehssaine/ReservENSAM) | Room reservation system for ENSAM | PHP · JavaScript |

---

## 🛠️ Toolbox

**AI / ML**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?logo=mlflow&logoColor=white)

**Data engineering**
![Apache Spark](https://img.shields.io/badge/PySpark-E25A1C?logo=apachespark&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?logo=duckdb&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi&logoColor=black)

**Software & infrastructure**
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?logo=springboot&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

---

## 📈 GitHub activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=medaminehssaine&show_icons=true&theme=transparent&hide_border=true&count_private=true" alt="GitHub stats">
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=medaminehssaine&layout=compact&theme=transparent&hide_border=true&langs_count=8" alt="Top languages">

</div>

---

<div align="center">

**Open to research and engineering internships in ML, computer vision / motion, and data engineering.**
Happy to talk about multilingual models, evaluation that you can trust, or competitive programming.

</div>
