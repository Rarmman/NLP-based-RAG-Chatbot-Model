# NLP-based-RAG-Chatbot-Model
Repository consisting of an NLP chatbot model which uses RAG framework for Q&A purposes.

Author: Armman Roy

This project implements a Retrieval Augmented Generation (RAG) based system for a question answering chatbot. It is built on top of Google Gemini 2.0-Flash and ChromaDB, using the SQuAD v1.1 dataset. It consists of an end-to-end open domain QA Pipeline from data loading to evaluation

1. Data loading, including text extraction and flattening
2. Embedding and Vector Storage, including implicit tokenization
3. Retrieval Augmentation
4. Generation and Evaluation, including internal tokenization during generation
5. Interactive QA Loop

Dataset used: Stanford Question Answering Dataset (SQuAD v1.1)

Embedding Model: models/text-embedding-004 (Google Gemini Embeddings)

Vector Database: ChromaDB

Generation Model: Gemini-2.0-Flash

Evaluation Metrics: SQuAD EM and F1, ROUGE-L, BLEU, Precision, Recall, custom F1

Input: User query

Output: Corresponding Response
