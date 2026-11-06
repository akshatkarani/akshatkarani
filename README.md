<h1 align="center">Akshat Karani</h1>

<p align="center">
  Senior ML Engineer at <a href="https://needl.ai">Needl.ai</a> &middot; Mumbai<br>
  <sub>agent harnesses &middot; evals &middot; LLM infrastructure</sub>
</p>

<p align="center">
  <a href="https://akshatkarani.github.io"><img alt="Website" src="https://img.shields.io/badge/website-akshatkarani.github.io-2b59c3?style=flat-square"></a>
  <a href="https://www.linkedin.com/in/akshat-karani"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-akshat--karani-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="https://x.com/akshatkarani"><img alt="X" src="https://img.shields.io/badge/X-akshatkarani-000000?style=flat-square&logo=x&logoColor=white"></a>
  <a href="mailto:akshatkarani@gmail.com"><img alt="Email" src="https://img.shields.io/badge/email-akshatkarani%40gmail.com-555555?style=flat-square&logo=gmail&logoColor=white"></a>
</p>

I build and own the agent platform and the LLM layer behind **AskNeedl**, Needl's answer engine for financial and enterprise data. Five years at Needl, from data connectors and retrieval infrastructure to production LLM agents that run both sub-minute chat and twenty-minute due-diligence reports. I studied Computer Science and Engineering at IIT Dharwad.

## What I build

- **Agent harness** &mdash; config-driven agents over a shared tool registry; skills that load business context and tool playbooks only when needed; tool-call budgets; per-fragment citations with quote validation; Langfuse tracing across every service. One loop, from interactive chat to long-running report orchestrations.
- **LLM infrastructure** &mdash; a single typed layer over OpenAI, Azure OpenAI, Gemini and Claude, with fallback chains, type-based retries and per-call cost tracking, used by every service that talks to a model.
- **Text-to-SQL agents** over PostgreSQL and Snowflake, hardened with an LLM input guard, read-only checks and permitted-table lists, and gated by nightly recall and false-positive thresholds.
- **Evals as a ship gate** &mdash; LLM graders, golden datasets and regression runs on every agent change; customer-reported failures become test cases.
- **AI-native engineering** &mdash; the team's Claude Code skills for deploys, daily alert triage and agent-session debugging, so coding agents are first-class tools rather than autocomplete.

Most of this lives in Needl's private org, on my work account [aks-71](https://github.com/aks-71).

## Stack

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white">
  <img alt="OpenAI" src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white">
  <img alt="Gemini" src="https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=googlegemini&logoColor=white">
  <img alt="Claude" src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white">
  <img alt="Langfuse" src="https://img.shields.io/badge/Langfuse-000000?style=flat-square">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
  <img alt="Snowflake" src="https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white">
  <img alt="Elasticsearch" src="https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white">
  <img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white">
  <img alt="Terraform" src="https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white">
  <img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?style=flat-square">
  <img alt="Claude Code" src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white">
</p>

## Open source and projects

- **Google Summer of Code 2019, [coala](https://github.com/coala/coala)** &mdash; reworked the action system so analysis plugins can define their own fixes and offer alternative patches. [Final report](https://github.com/coala/projects/blob/master/_reports/akshatkarani.md) and an [eight-part log](https://akshatkarani.github.io/#writing).
- [randomized_tsp](https://github.com/akshatkarani/randomized_tsp) &mdash; genetic, simulated-annealing and ant-colony algorithms for the Travelling Salesman Problem, on [PyPI](https://pypi.org/project/randomized-tsp).
- [micro_compiler](https://github.com/akshatkarani/micro_compiler) &mdash; a compiler for the MICRO language in C++ with Flex and Bison.
