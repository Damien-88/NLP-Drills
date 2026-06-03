# NLP & Computational Linguistics Engineering Rotation

This repository tracks a rigorous, two-week rotational curriculum designed to sharpen hands-on engineering skills across modern NLP architecture, information retrieval (IR), and traditional computational linguistics. Each day features a targeted 30–60 minute practical drill balancing "from-scratch" algorithmic implementation with production-level pipeline optimization.

## 🗓️ Curriculum Overview

### Week 1: Core Mechanics & Retrieval Architecture
Focuses on the engineering backbone of modern language systems—handling data ingestion, high-throughput pipelines, and vector/lexical retrieval strategies.
* **Tuesday:** Text Parsing & Structured Info Extraction (JSON/Pydantic schemas)
* **Wednesday:** Information Retrieval (NumPy implementations of TF-IDF vs. BM25 vs. Embeddings)
* **Thursday:** High-Throughput Data Cleaning & Parallelized PII Anonymization
* **Friday:** Automated Pipeline Evaluation (ROUGE, BLEU, F1, & LLM-as-a-Judge frameworks)
* **Saturday:** Inference Optimization (Batching, Quantization via GGUF/AWQ, & Token-Caching)

### Week 2: Advanced Linguistics & Statistical Modeling
Dives into the foundational mathematics, syntactic rules, and statistical mechanics that govern how language is modeled.
* **Tuesday:** Custom Subword Tokenization (Byte Pair Encoding from scratch)
* **Wednesday:** Distributional Semantics & Alignment (Static vector semantic shifts)
* **Thursday:** Sequence Labeling (Viterbi Algorithm for HMMs & Local Transformer POS-Tagging)
* **Friday:** Statistical Language Modeling (N-Grams & Perplexity evaluation)
* **Saturday:** Vector Databases & Graph Mechanics (HNSW approximations & Chunking logic)

## 🛠️ Project Structure
Each drill is contained within its own self-contained directory containing the core logic, execution script, and a micro-corpus for testing:
```text
├── week-1-retrieval/
│   ├── day-1-extraction/
│   ├── day-2-ir-scratch/
│   └── ...
└── week-2-linguistics/
    ├── day-1-bpe-tokenizer/
    └── ...