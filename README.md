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

<p align="left">
  <a href="https://github.com/Anshu666666/Anshu666666/blob/main/Anshuman_Resume.pdf" target="_blank">
    <img src="https://img.shields.io/badge/Resume_(PDF)-ED2224?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Resume PDF">
  </a>
  <a href="https://www.linkedin.com/in/anshuman-biswas-iiitk/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
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

## 🌐 Open Source Contributions

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">
        <a href="https://github.com/quantumlib/Cirq">Google Quantum AI (Cirq)</a>
      </h3>
      <p align="center">
        <b>Core Developer Infrastructure &amp; Release Tooling</b>
      </p>
      <p align="center">
        <a href="https://github.com/quantumlib/Cirq/pull/8379" target="_blank">
          <img src="https://img.shields.io/badge/PR_%238379-Merged-8957e5?style=flat-square&logo=github&logoColor=white" alt="PR #8379">
        </a>
        <img src="https://img.shields.io/badge/CI-44%2F44_Passed-2ea44f?style=flat-square&logo=githubactions&logoColor=white" alt="CI Passed">
        <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
      </p>
      <ul>
        <li>Refactored developer release pipeline architecture and relative path hierarchies to standardize dev onboarding across the core repository.</li>
        <li>Completed Google CLA verification and collaborated directly with Google Quantum AI software engineers (<b>Michael Hucka</b>, <b>Pavol Juhas</b>) through code review to immediate merge.</li>
      </ul>
      <p align="center">
        <a href="https://github.com/quantumlib/Cirq/pull/8379"><b>View Pull Request →</b></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">
        <a href="https://github.com/munich-quantum-toolkit/bench">Munich Quantum Toolkit (TUM)</a>
      </h3>
      <p align="center">
        <b>Quantum Algorithms &amp; Compiler Benchmarking (MQT Bench)</b>
      </p>
      <p align="center">
        <a href="https://github.com/munich-quantum-toolkit/bench/pull/1037" target="_blank">
          <img src="https://img.shields.io/badge/PR_%231037-Merged-8957e5?style=flat-square&logo=github&logoColor=white" alt="PR #1037">
        </a>
        <img src="https://img.shields.io/badge/Qiskit-2.5+-613380?style=flat-square&logo=qiskit&logoColor=white" alt="Qiskit">
        <img src="https://img.shields.io/badge/CI-Green-2ea44f?style=flat-square&logo=githubactions&logoColor=white" alt="CI">
      </p>
      <ul>
        <li>Engineered scalable <b>Superdense Coding</b> communication benchmark (Bennett &amp; Wiesner, 1992) to evaluate circuit compilation and entanglement distribution across modular Bell pairs.</li>
        <li>Diagnosed and resolved a Qiskit 2.5+ target-independent compiler optimization anomaly where commutation passes collapsed entangling <b>CX</b> gates; introduced pair-local barriers to guarantee protocol workload retention.</li>
        <li>Constructed end-to-end regression suites with <code>StatevectorSampler</code> verifying full fidelity across all 2-bit permutations, actively triaged with TUM maintainers (<b>Dr. Lukas Burgholzer</b>, <b>Simon Hofmann</b>).</li>
      </ul>
      <p align="center">
        <a href="https://github.com/munich-quantum-toolkit/bench/pull/1037"><b>View Pull Request →</b></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">
        <a href="https://github.com/tenuo-ai/tenuo">Tenuo AI</a>
      </h3>
      <p align="center">
        <b>Agent Capability Authorization &amp; Testing Infrastructure</b>
      </p>
      <p align="center">
        <a href="https://github.com/tenuo-ai/tenuo/pull/716" target="_blank">
          <img src="https://img.shields.io/badge/PR_%23716-Merged-8957e5?style=flat-square&logo=github&logoColor=white" alt="PR #716">
        </a>
        <img src="https://img.shields.io/badge/CI-70%2F70_Passed-2ea44f?style=flat-square&logo=githubactions&logoColor=white" alt="CI Passed">
        <img src="https://img.shields.io/badge/CrewAI-1.5--1.15-FF6F61?style=flat-square" alt="CrewAI">
      </p>
      <ul>
        <li>Engineered the official quickstart architecture and test suite for the CrewAI <code>GuardedCrew</code> builder, enforcing role-based tool policies, argument regex constraints, and strict post-kickoff audit detection.</li>
        <li>Implemented an offline deterministic LLM double to run reproducible test runs without provider API keys; established cross-version compatibility across CrewAI 1.5–1.15 in the CI matrix.</li>
      </ul>
      <p align="center">
        <a href="https://github.com/tenuo-ai/tenuo/pull/716"><b>View Pull Request →</b></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">
        <a href="https://github.com/doobidoo/mcp-memory-service">MCP Memory Service</a>
      </h3>
      <p align="center">
        <b>Security Hardening &amp; Log Sanitization Infrastructure</b>
      </p>
      <p align="center">
        <a href="https://github.com/doobidoo/mcp-memory-service/pull/1308" target="_blank">
          <img src="https://img.shields.io/badge/PR_%231308-Merged-8957e5?style=flat-square&logo=github&logoColor=white" alt="PR #1308">
        </a>
        <img src="https://img.shields.io/badge/CI-14%2F14_Passed-2ea44f?style=flat-square&logo=githubactions&logoColor=white" alt="CI Passed">
        <img src="https://img.shields.io/badge/MCP-Protocol-4A90E2?style=flat-square" alt="MCP">
      </p>
      <ul>
        <li>Mitigated log injection vulnerabilities across configuration modules by migrating eager f-strings to lazy parameterized logging (<code>%</code>-formatting).</li>
        <li>Enforced static security boundaries by integrating configuration layers into <code>GUARDED_MODULES</code> regression suites.</li>
      </ul>
      <p align="center">
        <a href="https://github.com/doobidoo/mcp-memory-service/pull/1308"><b>View Pull Request →</b></a>
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
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://www.linkedin.com/in/anshuman-biswas-iiitk/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://github.com/Anshu666666/Anshu666666/blob/main/Anshuman_Resume.pdf" target="_blank">
    <img src="https://img.shields.io/badge/Resume_(PDF)-ED2224?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Resume PDF">
  </a>
</p>
