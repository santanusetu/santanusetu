# Hi, I'm Santanu

Software engineer building real-time distributed systems, backend platforms, and AI infrastructure.

Backend & platform | Real-time systems | Agentic AI & MCP | Observability | Java | Python | Go

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white) ![AI](https://img.shields.io/badge/AI-Agents_%26_MCP-5A3FC0?style=flat) ![Observability](https://img.shields.io/badge/Observability-Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)

I've spent 10+ years building systems that run inline, where being slow or wrong is felt right away. Most of that has been on a real-time decisioning platform used by 1,000+ banks, working inside a 100-millisecond budget. I care about correctness under load, making failures visible early, and turning repeated work into tools other teams can pick up on their own.

## What I work on

- ⚡ **Real-time backend services** - low-latency APIs and rule services in Java and Spring Boot, with heavier work like analytics kept off the hot path.
- 🤖 **AI infrastructure** - MCP servers that give agents permission-scoped access to production data, and agentic workflows with validation gates.
- 🔭 **Observability** - metrics, tracing and alerting that show problems in hours instead of weeks.
- 🧩 **Full-stack platforms** - React and TypeScript front ends, including large migrations done without downtime.

## Selected work

- 🔌 **Enterprise MCP server** - rule, KPI and reporting data exposed to AI agents as permission-scoped tools; adopted by 6 teams. Container cut from over 5 GB to about 500 MB with zero CVEs.
- 🛡️ **Agentic remediation framework** - approved fix patterns plus an agentic workflow with a validation gate; closed 130 of 130 security findings, with its patterns now standard across 40+ repositories.
- ⚙️ **Rule platform modernization** - rule lookup went from 8 minutes to 12 seconds across 800+ active rules.
- 📈 **Observability platform** - coverage across 8.34M+ monthly requests; detection of missed SLAs went from 3 weeks to under a day.
- 🧱 **Frontend migration** - 85+ pages moved from Angular to React micro-frontends with zero production incidents.

*This was internal work, so there's no code to link. I'm always happy to walk through the design and the trade-offs.*

## Open source

- 🧭 [claude-skills](https://github.com/santanusetu/claude-skills) - small, tested Claude Code skills. First one: **session-finder**, which finds a past session and resumes it in 1 click.
- 🛡️ [AI Commit Guardrails](https://github.com/santanusetu/ai-commit-guardrails) - AI commit assistant that catches secrets in staged changes and redacts them before the LLM sees anything, then writes the commit message. Java, tested in CI.
- 🐞 [SpotBugs #4354](https://github.com/spotbugs/spotbugs/pull/4354) - **merged** fix for an `OS_OPEN_STREAM` false positive in the Java static analyzer: closing a wrapper stream now counts as closing the stream it wraps.

## How I like to work

- Measure before building. The right fix often comes from checking what's actually happening first.
- Make it repeatable. Once a problem shows up a few times, the job is to build the tool, not fix it again.
- Keep things reviewable. Small, boring changes ship; clever ones sit in a queue.

## Recognition

- 🎓 Guest Lecturer, Stanford University (2×, 2025–2026)
- 📄 Co-author, [*Monitoring Fraudulent Transactions at Merchant Level in Real Time Payment*](https://www.tdcommons.org/dpubs_series/4761/), TD Commons 2021

## Get in touch

I'm open to conversations about backend and platform engineering, real-time systems, and AI infrastructure.

[Portfolio](https://santanusetu.github.io) · [LinkedIn](https://www.linkedin.com/in/santanu16) · [santanu.setu@gmail.com](mailto:santanu.setu@gmail.com)
