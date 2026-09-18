<!--
**usman250994/usman250994** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->

<h1 align="center">👋 Hi, I'm Usman Ali Siddiqui</h1>

<h3 align="center">Technical Lead — Agentic AI Engineering & Distributed Systems</h3>

<p align="center">🇩🇪 Germany · 10+ years across FinTech, HealthCare & startups · MSc Computer Science (AI)</p>

<p align="center">
  <a href="https://www.linkedin.com/in/usman-ali-siddiqui-744585132/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://mani9418.medium.com/"><img src="https://img.shields.io/badge/Medium-000000?logo=medium&logoColor=white" alt="Medium"></a>
  <a href="https://maanizstudio.com"><img src="https://img.shields.io/badge/maanizstudio.com-FF5A5F?logo=googlechrome&logoColor=white" alt="Website"></a>
  <a href="https://github.com/usman250994"><img src="https://img.shields.io/github/followers/usman250994?label=Followers&style=social" alt="GitHub followers"></a>
</p>

---

> 🤖 *"I hired an AI dev team. My architect billed me €40 before lunch."*
> That's the true story of how I ended up designing a multi-agent pipeline that now writes and reviews code for my own team. [Read it →](https://ai.plainenglish.io/i-hired-a-robot-dev-team-my-architect-billed-me-40-before-lunch-e3ec65706dca)

## 🧭 About me

I'm a technical lead and distributed-systems engineer — the person who ends up owning architecture, the hard trade-off calls, and the "why did this break at 3am" conversations. These days that means:

- 🏗️ **Leading** — sole technical decision-maker on one team, stepping into tech-lead duties on another; requirements, architecture, delivery, hiring, all of it.
- 🤖 **Building agentic AI systems** — not chat wrappers. Stateful multi-agent pipelines (LangGraph) with typed contracts, human-in-the-loop checkpoints, and cost discipline, running against real production code.
- ✍️ **Writing** — I publish what actually happened, including the parts that cost money or went sideways, on [Medium](https://mani9418.medium.com/).
- 🧑‍🏫 **Mentoring** — code reviews, architecture discussions, technical interviewing; I'd rather grow a team than be the only person who understands the system.
- 🔧 **Still shipping, when time permits** — solo-built two consumer apps end-to-end because the best way to trust an architecture opinion is to ship it yourself.

## ⚡ Right now

**Technical Lead @ Arbeitly** *(reverse-recruiting startup, part-time alongside my full-time role)*
- Sole technical decision-maker for a 4-person engineering team; inherited a tangled codebase and re-architected it into something new features can actually land on — now used daily by 100+ users across Europe & the UK
- Built a fail-fast CI/CD pipeline (GitHub Actions: tests + coverage/quality gates on every PR, isolated staging/production) — cut rollback/recovery time on bad deploys by **~90%**
- Introduced OpenTelemetry + Dash0 observability — production downtime down from ~twice a month to under once
- Rolled out my own multi-agent orchestrator as the team's real development workflow — throughput up **~40%**, with a human still accountable for every merge

**Senior Software Engineer @ WS Audiology**
- Own a core microservice on a global hearing-device fitting platform (~20,000 fitting sessions/month), built with DDD, EDA and state machines
- Step in as technical lead during absences; represent the team in cross-team architecture reviews
- Introduced AI-assisted, spec-driven development (custom Copilot workflows) — now the team's default, used by 20+ engineers

## 🧪 Testers wanted

I'm running two of my own products in a **closed/private environment** and looking for a small group of real testers:

- 💰 **Tally** — an AI personal-finance coach: track spending, set goals, get coaching that's grounded in your actual numbers, not generic tips.
- ⏱️ **168** — a mobile-first app for logging where your week's 168 hours actually go.

Both are real, running infrastructure — not mockups. If you want in on the closed beta, ping me on [LinkedIn](https://www.linkedin.com/in/usman-ali-siddiqui-744585132/).

## 🚀 Things I've actually shipped

| | Project | What it does | Stack |
|---|---|---|---|
| 🤖 | **Multi-Agent Orchestrator** *(private — [write-up](https://ai.plainenglish.io/i-hired-a-robot-dev-team-my-architect-billed-me-40-before-lunch-e3ec65706dca))* | Three agent personas — architect, developer, reviewer — turn a GitHub issue into a reviewed, mergeable PR. Typed agent contracts, human approval at spec and merge. Now my team's real workflow. | LangGraph · Python · GitHub Actions |
| 💰 | **Tally** *(private — [maanizstudio.com](https://maanizstudio.com))* | AI-powered personal finance coach. Solo-designed and shipped to production in ~2 months: 11 features, serverless AWS backend, natural-language financial insights. | React Native · Go · AWS (Lambda, Cognito, DynamoDB) · OpenAI |
| ⏱️ | **168 / Weekly** *(private — [maanizstudio.com](https://maanizstudio.com))* | Mobile-first hour-tracking app — where did your week actually go? Live in dev as an installable PWA, full CI/CD and coverage gates. | Expo (React Native + Web) · Go · AWS CDK |
| 📄 | **[smart-system](https://github.com/usman250994/smart-system)** | Upload a PDF, ask a question in plain English, get an answer grounded in the document — with a confidence score, source page, and an honest "not found" instead of a guess. | Python · FastAPI · LangChain · FAISS |
| ☁️ | **[aws-eda-saga-playground](https://github.com/usman250994/aws-eda-saga-playground)** | The same workflow built two ways, side by side: EventBridge choreography vs. Step Functions orchestration. | AWS EventBridge · Step Functions |
| 🐹 | **[go-serverless-microservices](https://github.com/usman250994/go-serverless-microservices)** | Clean-architecture Go boilerplate for serverless AWS microservices — JWT auth, DynamoDB, OpenSearch, Lambda-ready. | Go · AWS Lambda |
| 🏠 | **[MicroRentXPlatform](https://github.com/usman250994/MicroRentXPlatform)** | Event-driven peer-to-peer rental platform boilerplate — secure BFF gateway, polyglot persistence. | NestJS · Kafka · Docker |

🔒 A few of these are private (client/product work), so the code isn't public — but I've written up how they're built. Legal/privacy pages for the live apps are public too: [tally-legal](https://github.com/usman250994/tally-legal) · [weekly-legal](https://github.com/usman250994/weekly-legal).

## 📝 Writing

- 🤖 [I Hired a Robot Dev Team. My Architect Billed Me €40 Before Lunch.](https://ai.plainenglish.io/i-hired-a-robot-dev-team-my-architect-billed-me-40-before-lunch-e3ec65706dca)
- 📄 [I Built a RAG-Powered Smart PDF Assistant — Here's What I Learned](https://ai.plainenglish.io/i-built-a-rag-powered-smart-pdf-assistant-heres-what-i-learned-274db8b6dc48)
- ☁️ [EventBridge or Step Functions? I Built Both to Find Out](https://aws.plainenglish.io/eventbridge-or-step-functions-i-built-both-to-find-out-35b11117be86)
- 🐹 [Go Serverless Microservices: A Clean-Architecture Boilerplate for Go Developers](https://blog.stackademic.com/go-serverless-microservices-a-clean-architecture-boilerplate-for-go-developers-474fc1c9c792)
- 🏠 [Building a Peer-to-Peer Rental Platform with Event-Driven Microservices](https://blog.stackademic.com/building-a-peer-to-peer-rental-platform-with-event-driven-microservices-open-source-8bfe4ff2032c)

More on [Medium →](https://mani9418.medium.com/)

## 🛠️ Tech I work in

**Agentic AI & LLM**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-4B8BBE?logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?logo=anthropic&logoColor=white)

**Languages & Frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?logo=nestjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React%20Native-61DAFB?logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)

**Cloud & Data (AWS-first)** — the services actually behind Tally, 168, and the boilerplates above

*Compute & delivery*

![AWS Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&labelColor=232F3E)
![API Gateway](https://img.shields.io/badge/API%20Gateway-FF9900?style=flat-square&labelColor=232F3E)
![AWS CDK](https://img.shields.io/badge/CDK-FF9900?style=flat-square&labelColor=232F3E)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)

*Auth, orchestration & messaging*

![Cognito](https://img.shields.io/badge/Cognito-FF9900?style=flat-square&labelColor=232F3E)
![Step Functions](https://img.shields.io/badge/Step%20Functions-FF9900?style=flat-square&labelColor=232F3E)
![EventBridge](https://img.shields.io/badge/EventBridge-FF9900?style=flat-square&labelColor=232F3E)
![SES](https://img.shields.io/badge/SES-FF9900?style=flat-square&labelColor=232F3E)
![Kafka](https://img.shields.io/badge/Kafka-231F20?logo=apachekafka&logoColor=white)

*Data & storage*

![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&labelColor=232F3E)
![S3](https://img.shields.io/badge/S3-FF9900?style=flat-square&labelColor=232F3E)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&labelColor=CC2927)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?logo=graphql&logoColor=white)

**Architecture**

Domain-Driven Design · Event-Driven Architecture · Saga Pattern · Microservices · Multi-Agent Orchestration

## 📈 GitHub stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=usman250994&show_icons=true&theme=tokyonight" alt="usman250994's GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=usman250994&layout=compact&theme=tokyonight" alt="usman250994's top languages" />
</p>

---

### 💡 Philosophy

> "Abstract complexity, deliver value — and if an AI agent can do the boring 90%, spend the saved time mentoring someone or writing down what you learned."

## ✨ Let's connect

- 💼 [LinkedIn](https://www.linkedin.com/in/usman-ali-siddiqui-744585132/) — professional journey, always open to a conversation
- ✍️ [Medium](https://mani9418.medium.com/) — how things actually got built
- 🌐 [maanizstudio.com](https://maanizstudio.com) — portfolio, CV, and the apps I've shipped
- 🧪 Closed beta for Tally & 168 — DM me on LinkedIn if you want in
