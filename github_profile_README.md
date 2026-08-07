# Hi, I'm Varun 👋

Data Scientist / Data Analyst — causal inference, uplift modeling, and production ML.

## About Me

- 🎓 M.S. in Data Science, University of Massachusetts Dartmouth (conferred January 2026)
- 💼 Software Developer Intern @ Sapot Systems — building cardmember attrition & churn models for a client engagement with American Express
- 🏭 Three years as the sole data analyst at a steel manufacturer — built KPI dashboards, demand forecasting, and a pricing strategy from scratch, no framework to inherit
- 🔍 Focused on separating real causal impact from correlation: propensity scores, inverse probability weighting, doubly robust (AIPW) estimation, uplift modeling (T-learner / X-learner), Qini curve analysis
- 🧪 Rigorous about experimentation — power analysis, pre-registered hypotheses, and quantifying the real cost of peeking early (false-positive rate inflates from 5% → 25.9%)

## Featured Projects

**[Customer Retention Decision Intelligence System](#)**
LightGBM + Optuna churn model (PR-AUC 0.843, 13.6x lift on top 5% risk), full causal inference pipeline (propensity scores, IPW, doubly robust AIPW), T-learner uplift model validated with Qini curves, MLflow tracking, 15 pytest tests, combined-model FastAPI service.
`Python` `LightGBM` `Optuna` `causalml` `MLflow` `FastAPI` `SHAP`

**[Customer Churn Prediction & Retention Intervention Analysis](#)**
XGBoost churn model tuned via GridSearchCV, SHAP explainability, X-learner heterogeneous treatment effect analysis on a real 64,000-customer randomized controlled trial, PSI drift monitoring, deployed as a FastAPI service.
`Python` `SQL` `DuckDB` `XGBoost` `causalml` `FastAPI`

**[A/B Testing & Causal Measurement Framework](#)**
Full experimentation pipeline — power analysis for sample sizing, pre-registered hypothesis, confirmatory test with confidence intervals. Simulated 2,000 null-effect tests to quantify how premature peeking inflates false positives.
`Python` `SciPy` `statsmodels` `pandas`

**[NYC Taxi Anomaly Detection Engine](#)**
Isolation Forest anomaly detection on 2.83M real NYC taxi trips (~70% more true anomalies caught than a z-score baseline), 7-tab Streamlit dashboard with a local LLM (Ollama) for natural-language queries — runs entirely on an 8GB laptop, no paid APIs.
`Python` `DuckDB` `scikit-learn` `SHAP` `Streamlit` `Ollama`

**[Analytics Engineering: dbt on BigQuery (34M rows)](#)**
Version-controlled dbt project — staging/mart models, automated data-quality tests, auto-generated lineage. Caught a real production defect: a uniqueness constraint failure traced to 14 years of entity-name drift.
`dbt Core` `Google BigQuery` `SQL`

*(Replace the `#` links above with your actual repo URLs.)*

## Tech Stack

**Languages & Query:** Python · SQL · PL/SQL · R
**ML & Causal Inference:** XGBoost · LightGBM · scikit-learn · SHAP · causalml · uplift modeling · propensity scores
**Data & Pipelines:** dbt Core · Google BigQuery · Databricks · Snowflake · DuckDB
**MLOps & Deployment:** MLflow · FastAPI · Docker · pytest
**BI & Visualization:** Tableau · Power BI · Streamlit · Plotly

## Let's Connect

📫 call4vk@gmail.com
🔗 [LinkedIn](https://linkedin.com/in/varun-kumar-uppula-559b031a1)
