<div align="center">

# Hi there, I'm Aakash S S 👋

### 🤖 AI & Machine Learning Engineer · Full-Stack ML Builder · Open-Source Contributor
**CSE Student @ Vel Tech, Chennai**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aakash-s-s-88b91a301)
&nbsp;&nbsp;
[![Portfolio](https://img.shields.io/badge/Portfolio-0A101F?style=for-the-badge&logo=vercel&logoColor=white)](https://aakash1552005.github.io/)
&nbsp;&nbsp;
[![Gmail](https://img.shields.io/badge/Gmail-0A101F?style=for-the-badge&logo=gmail&logoColor=EA4335)](mailto:aakash1552005@gmail.com)
&nbsp;&nbsp;
[![LeetCode](https://img.shields.io/badge/LeetCode-0A101F?style=for-the-badge&logo=leetcode&logoColor=FFA116)](https://leetcode.com/u/Aakash_1528/)

<br/>

[![Open Source Merged](https://img.shields.io/badge/Merged%20in%20OSS-4%20PRs%20%F0%9F%8E%89-10B981?style=flat-square&logo=github)](https://github.com/aakash1552005)
[![PyPI Package](https://img.shields.io/badge/PyPI-rerunner%20v0.2.0-3776AB?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/project/rerunner/)
[![Target](https://img.shields.io/badge/Target-LF%20AI%20%26%20Data%20%7C%20MLOps-6366F1?style=flat-square)](https://github.com/aakash1552005)

</div>

---

## 🧑‍💻 About Me

- 🎓 B.Tech Computer Science student at **Vel Tech**, Chennai — specializing in **AI, Machine Learning & MLOps**.
- 📼 **Author & Maintainer of [`rerunner`](https://github.com/aakash1552005/rerunner)** ([PyPI](https://pypi.org/project/rerunner/)) — Deterministic flight recorder, $0 CI replay engine & time-travel debugger for LLMs & AI agents.
- 🌐 **Active Open Source Contributor** across tier-1 data & AI libraries:
  - **`kedro-plugins`**: **3 PRs MERGED** 🎉 (`#1536`, `#1538`, `#1543`) into `main` by core maintainers.
  - **`sktime`**: **1 PR MERGED** 🎉 (`#11445`), and authored PR `#11448` whose foundation model streaming update logic became the **community blueprint** for issue #11245.
  - **`cleanlab`**, **`zenml`**, **`kedro`**, and **`evidently`**: Actively solving runtime bugs, NumPy 2.0 / Python 3.12 compatibility, and distributed runners.
- 🛰️ Built **SatQuery-AI** for **SIH 2026 (ISRO / SAC)** — multimodal Earth observation AI featuring SAR-optical fusion & deterministic GIS verification.
- 🚀 Shipped full-stack ML system — **Smart Child Nutrition Deficiency Tracking System** across 10 state districts (currently under **IEEE conference submission**).
- 📍 Based in Chennai, Tamil Nadu · 📬 `aakash1552005@gmail.com`

---

## 📦 Featured Project: `rerunner`

<div align="center">

[![PyPI Version](https://img.shields.io/pypi/v/rerunner?style=flat-square&color=blue&logo=pypi&logoColor=white)](https://pypi.org/project/rerunner/)
[![License](https://img.shields.io/github/license/aakash1552005/rerunner?style=flat-square&color=green)](https://github.com/aakash1552005/rerunner/blob/main/LICENSE)
[![Python Versions](https://img.shields.io/pypi/pyversions/rerunner?style=flat-square)](https://pypi.org/project/rerunner/)

</div>

> **[rerunner](https://github.com/aakash1552005/rerunner)** records real external API interactions (OpenAI, Anthropic, Gemini, custom HTTP APIs) into deterministic cassettes, enabling instant, offline, zero-token-cost CI test runs and time-travel replay.

- ⚡ **Server-Sent Events (SSE) Streaming Replayer**: Replay streaming token deltas for OpenAI SDK / Anthropic SDK with zero network calls.
- ☁️ **Pluggable Storage**: First-class support for Local, AWS S3 (`s3://`), and Google Cloud Storage (`gs://`) cassette backends.
- 🛡️ **PII & Secret Redaction Engine**: Zero-leak guarantee masking API keys, JWTs, emails, phone numbers, and IP addresses before cassettes touch disk.
- 📊 **OpenTelemetry Export**: Out-of-the-box telemetry export for test suite cost savings and LLM request distributions.

```bash
pip install rerunner
```

---

## 🌐 Open Source Contributions

| Project | Stars | Status | What I Built / Fixed |
| :--- | :---: | :---: | :--- |
| **[`kedro-org/kedro-plugins`](https://github.com/kedro-org/kedro-plugins)** | 9.3k+ ⭐ | **3 MERGED 🎉 · 5 Active** | • [PR #1536](https://github.com/kedro-org/kedro-plugins/pull/1536) & [PR #1538](https://github.com/kedro-org/kedro-plugins/pull/1538): **MERGED** into main.<br/>• [PR #1543](https://github.com/kedro-org/kedro-plugins/pull/1543): **MERGED** into main (experimental dataset YAML documentation).<br/>• [PRs #1532-#1539](https://github.com/kedro-org/kedro-plugins/pulls/aakash1552005): Dask PathLike datasets, remote pickle, Polars Calamine, and Opik prompt telemetry. |
| **[`sktime/sktime`](https://github.com/sktime/sktime)** | 3.5k+ ⭐ | **1 MERGED 🎉 · Blueprint Adopted** | • [PR #11445](https://github.com/sktime/sktime/pull/11445): **MERGED** into main by lead maintainer `@fkiraly`.<br/>• [PR #11448](https://github.com/sktime/sktime/pull/11448): Zero-shot `TimerForecaster` streaming context update logic. **Adopted as reference architecture** by contributors for 6+ foundation models (#11245). |
| **[`cleanlab/cleanlab`](https://github.com/cleanlab/cleanlab)** | 10k+ ⭐ | **Active PRs (Green CI)** | • [PR #1343](https://github.com/cleanlab/cleanlab/pull/1343): Fixed ranking cutoff bounds checking in token classification (#1338).<br/>• [PR #1344](https://github.com/cleanlab/cleanlab/pull/1344): Added background-only bounding box normalization & NumPy 2.0 `np.isin` migration (#1234). |
| **[`zenml-io/zenml`](https://github.com/zenml-io/zenml)** | 4.1k+ ⭐ | **Active PRs (CLA Signed)** | • [PR #5346](https://github.com/zenml-io/zenml/pull/5346): Fixed step retry exponential backoff calculation (#5325).<br/>• [PR #5347](https://github.com/zenml-io/zenml/pull/5347): Fixed remote S3/GCS cloudpickle materializer check (#5322).<br/>• [PR #5348](https://github.com/zenml-io/zenml/pull/5348): Fixed client active project global fallback (#5323). |
| **[`kedro-org/kedro`](https://github.com/kedro-org/kedro)** | 9.3k+ ⭐ | **In Team Discussion** | • [PR #5811](https://github.com/kedro-org/kedro/pull/5811): Modernized `DaskRunner` distributed deployment guide and native CLI parameters. Core maintainer `@ankatiyar` confirmed internal team review. |
| **[`evidentlyai/evidently`](https://github.com/evidentlyai/evidently)** | 5.5k+ ⭐ | **Active PR** | • [PR #1955](https://github.com/evidentlyai/evidently/pull/1955): Fixed Python 3.12+ regex escape warnings & NumPy 2.0+ compatibility layer. |

---

## 🛠️ Tech Stack

<div align="center">

### Core & Data Science
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-0A101F?style=for-the-badge&logo=xgboost&logoColor=EC4E20)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Dask](https://img.shields.io/badge/Dask-FDA061?style=for-the-badge&logo=dask&logoColor=black)

### Web & Infrastructure
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img width="100%" src="https://streak-stats.demolab.com/?user=aakash1552005&hide_border=true&background=0A101F&stroke=22D3EE&ring=A78BFA&fire=10B981&currStreakLabel=22D3EE&sideLabels=94A3B8&currStreakNum=F8FAFC&sideNums=F8FAFC&dates=64748B&titleColor=22D3EE&card_width=1180" alt="streak stats" />

<br/><br/>

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=aakash1552005&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&title_color=22D3EE&icon_color=A78BFA&text_color=94A3B8&bg_color=0A101F&card_width=500" alt="stats" />
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=aakash1552005&layout=compact&langs_count=8&hide_border=true&title_color=22D3EE&text_color=94A3B8&bg_color=0A101F&card_width=500" alt="top langs" />

</div>

---

<div align="center">

⭐ *"Turning data into decisions, one model at a time."*

</div>

