<div align="center">

# Vibhanshu Dutt

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1500&color=58A6FF&center=true&vCenter=true&width=720&lines=Backend+%26+Distributed-Systems+Engineer;Java+%E2%80%A2+Python+%E2%80%A2+Kafka+%E2%80%A2+Redis+%E2%80%A2+Neo4j;Building+Local-First+Multi-Agent+AI+Labs)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/vibhanshu05)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:vibhanshu.0511@gmail.com)
[![Bangalore](https://img.shields.io/badge/Bangalore,%20India-2EA44F?style=flat-square&logo=googlemaps&logoColor=white)](#)
[![Open to roles](https://img.shields.io/badge/Open%20to-Backend%20%2F%20Platform%20%2F%20SDE%20roles-blueviolet?style=flat-square)](mailto:vibhanshu.0511@gmail.com)

</div>

---

## About

Backend & distributed-systems engineer at **Vimaan** - 2 years building event-driven Python microservices that orchestrate health checks, event triggering, and accuracy validation across **12+ microservices** in production. **IIT Madras Dual Degree, 2024.**

Threads I'm pulling on right now:

- **Distributed systems** - Kafka, Redis, Neo4j, PostgreSQL: the messy production parts of building reliable services.
- **DSA/programming** - trying to build habit of finding patterns, writing my own tricks, backed by a personal **200+ card DSA Mastery Map** spanning every pattern, tricks I've shipped, debugged, or interviewed on.
- **Local-first AI** - multi-agent simulations and system-design copilots running on Ollama. No API quotas, no rate limits, just a laptop and a hypothesis. Using Aquarium to run social experiments, explore discussions, and understand how agents behave under different scenarios.
- **System Design** - Learning about **HLD** to help my peers solving production level issue and to optimize the systems

## Turning Ideas into Execution

### [aquarium-for-mirofish](https://github.com/vibhu-0511/aquarium-for-mirofish)

> *Most multi-agent simulations either let agents lie freely (no verification) or lock them into rigid scripts (no emergence). Neither captures how real social systems behave.*

An experimentation lab built on **MiroFish-Offline** — adds claim verification, persistent agent memory, robustness scoring, and a pluggable LLM backend. Lets you stress-test a society of agents the way you'd stress-test a distributed system.

| | |
|---|---|
| **Stack** | Python · MiroFish · Local LLMs (Ollama) · Multi-agent orchestration |
| **Features** | Claim verification layer · Agent memory store · Robustness scoring · Swappable LLM backend |
| **Impact** | Reproducible offline social simulations — zero API cost, zero rate limits |

---

### RootScope

> *Engineers waste hours retracing the same incident across Jira, Confluence, and GitLab. Search is keyword-based; debugging is semantic.*

Concurrent ingestion pipeline indexing **Jira, Confluence, and GitLab** into a vector DB, fronted by a **ReAct agent** that does cascading multi-source search for automated root-cause analysis.

| | |
|---|---|
| **Stack** | Python · FastAPI · LangChain · pgvector · PostgreSQL · Elasticsearch · asyncio |
| **Features** | Concurrent multi-source ingestion · Semantic + keyword cascade · ReAct loop · REST API |
| **Impact** | **−30% mean time-to-debug** for engineering teams |

---

### InfraDesk

> *Self-serve infra without governance is chaos. Governance without self-serve is a ticket queue. The platform should handle both.*

Role-based **server provisioning platform** with multi-stage approval workflows, OAuth2 RBAC, Kafka-driven notifications, and a real-time WebSocket metrics dashboard.

| | |
|---|---|
| **Stack** | Java · Spring Boot · Kafka · WebSocket · OSHI · OAuth2 |
| **Features** | Multi-stage approvals · Kafka event-driven alerts · Live CPU/memory dashboard via OSHI |
| **Impact** | Monitors **25+ servers** with full audit trail |

---

### [hld-architect-copilot](https://github.com/vibhu-0511/hld-architect-copilot)

> *System-design interviews and real outages ask the same question — can you spot the bottleneck before it bites? But there's no gym for it. You read post-mortems, then forget them.*

A browser-based system-design playground. Practice architecting real systems, replay famous outages, hunt bugs in deliberately flawed designs, run capacity numbers — grounded in a curated **255-note system-design vault**.

| | |
|---|---|
| **Stack** | JavaScript · Browser-first (no backend) · Static deploy |
| **Features** | Outage replay · Flawed-design bug hunts · Capacity calculators · 255-note design vault |
| **Impact** | Turns passive post-mortem reading into active interview prep — works offline |

<!-- [Live Demo](https://vibhu-0511.github.io/hld-architect-copilot) — uncomment after deploy -->

---

