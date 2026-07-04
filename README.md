<p align="center">
  <img src="./assets/banner.svg" alt="weiqiang - Backend-grounded Agent Developer and Researcher" width="100%" />
</p>

<h2 align="center">weiqiang · Backend-grounded Agent Developer & Researcher</h2>

<p align="center">
  <a href="./README.md"><strong>English</strong></a> ·
  <a href="./README.zh-CN.md">简体中文</a>
</p>

<p align="center">
  Weiqiang means "wall" in Chinese. I use it as a reminder to look at the walls worth crossing.
</p>

<p align="center">
  Building agent systems with real backend engineering behind them: domain boundaries,
  durable workflow state, reliable tool use, retrieval grounding, evaluation, and failure recovery.
</p>

<p align="center">
  Currently exploring how AI Agents move from demos into production-grade applications.
</p>

<p align="center">
  <a href="https://github.com/weiqiang612/Personal-CRM-Intelligent-Contact-Management-Platform">Personal CRM</a> ·
  <a href="https://github.com/weiqiang612/Ethan_Notes">Engineering Notes</a>
</p>

<p align="center">
  <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img alt="Spring Boot" src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img alt="Redis" src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img alt="Vue" src="https://img.shields.io/badge/Vue-42B883?style=for-the-badge&logo=vuedotjs&logoColor=white" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
</p>

## Why "weiqiang"?

`weiqiang` means "wall" in Chinese.

I did not choose this name to build a wall.

The name reminds me that every era creates new walls. They may come from technology, knowledge, or information asymmetry.

I believe valuable technology should not become a privilege for a few people. It should help more people cross those thresholds.

**weiqiang focuses on the walls that need to be crossed.**

## What I'm Building Toward

I want `weiqiang` to represent a practical direction: **agent applications grounded in backend engineering, not just prompt demos**.

My current focus is Agent productionization:

- Representing agent workflows as explicit, recoverable state machines
- Designing tool-calling systems with permission checks, confirmations, retries, and audit trails
- Connecting RAG pipelines with documents, domain data, and user intent
- Evaluating whether an agent completed the right task, not only whether it returned fluent text
- Integrating agent capability into real CRM, admin, and automation workflows

## Engineering Foundation

| Area | Focus |
| --- | --- |
| Backend | Java, Spring Boot, MyBatis / MyBatis-Plus, REST APIs, JWT, domain-oriented service design |
| Data | MySQL transactions and indexing, Redis caching and consistency, Elasticsearch basics |
| Agent / AI | RAG, tool calling, workflow orchestration, context assembly, evaluation, OpenAI-compatible APIs |
| Frontend | Vue 3, Vite, TypeScript, Pinia, Element Plus, ECharts |
| Deployment | Docker Compose, Linux, Nginx, environment configuration, public demo delivery |
| Practice | Documentation-driven development, code review, test planning, system design notes |

## Main Direction

| Project | Positioning |
| --- | --- |
| [Personal CRM Intelligent Contact Management Platform](https://github.com/weiqiang612/Personal-CRM-Intelligent-Contact-Management-Platform) | My main full-stack product and Agent landing practice. It includes contact management, reminders, activity timeline, dashboard, deployment, and a Contact Agent with query and confirmed write actions. Public demo: `crm.weiqiang.me` |
| [Ethan Notes](https://github.com/weiqiang612/Ethan_Notes) | My long-term engineering knowledge base for Java, MySQL, Redis, system design, and Agent-related learning notes |
| [Bagu Basecamp](https://github.com/weiqiang612/bagu-basecamp) | A structured review base for backend fundamentals and AI-assisted study workflows |

## Practice Series

The Sky projects are practice projects. They helped me build backend and frontend engineering fundamentals, but they are not the main Agent direction.

| Series | Repositories | What I practiced |
| --- | --- | --- |
| Sky Take Out | [Backend](https://github.com/weiqiang612/sky-take-out) · [Admin Web](https://github.com/weiqiang612/project-sky-admin-vue-ts) · [Mini Program](https://github.com/weiqiang612/sky-take-out-mini-program) | Ordering business flows, store operations, admin UI, mini-program workflow, MySQL, Redis, and full-stack coordination |

## Agent Productionization Map

<p align="center">
  <img src="./assets/agent-architecture.svg" alt="Agent productionization architecture map" width="100%" />
</p>

## Research Questions

- How should an agent remember state without hiding critical control flow?
- Where should permission checks, user confirmations, and rollback paths live?
- How can RAG be evaluated against real domain tasks instead of generic Q&A?
- What belongs in deterministic backend code, and what should be delegated to the model?
- How can agent behavior be made observable enough for debugging and review?

## Principles

- Backend systems are the control plane; agents are one capability inside them
- Prefer explicit state, typed contracts, and audit trails over implicit prompt behavior
- Treat tool calling as a production workflow with permissions, validation, and recovery
- Keep documentation close to implementation so design decisions stay inspectable
- Build small working loops first, then expand the agent's authority gradually
