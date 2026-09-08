<div align="center">

# Arman Ahmed

**MSc Artificial Intelligence Systems @ EPITA, Paris**

I build the parts of machine learning that live after the notebook — orchestrated training pipelines,
model registries, containerised serving, and monitoring that tells you when data or a model has drifted.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/armanahmed24/)
[![Portfolio](https://img.shields.io/badge/Portfolio-1F2328?style=flat-square&logo=readdotcv&logoColor=white)](https://www.datascienceportfol.io/arman_240102)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:armanofficial2401@gmail.com)

</div>

---

## About

I'm a Master's student in Artificial Intelligence Systems at EPITA Paris, with a B.Tech in Computer
Science and five months of industry data science experience in Bengaluru.

My interest is production reliability rather than leaderboard scores: reproducible training,
orchestrated pipelines, versioned models, serving that fails safely, and observability so a
degradation is caught before a user notices it. The repositories below are built to be run, not just
read — each one stands up from a clean clone.

**Currently looking for a six-month AI Engineer / MLOps internship in France, starting April 2027.**

---

## Featured Projects

| Project | What it demonstrates | Stack |
|---|---|---|
| **[Credit Risk Scoring System](https://github.com/ArmanAhmed00/Credit-Risk-Scoring-System)** | End-to-end MLOps platform: trains a credit-default model, serves it over a REST API, and puts an underwriting console on top. Two Airflow DAGs handle scheduled retraining and drift monitoring; MLflow holds the registry. The API returns `503` until a model is registered rather than serving an unvalidated one. | Airflow · MLflow · FastAPI · Streamlit · Docker Compose · GitHub Actions · pytest |
| **[French Property Sales Pipeline (DVF)](https://github.com/ArmanAhmed00/property-sales-pipeline)** | Processing pipeline over five years of French DVF open real-estate data — pipe-delimited government files turned into an analysis-ready dataset through modular cleaning, outlier detection and feature engineering, with 1D/2D exploratory analysis. Runs as a single command. | Python · pandas · Jupyter · MIT |
| **[BST-Backed Hyperparameter Optimiser](https://github.com/ArmanAhmed00/BST-Backed-Hyperparameter-Optimiser-with-Transfer-Analysis)** | A custom binary search tree registry giving O(log n) lookup over grid-search trials, used to measure how hyperparameters transfer between deliberately contrasting datasets — WDBC (569 × 32, correlated) and Banknote Authentication (1,372 × 4, independent). | Python 3.12 · scikit-learn · uv |

> Every featured repository ships with setup instructions and a one-command run.

---

## Tools

| Category | Tools |
|---|---|
| Languages | Python · SQL · Bash · Java |
| ML & Deep Learning | scikit-learn · XGBoost · TensorFlow / Keras · Transformers · pandas · NumPy |
| Orchestration & Tracking | Apache Airflow · MLflow |
| Serving & Interfaces | FastAPI · Streamlit · Flask |
| Containers & CI | Docker · Docker Compose · GitHub Actions · pytest · Make |
| Data | PostgreSQL · MySQL · NoSQL · Apache Spark |
| Environments | uv · conda · Git · Linux · Jupyter |

**Currently learning:** LLM engineering (RAG, evaluation, LLMOps, agent tooling), Kubernetes, cloud deployment.

---

## Background

- **MSc Artificial Intelligence Systems** — EPITA, Paris · 2026–2027
  Data Science in Production · Big Data Infrastructure & Cloud · Neural Networks & Deep Learning · NLP · Spark · NoSQL · Time Series · Reinforcement Learning
- **B.Tech Computer Science & Engineering** — Vel Tech R&D Institute, Chennai · 2021–2025
- **Data Science Intern** — Personifwy, in collaboration with CELL, IIT Guwahati · Bengaluru, Dec 2024 – May 2025
- **3rd place**, AlgoZen competitive programming — Technex'25, IIT (BHU) Varanasi

---

<div align="center">
<sub>
Open to a six-month AI Engineer / MLOps internship in France from April 2027 ·
<a href="mailto:armanofficial2401@gmail.com">armanofficial2401@gmail.com</a>
</sub>
</div>
