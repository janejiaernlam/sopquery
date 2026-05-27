# Task 1 Ideation — SOP Q&A Agent

> Anchor document. Reference this to ensure all subsequent deliverables stay aligned with the original problem framing.

---

## Project Idea: RAG-Based Q&A System for Pharmaceutical SOP Documents

### Problem

Pharmaceutical staff spend significant time manually searching through lengthy SOP documents to find procedural answers. This is slow, error-prone, and a compliance risk when the wrong document version is referenced.

### Target Users

QA officers, production operators, and compliance teams in pharmaceutical manufacturing environments.

### Core Features

1. PDF ingestion and chunking of SOP documents
2. Embedding and vector storage for semantic search
3. Natural language query interface
4. Retrieved answers with source citation (document + section)
5. Conversation history for follow-up queries

### Emerging Technology

Retrieval-Augmented Generation (RAG) using LangChain and a hosted LLM API.

### Ratings

| Criterion        | Rating |
|------------------|--------|
| Personal Interest | 8 / 10 |
| Feasibility (12-week) | 8 / 10 |

---

## 1-Minute Pitch

**Problem:** SOP documents in pharma are long, dense, and version-controlled. Finding a specific procedure manually takes time and carries compliance risk if the wrong section or version is used.

**Solution:** A RAG-based system that lets users type a natural language question and receive a cited answer pulled directly from the relevant SOP section, with the source document and section clearly referenced.

**Why it matters:** Reduces lookup time, reduces human error, and creates an auditable trail of which document version was referenced — directly addressing a real compliance need in regulated industries.

---

*Last updated: 2025-06-27*
