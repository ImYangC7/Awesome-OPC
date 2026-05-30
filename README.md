<div align="center">
    <h1>Awesome OPC: Agentic One-Person Company</h1>
</div>

<p align="center">
    <a href="https://github.com/sindresorhus/awesome"><img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome list badge"></a>
    <a href="https://github.com/ImYangC7/Awesome-OPC/stargazers"><img src="https://img.shields.io/github/stars/ImYangC7/Awesome-OPC?style=social" alt="GitHub stars"></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="MIT License"></a>
    <a href="CONTRIBUTING.md"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs welcome"></a>
</p>

This repository manually collects papers, surveys, tools, reports, and legal context for **OPC**: AI-enabled **One-Person Company** and agentic company automation.

The core thesis is simple: a one-person company does not become scalable because of one model. It becomes scalable when agentic systems can reliably plan, use tools, operate software, coordinate multiple roles, preserve memory, verify outputs, and stay inside auditable permission boundaries.

## 📖 News

**[2026/05/30]** Initial version released with agentic automation surveys, computer-use agents, research automation, security/governance, industry signals, and legal OPC context.

## 🌟 Overview

- [📖 News](#-news)
- [🌟 Overview](#-overview)
- [🤝 Contributing](#-contributing)
- [🧭 Scope](#-scope)
- [🔥 Methods](#-methods)
  - [Agentic-LLM-Surveys](#agentic-llm-surveys)
  - [Multi-Agent-Systems](#multi-agent-systems)
  - [Computer-Use-GUI-and-OS-Agents](#computer-use-gui-and-os-agents)
  - [Research-Automation-and-Agentic-Science](#research-automation-and-agentic-science)
  - [Security-and-Governance](#security-and-governance)
- [🏢 OPC Context](#-opc-context)
  - [Industry-Reports-and-Market-Signals](#industry-reports-and-market-signals)
  - [Legal-and-Corporate-Form](#legal-and-corporate-form)
- [🧩 OPC Reading Map](#-opc-reading-map)

## 🤝 Contributing

We welcome contributions of high-signal resources through pull requests. Please see [CONTRIBUTING.md](CONTRIBUTING.md).

## 🧭 Scope

In this list, **OPC** means AI-enabled **One-Person Company** rather than only the legal form named one person company in some jurisdictions. Relevant work usually falls into one of these layers:

- **Agentic automation**: LLM agents, planning, tool use, memory, evaluation, and workflow-level autonomy.
- **Multi-agent organization**: role decomposition, collaboration protocols, coordination, and virtual teams.
- **Computer and SaaS operation**: GUI agents, browser agents, OS agents, and computer-use agents.
- **Research and knowledge work**: AI-powered research automation, scientific discovery agents, coding, analysis, and report generation.
- **Governance and safety**: human-in-the-loop control, least privilege, secrets, audit logs, and long-horizon reliability.
- **Company context**: solopreneurs, nanocorps, small-business formation, legal OPC forms, tax, liability, and corporate governance.

## 🔥 Methods

### Agentic-LLM-Surveys

| Date     | Paper Title                                                                                                                                                                       | Introduction                                                                                                          | Code |
|----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|------|
| 2025/03  | [Large Language Model Agent: A Survey on Methodology, Applications and Challenges](https://arxiv.org/abs/2503.21460)                                                             | Methodology-centered LLM agent taxonomy covering architecture, collaboration, evolution, tools, evaluation, and use cases. | [Github](https://github.com/luo-junyu/Awesome-Agent-Papers) |
| 2025/03  | [Agentic Large Language Models, a survey](https://arxiv.org/abs/2503.23037)                                                                                                      | Organizes agentic LLMs around reasoning, acting, and interacting. Useful for mapping each OPC role agent.              | - |
| 2025/04  | [From LLM Reasoning to Autonomous AI Agents: A Comprehensive Review](https://arxiv.org/abs/2504.19678)                                                                           | Reviews reasoning, benchmarks, agent frameworks, real applications, and agent collaboration protocols.                 | - |
| 2025/08  | [LLM-based Agentic Reasoning Frameworks: A Survey from Methods to Scenarios](https://arxiv.org/abs/2508.17692)                                                                   | Classifies single-agent, tool-based, and multi-agent reasoning frameworks across scientific discovery, software engineering, healthcare, social simulation, and economics. | - |
| 2025/10  | [Agentic AI: A Comprehensive Survey of Architectures, Applications, and Future Directions](https://arxiv.org/abs/2510.25445)                                                     | Surveys agentic AI architectures and argues for hybrid neural-symbolic systems in higher-risk settings.                | - |
| 2026/01  | [Agentic Reasoning for Large Language Models](https://arxiv.org/abs/2601.12538)                                                                                                  | Frames agentic reasoning as single-agent, self-evolving, and collective multi-agent reasoning.                         | - |

### Multi-Agent-Systems

| Date     | Paper Title                                                                                                                                                                      | Introduction                                                                                                      | Code |
|----------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|------|
| 2024/10  | [A Survey on LLM-based Multi-Agent Systems: Workflow, Infrastructure, and Challenges](https://link.springer.com/article/10.1007/s44336-024-00009-2)                             | Reviews LLM multi-agent workflows through profile, perception, self-action, mutual interaction, and evolution.     | - |
| 2025/01  | [Multi-Agent Collaboration Mechanisms: A Survey of LLMs](https://arxiv.org/abs/2501.06322)                                                                                      | Surveys actors, collaboration types, structures, strategies, and coordination protocols for LLM-based MAS.          | - |
| 2025/04  | [LLMs Working in Harmony: A Survey on the Technological Aspects of Building Effective LLM-Based Multi-Agent Systems](https://arxiv.org/abs/2504.01963)                          | Engineering-oriented survey of architecture, memory, planning, and frameworks for LLM-based multi-agent systems.   | - |

### Computer-Use-GUI-and-OS-Agents

| Date     | Paper Title                                                                                                                                                                      | Introduction                                                                                                      | Code |
|----------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|------|
| 2024/11  | [Large Language Model-Brained GUI Agents: A Survey](https://arxiv.org/abs/2411.18279)                                                                                           | Surveys GUI agents for visual understanding, action modeling, agent frameworks, datasets, and evaluation.           | - |
| 2025/01  | [A Comprehensive Survey of Agents for Computer Use: Foundations, Challenges, and Future Directions](https://arxiv.org/abs/2501.16150)                                            | Surveys agents that operate desktops, mobile devices, and web platforms using low-level actions such as clicks and gestures. | - |
| 2025/08  | [OS Agents: A Survey on MLLM-based Agents for General Computing Devices Use](https://arxiv.org/abs/2508.04482)                                                                  | Reviews multimodal OS-level agents that operate computers, phones, browsers, and general computing interfaces.      | - |

### Research-Automation-and-Agentic-Science

| Date     | Paper Title                                                                                                                                                                      | Introduction                                                                                                      | Code |
|----------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|------|
| 2025/08  | [From AI for Science to Agentic Science: A Survey on Autonomous Scientific Discovery](https://arxiv.org/abs/2508.14111)                                                         | Surveys autonomous scientific discovery across biology, chemistry, materials, physics, and other scientific workflows. | - |
| 2026/05  | [AutoResearch AI: Towards AI-Powered Research Automation for Scientific Discovery](https://arxiv.org/abs/2605.23204)                                                             | Moves research automation from task-level assistance to workflow-level automation with grounding, hypothesis generation, tool use, validation, and reporting. | [Project](https://mr-tieguigui.github.io/Autoresearch/) |

### Security-and-Governance

| Date     | Paper Title                                                                                                                                                                      | Introduction                                                                                                      | Code |
|----------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|------|
| 2025/06  | [A Survey on Autonomy-Induced Security Risks in Large Model-Based Agents](https://arxiv.org/abs/2506.23844)                                                                      | Surveys autonomy-induced risks such as memory poisoning, tool misuse, reward hacking, and emergent misalignment.   | - |
| 2026/04  | [A Systematic Survey of Security Threats and Defenses in LLM-Based AI Agents](https://arxiv.org/abs/2604.23338)                                                                 | Layered attack-surface survey for agentic systems covering foundation, cognition, memory, tools, multi-agent coordination, ecosystem, and governance. | - |
| 2026/05  | [When Agents Handle Secrets: A Survey of Confidential Computing for Agentic AI](https://arxiv.org/abs/2605.03213)                                                               | Reviews confidential computing and trusted execution environments for agents that hold sensitive context and credentials. | - |

## 🏢 OPC Context

### Industry-Reports-and-Market-Signals

| Date     | Resource Title                                                                                                                                                                    | Introduction                                                                                                      | Code |
|----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|------|
| 2025     | [MIT 2025 AI Agent Index](https://aiagentindex.mit.edu/)                                                                                                                         | Product and ecosystem index for AI agents across enterprise functions and workflows.                               | - |
| 2025     | [PwC AI Agent Survey 2025](https://www.pwc.com/gx/en/issues/artificial-intelligence/ai-agent-survey.html)                                                                        | Enterprise survey on AI agent adoption, ROI, governance, and organizational impact.                                | - |
| 2025     | [McKinsey: The State of AI](https://www.mckinsey.com/capabilities/quantumblack/our-insights/the-state-of-ai)                                                                     | Tracks generative and agentic AI adoption, workflow integration, risk management, and scale-up barriers.           | - |
| 2025     | [KPMG: Experiment with a zero-person company](https://kpmg.com/xx/en/our-insights/ai-and-technology/aiq/a-zero-person-company.html)                                              | Practical thought experiment on what AI agents can and cannot do when building and running a company workflow.     | - |
| 2025     | [Gusto New Business Formation and Startup Stats](https://gusto.com/company-news/new-business-formation-startup-stats)                                                            | Small-business and solopreneur formation data useful for grounding OPC market context.                             | - |
| 2026     | [Stripe Sessions 2026: Indexing the economy](https://stripe.com/en-cz/sessions/2026/indexing-the-economy)                                                                        | Industry context for smaller, faster business entities, embedded financial infrastructure, and nanocorp narratives. | - |

### Legal-and-Corporate-Form

| Date     | Paper Title                                                                                                                                                                      | Introduction                                                                                                      | Code |
|----------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|------|
| 2022     | [One Person Company and Its Role in Promotion of Entrepreneurship in India](https://ijcrt.org/papers/IJCRT22A6066.pdf)                                                           | Legal and entrepreneurship-oriented discussion of the One Person Company form under Indian company law.             | - |
| 2024     | [Legal Study on Single-Shareholder Limited Liability Companies in Indonesia](https://journal.fh.unsri.ac.id/index.php/sriwijayalawreview/article/view/2142/0)                   | Studies single-shareholder limited liability companies and their role in company-law design.                       | - |

## 🧩 OPC Reading Map

For a compact path through this list:

1. Start with **Large Language Model Agent** and **From LLM Reasoning to Autonomous AI Agents** to understand the agentic automation stack.
2. Read **Multi-Agent Collaboration Mechanisms** and **LLMs Working in Harmony** to design the virtual company team.
3. Add **Agents for Computer Use**, **GUI Agents**, and **OS Agents** when the agent must operate SaaS, browser, desktop, or mobile workflows.
4. Use **AutoResearch AI** and **Agentic Science** as examples of high-value knowledge-work automation.
5. Use the security surveys before giving agents access to real customer data, money movement, production code, email, credentials, or legal workflows.
6. Use the industry and legal resources to connect the technical stack back to actual solopreneurs, nanocorps, and one-person legal entities.
