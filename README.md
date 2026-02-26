# Chunking Size Explore

This repository contains an in-depth exploratory analysis of how different chunk sizes influence Retrieval-Augmented Generation (RAG) pipelines. Implemented in notebook format, the project focuses on systematically evaluating how chunking strategies impact document indexing, embedding generation, vector storage efficiency, retrieval relevance, and final LLM response quality.

The notebooks experiment with varying:

- Chunk sizes  
- Chunk overlap values  
- Text splitting strategies  
- Embedding and retrieval behavior  

Through controlled comparisons, the project highlights key trade-offs:

- **Smaller chunks** → Higher retrieval precision, more granular embeddings, but increased index size and potential loss of broader context.  
- **Larger chunks** → Richer contextual information per chunk, fewer embeddings, but possible noise and reduced retrieval specificity.  

This repository is designed as a practical learning and experimentation space to better understand how chunking decisions directly affect RAG system performance. It can serve as a reference for AI/ML practitioners building scalable, efficient, and production-ready RAG applications using vector databases and modern LLM frameworks.

The focus is purely on experimentation and insight generation—the detailed explanations and implementation walkthroughs are available within the notebooks.
