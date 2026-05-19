# Energy Intelligence RAG System

## Overview

This project implements a Retrieval-Augmented Generation (RAG) pipeline for energy intelligence analysis using Large Language Models (LLMs), semantic retrieval, and document-grounded response generation.

The system was developed using International Energy Agency (IEA) reports as the primary knowledge source and evaluates multiple approaches to question answering, including:

- Base LLM prompting
- Prompt engineering
- Standard RAG
- Tuned RAG

The project demonstrates how retrieval-based AI systems can improve factual grounding, traceability, and analytical usefulness when working with domain-specific document collections.

---

## Project Objectives

The primary goals of this project were to:

- Build a document-grounded question-answering system
- Compare standalone LLMs against RAG-enhanced systems
- Improve response quality through retrieval tuning
- Evaluate grounding, relevance, and hallucination reduction
- Demonstrate practical AI applications for energy intelligence analysis

---

## Features

- Semantic document retrieval
- Vector similarity search
- Prompt-engineered response generation
- Tuned top-k retrieval evaluation
- Retrieved chunk inspection
- Grounding and hallucination analysis
- Comparative evaluation framework
- Energy intelligence question answering

---

## Technologies Used

- Python
- OpenAI API
- LangChain
- ChromaDB / Vector Retrieval
- Sentence Transformers
- Pandas
- Jupyter Notebook

---

## Project Structure

```text
├── Energy_Intelligence_RAG_Model.ipynb
├── requirements.txt
├── README.md
└── data/
```

---

## Evaluation Approach

The project evaluates four system architectures:

1. Base LLM
2. Prompt-Engineered LLM
3. Base RAG
4. Tuned RAG

Evaluation focuses on:

- Document grounding
- Retrieval quality
- Response relevance
- Traceability
- Business usefulness
- Hallucination reduction

The tuned RAG system demonstrated the strongest overall performance due to improved retrieval configuration and better contextual grounding.

---

## Example Questions

- What are the major causes of power outages?
- How can renewable energy improve grid reliability?
- What challenges affect modern energy infrastructure?
- What trends are shaping the global energy market?

---

## Future Improvements

Potential future enhancements include:

- Hybrid search (BM25 + vector retrieval)
- Reranking models
- Citation generation
- Expanded energy datasets
- Quantitative benchmark testing
- Interactive dashboard deployment

---

## Author

James Grolig

Applied AI / Machine Learning Portfolio Project
