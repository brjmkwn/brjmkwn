# Hi, I'm Brij Makwana 👋

### **AI Systems & Backend Infrastructure Engineer**
Architecting production Model Context Protocol (MCP) gateways, high-throughput LLM inference systems, deterministic grammar-constrained decoding proxies, and hermetic containerized evaluation sandboxes.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Brij%20Makwana-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/brij-makwana-51506b250/)
[![Email](https://img.shields.io/badge/Email-brijmakwana6%40gmail.com-D14836?style=flat-square&logo=gmail)](mailto:brijmakwana6@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-brjmkwn-181717?style=flat-square&logo=github)](https://github.com/brjmkwn)

---

### 🚀 Flagship AI Systems Projects

| Project | Stack & Architecture | Key Measured Metric | Repository |
|---|---|---|---|
| **[mcp-control-plane](https://github.com/brjmkwn/mcp-control-plane)** | `Python`, `FastAPI`, `Streamable HTTP`, `SQLGlot`, `Redis`, `Terraform` | **Zero-Trust MCP Gateway** with SQL AST guardrails, scoped RBAC, 2-step HMAC write gate, 13 production tools & AWS serverless IaC | [🔗 Code](https://github.com/brjmkwn/mcp-control-plane) |
| **[swe-bench-verification-harness](https://github.com/brjmkwn/swe-bench-verification-harness)** | `Docker SDK`, `FastAPI`, `Linux Cgroups`, `SSE`, `Prometheus` | **88.1 ms P95** warm pool allocation, hermetic isolation (`--network none`, `cap_drop=ALL`), real-time SSE streaming | [🔗 Code](https://github.com/brjmkwn/swe-bench-verification-harness) |
| **[grammar-constrained-firewall](https://github.com/brjmkwn/grammar-constrained-firewall)** | `Python`, `FastAPI`, `PyTorch`, `interegular`, `DFAs` | **100.0% schema validity**, **1.34 ms/token P95** request time, logit masking to $-\infty$, zero retry overhead | [🔗 Code](https://github.com/brjmkwn/grammar-constrained-firewall) |
| **[speculative-inference-proxy](https://github.com/brjmkwn/speculative-inference-proxy)** | `PyTorch (CUDA)`, `FastAPI`, `Transformers`, `A100-SXM4` | **2.61x generation speedup** on A100 (34.7 $\to$ 90.7 t/s), **77.4% draft acceptance**, ITL reduced to 11.1ms | [🔗 Code](https://github.com/brjmkwn/speculative-inference-proxy) |
| **[semantic-cache-vector-gateway](https://github.com/brjmkwn/semantic-cache-vector-gateway)** | `FastAPI`, `Qdrant (Rust)`, `text-embedding-3-large`, `HNSW` | **3,072-dimensional vector search**, payload pre-filtering in HNSW graph, NVMe memory-mapped storage (Mmap) | [🔗 Code](https://github.com/brjmkwn/semantic-cache-vector-gateway) |

---

### 🛠️ Technical Primitives & Stack

* **Languages:** Python (`FastAPI`, `Asyncio`, `PyTorch`, `Pydantic v2`, `NumPy`), SQL (`PostgreSQL`, `pgvector`), Bash
* **AI & Agent Infrastructure:** Model Context Protocol (MCP), Speculative Decoding, Deterministic FSM Logit Masking (`interegular`), Semantic Caching, HNSW Vector Search
* **Systems, Security & Cloud:** Linux Kernel Sandboxing (Rootless Docker, Cgroups), Redis (Sliding-Window Rate Limiting), Qdrant Vector DB, AWS Serverless IaC (Terraform, Lambda, API Gateway), Prometheus Telemetry, Server-Sent Events (SSE)
* **Core CS Fundamentals:** Data Structures & Algorithms, Distributed Systems, Operating Systems, Compilers & Automata

---

📬 **Contact:** [brijmakwana6@gmail.com](mailto:brijmakwana6@gmail.com) | [LinkedIn](https://www.linkedin.com/in/brij-makwana-51506b250/)
