# Hi, I'm Ailene 👋

**Data Scientist — Analytics, Experimentation & Decisioning** · open to **data analytics / data science roles in Japan** 🇯🇵

I turn messy business data into decisions: SQL on production warehouses, experiment design and A/B testing, customer lifecycle analysis, and forecasting — then I make the results usable by the people who act on them.

At a Series C health-tech company I own the decisioning and LLM layer for multiple Southeast Asian markets: next-best-action systems, a **text-to-SQL analytics pipeline** that lets non-technical teams query the warehouse, and the evaluation and monitoring frameworks behind them.

Before data science, I was a registered Mechanical Engineer with two first-author research publications (finite element analysis of flywheel energy storage rotors). That background shapes how I work: clear problem framing, honest limitations, and decisions over leaderboard scores.

> **日本語:** 東南アジア複数市場向けのヘルステック企業でデータサイエンティストとして、SQL分析、A/Bテスト、顧客ライフサイクル分析、意思決定支援システムを担当しています。日本でのデータアナリスト／データサイエンティスト職を希望しています。日本語学習中（JLPT N4 合格、N3 勉強中）。

## What I bring to an analytics team

- **📊 SQL & analytics engineering** — querying and modeling data in Redshift; built a text-to-SQL pipeline (locally deployed open-source LLMs + validation) so business users get answers without writing SQL
- **🧪 Experimentation & causal inference** — A/B test design and readout, uplift modeling, hypothesis testing; the question is "what should we do, for whom, and when?"
- **👥 Customer & lifecycle analytics** — segmentation, churn and engagement modeling, next-best-action recommendations
- **📈 Forecasting & risk scoring** — time-series forecasting (ARIMA, Prophet), composite risk indices, geospatial analysis
- **🗣️ Communicating results** — every project below has a plain-language summary, findings first, and a limitations section

## Analytics projects

| Project | Question answered | Methods |
|---|---|---|
| 🛰️ [`project_silaw`](https://github.com/airimonda/project_silaw) | Which Philippine Marine Protected Areas face the fastest-rising light-pollution risk? | Satellite data, risk index, K-means segmentation, ARIMA vs Prophet forecasting |
| 🌀 [`bantay_bagyo`](https://github.com/airimonda/bantay_bagyo) | Which Metro Manila cities get hit hardest by a typhoon, and why? | Data fusion (hazard × vulnerability), XGBoost, evaluation |
| ☢️ [`microreactor_siting`](https://github.com/airimonda/microreactor_siting) | Where in the Philippines can a microreactor be sited safely? | 15+ GIS layers, Random Forest + SHAP (88.3% test accuracy), ranked shortlist |
| 🩺 [`diabetes_prediction_model`](https://github.com/airimonda/diabetes_prediction_model) | Who is at risk of diabetes? | EDA, statistical tests, logistic regression / tree / random forest |
| 🗂️ [`DataCampProjects`](https://github.com/airimonda/DataCampProjects) | 48 SQL and Python case studies | SQL, A/B testing, hypothesis testing, churn, customer analytics |
| 💰 [`bb-finances`](https://github.com/airimonda/bb-finances) | Am I on budget this month? | Personal finance dashboard: burn rate, anomaly alerts, savings projection |

## Machine learning & engineering

🎙️ **[`vcm-me2`](https://github.com/airimonda/vcm-me2)** — voice command model trained from scratch, running offline on a Raspberry Pi 4. Six architectures benchmarked under one recipe; released ensemble reaches **94.3% balanced accuracy** on a speaker-disjoint test set at **89 ms per window**. Shows controlled evaluation and honest error analysis (real human voices remain the weak spot at 77%, documented).

Also: [`vcm-benchmark`](https://github.com/airimonda/vcm-benchmark) (standardized live benchmark with latency/CPU logging) · [`ai231-me2-voice-data`](https://github.com/airimonda/ai231-me2-voice-data) (shared data-collection pipeline) · [`mlops1_cnn-via-einsum`](https://github.com/airimonda/mlops1_cnn-via-einsum) (CNN layers written with `einsum`)

## Toolbox

**Analytics:** `SQL` `Redshift` `PostgreSQL` `Python` `pandas` `statsmodels` `SciPy` `A/B testing`
**Modeling:** `scikit-learn` `XGBoost` `Optuna` `SHAP` `Prophet` `PyTorch`
**Geospatial:** `GeoPandas` `rasterio` `Google Earth Engine`
**LLMs & deployment:** `Ollama` `Hugging Face` `ONNX Runtime`

## Currently

- 🎓 MEng in Artificial Intelligence, University of the Philippines
- 🇯🇵 Studying Japanese — JLPT N4 ✅, N3 in progress
- 📫 [LinkedIn](https://www.linkedin.com/in/abnmondares)
