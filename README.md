# Ashley Luo

**NYU M.S. in Computer Science, 2026 · Distributed systems, databases, and applied AI**

I build systems that connect transaction processing, storage, and reliable AI. I am seeking software engineering roles where I can work on backend infrastructure and AI systems.

## Current research

- **Machine unlearning for shared LLM systems:** investigating how to remove targeted knowledge while preserving the usefulness of shared models.
- **Deterministic replication and transaction processing (Go):** my experimental system reached **310K transactions per second**, with **zero ledger inconsistencies observed in the evaluated runs**. These are experimental results for that system, separate from the C++ Caracal/Felis fork below.
- **Caracal/Felis (C++):** adapting an upstream deterministic concurrency-control system to CloudLab d710, repairing distributed builds, and extending multi-node YCSB experiments.
- **LLM evaluation:** building reproducible checks for grounded answers, tool-use behavior, fallback paths, and guardrails. PawPal+ includes an offline evaluation harness and a model card documenting limitations.

## Selected public work

| Project | What I contributed | Stack |
| --- | --- | --- |
| [Caracal / Felis](https://github.com/luoashley/felis) | CloudLab d710 adaptation, non-PIE distributed builds, and multi-node YCSB benchmarking in a research fork | C++, Linux, CloudLab |
| [DuckDB storage engine](https://github.com/luoashley/duckdb-lsm) | DuckDB/Badger integration with hash-partitioned key-value storage, versioned records, and batched writes | Go, DuckDB, SQL |
| [PawPal+](https://github.com/luoashley/applied-ai-system-project) | RAG-grounded assistant with Claude tool use, scheduling, guardrails, and reproducible offline evaluation | Python, Streamlit, Claude |

## Tools I use

**Languages:** Go, C++, Python, Java, SQL, TypeScript/JavaScript  
**Systems:** DuckDB, Badger, Linux, Docker, Kubernetes, AWS  
**AI:** LLM orchestration, retrieval-augmented generation, tool calling, evaluation  
**Observability:** Prometheus, Grafana, Loki

## Contact

[Email](mailto:jl11703@nyu.edu) · [GitHub](https://github.com/luoashley)
