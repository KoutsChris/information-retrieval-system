# Information Retrieval System - Lexical, Semantic & Hybrid Search

End‑to‑end information retrieval system built on a corpus of 18k documents using BM25, transformer embeddings and hybrid ranking.

## Overview
This project implements three retrieval approaches:
- **Lexical Search (BM25)**
- **Semantic Search (Sentence‑Transformers embeddings + FAISS)**
- **Hybrid Search (weighted fusion of lexical + semantic scores)**

The goal is to compare ranking quality across methods using standard IR metrics.

## Key Features
- Custom analyzers, tokenization and preprocessing for BM25
- Embedding generation using all‑MiniLM‑L6‑v2
- FAISS vector index for fast similarity search
- Hybrid ranking with score normalization and weighted fusion
- Evaluation with MAP, Precision@k and ranking stability analysis

## Tech Stack
Python, Pandas, NumPy, Scikit‑learn, FAISS, Sentence‑Transformers, Elasticsearch

## Project Files
- `lexical_search.ipynb` - BM25 implementation  
- `semantic_search.ipynb` - embedding-based retrieval  
- `hybrid_search.ipynb` - fusion of lexical + semantic scores  

### Reports
- `lexical_report.pdf` - analysis & results for lexical search  
- `semantic_report.pdf` - analysis & results for semantic search  
- `hybrid_report.pdf` - analysis & results for hybrid search


## How to Run
Open any notebook:
jupyter notebook lexical_search.ipynb
