# 🏛️ MNLP 2026 - RAG and Semantic Search Project

This repository contains the code and reports for the two Homework assignments of the **Multilingual Natural Language Processing (MNLP) 2026** course at Sapienza University of Rome.

## 👥 Authors
*   Mattia Cosimi (2278125)
*   Nicolò Romanelli (2283937)

## 🎯 Project Objectives

The project is divided into two sequential phases leading to the construction of a complete RAG (Retrieval-Augmented Generation) pipeline:

*   **Homework 1 (Retrieval):** Development and training of a Semantic Search system to retrieve the most relevant chunks (passages) from a Knowledge Base starting from a natural language query.
*   **Homework 2 (Augmented Generation & Evaluation):** Development of a full RAG system. Use of the top-k chunks retrieved in HW1 to augment the prompts fed to "Small LMs" (open-weight language models with $\le$ 3 billion parameters). The implementation includes three zero-shot setups (Baseline, RAG, Oracle). Evaluation is performed using standard metrics (Exact Match, METEOR) and LLM-as-a-Judge techniques, supported by manual validation.

## 📂 Repository Structure

*   `HW1/`: Contains the notebooks for chunk extraction and retriever fine-tuning.
*   `HW2/`: Contains the notebooks for augmented generation and automatic/manual evaluation.
*   `requirements.txt`: List of dependencies to run the code locally.
