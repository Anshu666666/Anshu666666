<h2>
  Hi, I'm <a href="https://github.com/Anshu666666" target="_blank">Anshuman</a>
  <img src="https://media.tenor.com/-Y7FM7VQEOAAAAAj/phoenix.gif" width="55px" alt="Fire Phoenix">
</h2>

<p>
  <b>CS Undergrad at <a href="https://www.iiitkottayam.ac.in/">IIIT Kottayam</a></b> &amp; <b>Lead, App Development Subclub at BetaLabs</b>.
</p>

<p>
  Previously <b>AI Engineering Intern</b>, building <b>multi-agent analytics frameworks in LangGraph</b>, 
  production LLM evaluation pipelines, and observability infrastructure.
</p>

<p>
  I enjoy building <b>agentic AI infrastructure, distributed systems, and storage engines</b> — exploring how systems work under the hood, from low-level LSM tree internals to real-time event streaming pipelines.
</p>

---

## ⚡ What I Work On

- **AI & Agent Infrastructure**: LangGraph, LangChain, DeepAgents, supervisor agent orchestration, evaluation harnesses, deterministic tool execution
- **Distributed Systems & Concurrency**: Multithreading, atomic primitives, race condition diagnosis, distributed locking, idempotency guarantees
- **Storage Engine Internals & Data Engineering**: LSM Trees (WAL, MemTable, SSTables, Bloom Filters), write amplification trade-offs, Change Data Capture (CDC), zero-loss replication
- **High-Performance Backend & Networking**: FastAPI, REST APIs, WebSockets, connection pooling, backpressure handling, rate limiting
- **Reliability & System Design**: Circuit breakers, exponential backoff with jitter, dead-letter queues (DLQ), telemetry, p95/p99 latency profiling

---

## 🚀 Featured Projects

<table>
  <tr>
    <td width="33%" valign="top">
      <h3 align="center">
        <a href="https://github.com/Anshu666666/TransactFlow">TransactFlow</a>
      </h3>
      <p align="center">
        <b>Enterprise CDC Streaming Pipeline</b>
      </p>
      <p align="center">
        <code>C++17</code> <code>Kafka</code> <code>Debezium</code> <code>PostgreSQL</code> <code>Redis</code> <code>Elasticsearch</code> <code>Docker</code>
      </p>
      <ul>
        <li>Real-time WAL change data capture ingesting <b>1,000+ req/s</b> with <b>zero data loss</b> across 216k+ soak events.</li>
        <li>High-throughput <b>C++ consumer workers</b> with manual offsets, exponential retries, and <b>DLQ</b> poison message isolation.</li>
        <li>Atomic Lua-scripted <b>LSN monotonicity guards</b> in Redis ensuring sub-millisecond cache consistency.</li>
      </ul>
      <p align="center">
        <a href="https://github.com/Anshu666666/TransactFlow"><b>View Repository →</b></a>
      </p>
    </td>
    <td width="33%" valign="top">
      <h3 align="center">
        <a href="https://github.com/Anshu666666/FlashDB">FlashDB</a>
      </h3>
      <p align="center">
        <b>Embedded LSM-Tree Storage Engine</b>
      </p>
      <p align="center">
        <code>C++20</code> <code>CMake</code> <code>Google Benchmark</code> <code>Python</code>
      </p>
      <ul>
        <li>Embedded Log-Structured Merge Key-Value engine built from scratch with zero database dependencies.</li>
        <li>Decoupled <b>WAL</b>, in-memory <b>MemTable</b>, immutable <b>SSTables</b>, and <b>Size-Tiered Compaction</b>.</li>
        <li>Probabilistic <b>Bloom Filters</b> delivering a <b>~68x–85x read speedup</b> on cache misses.</li>
      </ul>
      <p align="center">
        <a href="https://github.com/Anshu666666/FlashDB"><b>View Repository →</b></a>
      </p>
    </td>
    <td width="33%" valign="top">
      <h3 align="center">
        <a href="https://github.com/Anshu666666/deepTrade">DeepTrade</a>
      </h3>
      <p align="center">
        <b>Agentic Market & Trading Assistant</b>
      </p>
      <p align="center">
        <code>Python</code> <code>FastAPI</code> <code>LangGraph</code> <code>DeepAgents</code> <code>Upstox API</code> <code>Supabase</code>
      </p>
      <ul>
        <li>Self-hosted autonomous assistant orchestrating specialized research and broker execution subagents.</li>
        <li>Live/paper order execution on Upstox via Telegram with TOTP two-factor security.</li>
        <li>Upstream contributor: reported 2 critical bugs in official <b>Upstox Python SDK</b> (<a href="https://github.com/upstox/upstox-python/issues/155">#155</a>, <a href="https://github.com/upstox/upstox-python/issues/156">#156</a>).</li>
      </ul>
      <p align="center">
        <a href="https://github.com/Anshu666666/deepTrade"><b>View Repository →</b></a>
      </p>
    </td>
  </tr>
</table>

---

## ⚙️ Core Engineering & System Design

- **Concurrency & Thread Safety**: Mutexes, condition variables, lock contention analysis, atomic operations, race-condition mitigation, and memory lifecycle management.
- **Distributed Reliability & Fault Tolerance**: Idempotent message consumers, distributed rate-limiting (Token Bucket / Leaky Bucket), retry storm protection with exponential backoff & jitter, and Dead-Letter Queue (DLQ) patterns.
- **Storage Mechanics & Access Patterns**: LSM-tree design (sequential append-only logging vs random read penalties), in-memory MemTables, immutable SSTables, probabilistic membership testing with Bloom Filters, and atomic Lua-scripted cache transactions.
- **Network Transport & API Design**: Connection pooling, HTTP/REST state contracts, persistent WebSocket streaming, backpressure control, and payload serialization optimization.

---

## 🛠️ Tech Stack

### Languages

<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=cpp,py,ts,js,c" />
  </a>
</p>

### Backend & AI

<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=fastapi,nodejs,express,supabase" />
  </a>
</p>

### Databases & Streaming

<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=postgres,kafka,redis,elasticsearch,mongodb,mysql" />
  </a>
</p>

### Infrastructure & DevOps

<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=docker,kubernetes,linux,github,cmake" />
  </a>
</p>

### Frontend

<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=react,nextjs,vite,tailwind" />
  </a>
</p>

---

## 🧠 Skills

- **AI & Agent Architecture:** LangGraph, LangChain, DeepAgents, Multi-Agent Systems, LLM Evaluation, Observability, RAG
- **Core Systems & Concurrency:** Multithreading, Thread Pools, Mutexes & Locks, Race Condition Triage, Memory Management (RAII, Pointers)
- **Distributed Systems & Streaming:** Apache Kafka, Debezium (CDC), Redis, Elasticsearch, Idempotency, Circuit Breakers, Dead-Letter Queues (DLQ)
- **Storage Engines & Databases:** LSM Trees, Write-Ahead Logs (WAL), SSTables, Bloom Filters, PostgreSQL, MySQL, Redis (Lua Scripting)
- **Backend & Networking:** FastAPI, Node.js, Express, REST APIs, WebSockets, Rate Limiting, Connection Pooling, Supabase
- **Infrastructure & Tools:** Docker, Kubernetes, Linux (POSIX, Bash), GitHub, CMake, Google Benchmark, VS Code

---

## 📊 GitHub Activity

<p>
  <img
    src="https://github-readme-stats-eight-theta.vercel.app/api?username=Anshu666666&show_icons=true&theme=github_dark&hide_border=true"
    alt="GitHub Stats"
  />
</p>

<p>
  <img
    src="https://fabianocouto-activity-graph.vercel.app/graph/?username=Anshu666666&theme=react-dark&hide_border=true"
    alt="Contribution Graph"
  />
</p>

---

## 📫 Let's Connect

<p align="left">
  <a href="mailto:anshuproductions@gmail.com">
    <img src="https://img.shields.io/badge/Email-%23333?style=for-the-badge&logo=gmail&logoColor=red">
  </a>
  <a href="https://www.linkedin.com/in/anshuman-biswas-iiitk/">
    <img src="https://img.shields.io/badge/LinkedIn-%23333?style=for-the-badge&logo=linkedin&logoColor=blue">
  </a>
  <a href="https://github.com/Anshu666666/Anshu666666/blob/main/resume.tex" target="_blank">
    <img src="https://img.shields.io/badge/Resume-LaTeX-%23333?style=for-the-badge&logo=latex&logoColor=white">
  </a>
</p>
