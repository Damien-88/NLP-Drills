# NLP & Computational Linguistics Engineering Rotation

This repository tracks a rigorous, continuous training loop designed to sharpen hands-on engineering skills across \
modern NLP architecture, information retrieval (IR), and traditional computational linguistics. 

Operating on a **3-day-a-week schedule (Tuesday to Thursday)**, this repository serves as an active laboratory. Once a \
full 4-week cycle completes, the rotation resets back to Week 1, utilizing fresh, progressively complex datasets and \
advanced edge-case variations of the same core mechanics. Each daily 30–60 minute practical drill balances \
"from-scratch" algorithmic implementation with production-level pipeline optimization.

## Rotational Curriculum Overview

### Week 1: Production Data & Retrieval Foundations
Focuses on the engineering backbone of language systems, handling structured data ingestion, coding lexical retrieval \
strategies, and building rule-based morphological analyzers.
* **Tuesday:** Text Parsing & Structured Info Extraction (JSON/Pydantic schema enforcement)
* **Wednesday:** Information Retrieval (Pure NumPy implementations of TF-IDF vs. BM25 vs. Dense Vectors)
* **Thursday Old:** High-Throughput Data Cleaning & Parallelized PII Anonymization
* **Thursday New:** Finite-State Morphology & Text Processing (Implementing Finite State Transducers, Stemmers, & \
    Regex engines)

### Week 2: Evaluation, Scaling & Tokenization
Transitions from basic text pipelines to automated performance assessment, model optimization, and processing raw \
characters into machine-readable subwords.
* **Tuesday:** Automated Pipeline Evaluation (ROUGE, BLEU, F1, & LLM-as-a-Judge frameworks)
* **Wednesday:** Inference Optimization (Batching metrics, Quantization via GGUF/AWQ, & Token-Caching)
* **Thursday:** Custom Subword Tokenization (Implementing Byte Pair Encoding from scratch)

### Week 3: Semantics, Syntax & Hidden Markov Models
Dives into structural linguistics, distributional vector mechanics, and sequential dynamic programming algorithms.
* **Tuesday:** Distributional Semantics & Alignment (Tracking semantic shifts using static GloVe/Word2Vec vectors)
* **Wednesday:** Sequence Labeling & Dynamic Programming (The Viterbi Algorithm for Hidden Markov Models)
* **Thursday Old:** Local Transformer Inference (Token classification and POS/NER tagging using local encoder models)
* **Thursday New:** Formal Parsing & Syntactic Structure (Implementing CYK parsing from scratch)

### Week 4: Language Modeling & Graph Mechanics
Explores the statistical mechanics of prediction, information-theoretic evaluation metrics, and production-scale vector \
indexing.
* **Tuesday:** Statistical Language Modeling (Building character/word-level N-Gram models from scratch)
* **Wednesday:** Model Evaluation via Information Theory (Calculating text corpus Perplexity metrics)
* **Thursday:** Vector Databases & Graph Mechanics (Hierarchical Navigable Small World (HNSW) approximations)


## Project Structure
Drills are organized into chronological modules. As rotations repeat, successive iterations are saved with incremental \
versioning tags (e.g., `v1`, `v2`) within their respective focus directories:

```text
├── Week_1_Data_Retrieval_FiniteState/
│   ├── Day_1_Data_Extraction/
│   │   ├── v1_ollama_pydantic.ipynb
│   │   ├── v2_...
│   │   └── v3_...
│   ├── Day_2_ir-scratch/
│   │   ├── v1_numpy_tfidf_bm25.ipynb
│   │   ├── v2_...
│   │   └── v3_...
│   ├── Day_3_fsa_morphology/
│   │   ├── v1_parallel_cleaner.ipynb
│   │   ├── v2_fst_morph_analyzer.ipynb
│   │   └── v3_...
├── Week_2_Eval_Tokenization/
│   ├── Day_4_evaluation/
│   │   ├── v1_pipeline_evaluation.ipynb/
│   │   ├── v2_...
│   │   └── v3_...
│   ├── Day_5_optimization/
│   │   ├── v1_inference_opt.ipynb
│   │   ├── v2_...
│   │   └── v3_...
│   ├── Day_6_tokenization/
│   │   ├── v1_bpe_tokenizer.ipynb
│   │   ├── v2_...
│   │   └── v3_...
├── Week_3_Semantics_Syntax_Parsing/
│   ├── Day_7_semantics/
│   │   ├── v1_vector_alignment.ipynb
│   │   ├── v2_...
│   │   └── v3_...
│   ├── Day_8_sequence_labeling/
│   │   ├── v1_viterbi_tagger.ipynb
│   │   ├── v1_local_encoder.ipynb
│   │   ├── v2_...
│   │   └── v3_...
│   ├── Day_9_formal_parsing/
│   │   ├── v1_statistical_weighting.ipynb
│   │   ├── v2_cyk_parser.ipynb
│   │   └── v3_...
└── Week_4_Modeling_Lexicons_Graphs/
│   ├── Day_10_language_modeling/
│   │   ├── v1_ngram_model.ipynb
│   │   ├── v2_ngram_wordnet_similarity.ipynb
│   │   └── v3_...
│   ├── Day_11_perplexity/
│   │   ├── v1_perplexity_eval.ipynb
│   │   ├── v2_...
│   │   └── v3_...
│   ├── Day_12_hnsw_graphs/
│   │   ├── v1_hnsw_scratch.ipynb
│   │   ├── v2_...
└── └── └── v3_...
Start Over with v2, then v3, etc.