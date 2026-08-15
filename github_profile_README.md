<h1 align="center">Hi, I'm Varun Kumar Uppula 👋</h1>
<h3 align="center">Data Scientist / Data Analyst — Causal Inference, Uplift Modeling, MLOps, and End-to-End Production ML</h3>

<p align="center">
M.S. Data Science, UMass Dartmouth &nbsp;|&nbsp; New Bedford, MA &nbsp;|&nbsp;
<a href="https://linkedin.com/in/varun-kumar-uppula-559b031a1">LinkedIn</a> &nbsp;|&nbsp;
call4vk@gmail.com
</p>

---

## About Me

- 🎓 M.S. in Data Science, University of Massachusetts Dartmouth (conferred January 2026) · B.E. in Computer Science and Engineering, Sathyabama Institute of Science and Technology (2021)
- 💼 Software Developer Intern @ Sapot Systems — selected for a client-facing engagement with American Express based on direct skill match, building cardmember attrition & churn models (Logistic Regression, Random Forest, XGBoost, Gradient Boosting, SHAP, A/B-tested retention offers)
- 🏭 Three years as the sole data analyst at a steel manufacturer — built the entire reporting function from nothing: SQL reports, Tableau dashboards, a KPI framework across production/quality/maintenance/supply chain, and a pricing strategy that drove an 8%+ profit margin improvement
- 🔍 Focused on separating real causal impact from correlation: propensity scores, inverse probability weighting, doubly robust (AIPW) estimation, uplift modeling (T-learner / X-learner), Qini curve analysis
- 🧪 Rigorous about experimentation — power analysis, pre-registered hypotheses, and quantifying the real cost of peeking early (false-positive rate inflates from 5% → 25.9%)
- 🤖 Use Claude, ChatGPT, and Gemini daily to move faster — verify everything before trusting it, never skip the test

## Featured Projects

**[Customer Retention Decision Intelligence System](#)**
LightGBM + Optuna churn model (PR-AUC 0.843, 13.6x lift on top 5% risk), full causal inference pipeline (propensity scores, IPW, doubly robust AIPW), T-learner uplift model validated with Qini curves identifying a four-quadrant targeting pattern, per-customer expected-value framework worth $20K+ in incremental value, MLflow tracking, 15 pytest tests, combined-model FastAPI service.
`Python` `LightGBM` `Optuna` `causalml` `MLflow` `FastAPI` `SHAP` `pytest`

**[Customer Churn Prediction & Retention Intervention Analysis](#)**
Star-schema data model in DuckDB, XGBoost churn model tuned via GridSearchCV (405 model fits), SHAP explainability, X-learner heterogeneous treatment effect analysis on a real 64,000-customer randomized controlled trial, PSI drift monitoring, deployed as a FastAPI service.
`Python` `SQL` `DuckDB` `XGBoost` `causalml` `FastAPI`

**[Analytics Engineering: dbt on BigQuery (34M rows)](#)**
Version-controlled dbt project — staging/mart models, automated data-quality tests, auto-generated lineage. Caught a real production defect: a uniqueness constraint failure traced to 14 years of entity-name drift.
`dbt Core` `Google BigQuery` `SQL`

**[Retail Analytics Pipeline: BigQuery to Power BI (34M rows)](#)**
Star-schema data model (1 fact table, 3 dimension tables) on a 34-million-row retail dataset, resolved anomalous transactions and entity-identity inconsistencies, authored DAX measures for time-intelligence and safe division.
`Google BigQuery` `SQL` `Power BI` `DAX`

**[Production Model Deployment: FastAPI and Docker](#)**
Took a trained model from a batch-scoring script to a live containerized REST API, verified bit-for-bit identical predictions across three separate environments before calling it done.
`FastAPI` `Docker` `scikit-learn` `joblib`

**[NYC Taxi Anomaly Detection Engine](#)**
Isolation Forest anomaly detection on 2.83M real NYC taxi trips (~70% more true anomalies caught than a z-score baseline), diagnosed and fixed two model bias issues (45x and 40.7x over-representation), 7-tab Streamlit dashboard with a local LLM (Ollama) for natural-language queries — runs entirely on an 8GB laptop, no paid APIs.
`Python` `DuckDB` `scikit-learn` `SHAP` `Streamlit` `Ollama`

**[A/B Testing & Causal Measurement Framework](#)**
Full experimentation pipeline — power analysis for sample sizing (n=3,835/group), pre-registered hypothesis, confirmatory test with confidence intervals. Simulated 2,000 null-effect tests to quantify how premature peeking inflates false positives from 5% to 25.9%; found a real 21.6% lift concentrated in one segment.
`Python` `SciPy` `statsmodels` `pandas`

**[Portfolio RAG: Retrieval-Augmented Generation QA System](#)**
Indexed project documentation into a ChromaDB vector store for citation-backed generation with a local LLM; diagnosed and fixed a cross-document hallucination via a two-stage retrieval redesign.
`Python` `ChromaDB` `Ollama`

**[Multi-Engine Data Analytics Platform](#)**
Modular platform with independent data ingestion, quality validation, NL query routing, and visualization components; automatic encoding fallback, regex-based PII detection/hashing, fuzzy-match deduplication.
`Python` `Streamlit` `pandas` `scikit-learn` `NetworkX` `Plotly`

**[Streaming Data Pipeline with Embedded Data Quality Contracts](#)**
Containerized streaming pipeline — Kafka ingestion, Dockerized Python transformation, Great Expectations data-quality contracts with automatic quarantine, Parquet storage, DuckDB analysis, schema evolution handling to prevent silent failures.
`Apache Kafka` `Docker` `Great Expectations` `AWS`

**[Audiobook Recommender: Collaborative Filtering](#)**
SVD matrix factorization recommender, 22.5% RMSE improvement over baseline, validated with 5-fold CV and NDCG@10/Precision@10/Recall@10.
`Python` `scikit-surprise` `scikit-learn`

**[Comparative Protest Pattern Analysis: US and India](#)**
Analyzed 144,000+ protest/conflict records using time-series, network, and geospatial methods; actor-interaction network graphs and DBSCAN geo-clustering to identify escalation patterns.
`Python` `pandas` `NetworkX` `DBSCAN`

**[Real-Time Sentiment Analysis Pipeline on AWS](#)**
Serverless pipeline using Kinesis, Lambda, Comprehend, S3, and CloudWatch, replacing a traditional batch ETL model with sub-minute insight latency.
`AWS Kinesis` `Lambda` `Comprehend` `S3` `CloudWatch`

**[Human Disease Prediction from Tongue Images](#)**
Two transfer-learning CNNs (ResNet50 for diabetes screening, MobileNetV2 for oral cancer screening) deployed behind a Flask app with authentication and prediction history.
`PyTorch` `TensorFlow` `Keras` `OpenCV` `Flask`

*(Replace the `#` links above with your actual repo URLs.)*

## Tech Stack

**Languages & Query:** Python · SQL · PL/SQL · DAX · M (Power Query) · R · C
**ML & Causal Inference:** XGBoost · LightGBM · scikit-learn · SHAP · causalml · uplift modeling (T-learner, X-learner) · propensity scores · IPW · doubly robust (AIPW) estimation · Qini curve analysis
**Deep Learning & CV:** PyTorch · TensorFlow · Keras · OpenCV · CNNs (ResNet50, MobileNetV2) · 1D CNN/RNN
**NLP & RAG:** transformer embeddings · RAG · ChromaDB · prompt engineering · Ollama (local LLMs)
**Time-Series:** ARIMA · SARIMA · Prophet · exponential smoothing
**Data & Pipelines:** dbt Core · Apache Kafka · Great Expectations · Google BigQuery · Databricks · Snowflake · DuckDB
**MLOps & Deployment:** MLflow · FastAPI · Docker · pytest · Population Stability Index drift monitoring
**BI & Visualization:** Tableau · Power BI · Streamlit · Matplotlib · Seaborn · Plotly
**Cloud:** AWS (S3, Lambda, Kinesis, Comprehend, CloudWatch) · Azure (Event Hubs, Stream Analytics, Blob Storage, ADLS Gen2)

## Let's Connect

📫 call4vk@gmail.com
🔗 [LinkedIn](https://linkedin.com/in/varun-kumar-uppula-559b031a1)

<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=varunkumaruppula&show_icons=true&theme=default" alt="GitHub stats" />
</p>
