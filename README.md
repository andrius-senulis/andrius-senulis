<div align="center">

## Labas! I'm Andrius

**Senior backend engineer · Python and Go · Copenhagen 🇩🇰**

I build the backend behind AI and data products: APIs, pipelines, and the
infrastructure that keeps models serving in production.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-andrius--senulis-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/andrius-senulis/)

</div>

> [!TIP]
> **Open to new roles.** Senior AI engineering on LLM products, or backend work with AI features.
> Based in Copenhagen, EU citizen, available now.

---

### What I work on

I like owning a piece of work end to end: write the spec, get people to agree on it, ship it,
then keep it healthy in production. Thirteen years in, I've learned that deciding what to build
matters as much as building it, so I write things down early (ADRs, PRDs, technical specs) and
bring them to the people affected before the code exists.

<table>
<tr>
<td width="50%" valign="top">

**🧠 AI and LLMs**

LLM compliance analysis with Pydantic AI, evaluated by LLM-as-a-Judge pipelines.
Automated Codex PR review in GitHub Actions, and Claude Code agents with specialised
sub-agents for the team's daily work.

</td>
<td width="50%" valign="top">

**⚙️ Model serving at scale**

Six years at DataRobot on enterprise MLOps. Tech lead on Serverless Predictions:
scale-to-zero for idle inference pods, then the GA rollout across multi-tenant SaaS,
single-tenant clouds (EKS, GKE, AKS) and on-prem OpenShift.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🌊 Data pipelines**

The ML pipelines integration between Apache Airflow and DataRobot, built on a Go gRPC
service. Earlier, Spark jobs for a team-built ELT warehouse that cut cloud costs by
$500k a year.

</td>
<td width="50%" valign="top">

**📈 Time-series APIs**

Took a time-series data API from PRD to an approved ADR, then delivered one query
contract across endpoints. Rebuilt Go integration-test infrastructure, part of a CI
effort that roughly halved test time.

</td>
</tr>
</table>

### Open source

📦 **[airflow-provider-datarobot](https://github.com/datarobot/airflow-provider-datarobot)**:
the Apache Airflow provider for DataRobot, which I built and published on
[PyPI](https://pypi.org/project/airflow-provider-datarobot/), with docs, tutorials and a
[blog post](https://www.datarobot.com/blog/how-to-integrate-datarobot-and-apache-airflow-for-orchestration-and-mlops-workflows/)
on using it for MLOps workflows.

### Toolbox

| | |
| --- | --- |
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776ab?style=flat&logo=python&logoColor=white) ![Go](https://img.shields.io/badge/Go-00add8?style=flat&logo=go&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4b5563?style=flat) |
| **Backend** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-e92063?style=flat&logo=pydantic&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-d71f00?style=flat&logo=sqlalchemy&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white) ![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat) |
| **Data** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169e1?style=flat&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47a248?style=flat&logo=mongodb&logoColor=white) ![Airflow](https://img.shields.io/badge/Apache%20Airflow-017cee?style=flat&logo=apacheairflow&logoColor=white) ![PySpark](https://img.shields.io/badge/PySpark-e25a1c?style=flat&logo=apachespark&logoColor=white) |
| **Infra** | ![Kubernetes](https://img.shields.io/badge/Kubernetes-326ce5?style=flat&logo=kubernetes&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ed?style=flat&logo=docker&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232f3e?style=flat) ![Terraform](https://img.shields.io/badge/Terraform-7b42bc?style=flat&logo=terraform&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088ff?style=flat&logo=githubactions&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-f46800?style=flat&logo=grafana&logoColor=white) |
| **AI** | ![Pydantic AI](https://img.shields.io/badge/Pydantic%20AI-e92063?style=flat&logo=pydantic&logoColor=white) ![Claude Code](https://img.shields.io/badge/Claude%20Code-d97757?style=flat&logo=claude&logoColor=white) ![Codex](https://img.shields.io/badge/Codex-412991?style=flat) ![Copilot](https://img.shields.io/badge/GitHub%20Copilot-000000?style=flat&logo=githubcopilot&logoColor=white) |

### The road so far

| When | Where | What I did |
| --- | --- | --- |
| 2026 | **Archon Tech**<br><sub>Senior Software Engineer</sub> | Backend services and data ingestion for a high-volume risk-analytics platform, in Go and Python.<br>• Project lead for the Time-Series Data API, from the PRD through an approved ADR to one shared query contract across endpoints<br>• Owned a partner integration end to end: a scheduled GraphQL indexer, append-only versioned tables for auditability, alerts, runbooks and the UI<br>• Built automated Codex PR review in GitHub Actions and rebuilt the Go integration-test harness, part of a CI effort that roughly halved test time |
| 2025–26 | **Fortiv.io**<br><sub>Senior Software Engineer</sub> | Early engineer at a pre-seed B2B SaaS startup building a Business Continuity Management System.<br>• Built LLM compliance analysis with Pydantic AI, and the team's first evaluation pipeline with LLM-as-a-Judge scoring<br>• Built multi-channel alerts (email, SMS, voice), Microsoft SSO for enterprise customers, rate limiting and PDF exports<br>• Built an orchestrator Claude Code agent with specialised sub-agents for feature work |
| 2019–25 | **DataRobot**<br><sub>Software Engineer to Senior</sub> | Six years on an enterprise AI platform, promoted twice.<br>• Technical lead for three Serverless Predictions projects, including scale-to-zero for idle inference pods, then led the GA rollout to every deployment type, from multi-tenant SaaS to on-prem OpenShift<br>• Designed and built the ML pipelines integration between Apache Airflow and DataRobot, with a Go gRPC service and specs signed off by engineering leadership<br>• Built the open-source Airflow provider and a PySpark library for Palantir Foundry<br>• Worked on Covid Simulator data pipelines for the US government's pandemic response, part of a team-built warehouse that cut cloud costs by $500k a year |
| 2017–19 | **CSIS Security Group**<br><sub>Python Developer</sub> | Built features for customer-facing threat intelligence portals and internal tools in Python, Flask and PostgreSQL, with automated tests and daily code review. |
| 2014–17 | **Isynet**<br><sub>Web / System Developer</sub> | Built Django apps with PDF reports for drug market research, kept the data scrapers running, and mentored new engineers. |
| 2013–14 | **University of Copenhagen**<br><sub>IT Developer / Bioinformatician</sub> | Built a Python pipeline for miRNA and non-coding RNA expression profiling from next-generation sequencing data at the Forensic Medicine Institute. |

<details>
<summary><b>A few things you won't find in my commits</b></summary>
<br>

- 🧬 I came to software through bioinformatics: a BSc in Vilnius, an MSc in Copenhagen, and a
  first job profiling miRNA from sequencing data
- 🎹 I hold a music academy diploma in piano
- 🇱🇹 I'm Lithuanian, and I've served on the boards of Lithuanian Professionals in Copenhagen and
  the Lithuanian Youth Society
- 🗣️ Lithuanian, English, and some Danish and French

</details>
