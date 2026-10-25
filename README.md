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
</div>

---

## 🧑‍💻 About Me

- 🎓 Computer Science Engineering student at **Vel Tech, Chennai**, specializing in **AI, Machine Learning, and MLOps**.
- 📼 **Author & Maintainer of [`rerunner`](https://github.com/aakash1552005/rerunner)** ([PyPI](https://pypi.org/project/rerunner/)) — Deterministic record-and-replay engine for offline testing and debugging of LLMs and AI agents.
- 🌐 **Open Source Contributor**:
  - **`huggingface/transformers`**: Authored PR [#49969](https://github.com/huggingface/transformers/pull/49969) fixing GOT-OCR2 NumPy coordinate normalization bug (Issue #49902).
  - **`huggingface/accelerate`**: Authored PR [#4455](https://github.com/huggingface/accelerate/pull/4455) fixing Windows automatic checkpoint sorting & retention bug (Issue #4454).
  - **`kedro-plugins`**: 3 merged PRs ([#1536](https://github.com/kedro-org/kedro-plugins/pull/1536), [#1538](https://github.com/kedro-org/kedro-plugins/pull/1538), [#1543](https://github.com/kedro-org/kedro-plugins/pull/1543)) improving dataset serialization, test coverage, and documentation.
  - **`sktime`**: Merged PR [#11445](https://github.com/sktime/sktime/pull/11445) (forecasting horizon API modernization); authored PR [#11448](https://github.com/sktime/sktime/pull/11448) whose foundation model streaming update pattern was adopted across 6 models (Issue #11245).
  - **`cleanlab`**, **`litellm`**, and **`zenml`**: Actively fixing NumPy 2.0 / Python 3.12 compatibility, retry backoffs, and distributed runner pipelines.
- 🛰️ Built **SatQuery-AI** for **SIH 2026 (ISRO / SAC)** — multimodal Earth observation AI integrating SAR-optical fusion and deterministic GIS verification.
- 🚀 Engineered the **Smart Child Nutrition Deficiency Tracking System**, deployed across 10 districts (under review for IEEE conference publication).
- 📍 Chennai, India · 📬 `aakash1552005@gmail.com`

---

## 📦 Featured Project: `rerunner`

<div align="center">

[![PyPI Version](https://img.shields.io/pypi/v/rerunner?style=flat-square&color=blue&logo=pypi&logoColor=white)](https://pypi.org/project/rerunner/)
[![License](https://img.shields.io/github/license/aakash1552005/rerunner?style=flat-square&color=green)](https://github.com/aakash1552005/rerunner/blob/main/LICENSE)
[![Python Versions](https://img.shields.io/pypi/pyversions/rerunner?style=flat-square)](https://pypi.org/project/rerunner/)

</div>

> **[rerunner](https://github.com/aakash1552005/rerunner)** records external API interactions (OpenAI, Anthropic, Gemini, HTTP APIs) into deterministic cassettes, enabling fast, offline, zero-token-cost CI test execution and time-travel debugging.

- ⚡ **Server-Sent Events (SSE) Replayer**: Deterministically replays streaming tokens for OpenAI and Anthropic SDKs without network access.
- ☁️ **Pluggable Storage**: First-class support for Local, AWS S3 (`s3://`), and Google Cloud Storage (`gs://`) backends.
- 🛡️ **Automated Sanitization**: Masks API keys, JWTs, emails, phone numbers, and IP addresses before cassettes are written to disk.
- 📊 **OpenTelemetry Export**: Native telemetry export for request latency, cost savings, and token distribution analysis.

```bash
pip install rerunner
```

---

## 🌐 Open Source Contributions

| Project | Stars | Status | What I Built / Fixed |
| :--- | :---: | :---: | :--- |
| **[`huggingface/transformers`](https://github.com/huggingface/transformers)** | 140k+ ⭐ | **Active PR** | • [PR #49969](https://github.com/huggingface/transformers/pull/49969): Fixed NumPy image bounding-box normalization coordinate inversion and input mutation in GOT-OCR2 (Issue #49902). |
| **[`huggingface/accelerate`](https://github.com/huggingface/accelerate)** | 10k+ ⭐ | **Active PR** | • [PR #4455](https://github.com/huggingface/accelerate/pull/4455): Fixed Windows checkpoint path sorting regex in `save_state` & `load_state` when parent directories contain digits (Issue #4454). |
| **[`kedro-org/kedro-plugins`](https://github.com/kedro-org/kedro-plugins)** | 9.3k+ ⭐ | **3 Merged · 7 Active** | • [PR #1536](https://github.com/kedro-org/kedro-plugins/pull/1536) & [PR #1538](https://github.com/kedro-org/kedro-plugins/pull/1538): Merged into `main` (CSVDataset index rationale & HoloViews Python 3.10 fixes).<br/>• [PR #1543](https://github.com/kedro-org/kedro-plugins/pull/1543): Merged into `main` (experimental dataset YAML documentation).<br/>• [PR #1545](https://github.com/kedro-org/kedro-plugins/pull/1545) & [PR #1546](https://github.com/kedro-org/kedro-plugins/pull/1546): SQLTableDataset preview schema fix & PathLike support across 11 datasets. |
| **[`BerriAI/litellm`](https://github.com/BerriAI/litellm)** | 18k+ ⭐ | **Maintainer Reviewed** | • [PR #48008](https://github.com/BerriAI/litellm/pull/48008): Preserved extra_body across mock_response and completions responses.<br/>• [PR #48014](https://github.com/BerriAI/litellm/pull/48014): Excluded zero usage values from streamed completion chunks. |
| **[`sktime/sktime`](https://github.com/sktime/sktime)** | 3.5k+ ⭐ | **1 Merged · Blueprint Adopted** | • [PR #11445](https://github.com/sktime/sktime/pull/11445): Merged into `main` (forecasting horizon API modernization).<br/>• [PR #11617](https://github.com/sktime/sktime/pull/11617): Added panel and multi-instance data support for HampelDetector (Issue #11615). |
| **[`cleanlab/cleanlab`](https://github.com/cleanlab/cleanlab)** | 10k+ ⭐ | **Active PRs** | • [PR #1351](https://github.com/cleanlab/cleanlab/pull/1351): Dynamic and forward-compatible issue type argument mapping across IssueManagers (Issue #995).<br/>• [PR #1344](https://github.com/cleanlab/cleanlab/pull/1344): Added bounding box normalization and migrated to NumPy 2.0 `np.isin`. |
| **[`zenml-io/zenml`](https://github.com/zenml-io/zenml)** | 4.1k+ ⭐ | **Active PRs** | • [PR #5346](https://github.com/zenml-io/zenml/pull/5346): Fixed step retry exponential backoff calculation.<br/>• [PR #5347](https://github.com/zenml-io/zenml/pull/5347): Fixed remote S3/GCS cloudpickle materializer check.<br/>• [PR #5348](https://github.com/zenml-io/zenml/pull/5348): Implemented global active project fallback. |

---

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-0A101F?style=for-the-badge&logo=xgboost&logoColor=EC4E20)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

</div>

---

<div align="center">

⭐ *"Turning data into decisions, one model at a time."*

</div>

