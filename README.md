### Jose Hidalgo

**Senior Full-Stack Engineer** — distributed systems & software architecture in Java, Scala, and Angular.
Nashville, TN · US-remote.

Six-plus years building production distributed systems and enterprise web applications where the domain
model comes first: microservices with real bounded contexts, CQRS and event sourcing where they earn
their keep, and messaging (Akka Persistence & Streams, Dapr) rather than shared databases. Most of my
production work has been in **energy & utilities, IoT / device platforms, and logistics** — domains
where ingest volume, eventual consistency, and operational visibility are the actual engineering
problems, not incidental ones.

I also ship frontends (Angular and React on TypeScript) and desktop apps, and after years of
client-facing consultancy I'm comfortable being the person who explains the architecture to
non-engineers.

**Currently:** based in Nashville, TN and open to **Senior Backend / Full-Stack** roles, US-remote.
US citizen — no sponsorship required.

<p>
  <a href="https://jhidalgo.dev/cv"><img src="https://img.shields.io/badge/CV-jhidalgo.dev-BD93F9?style=for-the-badge&logo=googlechrome&logoColor=white" alt="CV"/></a>
  <a href="https://www.linkedin.com/in/jhidalgopalacios/"><img src="https://img.shields.io/badge/LinkedIn-jhidalgopalacios-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://medium.com/@johidalgo04"><img src="https://img.shields.io/badge/Medium-@johidalgo04-12100E?style=for-the-badge&logo=medium&logoColor=white" alt="Medium"/></a>
</p>

---

### Master's thesis — Command Event Query Separation

My MSc thesis (JAMK, 2025) validated **CEQS**, an architectural framework by Simo Roikonen that
extends CQRS and Clean Architecture by treating events as first-class architectural citizens. Using
Design Science Research, I built the first working reference implementation of the framework — a
Kotlin microservices system — and analysed where event-centric modelling helped and where it added
cost.

> **[Command Event Query Separation, A Framework for Modeling Scalable Services](https://urn.fi/URN:NBN:fi:amk-2025090124304)** — Hidalgo, Jose (2025), JAMK University of Applied Sciences

The implementation is public: [**blcms-ceqs**](https://github.com/kurohige/blcms-ceqs).

---

### Selected work

| Project | What it is | Stack |
|---|---|---|
| [**blcms-ceqs**](https://github.com/kurohige/blcms-ceqs) | Reference implementation for the CEQS thesis. Event-sourced aggregates, two bounded contexts, cross-service event bus, API gateway with circuit breaking. | Kotlin · http4k · Cassandra · Pulsar · PostgreSQL · Docker |
| [**mappoc-scala-vs-go**](https://github.com/kurohige/mappoc-scala-vs-go) | Architecture spike: rendering and operating a 1–10M device fleet on a live map. Two parallel implementations over identical infrastructure, plus a k6 load-test harness. | Scala 3 · Pekko HTTP · Go · Dapr · PostGIS · ClickHouse |
| [**ABPlayer**](https://github.com/kurohige/ABPlayer) | Desktop audiobook player. Chapter-aware M4B streaming, Web Audio signal chain, multi-window. Shipped, versioned releases. | Rust · Tauri v2 · Svelte 5 · TypeScript |
| [**BdoLifeCompanion**](https://github.com/kurohige/BdoLifeCompanion-Pub) | Desktop companion app with real users across 20+ releases. Session analytics, spatial route planning, offline data model. | Rust · Tauri · Svelte 5 · TypeScript |
| [**envOptimizerMMO**](https://github.com/kurohige/envOptimizerMMO) | Windows tuning toolkit with topology-aware CPU pinning. Every tweak documented with its evidence and its downside. | PowerShell |

---

### Stack

**Backend** — Java, Scala, Spring Boot, Akka (Streams, Persistence), Play, Lagom, http4s, Node.js
**Architecture** — DDD, CQRS, event sourcing, microservices, gRPC, GraphQL, Dapr, REST
**Frontend** — Angular, React, React Native, TypeScript, Tailwind
**Data** — PostgreSQL, MongoDB Atlas, Cassandra, Elasticsearch, Redis
**Cloud & delivery** — Google Cloud Platform, Azure, Docker, CI/CD

---

<sub>Most of my recent commits are in private repositories — happy to walk through any of it in a conversation.</sub>
