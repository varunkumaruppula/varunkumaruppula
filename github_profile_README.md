# Varun Kumar

**Data Scientist** — predictive modeling, causal inference, experimentation.
MS Data Science, UMass Dartmouth · currently building RAG and document intelligence systems in financial services.

Most of the projects here started the same way: a model that worked, and a number I didn't quite believe. The write-ups are about what I found when I went looking.

---

## Selected work

### [Customer Retention Decision Intelligence System](#)

**A churn model that targets persuadable customers rather than likely leavers.**

Ranking by churn probability spends retention budget on two groups who won't respond: customers already gone, and customers who were never at risk. T-learner uplift modeling isolates the segment where intervention actually moves the outcome, and an expected-value framework turns that into a targeting list with a dollar figure attached to it.

The underlying LightGBM model reaches PR-AUC 0.843 with 13.6x lift in the top decile. Served through FastAPI, tracked in MLflow.

`LightGBM` · `causal inference` · `uplift modeling` · `FastAPI` · `MLflow`

### [A/B Testing & Causal Measurement Framework](#)

**Checking the dashboard every morning takes your false positive rate from 5% to 25.9%.**

That number came out of this harness, which is built around the ways experiments fail rather than the way they're supposed to work. Hypotheses are registered before the data is seen, effects are powered in advance, and segment-level results carry multiple-hypothesis correction.

It also recovered a genuine 21.6% lift in one segment that the pooled result had averaged into nothing.

`power analysis` · `pre-registration` · `segmentation` · `FDR correction`

### [NYC Taxi Anomaly Detection Engine](#)

**The anomalies were coming from the ingest pipeline, not from the city.**

Isolation Forest across 2.83M trips flagged outliers clustering in patterns the geography couldn't account for. Tracing that back surfaced two sampling bias issues upstream. Fixing the data moved the results considerably further than tuning the model would have.

Explorable in a Streamlit dashboard.

`Isolation Forest` · `2.83M records` · `Streamlit`

### [Analytics Engineering: dbt on BigQuery](#)

**A uniqueness violation in the source system, caught by a test rather than by a reconciliation meeting six months later.**

Version-controlled staging and mart layers over 34M records, with automated data-quality tests and lineage tracking running in CI. The duplicate-key problem it caught was quietly inflating every aggregate downstream of it.

`dbt` · `BigQuery` · `34M records` · `data quality testing`

### [Portfolio RAG Question-Answering System](#)

**The system was blending facts from two unrelated documents into one fluent, confident, wrong answer.**

Retrieval scores looked healthy the whole time, which is what made it hard to catch. The fix was scoping retrieval at the document level instead of trusting chunk similarity on its own. Most RAG failures live in retrieval — the generator is usually doing exactly what it was handed.

`ChromaDB` · `local LLM` · `retrieval evaluation`

---

## Also here

Collaborative filtering recommenders (SVD), Kafka and Spark streaming ingestion, sentiment classification deployed on AWS, and demand forecasting with ARIMA, SARIMA, and Prophet against real seasonal data.

---

## Toolkit

- **Modeling** — Python · scikit-learn · XGBoost · LightGBM · statsmodels · PyTorch · TensorFlow
- **Statistics** — A/B testing · power analysis · propensity scores · doubly robust estimation · uplift modeling · bootstrap CIs · FDR correction
- **Data** — SQL · PySpark · PostgreSQL · Snowflake · BigQuery · dbt · Airflow · Kafka
- **Production** — MLflow · DVC · Docker · FastAPI · AWS (SageMaker, Lambda, EKS) · Azure ML
- **GenAI** — LangChain · LlamaIndex · RAG · pgvector · FAISS · ChromaDB · LoRA
- **Visualization** — Power BI · Tableau · Streamlit · matplotlib · seaborn · plotly

---

**Open to Data Scientist roles across the US.**

📫 call4varun@gmail.com · 💼 [LinkedIn](https://www.linkedin.com/in/varun-kumar-uppula-299a97428)
