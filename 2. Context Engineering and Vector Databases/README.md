# AI Employee Knowledge Explorer

An AI-powered employee knowledge retrieval system built using Python, TF-IDF, Sentence Transformers, FAISS, LlamaIndex, ChromaDB, and optionally the DeepSeek API.

The project explores lexical and semantic retrieval techniques over six Northstar Systems employee policy documents.

### Key Features
- Structured document ingestion and metadata preservation.
- TF-IDF-based lexical retrieval.
- Sentence Transformer embeddings.
- FAISS-based semantic search.
- LlamaIndex document chunking.
- Persistent ChromaDB storage and retrieval.
- Metadata-based departmental filtering.
- Record metadata updates.
- Retrieval evaluation using predefined test questions.
- Optional grounded answer generation using DeepSeek.

### Technologies
Python · Scikit-learn · Sentence Transformers · FAISS · LlamaIndex · ChromaDB · DeepSeek API · Google Colab

### Execution
Open the executed notebook in Google Colab and run the cells sequentially. The six supplied Northstar policy files must be available in the configured data directory.

**Note:** The DeepSeek answer-generation extension is optional and requires a securely configured API key.
