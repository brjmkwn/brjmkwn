# Hi, I'm Brij Makwana 👋

### **AI Engineer | GenAI, Agentic Systems (LangGraph, MCP) & Backend**
Building governed Model Context Protocol (MCP) gateways, sandboxed agent evaluation harnesses, deterministic grammar-constrained decoding firewalls, and CI-tested full-stack AI backends.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Brij%20Makwana-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/brijmakwana/)
[![Email](https://img.shields.io/badge/Email-brijmakwana6%40gmail.com-D14836?style=flat-square&logo=gmail)](mailto:brijmakwana6@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-brjmkwn-181717?style=flat-square&logo=github)](https://github.com/brjmkwn)

---

### 🚀 Flagship AI Systems Projects

| Project | Stack & Architecture | Architectural Primitives & Measured Metrics | Repository |
|---|---|---|---|
| **[mcp-control-plane](https://github.com/brjmkwn/mcp-control-plane)** | `Python`, `FastAPI`, `Streamable HTTP`, `PostgreSQL (pgvector)`, `SQLGlot`, `Redis`, `Docker`, `Terraform` | **Zero-Trust MCP Gateway** with SQLGlot AST read-only guards, scoped Bearer RBAC, 2-step HMAC write gate, 13 tools, 68 passing pytest tests, 28.3 ms P95 / 46.4 req/s, 100.0% SQLi block rate, and CI-validated AWS Terraform IaC | [🔗 Code](https://github.com/brjmkwn/mcp-control-plane) |
| **[swe-bench-verification-harness](https://github.com/brjmkwn/swe-bench-verification-harness)** | `Docker SDK`, `FastAPI`, `Linux Cgroups`, `SSE`, `Prometheus` | **88.1 ms P95** warm pool allocation, hermetic security isolation (`--network none`, `cap_drop=ALL`), real-time SSE streaming | [🔗 Code](https://github.com/brjmkwn/swe-bench-verification-harness) |
| **[grammar-constrained-firewall](https://github.com/brjmkwn/grammar-constrained-firewall)** | `Python`, `FastAPI`, `PyTorch`, `interegular`, `DFAs` | **100.0% schema validity**, **1.34 ms/token P95** request time, logit masking to $-\infty$, zero retry overhead | [🔗 Code](https://github.com/brjmkwn/grammar-constrained-firewall) |
| **[speculative-inference-proxy](https://github.com/brjmkwn/speculative-inference-proxy)** | `PyTorch`, `FastAPI`, `Transformers`, `CUDA` | **OpenAI-compatible speculative decoding proxy** pairing draft & target models with unbiased rejection sampling, dynamic KV-cache sync, and Prometheus telemetry | [🔗 Code](https://github.com/brjmkwn/speculative-inference-proxy) |
| **[semantic-cache-vector-gateway](https://github.com/brjmkwn/semantic-cache-vector-gateway)** | `FastAPI`, `Qdrant (Rust)`, `text-embedding-3-large`, `HNSW` | **3,072-dimensional vector search**, payload pre-filtering in HNSW graph, NVMe memory-mapped storage (Mmap) | [🔗 Code](https://github.com/brjmkwn/semantic-cache-vector-gateway) |

---

### 🛠️ Technical Primitives & Stack

* **GenAI & Agentic AI:** LangGraph, Model Context Protocol (MCP, Streamable HTTP), FastMCP, Hybrid RAG (BM25, RRF, FlashRank), Deterministic FSM Logit Masking (`interegular`), PyTorch
* **Backend & Web:** Python (`FastAPI`, `Asyncio`, `Pydantic`), TypeScript, Next.js, React, Tree-sitter, `sqlglot`, Streamlit
* **Data, Observability & Infra:** PostgreSQL (`pgvector`), Redis, ChromaDB, Qdrant, Docker (Linux cgroups), Terraform (AWS), Prometheus, LangSmith, Server-Sent Events (SSE)
* **Testing & CI:** `pytest`, Ruff, Black, GitHub Actions, GitLab CI

---

📬 **Contact:** [brijmakwana6@gmail.com](mailto:brijmakwana6@gmail.com) | [LinkedIn](https://www.linkedin.com/in/brijmakwana/)
