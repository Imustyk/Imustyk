<h1 align="center">Hi, I'm Igor 👋</h1>

<p align="center">
  <a href="https://readme-typing-svg.demolab.com">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=3000&pause=1200&color=2F81F7&center=true&vCenter=true&width=560&lines=Software+engineer+from+Chi%C8%99in%C4%83u;I+build+Python+APIs+and+ML+platforms;I+write+tests+before+they+get+angry;Currently+finishing+a+Master%27s+in+Data+Science" alt="Typing animation" />
  </a>
</p>

<p align="center">
  <a href="https://igor-musteata-portfolio.netlify.app/en">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/imustyk/">LinkedIn</a> ·
  <a href="mailto:imustyk@gmail.com">Email</a>
</p>

---

## About me

I started as a front-end developer, and over the last couple of years I moved to Python backends, data and machine learning. I like the part of ML that comes after the notebook: the API around the model, the database, the tests, the dashboard that tells you when the data has changed.

I'm in the final year of a Master's in Data Science at the Technical University of Moldova. My research is about finding anomalies and corruption-risk signals in public procurement data.

## What I'm working on

- **[IAD](https://github.com/Imustyk/IAD)**: a Python ML platform with APIs for training and prediction, experiment tracking, drift detection and monitoring.
- **[MRPRI](https://github.com/Imustyk/MRPRI)**: a risk analysis tool built on 152,378 real procurement procedures from Moldova's MTender API. It is also the base for my thesis.

## Projects

| Project | What it does | Stack |
| --- | --- | --- |
| [**IAD**](https://github.com/Imustyk/IAD) | Upload a dataset, train a model, get predictions through an API. Runs are tracked, data drift is checked, metrics go to Grafana. | Python, FastAPI, Streamlit, PostgreSQL, SQLAlchemy, Alembic, MLflow, Prometheus, Grafana, Docker, pytest, GitHub Actions |
| [**MRPRI**](https://github.com/Imustyk/MRPRI) | Loads Moldovan procurement data, scores anomalies, and gives analysts a workspace to rank risks and keep notes. Legal documents are searchable, and every answer quotes its source. | Python, FastAPI, MongoDB, SQLite, scikit-learn, pandas, React, pytest |
| [**Reader Activity Analytics**](https://github.com/Imustyk/TBD) | Collects reading data, models a warehouse, and forecasts book popularity. | Python, SQL, SQLite, MongoDB, PySpark, XGBoost, LightGBM, Streamlit |
| [**Aggregator Home Finder**](https://github.com/Imustyk/aggregator-home-finder) | A web app for browsing property listings from several sources. | TypeScript, React, Vite, Supabase |

## Where to look in the code

If you would rather read code than a list of technologies, start here:

- [FastAPI routes in IAD](https://github.com/Imustyk/IAD/blob/main/iad/backend/api/routes/ml.py): training and prediction, with blocking ML work moved off the event loop using `asyncio.to_thread`.
- [MLflow tracking](https://github.com/Imustyk/IAD/blob/main/iad/ml/tracking/mlflow_tracker.py): logs parameters, metrics and artifacts, and keeps working if MLflow is down.
- [Drift detection](https://github.com/Imustyk/IAD/blob/main/iad/ml/preprocessing/drift/detector.py): PSI, KS test and Jensen–Shannon divergence between reference and current data.
- [Prometheus metrics](https://github.com/Imustyk/IAD/blob/main/iad/core/observability/prometheus.py) for the API and ML operations.
- [CI pipeline](https://github.com/Imustyk/IAD/blob/main/.github/workflows/ci.yml): lint, type checks, tests and a Docker build.
- [Document search in MRPRI](https://github.com/Imustyk/MRPRI/blob/main/src/mtender/rag.py): returns passages from the source and checks the quotes, instead of letting a model make up legal claims.
- [Analyst workspace storage](https://github.com/Imustyk/MRPRI/blob/main/src/mtender/workspace.py): SQLite with transactions for cases, notes and audit history.

## Tools I use

<p>
  <img src="https://skillicons.dev/icons?i=python,fastapi,postgres,sqlite,mongodb,docker,githubactions,prometheus,grafana,linux,git&perline=11" alt="Backend and infrastructure" />
  <br />
  <img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,nodejs,tailwind,vite,supabase&perline=8" alt="Languages and front-end" />
</p>

Also: Pydantic, SQLAlchemy, Alembic, scikit-learn, pandas, NumPy, XGBoost, LightGBM, MLflow, PySpark, Streamlit, pytest, Ruff, mypy.

## Work experience

**Salesforce Front-end Developer, freelance · D2Force**, Mar 2025 – Feb 2026
Reusable Lightning Web Components and B2B workflows. Connected interfaces to APIs and worked on speed and maintainability.

**Front-end Developer · Law Trust Impex**, Apr 2024 – Mar 2025
Web interfaces for real-estate and automotive apps in React and Next.js, with REST integrations. Added an AI chatbot together with a data science engineer.

## Education

- **M.Sc. Data Science**, Technical University of Moldova, 2025 – present
- **B.Sc. Information Management**, Technical University of Moldova, 2022 – 2025

## GitHub activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Imustyk&show_icons=true&hide_border=true&count_private=true" height="160" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Imustyk&layout=compact&hide_border=true" height="160" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Imustyk&hide_border=true" alt="GitHub streak" />
</p>

---

<p align="center">
  If you work on ML platforms, data engineering or something with a lot of Python, write to me on
  <a href="https://www.linkedin.com/in/imustyk/">LinkedIn</a> or by <a href="mailto:imustyk@gmail.com">email</a>.
</p>
