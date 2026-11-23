<h1 align="center">Krishna Vamsi Dhulipalla</h1>

<p align="center">
  <a href="https://krishna-dhulipalla.github.io/">
    <img src="https://img.shields.io/badge/Portfolio-000?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" />
  </a>&nbsp;
  <a href="https://krishna-dhulipalla.github.io/assets/KrishnaDhulipalla.pdf">
    <img src="https://img.shields.io/badge/Résumé-222?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Résumé" />
  </a>&nbsp;
  <a href="https://www.linkedin.com/in/krishnavamsidhulipalla">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>&nbsp;
  <a href="mailto:krishnadhulipalla13@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>&nbsp;
  <a href="https://krishnadhulipalla-chatbot.hf.space">
    <img src="https://img.shields.io/badge/Chat%20with%20my%20AI-FF6F00?style=for-the-badge&logo=huggingface&logoColor=white" alt="Chatbot" />
  </a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Inter&weight=500&size=22&duration=3000&pause=1200&color=D97757&center=true&vCenter=true&width=580&lines=AI+Engineer+%C2%B7+Agent+Systems+%26+Retrieval;Building+tools+that+ground+answers+in+evidence;From+question+to+validated+response" alt="Typing SVG" />
</p>

---

## About

Hey, I'm Krishna. I work on AI agents, LLM systems, and the engineering that makes them reliable in real-world environments. I enjoy building multi-agent systems and working with tool use, retrieval, and evaluation. I'm also curious about how AI systems behave beyond their intended workflows.

I'm particularly interested in AI security and agent red teaming: experimenting with attack techniques, testing guardrails, finding failure modes, and understanding how agents can be manipulated. I enjoy learning by building, breaking things, investigating how systems work, and contributing to open source along the way.

Outside of work, you'll find me reading about space exploration 🚀, catching a Marvel movie or reading comics 🎬, or out on a trail somewhere 🥾.

---

## What I work with

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,go,fastapi,pytorch,docker,kubernetes,aws,linux&theme=dark&perline=8" alt="Core stack" />
</p>

<table align="center">
<tr>
<td align="center" width="33%">

**Agent Systems**<br/>
<sub>LangGraph · MCP · FastAPI<br/>AWS Bedrock · A2A</sub>

</td>
<td align="center" width="33%">

**Retrieval & Evaluation**<br/>
<sub>Hybrid search · Reranking<br/>RAGAS · LangSmith</sub>

</td>
<td align="center" width="33%">

**ML & Infrastructure**<br/>
<sub>PyTorch · LoRA · MLflow<br/>Docker · Kubernetes · Go</sub>

</td>
</tr>
</table>

---

## What's on my desk

- 🔭 &nbsp;Building agent systems that validate their own tool outputs before returning an answer
- 🧪 &nbsp;Designing offline evaluation suites that catch regressions before prompt or model changes ship
- 🌱 &nbsp;Exploring policy-aware agent execution — checking proposed actions against rules and recording evidence for each decision
- 💬 &nbsp;Ask me about retrieval-augmented generation, text-to-SQL, agent evaluation, or MCP tooling

---

## Writing

| Post | Date |
| --- | --- |
| [Building Rounds: Clinical Briefings That Keep Every Claim Tied to Evidence](https://krishna-dhulipalla.github.io/engineering/healthcare%20ai/llm%20systems/2026/10/26/building-rounds.html) | Oct 2026 |
| [Building CoreLink AI: An Evidence-Grounded Reasoning Engine](https://krishna-dhulipalla.github.io/engineering/llm%20systems/agents/2026/04/21/building-corelink-ai.html) | Apr 2026 |
| [Building VIRK: A Flight Recorder for Vision Drift You Can Actually Replay](https://krishna-dhulipalla.github.io/engineering/mlops/computer%20vision/2026/02/07/vision-model-lying.html) | Feb 2026 |
| [PostgreSQL Might Be the Most Underrated Tool in Your Stack](https://krishna-dhulipalla.github.io/engineering/databases/systems/2026/04/21/postgresql-is-the-most-underrated-tool-in-your-stack.html) | Apr 2026 |
| [Why Fast AI Power Estimation Matters More Than It Sounds](https://krishna-dhulipalla.github.io/engineering/ai%20infrastructure/sustainability/2026/04/28/why-fast-ai-power-estimation-matters-more-than-it-sounds.html) | Apr 2026 |

[All posts →](https://krishna-dhulipalla.github.io/blog.html)

---

## Selected projects

<table>
<tr>
<td width="50%">

### [CoreLink AI](https://github.com/krishna-dhulipalla/CoreLink-AI)
A finance agent that retrieves and validates evidence before using deterministic tools to compute numerical answers. Built with LangGraph, A2A, and MCP and evaluated on OfficeQA.

<sub>

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangGraph](https://img.shields.io/badge/-LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/-MCP-D97757?style=flat-square)

</sub>
</td>
<td width="50%">

### [CoreLink AI Safe](https://github.com/krishna-dhulipalla/corelinkai-safe)
A policy evaluation prototype that checks proposed tool actions against a policy and records evidence for each decision.

<sub>

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Policy](https://img.shields.io/badge/-Policy%20Engine-D97757?style=flat-square)

</sub>
</td>
</tr>
<tr>
<td width="50%">

### [AgentTask Operator](https://github.com/krishna-dhulipalla/AgentTask-Operator)
A Go operator for temporary Kubernetes sandboxes with network isolation, execution limits, result capture, and automatic cleanup.

<sub>

![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

</sub>
</td>
<td width="50%">

### [Rounds](https://github.com/krishna-dhulipalla/Clinical-pre-rounding-ai)
A FHIR clinical review prototype that links briefing statements to source records and flags missing evidence.

<sub>

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FHIR](https://img.shields.io/badge/-FHIR-E44D26?style=flat-square)

</sub>
</td>
</tr>
<tr>
<td colspan="2" align="center">

### [Vision Incident Response Kit](https://github.com/krishna-dhulipalla/Vision-Incident-Response-Kit--VIRK-)
A toolkit for detecting vision-model drift, identifying affected data slices, and packaging examples for incident analysis.

<sub>

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![MLOps](https://img.shields.io/badge/-MLOps-D97757?style=flat-square)

</sub>
</td>
</tr>
</table>

---

## Open source contributions

| Pull request | Contribution |
| --- | --- |
| [microsoft/PyRIT #3919](https://github.com/microsoft/PyRIT/pull/3919) | Deduplicate dataset filters in URL parsing and serialization. |
| [browser-use/browser-use #3677](https://github.com/browser-use/browser-use/pull/3677) | Fix the async sandbox example so it runs as a standalone script. |
| [niknarra/SE-Project---IntelliMeet #1](https://github.com/niknarra/SE-Project---IntelliMeet/pull/1) | Update the SMTP server setup. |
| [microsoft/PyRIT #4329](https://github.com/microsoft/PyRIT/pull/4329) | Propose removing the temporary upper bound on the regex dependency. |
| [promptfoo/promptfoo #12433](https://github.com/promptfoo/promptfoo/pull/12433) | Add an IteraCompute example using the generic OpenAI-compatible gateway. |
| [confident-ai/deepeval #2691](https://github.com/confident-ai/deepeval/pull/2691) | Clarify documentation for misuse, MCP use, and tool correctness. |
| [langchain-ai/langgraph #6513](https://github.com/langchain-ai/langgraph/pull/6513) | Correct an async task example and clarify blocking behavior. |
| [NVIDIA-NeMo/Guardrails #1930](https://github.com/NVIDIA-NeMo/Guardrails/pull/1930) | Update README documentation links. |
| [google/adk-python #3875](https://github.com/google/adk-python/pull/3875) | Correct `run_async` usage and the `ticketId` payload key in examples. |
| [niknarra/SE-Project---IntelliMeet #10](https://github.com/niknarra/SE-Project---IntelliMeet/pull/10) | Contribute development UI changes. |

I also filed reports on an [OpenClaw update failure](https://github.com/openclaw/openclaw/issues/182967) and an [Open VSX namespace request](https://github.com/EclipseFdn/open-vsx.org/issues/9272). [All my public PRs →](https://github.com/search?q=is%3Apr+author%3Akrishna-dhulipalla&type=pullrequests)

---

## GitHub activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/krishna-dhulipalla/krishna-dhulipalla/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/krishna-dhulipalla/krishna-dhulipalla/output/github-snake.svg" />
    <img src="https://raw.githubusercontent.com/krishna-dhulipalla/krishna-dhulipalla/output/github-snake.svg" alt="Contribution snake animation" width="100%" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats-alpha-two-72.vercel.app/api/top-langs?username=krishna-dhulipalla&layout=compact&hide=jupyter%20notebook,html&theme=github_dark&hide_border=true&bg_color=00000000" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats-alpha-two-72.vercel.app/api/top-langs?username=krishna-dhulipalla&layout=compact&hide=jupyter%20notebook,html&hide_border=true" />
    <img src="https://github-readme-stats-alpha-two-72.vercel.app/api/top-langs?username=krishna-dhulipalla&layout=compact&hide=jupyter%20notebook,html&hide_border=true" alt="Most used languages" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-streak-stats.herokuapp.com/?user=krishna-dhulipalla&theme=github-dark-blue&hide_border=true&background=00000000" />
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-streak-stats.herokuapp.com/?user=krishna-dhulipalla&hide_border=true" />
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=krishna-dhulipalla&hide_border=true" alt="GitHub contribution streak" />
  </picture>
</p>

---

<p align="center">
  <sub>If the system answered it, I want to know where it looked.</sub>
</p>
