<div align="center">

# Hey, I'm Digvijay 👋

### Open-source engineer · Cloud Native · AI Systems · Linux

[GitHub](https://github.com/Digvijay-x1) · [LinkedIn](https://www.linkedin.com/in/digvijay-singh-rawat/) · [Email](mailto:work@digvijayrawat.me)

</div>

> I like software that is easy to reason about, hard to break, and pleasant to operate.

I build systems across **cloud-native infrastructure, distributed software, AI/LLM applications, developer tooling, and Linux**. I care less about collecting frameworks and more about understanding what happens underneath them: failure modes, performance, concurrency, observability, and the boundaries between components.

## What I work on

```text
Distributed systems     →   concurrency, queues, storage, networking
Cloud Native             →   Kubernetes, containers, Linux, observability
AI / LLM systems         →   agents, structured output, evaluation, safety
Developer infrastructure →   CI/CD, automation, testing, tooling
Application engineering  →   APIs, full-stack systems, real-time software
```

## Featured work

### 🛰️ [UyuniAI](https://github.com/Digvijay-x1/UyuniAI)
**Evidence-driven AI monitoring and root-cause analysis for Uyuni.**

A Google Summer of Code 2026 project for openSUSE. The system combines Prometheus telemetry, bounded read-only Uyuni/Salt diagnostics, deterministic evidence checks, and an LLM investigation path to produce structured incident analysis. The design deliberately **fails closed**: weak, stale, contradictory, or unsupported evidence is reported as inconclusive instead of being turned into a confident guess.

**Focus:** observability · RCA · LangGraph · Prometheus · Salt · Alertmanager · reliability

### 🔎 [IGI](https://github.com/Digvijay-x1/IGI)
**A distributed search engine built from the ground up.**

IGI combines a C++ crawler/indexer, a Python BM25 ranking layer, and a Ruby interface, backed by components such as RocksDB and Redis. It explores the whole search pipeline rather than treating search as a black box: crawling, storage, indexing, ranking, caching, and serving.

**Focus:** C++ · distributed systems · information retrieval · RocksDB · Redis

### 👁️ [ClaimLens](https://github.com/Digvijay-x1/ClaimLens)
**AI-powered visual evidence review for damage claims.**

ClaimLens combines claim conversations, submitted images, user history, a vision-language ensemble, and deterministic post-processing to produce an explainable verdict. Its evaluation set intentionally includes adversarial cases such as wrong-object submissions, severity exaggeration, stock imagery, and prompt injection hidden inside images.

**Focus:** VLMs · Python · async pipelines · evaluation · trustworthy AI

### 🎬 [GenAI Video Platform](https://github.com/Digvijay-x1/GenAI-Video-Platform)
**An end-to-end generative video product.**

A full-stack system covering avatar generation, voice cloning/TTS, multilingual video translation with lip-sync, background GPU workloads, job orchestration, authentication, credits, and a web dashboard.

**Focus:** FastAPI · Next.js · Modal · Inngest · AI media pipelines

## Open-source, beyond my own repos

I also spend a lot of time working upstream rather than only building isolated projects.

| Ecosystem | What I've worked on |
|---|---|
| **openSUSE / Uyuni** | reliability fixes, SSL/certificate diagnostics, FQDN verification, UX fixes, documentation, dependency/security updates |
| **openSUSE / Open Build Service** | validation hardening, malformed-input handling, crash fixes, race-condition handling, and performance improvements |
| **Rage** | WebSocket stream lifecycle APIs and OpenAPI-related work in a modern Ruby backend framework |
| **Talawa** | GraphQL/DataLoader performance work, cache invalidation, test coverage, developer tooling, and rootless container development |
| **CNCF ecosystem** | contributions across Koordinator, Volcano, Chaos Mesh, and KubeEdge |
| **Observability tooling** | Superlog tests, CI, telemetry utilities, and reliability-focused changes |

That work has taught me an important lesson: **a good patch is not just code that works locally; it is code that fits the architecture, survives edge cases, and is easy for the next engineer to trust.**

## Engineering principles

- **Evidence over vibes.** Measure behavior, then make claims.
- **Fail safely.** A system should degrade predictably instead of silently lying.
- **Make failure observable.** Logs, metrics, tests, and diagnostics are part of the feature.
- **Keep boundaries sharp.** Small interfaces make large systems easier to evolve.
- **Test the ugly paths.** The interesting bugs usually live in malformed input, retries, races, partial failures, and unexpected state.
- **Prefer simpler operations.** Fewer moving parts usually means fewer ways to break production.

## Toolbox

**Languages**

`C++` · `Rust` · `Python` · `Ruby` · `Go` · `TypeScript` · `JavaScript`

**Infrastructure**

`Linux` · `Docker` · `Kubernetes` · `Prometheus` · `Grafana` · `OpenTelemetry` · `GitHub Actions`

**Systems & data**

`PostgreSQL` · `Redis` · `RocksDB` · `REST` · `GraphQL` · `WebSockets`

**Application stack**

`Next.js` · `React` · `FastAPI` · `Rails` · `Node.js`

## A few things I enjoy building

```text
Something starts as a rough idea.
        ↓
Model the problem.
        ↓
Build the smallest real system.
        ↓
Measure it.
        ↓
Break it on purpose.
        ↓
Fix the failure mode.
        ↓
Document what actually works.
        ↓
Ship it.
```

## Explore

The repositories below are only a snapshot. I keep experiments, production-oriented work, open-source contributions, and learning projects in public, so the best way to see what I'm doing now is to browse the full repository list.

**[→ Browse all public repositories](https://github.com/Digvijay-x1?tab=repositories)**

---

> “Building large software remains hard. And it always will, because our ambition will forever outstrip the metal.”

<div align="center">

**Build things. Break things. Understand why they broke.**

</div>
