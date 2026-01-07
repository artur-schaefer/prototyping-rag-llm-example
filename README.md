# RAG Chatbot Notebook

This repo contains a single Jupyter notebook prototype that builds a small RAG chatbot using the markdown documents in `data/docs`.

What the notebook does:

- Loads and chunks the documents.
- Builds multilingual embeddings and a BM25 keyword index.
- Retrieves relevant chunks with a hybrid score.
- Feeds the context into a local LLM to answer questions strictly from the docs.
- Caches embeddings on disk in `index/` for faster reloads.

Open `rag_chatbot.ipynb` to view and run the full code.
