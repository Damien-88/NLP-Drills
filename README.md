# NLP & Computational Linguistics Engineering Rotation

This repository tracks a rigorous, continuous training loop designed to sharpen hands-on engineering skills across modern NLP architecture, information retrieval (IR), and traditional computational linguistics. 

Operating on a **3-day-a-week schedule (Tuesday to Thursday)**, this repository serves as an active laboratory. Once a full 4-week cycle completes, the rotation resets back to Week 1, utilizing fresh, progressively complex datasets and advanced edge-case variations of the same core mechanics. Each daily 30–60 minute practical drill balances "from-scratch" algorithmic implementation with production-level pipeline optimization.

## Rotational Curriculum Overview

### Week 1: Production Data & Retrieval Foundations
Focuses on the engineering backbone of language systems—handling structured data ingestion, building high-throughput cleaning pipelines, and coding foundational lexical retrieval strategies.
* **Tuesday:** Text Parsing & Structured Info Extraction (JSON/Pydantic schema enforcement)
* **Wednesday:** Information Retrieval (Pure NumPy implementations of TF-IDF vs. BM25 vs. Dense Vectors)
* **Thursday:** High-Throughput Data Cleaning & Parallelized PII Anonymization

### Week 2: Evaluation, Scaling & Tokenization
Transitions from basic text pipelines to automated performance assessment, model optimization, and processing raw characters into machine-readable subwords.
* **Tuesday:** Automated Pipeline Evaluation (ROUGE, BLEU, F1, & LLM-as-a-Judge frameworks)
* **Wednesday:** Inference Optimization (Batching metrics, Quantization via GGUF/AWQ, & Token-Caching)
* **Thursday:** Custom Subword Tokenization (Implementing Byte Pair Encoding from scratch)

### Week 3: Semantics, Syntax & Hidden Markov Models
Dives into structural linguistics, distributional vector mechanics, and sequential dynamic programming algorithms.
* **Tuesday:** Distributional Semantics & Alignment (Tracking semantic shifts using static GloVe/Word2Vec vectors)
* **Wednesday:** Sequence Labeling & Dynamic Programming (The Viterbi Algorithm for Hidden Markov Models)
* **Thursday:** Local Transformer Inference (Token classification and POS/NER tagging using local encoder models)

### Week 4: Language Modeling & Graph Mechanics
Explores the statistical mechanics of prediction, information-theoretic evaluation metrics, and production-scale vector indexing.
* **Tuesday:** Statistical Language Modeling (Building character/word-level N-Gram models from scratch)
* **Wednesday:** Model Evaluation via Information Theory (Calculating text corpus Perplexity metrics)
* **Thursday:** Vector Databases & Graph Mechanics (Hierarchical Navigable Small World (HNSW) approximations)


## Project Structure
Drills are organized into chronological modules. As rotations repeat, successive iterations are saved with incremental versioning tags (e.g., `v1`, `v2`) within their respective focus directories:

```text
├── Week_001_Data-Retrieval/
│   ├── Day_001_Extraction/
│   │   ├── v1_ollama_pydantic.ipynb
│   │   └── ...
│   ├── Day_002_ir-scratch/
│   │   ├── v1_numpy_tfidf_bm25.ipynb
│   │   └── ...
│   ├── Day_003_pii_anonymizer/
│   │   ├── v1_parallel_cleaner.ipynb
│   │   └── ...
├── Week_002_Eval_Tokenization/
│   ├── Day_001_extraction/
│   │   ├── v1_ollama_pydantic/
│   │   └── ...
│   ├── Day_002_ir-scratch/
│   │   ├── ...
│   │   └── ...
│   ├── Day_003_pii_anonymizer/
│   │   ├── ...
│   │   └── ...
├── Week_003_Semantics_Syntax/
│   ├── Day_001_extraction/
│   │   ├── ...
│   │   └── ...
│   ├── Day_002_ir-scratch/
│   │   ├── ...
│   │   └── ...
│   ├── Day_003_pii_anonymizer/
│   │   ├── ...
│   │   └── ...
└── Week_004_Modeling_Graphs/
│   ├── Day_001_extraction/
│   │   ├── ...
│   │   └── ...
│   ├── Day_002_ir_scratch/
│   │   ├── ...
│   │   └── ...
│   ├── Day_003_pii_anonymizer/
│   │   ├── ...
└── └── └── ...
Start Over with v2, then v3, etc.