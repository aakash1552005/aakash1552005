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
- 📼 **Author & Maintainer of [`rerunner`](https://github.com/aakash1552005/rerunner)** ([PyPI](https://pypi.org/project/rerunner/) · [GitHub Marketplace](https://github.com/marketplace/actions/rerunner-ci-replay-cost-reporter)) — Deterministic record-and-replay engine for offline testing and debugging of LLMs and AI agents.
- 🌐 **Open Source Contributor**:
  - **`huggingface/transformers`**: Authored PR [#49969](https://github.com/huggingface/transformers/pull/49969) (GOT-OCR2 NumPy coordinate normalization bug #49902).
  - **`huggingface/accelerate`**: Authored PR [#4455](https://github.com/huggingface/accelerate/pull/4455) fixing Windows automatic checkpoint sorting & retention bug (Issue #4454).
  - **`kedro-plugins`**: **6 merged PRs** ([#1532](https://github.com/kedro-org/kedro-plugins/pull/1532), [#1536](https://github.com/kedro-org/kedro-plugins/pull/1536), [#1538](https://github.com/kedro-org/kedro-plugins/pull/1538), [#1539](https://github.com/kedro-org/kedro-plugins/pull/1539), [#1543](https://github.com/kedro-org/kedro-plugins/pull/1543), [#1546](https://github.com/kedro-org/kedro-plugins/pull/1546)), and active PR [#1553](https://github.com/kedro-org/kedro-plugins/pull/1553) (Ibis append save).
  - **`sktime`**: Merged PR [#11445](https://github.com/sktime/sktime/pull/11445) (forecasting horizon API modernization); authored PR [#11701](https://github.com/sktime/sktime/pull/11701) (global pooling NaN/Inf check fix #11521), PR [#11657](https://github.com/sktime/sktime/pull/11657) (detector update with Series/NumPy #11606) & PR [#11448](https://github.com/sktime/sktime/pull/11448).
  - **`zenml`**: Authored PR [#5394](https://github.com/zenml-io/zenml/pull/5394) (deployment filter #5274), PR [#5346](https://github.com/zenml-io/zenml/pull/5346), PR [#5347](https://github.com/zenml-io/zenml/pull/5347), PR [#5348](https://github.com/zenml-io/zenml/pull/5348).
  - **`litellm`**: PR [#46900](https://github.com/BerriAI/litellm/pull/46900) (fallback team-member budget enforcement #46874, endorsed by `@Jahanzeb-git`) & PR [#48008](https://github.com/BerriAI/litellm/pull/48008) (preserved `extra_body` kwargs).
  - **`cleanlab`**: Authored PR [#1351](https://github.com/cleanlab/cleanlab/pull/1351) (dynamic issue type mapping #995) & PR [#1344](https://github.com/cleanlab/cleanlab/pull/1344) (bounding box normalization #1234).
- 🛰️ Built **SatQuery-AI** for **SIH 2026 (ISRO / SAC)** — multimodal Earth observation AI integrating SAR-optical fusion and deterministic GIS verification.
- 🚀 Engineered the **Smart Child Nutrition Deficiency Tracking System**, deployed across 10 districts (under review for IEEE conference publication).
- 📍 Chennai, India · 📬 `aakash1552005@gmail.com`

---

## 📦 Featured Project: `rerunner`

<div align="center">

[![GitHub Marketplace](https://img.shields.io/badge/Marketplace-Rerunner_CI_Action-blue?style=flat-square&logo=github-actions&logoColor=white)](https://github.com/marketplace/actions/rerunner-ci-replay-cost-reporter)
[![PyPI Version](https://img.shields.io/pypi/v/rerunner?style=flat-square&color=blue&logo=pypi&logoColor=white)](https://pypi.org/project/rerunner/)
[![Release](https://img.shields.io/badge/release-v0.3.1-blue.svg?style=flat-square)](https://github.com/aakash1552005/rerunner/releases/tag/v0.3.1)
[![License](https://img.shields.io/github/license/aakash1552005/rerunner?style=flat-square&color=green)](https://github.com/aakash1552005/rerunner/blob/main/LICENSE)
[![Python Versions](https://img.shields.io/pypi/pyversions/rerunner?style=flat-square)](https://pypi.org/project/rerunner/)

</div>

> **[rerunner](https://github.com/aakash1552005/rerunner)** records external AI and agent interactions (Anthropic Claude, OpenAI, AWS Bedrock, Google GenAI, AutoGen, Semantic Kernel, LangGraph, Model Context Protocol) into deterministic cassettes, enabling fast, offline, zero-token-cost CI test execution and time-travel debugging.

- 🖥️ **Interactive Terminal Flight Deck (`rerunner tui`)**: Visually scrub and inspect multi-turn agent execution steps, tokens, and cryptographic security audits in the terminal.
- 🤖 **Model Context Protocol (MCP) Replay**: Deterministically record and replay MCP tool invocations without running local servers.
- ⚡ **Streaming SSE Replayer**: Native token-by-token replay for `text/event-stream` chunks with simulated network latency.
- ☁️ **Multi-Cloud Storage**: First-class support for Local, AWS S3 (`s3://`), Google Cloud Storage (`gs://`), and Microsoft Azure Blob Storage (`az://`).
- 🛡️ **Enterprise PII & Secret Redaction**: Pluggable redaction pipelines (Microsoft Presidio & Sether) masking API keys, cards, SSNs, and emails.
- 📊 **Official GitHub Action & OTel Export**: 3-line CI action rendering automatic token savings reports directly in `$GITHUB_STEP_SUMMARY`.

```bash
pip install rerunner
```

---

## 🌐 Open Source Contributions

| Project | Stars | Status | What I Built / Fixed |
| :--- | :---: | :---: | :--- |
| **[`huggingface/transformers`](https://github.com/huggingface/transformers)** | 140k+ ⭐ | **Active PR** | • [PR #49969](https://github.com/huggingface/transformers/pull/49969): Fixed NumPy image bounding-box normalization coordinate inversion and input mutation in GOT-OCR2 (#49902). |
| **[`huggingface/accelerate`](https://github.com/huggingface/accelerate)** | 10k+ ⭐ | **Active PR** | • [PR #4455](https://github.com/huggingface/accelerate/pull/4455): Fixed Windows checkpoint path sorting regex in `save_state` & `load_state` when parent directories contain digits (#4454). |
| **[`sktime/sktime`](https://github.com/sktime/sktime)** | 3.5k+ ⭐ | **1 Merged · Active PRs** | • [PR #11701](https://github.com/sktime/sktime/pull/11701): Fixed NaN and Inf detection logic in global pooling reduction forecasters (#11521).<br/>• [PR #11657](https://github.com/sktime/sktime/pull/11657): Fixed `BaseDetector.update()` crashing on `pd.Series` and `np.ndarray` inputs (#11606).<br/>• [PR #11445](https://github.com/sktime/sktime/pull/11445): Merged into `main` (forecasting horizon API modernization).<br/>• [PR #11617](https://github.com/sktime/sktime/pull/11617): Added panel and multi-instance data support for HampelDetector (#11615). |
| **[`zenml-io/zenml`](https://github.com/zenml-io/zenml)** | 4.1k+ ⭐ | **Active PRs** | • [PR #5394](https://github.com/zenml-io/zenml/pull/5394): Added `triggered_by_deployment` filter to prevent deployment runs skewing pipeline run statistics (#5274).<br/>• [PR #5346](https://github.com/zenml-io/zenml/pull/5346), [#5347](https://github.com/zenml-io/zenml/pull/5347), [#5348](https://github.com/zenml-io/zenml/pull/5348): Step retry backoff, remote materializer check, and active project fallback. |
| **[`kedro-org/kedro-plugins`](https://github.com/kedro-org/kedro-plugins)** | 9.3k+ ⭐ | **6 Merged · Active** | • [PR #1546](https://github.com/kedro-org/kedro-plugins/pull/1546): **Merged into `main`** (approved by @merelcht & @ankatiyar) — added `os.PathLike` filepath support across 11 datasets.<br/>• [PR #1539](https://github.com/kedro-org/kedro-plugins/pull/1539): **Merged into `main`** (approved by @merelcht & @ankatiyar) — supported `calamine` engine in `EagerPolarsDataset` Excel loader with parameterized multi-engine test suite.<br/>• [PR #1532](https://github.com/kedro-org/kedro-plugins/pull/1532): **Merged into `main`** (approved by @merelcht & @ankatiyar, 18 CI jobs passing) — `os.PathLike` test coverage for Dask datasets.<br/>• [PR #1536](https://github.com/kedro-org/kedro-plugins/pull/1536), [#1538](https://github.com/kedro-org/kedro-plugins/pull/1538), [#1543](https://github.com/kedro-org/kedro-plugins/pull/1543): **Merged into `main`** (CSVDataset index, HoloViews Python 3.10+, and dataset docs).<br/>• [PR #1553](https://github.com/kedro-org/kedro-plugins/pull/1553) & [#1545](https://github.com/kedro-org/kedro-plugins/pull/1545): Ibis dataset append argument filter (#1551) & SQL preview schema fix. |
| **[`cleanlab/cleanlab`](https://github.com/cleanlab/cleanlab)** | 10k+ ⭐ | **Active PRs** | • [PR #1351](https://github.com/cleanlab/cleanlab/pull/1351): Dynamic and forward-compatible issue type argument mapping across IssueManagers (#995).<br/>• [PR #1344](https://github.com/cleanlab/cleanlab/pull/1344): Added bounding box normalization and migrated to NumPy 2.0 `np.isin` (#1234). |
| **[`BerriAI/litellm`](https://github.com/BerriAI/litellm)** | 18k+ ⭐ | **Maintainer Reviewed & Endorsed** | • [PR #46900](https://github.com/BerriAI/litellm/pull/46900): **Reviewed & Endorsed by contributor** (@Jahanzeb-git) — Enforced team member overall budget on fallback targets with full e2e tests & UI schema sync (#46874).<br/>• [PR #48008](https://github.com/BerriAI/litellm/pull/48008): Preserved `extra_body` across `mock_response` and completions responses. |

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

