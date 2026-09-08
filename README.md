# An AI-Driven Knowledge Platform for Personalized Policy Analysis and Impact Assessment

## Engineering Goal
Achieve at least 90% factual accuracy and at least 95% citation precision using the RAGAS evaluation framework on campus policy queries.

## Technology Stack
- **Orchestration:** LangChain
- **Database:** FAISS (Facebook AI Similarity Search) Vector Store
- **Models:** OpenAI `text-embedding-3-small` (Embeddings) & `gpt-4o-mini` (LLM)
- **Backend:** Python (FastAPI)
- **Frontend:** React.js

## Project Structure
- `backend/`: FastAPI application and RAG pipeline logic
- `frontend/`: React chat interface
- `data/`: Policy document store and FAISS index