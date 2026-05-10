# 🛡️ Cybersecurity RAG System: Zero Trust Architecture Guidelines

An advanced Retrieval-Augmented Generation (RAG) pipeline designed to retrieve complex, domain-specific cybersecurity frameworks (e.g., NIST SP 800-207) and generate actionable, hallucination-free guidelines for security practitioners. 

**Academic Context:** Built for the *Advanced Topics in Artificial Intelligence and Machine Learning* course.

---

## 🎯 Project Overview
Standard Large Language Models (LLMs) often lack up-to-date, highly specific technical knowledge and are prone to hallucinating when asked about strict cybersecurity policies. This project solves that by grounding an open-source LLM in verified cybersecurity documentation using a robust RAG architecture.

**Core Objectives:**
1. Ingest and semantically chunk dense cybersecurity policy documents.
2. Retrieve highly relevant context using advanced embedding strategies.
3. Generate concise, actionable advice for security practitioners.
4. Rigorously evaluate system trustworthiness using reference-free metrics (RAGAS & DeepEval).

## 🛠️ The Tech Stack
* **Orchestration:** LangChain
* **Vector Database:** ChromaDB
* **Embeddings:** HuggingFace (`all-mpnet-base-v2` / `all-MiniLM-L6-v2`)
* **LLM:** Open-Source (e.g., Llama 3 or Mistral via local inference/API)
* **Evaluation:** RAGAS & DeepEval

---

## 🚀 Getting Started

### Prerequisites
Make sure you have Python 3.10+ installed. It is highly recommended to use a virtual environment.

### Installation
1. Clone this repository:
   ```bash
   git clone <your-repo-link-here>
   cd <your-repo-name>
