<p align="center">
  <img src="./assets/banner.svg" alt="weiqiang - Backend-grounded Agent Developer and Researcher" width="100%" />
</p>

<h2 align="center">weiqiang · Backend-grounded Agent Developer & Researcher</h2>

<p align="center">
  I focus on building agent systems with real backend engineering behind them: clear domain boundaries,
  durable workflow state, reliable tool use, retrieval grounding, evaluation, and failure recovery.
</p>

<p align="center">
  Currently exploring how AI Agents move from demos into production-grade applications.
</p>

<p align="center">
  <a href="https://github.com/weiqiang612/Personal-CRM-Intelligent-Contact-Management-Platform">Personal CRM</a> ·
  <a href="https://github.com/weiqiang612/sky-take-out">Sky Take Out</a> ·
  <a href="https://github.com/weiqiang612/project-sky-admin-vue-ts">Admin Web</a> ·
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

## What I'm Building Toward

I want `weiqiang` to represent a practical direction: **agent applications that are grounded in backend systems, not just prompt demos**.

My current exploration is around:

- Agent workflows that can be represented as explicit, recoverable state machines
- Tool-calling systems with permission checks, confirmations, retries, and audit trails
- RAG pipelines that connect documents, domain data, and user intent in a maintainable way
- Evaluation loops that test whether an agent did the right thing, not only whether it returned text
- Product integration patterns for bringing agent capability into real CRM, admin, and automation workflows

## Engineering Foundation

| Area | Focus |
| --- | --- |
| Backend | Java, Spring Boot, MyBatis / MyBatis-Plus, REST APIs, JWT, domain-oriented service design |
| Data | MySQL transactions and indexing, Redis caching and consistency, Elasticsearch basics |
| Agent / AI | RAG, tool calling, workflow orchestration, context assembly, evaluation, OpenAI-compatible APIs |
| Frontend | Vue 3, Vite, TypeScript, Pinia, Element Plus, ECharts |
| Deployment | Docker Compose, Linux, Nginx, environment configuration, public demo delivery |
| Engineering Practice | Documentation-driven development, code review, test planning, system design notes |

## Selected Work

| Project | Why it matters |
| --- | --- |
| [Personal CRM Intelligent Contact Management Platform](https://github.com/weiqiang612/Personal-CRM-Intelligent-Contact-Management-Platform) | My main full-stack product practice: contacts, reminders, activity timeline, dashboard, avatar upload, deployment, and a Contact Agent with query and confirmed write actions. Public demo: `crm.weiqiang.me` |
| [Sky Take Out](https://github.com/weiqiang612/sky-take-out) | Backend business-flow practice around ordering, store operations, service layers, MySQL, and Redis |
| [Project Sky Admin Vue TS](https://github.com/weiqiang612/project-sky-admin-vue-ts) | Admin-side frontend practice for operational management workflows |
| [Ethan Notes](https://github.com/weiqiang612/Ethan_Notes) | Long-term engineering notes for Java, MySQL, Redis, system design, and backend interview preparation |
| [Bagu Basecamp](https://github.com/weiqiang612/bagu-basecamp) | A study workflow base for structured review and AI-assisted preparation |

## Agent Productionization Map

<p align="center">
  <img src="./assets/agent-architecture.svg" alt="Agent productionization architecture map" width="100%" />
</p>

## Current Research Questions

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
