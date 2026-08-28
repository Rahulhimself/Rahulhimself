<div align="center">
  <h1>Rahul B</h1>
  <p><strong>Aspiring AI/ML Engineer | LLM Applications, Agentic Workflows & MLOps</strong></p>
  <p>Open to full-time AI/ML Engineer roles · Bengaluru, India (Remote-friendly)</p>
  <p>Bengaluru, India • <a href="mailto:rahulbkumar117@gmail.com">rahulbkumar117@gmail.com</a> • [+91-XXXXXXXXXX]</p>

  <p>
    <a href="https://rahul-bansode.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-rahul--bansode.vercel.app-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
    <a href="https://www.linkedin.com/in/rahulbanasode/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="https://github.com/Rahulhimself"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
    <a href="https://www.hackerrank.com/profile/rahulbkumar118"><img src="https://img.shields.io/badge/HackerRank-00EA64?style=for-the-badge&logo=hackerrank&logoColor=black" alt="HackerRank" /></a>
    <a href="https://leetcode.com/u/rahulbkumar118"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" /></a>
    <a href="mailto:rahulbkumar117@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  </p>
</div>

<sub>Last updated: [Month Year]</sub>

---

### 📌 Overview

I work on taking ML from notebooks to deployed, observable pipelines — containerized deep learning workflows (DVC, MLflow, Docker, Kubernetes) and LLM/agentic systems that turn natural language into structured actions (e.g. SQL). My strength is on the Building ML Models, Multi AI Agent models and deployment/MLOps.
Cuurently learning LLMOps

---

### 💼 Experience

**Data Scientist Intern — Intellipaat Software Solutions Pvt. Ltd.** · Bengaluru
*[May/2025] – [May/2026]*
* Data cleanign, Ingestion, Validation, Build, trained, and rigorously evaluated Machine Learning models using TensorFlow and scikit-learn, 
tracking all experiments and metrics with MLflow, DVC, and GitHub Actions.
* Containerized the model serving logic using Docker, orchestration using Kubernetes, and a high-performance 
FastAPI endpoint for deployment to a cloud environment (AWS/Vertex AI, Azure ML). This work demonstrably improved model accuracy by 
15% and reduced data processing time by 40% through pipeline optimization. 

---

### 🛠️ Technical Skills Matrix

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Agentic AI & GenAI** | LangChain, LangGraph, Autonomous Agents, AgenticSQL(Current project), RAG, Harness Engineering, Ai evals |
| **Machine Learning & Deep Learning** | TensorFlow, Keras, Scikit-Learn, OpenCV, CNNs, Time Series (ARIMA, Prophet) |
| **MLOps, CI/CD & Observability** | MLflow, DVC, Docker, Kubernetes, Jenkins, GitHub Actions, Grafana Prometheus|
| **Cloud & Infrastructure** | AWS (SageMaker, EC2, ECR, S3), Microsoft Azure, Linux |
| **Data Engineering & Backend** | Python, C++, MS SQL Server, Apache Spark, FastAPI, Flask, REST APIs |
| **Analytics & UI Interfaces** | Streamlit, Power BI, Pandas, NumPy, Data Modeling & Cohort Analysis |

---

### 🚀 Featured Projects

### 🚀 Featured Projects

#### 🤖 [AgenticSQL — Natural Language Database Agent](https://github.com/Rahulhimself/AgenticSQL)
* **Stack:** Python, LangChain (ReAct agent), Google Gemini 2.5 Flash, MS SQL Server (SQLAlchemy + PyODBC), FastAPI, WebSocket
* Conversational agent that turns plain-English questions into validated T-SQL, executes them, and explains results — with multi-turn memory for follow-up questions.
* Built-in safety guardrails block destructive queries (DROP/DELETE/ALTER/INSERT/UPDATE) with full audit logging; read-only by design.
* Ships as both an interactive REPL (syntax highlighting, autocomplete, slash commands) and a REST/WebSocket API with auto-generated docs.
* **Result:** Zero-write-access-by-design architecture — every query attempt logged; auto-generates charts and CSV/JSON exports from natural language queries.

#### 🏥 [Chest Disease Classification — End-to-End MLOps Pipeline](https://github.com/Rahulhimself/Chest_Disease_Classification)
* **Stack:** TensorFlow/Keras, DVC, MLflow, Docker, Jenkins, AWS (S3, ECR, EC2)
* Deep learning pipeline for chest radiograph classification with data versioning via DVC (raw images streamed from S3, tracked by hash) and experiment tracking via MLflow.
* Jenkins CI/CD listens for GitHub pushes, builds a Docker image, pushes to ECR, and deploys to an EC2-hosted inference app.
* **Result:** [validation accuracy / dataset size — check `scores.json` in the repo and fill in; not visible from the README alone]

#### 🐱 [Cats vs. Dogs Image Classifier — CNN](https://github.com/Rahulhimself/CNNClassification)
* **Stack:** TensorFlow, Keras, Flask, Docker, AWS (EC2, ECR), GitHub Actions
* CNN built from scratch (4 conv/pooling blocks, 32→128 filters) with data augmentation, served through a Flask web app and deployed via a Dockerized AWS CI/CD pipeline.
* **Result:** ~72% validation accuracy at 15 epochs; identified and documented overfitting past that point rather than reporting an inflated number from longer training.

#### 🎬 [Movie Recommendation System](https://github.com/Rahulhimself/End-to-End-Movie-Recommendation-System-using-Machine-Learning)
* **Stack:** Python, Scikit-Learn, Streamlit
* Content-based recommender using TF-IDF/bag-of-words vectorization and cosine similarity over a Kaggle movie-poster metadata set.
* **Result:** Deployed live — [try it here](https://rb-movie-recommendation-system-using-machine-learning.streamlit.app/).

#### 📊 [Mobile Device Usage & User Behavior Dashboard](https://github.com/Rahulhimself/Mobile-Device-Usage-and-User-Behavior)
* **Stack:** Power BI, DAX
* Interactive dashboard comparing data usage, battery drain, and screen time across Android vs. iOS users, segmented by age and gender.
* **Result:** Found Android accounts for 78.34% of total data volume in the sample; identified a 75% male skew among Android users with peak screen time in the 50–55 age band, vs. a more balanced gender split and 55–60 peak for iOS.

#### 📈 [Cloud-Native Predictive Pipeline on AWS SageMaker](https://github.com/Rahulhimself/SageMaker-Predictive-Pipeline)
* **Stack:** AWS SageMaker, S3, Scikit-Learn, Python, REST APIs
* End-to-end training/deployment pipeline: S3 ingestion, automated feature engineering, hyperparameter tuning, deployed to a live SageMaker inference endpoint.
* **Result:** [model metric — fill in]

#### 🛒 [Walmart Multi-Store Demand & Sales Forecasting](https://github.com/Rahulhimself/Walmart-sales-prediction)
* **Stack:** Python, Statsmodels (ARIMA), Prophet, Scikit-Learn, Pandas
* Multi-factor demand forecasting accounting for holiday promotions, CPI shifts, and unemployment variation; benchmarked classical time series vs. ensemble regressors.
* **Result:** [forecast error / accuracy improvement — fill in]

---

### 🎓 Education & Certifications

* **Executive Post-Graduate Certificate in AI & Data Science** — IIT Roorkee (iHUB DivyaSampark), *[Year]*
* **B.E./B.Tech, Electronics & Communication (Minor: Machine Learning)** — PES University, *[Year]*
* [HackerRank Verified](https://www.hackerrank.com/profile/rahulbkumar118) • [LeetCode Profile](https://leetcode.com/u/rahulbkumar118)

---

<div align="center">
  <sub>Rahul B • Open to AI/ML Engineer & MLOps opportunities • <a href="https://rahul-bansode.vercel.app/">Portfolio</a></sub>
</div>
