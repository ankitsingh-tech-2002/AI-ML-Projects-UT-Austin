# Medical Knowledge RAG System

**Domain:** GenAI / Healthcare AI  
**Part of:** UT Austin PG Program in AI & ML

## Objective

Build a Retrieval-Augmented Generation (RAG) system using medical manuals to support accurate, source-grounded clinical decision-making.

## Key Focus Areas

- PDF ingestion & chunking
- Vector search & retrieval
- Hallucination reduction
- Trustworthy, source-cited AI responses

## How to Run

1. Open `RAG_medical_assistant.ipynb` in Jupyter Notebook, Google Colab, or Azure ML.
2. Ensure `medical_diagnosis_manual.pdf` is in the same folder (included in repo).
3. Install dependencies (e.g. `langchain`, `chromadb` or similar vector store, `pypdf`, PDF parsers, and an LLM API client). The notebook may include `pip install` cells.
4. Set any required API keys (e.g. OpenAI, Azure OpenAI) as indicated in the notebook.
5. Run all cells sequentially.

## Files in This Folder

| File | Description |
|------|-------------|
| `RAG_medical_assistant.ipynb` | Main notebook (PDF ingestion, chunking, embeddings, retrieval, RAG pipeline) |
| `medical_diagnosis_manual.pdf` | Medical reference used as knowledge base |

## Key Libraries

- Python, Pandas
- LangChain (or similar) for RAG orchestration
- Vector store (e.g. ChromaDB, FAISS)
- PDF processing (e.g. PyPDF, pdfplumber)
- LLM API (OpenAI, Azure OpenAI, or similar)
- Jupyter Notebook
