# Finance_RAG_Implementation
This project implements a Retrieval Augmented Generation (RAG) system for financial due diligence. It is inspired from: https://pub.aimind.so/build-a-financial-due-diligence-rag-system-in-60-minutes-using-gemma-121905e1bfc3

**Features:**

* **Data Cleaning and Preparation:** The code cleans and prepares the financial data for use in the RAG system.
* **Embedding Generation:** Embeddings are generated for the financial data using the SentenceTransformer library. This allows for efficient similarity search.
* **Vector Search:** A vector search pipeline is implemented to retrieve relevant information from the MongoDB database based on the user's query.
* **Query Handling:** The system handles user queries by retrieving relevant information and generating comprehensive answers.
* **LLM Model Integration:** The GEMMA language model and meta-llama/Llama-3.2-1B-Instruct is used to generate insightful answers to user queries.

**Note:**

This project is inspired by the following article:
[Build a Financial Due Diligence RAG System in 60 Minutes Using GEMMA](https://pub.aimind.so/build-a-financial-due-diligence-rag-system-in-60-minutes-using-gemma-121905e1bfc3)

