<div align="center">

# Igor Musteata

**Software Engineer · Python & AI/ML Platforms · Full-Stack Development**

Building dependable APIs, data pipelines, machine-learning tooling, and practical web applications.

Chișinău, Moldova · Master's student in Data Science, Technical University of Moldova

[LinkedIn](https://www.linkedin.com/in/imustyk/) · [GitHub](https://github.com/Imustyk) · [Email](mailto:imustyk@gmail.com)

</div>

---

## About

I'm a software engineer with commercial front-end development experience and a growing focus on **Python backend engineering, data science, and ML platforms**.

My work spans API-backed applications, relational and document databases, model training and evaluation, ETL workflows, automated tests, and observability. I enjoy connecting research and machine learning to software that people can actually use.

Currently, I'm completing a **Master's in Data Science** at the Technical University of Moldova, with research into anomaly detection and corruption-risk indicators in public procurement data.

## Selected projects

<table>
  <tr>
    <th align="left">Project</th>
    <th align="left">What I built</th>
    <th align="left">Key technologies</th>
  </tr>
  <tr>
    <td><a href="https://github.com/Imustyk/IAD"><strong>IAD — Intelligent Analytics & Data Science</strong></a></td>
    <td>Python ML platform with training and prediction APIs, experiment tracking, PostgreSQL persistence, data-drift detection, metrics, and automated quality checks.</td>
    <td>Python, FastAPI, Streamlit, PostgreSQL, SQLAlchemy, Alembic, MLflow, Prometheus, Grafana, Docker, pytest, GitHub Actions</td>
  </tr>
  <tr>
    <td><a href="https://github.com/Imustyk/MRPRI"><strong>MRPRI — Public Procurement Risk Intelligence</strong></a></td>
    <td>End-to-end ingestion and anomaly-analysis system built on real Moldovan procurement data, with explainable risk indicators, external-label evaluation, document retrieval, and an analyst dashboard.</td>
    <td>Python, FastAPI, MongoDB, SQLite, scikit-learn, pandas, React, pytest</td>
  </tr>
  <tr>
    <td><a href="https://github.com/Imustyk/TBD"><strong>Reader Activity Analytics</strong></a></td>
    <td>Data ingestion, warehouse modeling, Spark analytics, and prediction workflows for reader activity and book popularity.</td>
    <td>Python, SQL, SQLite, MongoDB, PySpark, XGBoost, LightGBM, Streamlit</td>
  </tr>
  <tr>
    <td><a href="https://github.com/Imustyk/aggregator-home-finder"><strong>Aggregator Home Finder</strong></a></td>
    <td>TypeScript web application for browsing and aggregating property listings with a Supabase-backed data layer.</td>
    <td>TypeScript, React, Vite, Supabase</td>
  </tr>
</table>

## Engineering highlights

A few places to start if you want to see the implementation rather than a list of technologies:

- **API design and async basics:** [IAD training/prediction routes](https://github.com/Imustyk/IAD/blob/main/iad/backend/api/routes/ml.py) use FastAPI and offload blocking ML work with `asyncio.to_thread`.
- **ML lifecycle:** [MLflow integration](https://github.com/Imustyk/IAD/blob/main/iad/ml/tracking/mlflow_tracker.py) tracks experiments, parameters, metrics, and model artifacts, with graceful handling when MLflow is unavailable.
- **Monitoring:** [Drift detection](https://github.com/Imustyk/IAD/blob/main/iad/ml/preprocessing/drift/detector.py) compares reference and current data using PSI, KS tests, and Jensen–Shannon divergence; [Prometheus instrumentation](https://github.com/Imustyk/IAD/blob/main/iad/core/observability/prometheus.py) tracks API and ML operations.
- **Software quality:** [CI pipeline](https://github.com/Imustyk/IAD/blob/main/.github/workflows/ci.yml) runs linting, type checking, tests, and Docker build checks.
- **Evidence-aware retrieval:** [MRPRI's document retrieval layer](https://github.com/Imustyk/MRPRI/blob/main/src/mtender/rag.py) uses source-aware, extractive retrieval and verifies quotations rather than generating unsupported legal claims.
- **Application data:** [MRPRI analyst workspace](https://github.com/Imustyk/MRPRI/blob/main/src/mtender/workspace.py) implements transactional SQLite storage for investigations, notes, and audit history.

## Professional experience

**Salesforce Front-end Developer (Freelance) · D2Force**  
*March 2025 – February 2026*

- Developed reusable Lightning Web Components for Salesforce applications and B2B workflows.
- Integrated application interfaces and improved performance, responsiveness, and maintainability.

**Front-end Developer · Law Trust Impex**  
*April 2024 – March 2025*

- Built web interfaces for real-estate and automotive applications using React/Next.js and backend APIs.
- Worked with REST integrations and data-backed features, including an AI-chatbot integration in collaboration with a data science engineer.

## Technical toolkit

| Area | Technologies |
| --- | --- |
| **Languages** | Python, TypeScript, JavaScript, SQL |
| **Backend & APIs** | FastAPI, Node.js, Express, REST APIs, Pydantic |
| **Machine learning** | scikit-learn, pandas, NumPy, XGBoost, LightGBM, MLflow, model evaluation, anomaly detection |
| **Databases & data** | PostgreSQL, SQLite, MongoDB, SQLAlchemy, Alembic, ETL, PySpark |
| **Infrastructure & quality** | Docker, GitHub Actions, pytest, Ruff, mypy, Prometheus, Grafana, Git, Linux |
| **Frontend** | React, Next.js, TypeScript, Streamlit, Tailwind CSS |

## Education

**MSc in Data Science** — Technical University of Moldova · *2025–present*  
**BSc in Information Management** — Technical University of Moldova · *2022–2025*

## GitHub activity

For the most accurate and up-to-date contribution history, visit my [GitHub profile and contribution graph](https://github.com/Imustyk).

<details>
  <summary>View contribution streak (external visualization)</summary>
  <br />
  <p align="center">
    <img src="https://streak-stats.demolab.com?user=Imustyk&theme=tokyonight&hide_border=true" alt="GitHub contribution streak" />
  </p>
</details>

---

<div align="center">

**Interested in ML platforms, data engineering, or software collaboration?**  
[Let's connect on LinkedIn](https://www.linkedin.com/in/imustyk/) · [Email me](mailto:imustyk@gmail.com)

</div>
