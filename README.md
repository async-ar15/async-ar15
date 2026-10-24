<h1 align="center">Aman Rajput</h1>

<p align="center">
  Software Engineer &nbsp;|&nbsp; Distributed Systems &nbsp;|&nbsp; AI Agents &nbsp;|&nbsp; Applied ML
</p>

<p align="center">
  I build production-grade systems from scratch: message queues, LLM routers, autonomous agents, and edge AI.
</p>


[Email](mailto:iamanrajput00@gmail.com) | [LinkedIn](https://www.linkedin.com/in/aman-rajput-55a190427/) 
---

## Featured Projects

### [FalconQ](https://github.com/YOUR_USERNAME/falconq): Distributed Message Queue with Priority Delivery
`Go` `Raft` `BadgerDB` `BoltDB` `Consistent Hashing` `Gin`

- **Problem:** Critical messages stuck behind bulk traffic (Head-of-Line blocking) in message queues.
- **Role:** Designed and built the entire broker from scratch in Go.
- **Solution:** Partition-level Raft consensus, LSM storage, dual-priority engine, leader proxying.
- **Result:** ~3,200 msg/s, p99 <10ms, ~150ms failover, zero data loss on single-node failure.

### [ForgeAI](https://github.com/YOUR_USERNAME/forgeai): Adaptive LLM Inference Router
`Python` `FastAPI` `gRPC` `vLLM` `Kafka` `Redis` `Qdrant`

- **Problem:** LLM routing picks only the model, wasting cost on quantization, retrieval, and token budget.
- **Role:** Built the gateway, policy engine, and retraining loop end-to-end.
- **Solution:** LinUCB contextual bandit over 81 arms, semantic caching, gRPC microservices, hot-swappable policy.
- **Result:** Up to 72.9% lower serving cost, <5ms feature extraction, <15ms cache hits.

### [Tensor Titans](https://github.com/YOUR_USERNAME/tensor-titans): Business Entity Resolution at Scale
`Python` `LightGBM` `Numba` `NLP` `Hungarian Algorithm`

- **Problem:** Matching 2.2M multilingual business records meant ~500B naive comparisons.
- **Role:** Built the full pipeline: blocking, features, models, thresholding.
- **Solution:** Sparse inverted-index blocking, 82-feature LightGBM ensemble, context re-ranking, Expected-F0.5.
- **Result:** 0.987 leaderboard F-score, 98.9% blocking recall, zero LLM dependency.

### [MIRA](https://github.com/YOUR_USERNAME/mira): Multi-Agent Code Review System
`Python` `LangGraph` `FastAPI` `Redis` `TimescaleDB` `Gemini` `Next.js`

- **Problem:** PR reviews are a team bottleneck and vary in quality from day to day.
- **Role:** Built the platform end-to-end, from GitHub webhooks to the review dashboard.
- **Solution:** 4 parallel specialist agents, hybrid vector + keyword retrieval, confidence-gated human escalation.
- **Result:** Auto-posted line-level GitHub reviews with critical-finding escalation and full audit trail.

### [SICA](https://github.com/YOUR_USERNAME/sica): Self-Improving Autonomous Coding Agent
`Python` `Docker` `Tree-sitter` `ChromaDB` `LiteLLM`

- **Problem:** Coding assistants are open-loop: they can't run tests, keep memory, or avoid repeat mistakes.
- **Role:** Designed and built the agent along with its safety and memory layers.
- **Solution:** 8-state FSM, Architect/Worker/Judge agents, sandboxed testing, fault localization, failure memory.
- **Result:** Autonomous bug repair with circuit breakers, $0.50/task budget cap, and iteration limits.

### [VoidChat](https://github.com/YOUR_USERNAME/voidchat): Zero-Trust In-Browser Edge AI
`TypeScript` `Next.js` `WebGPU` `WebLLM` `Web Crypto` `IndexedDB`

- **Problem:** Cloud LLMs bring recurring cost, privacy risk, and no offline access.
- **Role:** Architected and built all 7 subsystems solo in TypeScript.
- **Solution:** WebGPU-powered local models, encrypted storage, tiered context engineering, thermal-aware governor.
- **Result:** Zero servers, zero API cost, 100% offline with 3.8B-8B models on consumer GPUs.

### [Synaptic Transmission](https://github.com/YOUR_USERNAME/synaptic-transmission): Autonomous AI Engineering Framework
`Node.js` `Bash` `Python` `AST Parsing` `Agent Adapters`

- **Problem:** LLM agents lose context, approve their own buggy code, and burn budget in loops.
- **Role:** Designed the framework, the quality gates, and the tooling.
- **Solution:** Disk-anchored state, maker/checker verification, computed quality gates, dependency graphing.
- **Result:** <10s cold-session recovery, vendor-agnostic across Claude, Codex, Hermes, and Cursor.

### [Markup](https://github.com/YOUR_USERNAME/markup): Visual Feedback Loop for AI Coding Agents (MCP)
`TypeScript` `Node.js` `MCP` `WebSockets` `html2canvas`

- **Problem:** AI coding agents can't see their UI output, so feedback becomes clumsy text.
- **Role:** Built the open-source MCP server and browser viewer.
- **Solution:** Live-rendered artifacts, spatial pin annotations, clustered screenshots fed back as multimodal context.
- **Result:** Agents see annotated UI directly, with ~70% fewer vision tokens than full-page captures.

---

## Technical Skills

| Category | Technologies |
|---|---|
| **Languages** | Python, Go, TypeScript, JavaScript, Bash |
| **AI / ML** | LangGraph, LightGBM, vLLM, WebLLM, ChromaDB, Contextual Bandits, MCP |
| **Backend & Infra** | FastAPI, gRPC, Kafka, Redis, Raft, Docker |
| **Data** | PostgreSQL, TimescaleDB, Qdrant, BadgerDB, SQLite |
| **Frontend** | Next.js, React, WebGPU |

---


## Contact

Open to roles and collaborations in distributed systems, AI agents, and ML engineering.

[Email](mailto:iamanrajput00@gmail.com) | [LinkedIn](https://www.linkedin.com/in/aman-rajput-55a190427/) 
