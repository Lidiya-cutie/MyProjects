# Lidiya Korotkova · ML Engineering & MLOps Portfolio

Chief Data Officer at MCDis (Moscow), hands-on in MLOps, LLM serving and agentic systems.
Based in Moscow, open to relocation.

[LinkedIn](https://www.linkedin.com/in/lidiya-korotkova-a363b5274) · [Email](mailto:Lidushehca@mail.ru)

> My production work at MCDis is confidential and is not published here. The repositories below are personal projects or public, non-confidential versions of applied work.

---

## What I build at work (not public)

- **Self-hosted MLOps platform**: Ansible and Docker Compose; NVIDIA Triton Inference Server with a vLLM backend, ClearML, MLflow, MinIO, Keycloak and JupyterHub on RTX 4090 GPUs; Grafana and Zabbix monitoring.
- **LLM serving under tight GPU memory**: Gemma 3 27B in 4-bit AWQ on 24 GB GPUs; Qwen3-8B in bf16 with vLLM; NVIDIA MPS for GPU sharing.
- **Evaluated RAG** (department project): on a 40-question control run, raising the context limit from 512 to 1024 tokens took factual hallucinations from 6 to 0.
- **Production ad classifier** (department project): multi-label classification across 48+ regulated categories.

---

## Featured projects

| Project | What it shows | Stack |
| --- | --- | --- |
| [**MCP Context Pipeline**](https://github.com/Lidiya-cutie/mcp-context-pipeline) | Context management for MCP applications: PII masking with Presidio plus Russian-specific entities (84 tests, 0 leaks in the reference run), context compression, 31 MCP servers, an iterative generate → measure → hint → regenerate loop, and eval gates in CI (Recall@K ≥ 0.60, MRR ≥ 0.45, p95 ≤ 8 s). | Python, MCP, Presidio, Redis, PostgreSQL, NiceGUI, Docker Compose, pytest, GitHub Actions |
| [**Oil well region selection**](https://github.com/Lidiya-cutie/Diplom_SF) | Risk-aware ML: bootstrap profit, 95% CI, loss probability and CVaR; a data-quality check that flags target leakage in the "winning" region; data versioning and experiment tracking. | Python, scikit-learn, DVC, MinIO, MLflow, GitHub Actions |
| [**Qwen2-VL inference pipeline**](https://github.com/Lidiya-cutie/qwen2-vl-inference-pipeline) | Batch multimodal inference with resume from CSV, rule-based category mapping and keyword extraction. | Python, PyTorch, Transformers, Qwen2-VL, CUDA |
| [**GLM-Image / SDXL pipeline**](https://github.com/Lidiya-cutie/glm-image-pipeline) | Image-generation serving with auth, rate limiting, concurrency limits and health checks; category-specific banner generators. | Python, PyTorch, Diffusers, SDXL, FastAPI, Docker Compose |
| [**Model retraining pipeline**](https://github.com/Lidiya-cutie/Retrain-Model-Project) | Retraining with class balancing, Optuna tuning and experiment logging. | scikit-learn, XGBoost, LightGBM, Optuna, Comet ML |

## Applied computer vision (public versions)

| Project | Description |
| --- | --- |
| [Ad banner categorization](https://github.com/Lidiya-cutie/moderation-ai-project) | YOLO training and auto-annotation, Qwen-VL helpers, CVAT-based labeling. |
| [Text extraction and content categorization](https://github.com/Lidiya-cutie/multimodal-analyze) | Multimodal analysis with Qwen2-VL, CLIP and sentence embeddings. |

## Tools

| Project | Description |
| --- | --- |
| [MiMo Telegram Bot](https://github.com/Lidiya-cutie/mimo-telegram-bot) | aiogram bot with OpenRouter, SQLite/FTS5 memory, Docker and systemd deployment. |
| [Custom QR Code Generator](https://github.com/Lidiya-cutie/custom-qr-generator) | Python package for styled QR codes with logos, batch mode, CLI and API. |

<details>
<summary><b>Coursework, 2022–2023</b> (SkillFactory, Mathshub)</summary>

| Project | Topic |
| --- | --- |
| [Bank deposit classification](https://github.com/Lidiya-cutie/project_4) | Classification, feature selection, Optuna |
| [Seoul bike rental demand](https://github.com/Lidiya-cutie/Bicycle-rental-in-Korea) | Feature engineering, regression, Hyperopt |
| [Biological response prediction (Kaggle)](https://github.com/Lidiya-cutie/ML-model/blob/master/Korotkova-predicting-a-biologicalresponse-using-optimization.ipynb) | Hyperparameter optimization |
| [Water potability](https://github.com/Lidiya-cutie/ML-model/blob/master/Testing_for_water.ipynb) | Cross-validation, PR curves |
| [Boston housing](https://github.com/Lidiya-cutie/ML-model/blob/master/ML_Boston.ipynb) | Linear regression |
| [Content-based recommender](https://github.com/Lidiya-cutie/Mini_project_model_Netflix) | TF-IDF |
| [Wine reviews analysis](https://github.com/Lidiya-cutie/WineEnthusiastAnalysis) | EDA on ~130k reviews |
| [HeadHunter resumes](https://github.com/Lidiya-cutie/project_HH) | EDA, salary prediction |
| [HeadHunter vacancies](https://github.com/Lidiya-cutie/DS_SkillFactory/blob/main/Project_2_Короткова_ЛС.ipynb) | SQL on PostgreSQL |
| [OZON data with SQL](https://github.com/Lidiya-cutie/SQL-theory-practice/blob/master/Korotkova_db_connect.ipynb) | SQL analysis |
| [Hotel product metrics](https://github.com/Lidiya-cutie/Project-on-Product-Analytics/blob/master/README.md) | Product analytics |
| [Data cleaning](https://github.com/Lidiya-cutie/DATACLEANINGPROJECT) | Missing values, preprocessing |
| [Telegram bot](https://github.com/Lidiya-cutie/bots) | aiogram |

</details>

