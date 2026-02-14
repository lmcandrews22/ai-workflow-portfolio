# RAG Chunking Experiments (n8n + Pinecone + OpenAI)

This project explores how chunking strategy influences retrieval behavior and answer quality in a Retrieval-Augmented Generation (RAG) pipeline.

---

## System Components

The workflows implement a simple end-to-end RAG system using:

- n8n for orchestration  
- OpenAI embeddings for vectorization  
- Pinecone for vector storage and retrieval  
- Custom evaluator logic for attribution and context utilization  

---

## Objective

Evaluate whether reducing chunk size materially affects:

- Retrieval quality  
- Answer correctness  
- Context efficiency  

---

## Experiment Design

Two chunking strategies were compared on the same AWS reference corpus:

| Variant | Chunk Size | Overlap |
|--------|------------|---------|
| Baseline | 1200 | 200 |
| Variant | 600 | 100 |

---

## Key Findings

- Chunk size had minimal impact on answer correctness for this dataset  
- Smaller chunks introduced more variability in retrieved context  
- Corpus structure influenced behavior more than chunk size alone  


