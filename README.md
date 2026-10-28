<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&color=0:0f172a,50:1e1b4b,100:3b0764&height=200&section=header&text=Arnav%20Raut&fontSize=52&fontColor=ffffff&fontAlignY=42&desc=Applied%20ML%20%E2%80%A2%20GenAI%20%26amp%3B%20NLP%20%E2%80%A2%20Time%20Series%20Forecasting&descAlignY=68&descSize=17" width="100%" alt="Header Banner" />
</div>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3500&pause=1000&color=38BDF8&center=true&vCenter=true&width=750&lines=Benchmarking+encoder+and+decoder+LLMs+on+live+data+streams.;Extracting+next-token+logits+for+calibrated+LLM+scoring.;Building+leakage-free+time-series+and+semantic+search+pipelines." alt="Typing SVG" />
</div>

<div align="center">
  <a href="https://arnavraut.in/"><img src="https://img.shields.io/badge/Portfolio-76B900?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/arnav-raut-0824042a2/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square" alt="LinkedIn" /></a>
  <a href="mailto:arnavraut390@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://komarev.com/ghpvc/?username=Artifact19&label=profile%20views&color=brightgreen&style=flat-square" alt="Profile Views" />
</div>

<br/>

## Currently

Final-year **Computer Science Engineering undergraduate** at **MIT-ADT University, Pune** (CGPA: **8.47**, 2023–2027) building end-to-end NLP, time-series forecasting, and retrieval systems.

* 🔬 **Deep Learning & GenAI** - Benchmarking zero-shot encoder (`DeBERTa`) vs. decoder (`Qwen2.5-3B`) models, extracting next-token logits for exact probability scoring, and building `RAG` and fine-tuning workflows.
* 📈 **Machine Learning** - Engineering leakage-free rolling window features for `XGBoost` financial forecasting and mapping dense `BERT` embedding spaces for recommendation engines.
* ⚙️ **MLOps & Deployment** - Serving inference pipelines and interactive applications using `FastAPI`, `Streamlit`, `REST APIs`, and `AWS`.
* 🎓 **Certifications** - **DeepLearning.AI** Deep Learning Specialization (Coursera, 2026) & **AWS** Cloud Foundations Training Badge (2026).
* 💬 **Ask me about** - Next-token logit extraction, linearly weighted Cohen's Kappa on human-annotated datasets, chronological time-series validation, and `FastAPI` + `Streamlit` deployments.

---

## Featured Architectures

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🧠 Aspect-Based Sentiment Analysis Studio</h3>
      <p>Live X (Twitter) target-oriented sentiment pipeline classifying arbitrary topics across three polarity classes.</p>
      <p><b>Pipeline:</b> <code>FetchLayer API</code> → <code>URL/Handle Normalizer &amp; Deduplication Keys</code> → <code>DeBERTa vs. Qwen2.5-3B Benchmark</code> → <code>Two-Stage Qwen2.5-3B Logit Scoring &amp; Streaming Summary</code></p>
      <p><b>Evaluation:</b> Benchmarked against 104 manually annotated tweets, achieving linearly weighted Cohen's Kappa of <b>0.57</b> (<code>Qwen2.5-3B</code>) and <b>0.35</b> (<code>DeBERTa</code>).</p>
      <p>
        <code>PyTorch</code> <code>Hugging Face</code> <code>Qwen2.5-3B</code> <code>DeBERTa</code> <code>Logit Extraction</code>
      </p>
      <!-- <p><a href="#"><b>Explore Repo →</b></a> • <a href="#"><b>Live Studio →</b></a></p> -->
    </td>
    <td width="50%" valign="top">
      <h3>📈 Stock Return Forecasting Pipeline</h3>
      <p>Multi-step time-series regression pipeline predicting 5-day cumulative returns to project weekly price targets from Yahoo Finance data.</p>
      <p><b>Pipeline:</b> <code>Yahoo Finance Data</code> → <code>5d/20d Rolling Momentum, Lag &amp; Volatility</code> → <code>L2-Regularized Shallow XGBoost</code> → <code>Price Target Reconstruction</code></p>
      <p><b>Evaluation:</b> Prevented lookahead bias via chronological splits and benchmarked against a Linear Regression baseline on out-of-sample directional accuracy and MAPE.</p>
      <p>
        <code>Python</code> <code>XGBoost</code> <code>Scikit-learn</code> <code>Pandas</code> <code>NumPy</code>
      </p>
      <!-- <p><a href="#"><b>Explore Repo →</b></a></p> -->
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3>🎮 Content-Based Game Recommendation System (BERT + Streamlit)</h3>
      <p>Semantic recommendation engine representing video games in dense vector spaces via an automated <b>RAWG API + Kaggle ETL pipeline</b> fusing descriptions, genres, tags, and reviews.</p>
      <p><b>Evaluation:</b> Computed pairwise cosine similarity across normalized <code>BERT</code> embeddings for real-time retrieval in a <b>Streamlit</b> app, achieving a <b>60% Hit Ratio</b> in user acceptance testing across 50 campus participants.</p>
      <p>
        <code>BERT Embeddings</code> <code>Cosine Similarity</code> <code>RAWG API</code> <code>Streamlit</code> <code>ETL</code>
      </p>
    </td>
  </tr>
</table>

---

## Stack

| Category | Technologies |
| :--- | :--- |
| **Programming Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white) |
| **Deep Learning & GenAI** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white) ![Hugging Face Transformers](https://img.shields.io/badge/Hugging%20Face%20Transformers-FFD21E?style=flat&logo=huggingface&logoColor=black) ![LLM APIs](https://img.shields.io/badge/LLM%20APIs-412991?style=flat&logo=googlegemini&logoColor=white) ![RAG](https://img.shields.io/badge/RAG-10B981?style=flat) ![Fine-Tuning](https://img.shields.io/badge/Fine--Tuning-6366F1?style=flat) |
| **Machine Learning & Data Science** | ![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikitlearn&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white) ![Time Series Forecasting](https://img.shields.io/badge/Time%20Series%20Forecasting-2563EB?style=flat) ![Statistics](https://img.shields.io/badge/Statistics-0D9488?style=flat) |
| **MLOps & Deployment** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white) ![REST APIs](https://img.shields.io/badge/REST%20APIs-0284C7?style=flat) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white) ![Model Evaluation](https://img.shields.io/badge/Model%20Evaluation-7C3AED?style=flat) |
| **BI & Visualization** | ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black) ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat) ![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat) |

---

## Telemetry

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Artifact19&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117" height="165" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Artifact19&theme=tokyonight&hide_border=true&background=0D1117" height="165" alt="GitHub Streak" />
</div>
