<div align="center">
    <img src="https://capsule-render.vercel.app/api?type=venom&color=0:0f172a,50:1e1b4b,100:3b0764&height=200&section=header&text=Arnav%20Raut&fontSize=52&fontColor=ffffff&fontAlignY=42&desc=Applied%20ML%20%E2%80%A2%20GenAI%20%26amp%3B%20NLP%20%E2%80%A2%20Time%20Series%20Forecasting&descAlignY=68&descSize=17" width="100%" alt="Header Banner" />
</div>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3500&pause=1000&color=38BDF8&center=true&vCenter=true&width=750&lines=Benchmarking+encoder+and+decoder+LLMs+on+live+social+streams.;Cloning+voices+across+22+Indian+languages+with+zero-shot+TTS.;Forecasting+multi-horizon+returns+with+conformal+intervals." alt="Typing SVG" />
</div>

<div align="center">
  <a href="https://arnavraut.in/"><img src="https://img.shields.io/badge/Portfolio-76B900?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/arnav-raut-0824042a2/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square" alt="LinkedIn" /></a>
  <a href="mailto:arnavraut390@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://komarev.com/ghpvc/?username=Artifact19&label=profile%20views&color=brightgreen&style=flat-square" alt="Profile Views" />
</div>

<br/>

## Currently

Final-year **Computer Science Engineering undergraduate** at **MIT-ADT University, Pune** (CGPA: **8.47**, 2023-2027) building end-to-end NLP, speech, computer vision, and time-series forecasting systems.

* 🔬 **Deep Learning & GenAI** - Benchmarking encoder (`DeBERTa`) vs. decoder (`Qwen2.5-3B`) models using next-token logit scoring and linearly weighted Cohen's Kappa, and building a zero-shot voice cloning agent with hybrid dense + sparse + BM25 `RAG` retrieval.
* 📈 **Machine Learning** - Direct multi-horizon `XGBoost` forecasting with conformalized quantile regression intervals, leakage-tested causal features, and purged walk-forward validation.
* 👁️ **Computer Vision** - Fine-tuning `MobileNetV3` with transfer learning, calibrating confidence with temperature scaling, and explaining predictions with `Grad-CAM`.
* ⚙️ **ML Deployment** - Serving models through `FastAPI`, `Next.js`, `Supabase`, and `Hugging Face Spaces` (ZeroGPU), with `ONNX Runtime` for faster CPU inference, low-latency audio streaming, and audit ledgers that score live forecasts against realized prices.
* 🎓 **Certifications** - **DeepLearning.AI** Deep Learning Specialization (Coursera, 2026) & **AWS** Cloud Foundations Training Badge (2026).

---

## Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🧠 Aspect-Based Sentiment Analysis Studio</h3>
      <p>Live target-oriented sentiment pipeline that pulls posts from X and Reddit and classifies sentiment toward any entity across three polarity classes.</p>
      <p><b>Pipeline:</b> <code>FetchLayer API (X + Reddit)</code> → <code>Cleaning, Handle Masking &amp; SHA-256 Dedup</code> → <code>DeBERTa vs. Qwen2.5-3B Benchmark</code> → <code>Next-Token Probability Scoring on ZeroGPU</code> → <code>14-Day Recency-Weighted Sentiment &amp; Streamed Summaries</code></p>
      <p><b>Evaluation:</b> On 104 manually annotated tweets, <code>Qwen2.5-3B</code> reached a linearly weighted Cohen's Kappa of <b>0.57</b> vs. <b>0.35</b> for <code>DeBERTa</code> (<b>63% higher</b>).</p>
      <p>
        <code>PyTorch</code> <code>Hugging Face</code> <code>Qwen2.5-3B</code> <code>DeBERTa</code> <code>Supabase</code>
      </p>
      <p><a href="https://github.com/Artifact19/absa-studio"><img src="https://img.shields.io/badge/GitHub-absa--studio-181717?style=flat-square&logo=github&logoColor=white" alt="absa-studio repo" /></a></p>
    </td>
    <td width="50%" valign="top">
      <h3>📈 Log Pose Terminal: Multi-Horizon Stock Forecasting</h3>
      <p>Direct multi-horizon XGBoost models forecasting 1 to 20-day log-returns on 8 years of data, with calibrated prediction intervals and a live audit ledger.</p>
      <p><b>Pipeline:</b> <code>8 Years of Daily Prices</code> → <code>18 Causal Features (Yang-Zhang Vol, RSI, MACD, Lags)</code> → <code>Direct Multi-Horizon XGBoost</code> → <code>Conformalized Quantile Regression</code> → <code>Audit Ledger &amp; Live Scoring</code></p>
      <p><b>Evaluation:</b> 8-fold purged walk-forward testing on 504 unseen trading days. 80% and 95% intervals hit <b>78.8-79.9%</b> and <b>93.7-95.5%</b> coverage across 4 stocks. Unit tests perturb future prices to verify zero leakage.</p>
      <p>
        <code>Python</code> <code>XGBoost</code> <code>Conformal Prediction</code> <code>Pandas</code> <code>NumPy</code>
      </p>
      <p><a href="https://github.com/Artifact19/log-pose-terminal"><img src="https://img.shields.io/badge/GitHub-log--pose--terminal-181717?style=flat-square&logo=github&logoColor=white" alt="log-pose-terminal repo" /></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🎙️ BonClay: Multilingual Voice Cloning Agent</h3>
      <p>Zero-shot voice cloning and conversational agent routing across 6 TTS engines for 22 Indian languages, with consent checks and watermarked output.</p>
      <p><b>Components:</b> <code>Spoken Consent Verification</code> → <code>Hybrid RAG (BGE-M3 Dense + Sparse + ColBERT + BM25)</code> → <code>6-Engine TTS Router</code> → <code>AudioSeal Watermarking</code> → <code>FastAPI + Next.js Streaming</code></p>
      <p><b>Evaluation:</b> <b>8.9% WER</b> on cloned English voices and <b>0.68</b> speaker similarity across 8 Indian languages. Hybrid retrieval raised Top-1 accuracy from <b>64.4% to 75.6%</b>. <b>486 ms</b> median first-audio latency. Watermark survived <b>100%</b> of 70 compression and telephony tests.</p>
      <p>
        <code>Whisper</code> <code>ECAPA-TDNN</code> <code>BGE-M3</code> <code>AudioSeal</code> <code>FastAPI</code>
      </p>
      <p><a href="https://github.com/Artifact19/bonclay"><img src="https://img.shields.io/badge/GitHub-bonclay-181717?style=flat-square&logo=github&logoColor=white" alt="bonclay repo" /></a></p>
    </td>
    <td width="50%" valign="top">
      <h3>🍱 CalorieCAM: Food Recognition &amp; Macro Triage</h3>
      <p>Food image classifier that recognizes 101 dishes and estimates calories and macros, with calibrated confidence and visual explanations.</p>
      <p><b>Pipeline:</b> <code>Food-101 Images</code> → <code>MobileNetV3 Transfer Learning (CutMix + Label Smoothing)</code> → <code>Temperature Scaling &amp; Confidence Tiers</code> → <code>Grad-CAM</code> → <code>ONNX Inference + Nutrition Lookup</code></p>
      <p><b>Evaluation:</b> <b>82.9% top-1</b> and <b>93.5% top-3</b> accuracy with <b>0.829 macro-F1</b> on 25,250 test images. Calibration error of <b>1.96%</b>. ONNX export runs <b>5.1x faster</b> on CPU than PyTorch.</p>
      <p>
        <code>PyTorch</code> <code>MobileNetV3</code> <code>Grad-CAM</code> <code>ONNX</code> <code>Transfer Learning</code>
      </p>
      <p><a href="https://github.com/Artifact19/caloriecam-macro-triage"><img src="https://img.shields.io/badge/GitHub-caloriecam--macro--triage-181717?style=flat-square&logo=github&logoColor=white" alt="caloriecam-macro-triage repo" /></a></p>
    </td>
  </tr>
</table>

---

## Stack

| Category | Technologies |
| :--- | :--- |
| **Programming Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white) |
| **Deep Learning & GenAI** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white) ![Hugging Face Transformers](https://img.shields.io/badge/Hugging%20Face%20Transformers-FFD21E?style=flat&logo=huggingface&logoColor=black) ![LLMs](https://img.shields.io/badge/LLMs-412991?style=flat) ![RAG](https://img.shields.io/badge/RAG-10B981?style=flat) ![CNNs](https://img.shields.io/badge/CNNs-DB2777?style=flat) ![Fine-Tuning](https://img.shields.io/badge/Fine--Tuning-6366F1?style=flat) ![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat&logo=onnx&logoColor=white) |
| **Machine Learning & Data Science** | ![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikitlearn&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white) ![Time Series Forecasting](https://img.shields.io/badge/Time%20Series%20Forecasting-2563EB?style=flat) ![Statistics](https://img.shields.io/badge/Statistics-0D9488?style=flat) |
| **Deployment & Tools** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white) ![Hugging Face Spaces](https://img.shields.io/badge/HF%20Spaces-FFD21E?style=flat&logo=huggingface&logoColor=black) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white) ![REST APIs](https://img.shields.io/badge/REST%20APIs-0284C7?style=flat) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) |
| **BI & Visualization** | ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black) ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat) ![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat) |

---

## GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Artifact19&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117" height="165" alt="GitHub Stats" />
  <img src="https://streak-stats.demolab.com/?user=Artifact19&theme=tokyonight&hide_border=true&background=0D1117" height="165" alt="GitHub Streak" />
</div>
