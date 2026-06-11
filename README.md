# Generative AI Medical Chatbot System

## Overview
This repository contains a progressive Generative AI project focused on building a secure, accurate patient education chatbot. It demonstrates the evolution of a Large Language Model (LLM) application from basic prompt engineering to a sophisticated Retrieval-Augmented Generation (RAG) system equipped with strict clinical safety guardrails.

## Project Architecture & Assets

### 📓 Jupyter Notebooks
* **`01_Patient_Education_Chatbot_Basic.ipynb`:** Establishes the foundational LLM integration and basic conversational agent logic for answering patient queries.
* **`02_Patient_Education_Chatbot_RAG_Guardrails.ipynb`:** Upgrades the chatbot using Retrieval-Augmented Generation (RAG) to ground the AI's answers in a specific knowledge base, while implementing crucial safety guardrails to prevent AI hallucinations or unsafe medical advice.
* **`03_GenAI_Medical_Chatbot_App.ipynb`:** The comprehensive notebook tying the system together into a functional application structure.

### 📁 Knowledge Base (Dataset)
* **`medical_patient_education_qa_dataset.csv`:** The underlying dataset acting as the "source of truth" for the RAG system. It contains structured medical questions, trusted answers, and search text used to ground the LLM's responses.

## Potential Use Cases
* **Patient Triage & Navigation:** Helping patients understand their symptoms and directing them to the appropriate level of care.
* **Discharge Education:** Automating follow-up answers for patients post-discharge to reduce readmissions.
* **Administrative Load Reduction:** Deflecting routine medical Q&A away from busy nursing staff while ensuring safe, verified answers.

## How to Use
1. **Clone the Repository:** Download the files to your local machine.
2. **Review the Notebooks:** Open the numbered Jupyter Notebooks sequentially to understand how the AI pipeline is constructed and secured.
3. **Inspect the Data:** Review the CSV to see how trusted Q&A pairs are formatted for vectorization and RAG retrieval.

> **Disclaimer:** This chatbot application and its associated datasets are strictly for educational and portfolio demonstration purposes. It is not a substitute for professional medical advice, diagnosis, or treatment. Always consult a qualified healthcare provider with any questions regarding a medical condition.
