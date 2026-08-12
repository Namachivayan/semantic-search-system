# 🔎 Semantic Search System

A semantic search system for finding relevant news articles based on the
meaning of a user's query rather than exact keyword matching.

The system uses **Sentence Transformers** to convert text into numerical
embeddings and **FAISS** to efficiently retrieve semantically similar
documents.

---

## 📌 Project Overview

Traditional search systems mainly depend on matching exact keywords.

For example:

User Query:
"AI technology"

A traditional keyword search may look only for the words "AI" or
"technology".

Our semantic search system understands the meaning of the query and can
retrieve related articles even when the exact words are different.

### Example

**Query:**
```text
artificial intelligence
