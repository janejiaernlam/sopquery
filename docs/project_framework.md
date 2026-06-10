# Project Framework — SOP Q&A Agent

> Anchor document. Reference this to ensure all deliverables and sprints stay on track.

---

## Tech Stack

| Component | Tool |
|---|---|
| PDF ingestion | LangChain |
| Embedding | sentence-transformers (local, free) |
| Vector store | Chroma |
| LLM API | Groq API (Llama 3) |
| Web UI | Jupyter Notebook |
| Language | English only |

---

## Timeline

### Week 1 (27 May - 2 Jun)
Task 1 Ideation

### Week 2 (3 - 9 Jun)
- SRS document
- Python environment setup (virtual environment, VS Code plugins)
- Install dependencies: LangChain, Chroma, sentence-transformers
- Download 3-5 sample SOP PDFs into `data/`

### Week 3 - 4 (10 - 23 Jun) — Sprint 1
- PDF reading and text extraction
- Text chunking (splitting long documents into segments)
- Generate embeddings and store in Chroma vector store
- Basic similarity search working end-to-end

### Week 5 - 6 (24 Jun - 7 Jul) — Sprint 2
- LLM API integration (Groq)
- Natural language query interface
- Retrieval with source citation
- Interim progress report write up
- **Sprint 1 & 2 Interim submission (7 Jul)**

### Week 7 - 8 (8 - 21 Jul)
- Conversation history
- Tuning: chunk size and retrieval parameters
- Testing and evaluation (accuracy, response quality)

### Week 9 -10 (22 Jul - 2 Aug)
- Final report (IEEE format)
- Presentation preparation
- **Final submission (2 Aug)**

---

## Kanban Structure (MS Teams Planner)

Buckets: `Backlog (To-Do)` → `In Progress` → `Testing` → `Evaluation` → `Completed`

Each task within a sprint maps to a card in the board.

---

*Last updated: 2026-05-27*
