# 📚 Research & Literature

This folder serves as the **theoretical core** of the `graph-rigor` project. It contains a curated selection of academic papers that define the benchmarks, failure modes, and reasoning architectures used to evaluate LLMs in formal Graph Theory.

---

## 🏗️ Core Research Pillars

### 1. Reasoning Topologies

* **Chain-of-Thought (CoT):** Foundation for step-by-step logic.
* **Tree of Thoughts (ToT):** Strategies for backtracking and systematic exploration.
* **Graph of Thoughts (GoT):** Non-linear reasoning for complex dependencies.

### 2. State-Tracking & Rigor

* **Algorithmic Faithfulness:** Papers investigating if LLMs actually "reason" or just predict the next most likely node.
* **Traceability Metrics:** Frameworks for auditing intermediate steps in iterative algorithms (Dijkstra/Prim).

### 3. Structural Properties

* **Isomorphism & Planarity:** Research on identifying global graph invariants through natural language and tuple-based inputs.

---

## 📑 Document Index

| Filename | Key Contribution | Relevancy |
| --- | --- | --- |
| `got_reasoning.pdf` | Graph of Thoughts framework | Used for **Strategy C** |
| `nl_graph_bench.pdf` | Natural Language Graph Benchmarking | Basis for data generation |
| `trace_audit_llm.pdf` | Faithfulness in reasoning steps | Core of our **Traceability Score** |

---

## 🛠️ Usage

* **Theoretical Validation:** Use these papers to justify the selection of specific prompting templates.
* **Code Alignment:** The logic in `src/evaluators/` is built directly upon the definitions found in these documents.

> **Note:** These files are for internal research. Please cite the original authors in any formal reports or publications.

---
