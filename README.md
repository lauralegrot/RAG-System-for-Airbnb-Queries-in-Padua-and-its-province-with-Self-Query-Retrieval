# RAG System for Airbnb Queries in Padua and its province with Self Query Retrieval 🏠🛏️

## Project description 
* **Built a Retrieval-Augmented Generation (RAG) system to answer Airbnb-related queries** by grounding LLM responses in reviews, house rules, and structured metadata 
* **Collected and processed a custom dataset (12,867 texts from 112 listings) via web scraping**, including metadata-driven filtering (capacity, amenities, policies, superhost status)
* Compared naive semantic retrieval with **self-query retrieval**, using **LLaMA-2 (13B)** to automatically extract metadata from user queries and reduce hallucinations
* Implemented a vector-based retrieval pipeline with **Sentence-Transformers embeddings, ChromaDB, and MMR (Maximum Marginal Relevance)** for relevance–diversity trade-off
* Evaluated the system with **BERTScore (F1 ≈ 0.83)**, perplexity, latency, and human judgment, showing improved factual accuracy with self-query retrieval
