# Hi, I'm Ailene 👋

**Data Scientist — Applied LLM & Decisioning** at a Series C health-tech company, where I own the LLM and decisioning intelligence layer: next-best-action systems serving multiple Southeast Asian markets, a text-to-SQL analytics pipeline on locally deployed open-source models, and the evaluation and monitoring frameworks that keep them honest.

Before data science, I was a registered Mechanical Engineer with a research background — two first-author publications on finite element analysis of flywheel energy storage rotors. I bring that systems-engineering lens to ML: decisions over predictions, failure modes over leaderboard scores.

My projects split two ways: **deep learning / AI**, where I'm building up from classical ML into neural architectures, and **decision sciences**, where I turn predictions into recommended actions.

## What I work on

**🎯 Decisioning & causal inference** — next-best-action systems, uplift modeling, customer lifecycle modeling. The question that interests me isn't "what will happen?" but "what should we do, for whom, and when?"

**🤖 Applied LLMs** — local open-source model deployment (Ollama / Qwen), text-to-SQL, structured generation, transformer-based embeddings, and prompt/context engineering. One production pipeline chains an LLM with validation and retry logic to assign standardized labels — in hindsight, an early, primitive agent harness, built before agent frameworks were standard tooling. Backed by systematic evaluation: failure taxonomies, regression suites, and monitoring rather than vibes.

**🧠 Deep learning** — MS AI coursework moving from classical ML into CNNs, transformers, and LLM pretraining/fine-tuning, with deployment via ONNX, TensorRT, and Triton. Latest: a from-scratch speech model running live on a Raspberry Pi (see below).

**⚡ ML for energy & climate** — where my mechanical engineering background meets data science: GIS-based microreactor siting (Random Forest + SHAP, 88.3% test accuracy) and typhoon severity risk modeling for the Philippines.

## Featured: on-device voice command model

🎙️ **[`vcm-me2`](https://github.com/airimonda/vcm-me2)** — a tiny voice assistant brain trained entirely from scratch (no pretrained weights, no ASR, no LLM) that runs offline on a Raspberry Pi 4.

- Classifies a 5-second audio window into **19 commands + out-of-scope**, with slot heads for values like timer length, temperature, and color
- **Six architectures benchmarked under one recipe** (DS-CNN, BC-ResNet, TC-ResNet, MatchboxNet, CRNN, tiny Conformer) at ~100k and ~300k parameters
- Released model: 3-seed **Conformer ensemble** (883k params, 2.8 MB int8) — **94.3% balanced accuracy** on a speaker-disjoint test set vs. 87.3% for a size-matched DS-CNN baseline; real human voices remain the weak spot (77%), documented in the write-up
- Log-mel front end + model export to a **single ONNX file** that needs only `onnxruntime` + `numpy`; **89 ms per window** on one Pi 4 core, **90.8% intent accuracy** in the live class benchmark
- Also built the class tooling: [`vcm-benchmark`](https://github.com/airimonda/vcm-benchmark) (live, standardized Pi benchmark with latency/CPU/thermal logging) and [`ai231-me2-voice-data`](https://github.com/airimonda/ai231-me2-voice-data) (shared recording pipeline validated with whisper.cpp)

## Selected work

**Deep learning / AI**

| Project | What it is |
|---|---|
| 🎙️ [`vcm-me2`](https://github.com/airimonda/vcm-me2) | From-scratch Conformer voice command model, ONNX on Raspberry Pi 4 (94.3% balanced acc., 89 ms/window) |
| 📊 [`vcm-benchmark`](https://github.com/airimonda/vcm-benchmark) | Live, standardized benchmark harness for Raspberry Pi voice assistants |
| 🧮 [`mlops1_cnn-via-einsum`](https://github.com/airimonda/mlops1_cnn-via-einsum) | CNN on MNIST with custom layer math via `einops` / `torch.einsum` |
| 🗣️ [`ai231-me2-voice-data`](https://github.com/airimonda/ai231-me2-voice-data) | Shared voice-recording pipeline for a course speech dataset, validated with whisper.cpp |

**Decision sciences**

| Project | What it is |
|---|---|
| ☢️ [`microreactor_siting`](https://github.com/airimonda/microreactor_siting) | GIS + ML feasibility analysis for microreactor deployment in the Philippines (MEng AI capstone) |
| 🌀 [`bantay_bagyo`](https://github.com/airimonda/bantay_bagyo) | Typhoon severity index modeling for Philippine disaster risk |
| 🛰️ [`project_silaw`](https://github.com/airimonda/project_silaw) | Night-light pollution risk scoring + forecasting for Philippine Marine Protected Areas |
| 🩺 [`diabetes_prediction_model`](https://github.com/airimonda/diabetes_prediction_model) | Clinical diabetes-risk classifier comparing logistic regression, decision tree, and random forest |

## Toolbox

`Python` `SQL` `scikit-learn` `XGBoost` `statsmodels` `Optuna` `Ollama` `PyTorch` `ONNX Runtime` `Raspberry Pi` `Hugging Face` `pandas` `A/B testing` `Redshift`

## Currently

- 🎓 MEng in Artificial Intelligence, University of the Philippines
- 🇯🇵 Studying Japanese (JLPT N4 ✅, N3 in progress) — open to data science roles in Japan
- 📫 Reach me on [LinkedIn](https://www.linkedin.com/in/abnmondares)
