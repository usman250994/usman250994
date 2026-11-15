# Hi, I'm Usman

**Technical Lead · Agentic AI & Distributed Systems**

I've been building software for 10+ years and leading teams for the last few. I like finding the real problem before anyone starts building, and lately I spend most of my curiosity on how people and AI agents can build software together.

[Website](https://www.maanizstudio.com) · [CV](https://www.maanizstudio.com/#/cv) · [LinkedIn](https://www.linkedin.com/in/usman-ali-siddiqui/) · [Medium](https://mani9418.medium.com/)

---

## My most recent project: Cairn

**The problem.** AI coding agents forget everything between sessions, and they don't talk to each other across tools. So when my agent spends three hours on an idea that turns out to be a dead end, my teammate's agent happily walks into the same wall on Monday. Git remembers what we merged. Nothing remembers what we tried and threw away.

**The solution.** Cairn gives a team's agents a shared memory. When a piece of work is done, the agent leaves a few short notes: what was decided, what failed and why, what must never be touched. The next agent that opens the same repo starts with those notes already in hand, whether it runs in Claude Code, Cursor, GitHub Copilot or any other MCP client. Your conversations stay on your machine; only the short notes are shared.

Hikers stack stones to mark a trail for whoever comes next. Same idea, hence the name.

- Try it: [cairn.maanizstudio.com](https://cairn.maanizstudio.com)
- Install: [`@maaniz/cairn` on npm](https://www.npmjs.com/package/@maaniz/cairn)
- Status: version 1 is live and adopted by 3 startup engineering teams. The source is private for now.

<sub>Under the hood: an MCP server and CLI in TypeScript, a serverless Python API on AWS, Postgres with pgvector for search, 431 automated tests.</sub>

## How I build with agents

I run AI agents the way I'd run a small engineering team. An architect writes the spec, builders work on separate pieces in parallel, and an independent reviewer checks every change against the spec. People approve the plan and people approve the merge. Nothing ships on an agent's say-so.

It didn't start out that tidy. My first version ran in the cloud, and my "architect" agent billed me €40 before lunch for one medium-sized feature. I moved the whole thing onto my own machine, tightened who does what, and got the same quality for about a quarter of the cost. The full story, mistakes included:

[**I Hired a Robot Dev Team. My Architect Billed Me €40 Before Lunch.**](https://ai.plainenglish.io/i-hired-a-robot-dev-team-my-architect-billed-me-40-before-lunch-e3ec65706dca)

That same way of working later built Cairn: six agent roles, four human approval gates, from a written brief to production in a few weeks.

## Built, shipped and retired on purpose

**Tally** was an AI personal-finance app: track your money, set goals, and get coaching based on your real numbers. I built and shipped it on my own, with a serverless backend, encrypted data and a proper test suite. Then Claude launched a similar finance feature, and the app had no real reason to exist any more. I switched it off in 2026 and put the time into Cairn.

I don't count it as a failure. It taught me that building something well and building something people need are two different skills, and that knowing when to stop is part of the job.

## Open source

Earlier projects, built by hand to learn the fundamentals properly.

| Repo | What it is | Stack |
|---|---|---|
| [smart-system](https://github.com/usman250994/smart-system) | Ask questions about a PDF and get an answer with a confidence score, the source page, and an honest "not found" instead of a guess | Python, FastAPI, LangChain, FAISS |
| [aws-eda-saga-playground](https://github.com/usman250994/aws-eda-saga-playground) | The same workflow built twice, to compare events reacting to each other with one workflow in charge | Go, AWS EventBridge, Step Functions |
| [go-serverless-microservices](https://github.com/usman250994/go-serverless-microservices) | A layered starting point for Go services that run on AWS Lambda or locally | Go, AWS Lambda, DynamoDB |
| [MicroRentXPlatform](https://github.com/usman250994/MicroRentXPlatform) | A peer-to-peer rental backend split into services that talk over Kafka | NestJS, Kafka, Docker |

## Writing

- [I Hired a Robot Dev Team. My Architect Billed Me €40 Before Lunch.](https://ai.plainenglish.io/i-hired-a-robot-dev-team-my-architect-billed-me-40-before-lunch-e3ec65706dca)
- [I Built a RAG-Powered Smart PDF Assistant. Here's What I Learned](https://ai.plainenglish.io/i-built-a-rag-powered-smart-pdf-assistant-heres-what-i-learned-274db8b6dc48)
- [EventBridge or Step Functions? I Built Both to Find Out](https://aws.plainenglish.io/eventbridge-or-step-functions-i-built-both-to-find-out-35b11117be86)
- [Go Serverless Microservices: A Clean-Architecture Boilerplate for Go Developers](https://blog.stackademic.com/go-serverless-microservices-a-clean-architecture-boilerplate-for-go-developers-474fc1c9c792)
- [Building a Peer-to-Peer Rental Platform with Event-Driven Microservices](https://blog.stackademic.com/building-a-peer-to-peer-rental-platform-with-event-driven-microservices-open-source-8bfe4ff2032c)

More on [Medium](https://mani9418.medium.com/).

## Say hi

A GitHub profile is a snapshot, and some of this is old work. By the time you read it I've probably moved on to the next problem. If you want to know what I'm working on now, or just want to talk shop, say hi: **hello@maanizstudio.com**
