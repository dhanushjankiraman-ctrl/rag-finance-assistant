# 💰 RAG Finance Assistant

A Retrieval-Augmented Generation (RAG) based Finance Assistant that uses financial documents to provide context-aware answers.

## 📌 Project Overview

This project demonstrates how RAG can be used to build a finance-focused question-answering system.

The system retrieves relevant information from a financial document and provides it as context to a language model before generating an answer.

## 🎯 Objective

The main objective of this project is to build a finance assistant that can:

- Retrieve relevant information from financial documents
- Understand user questions
- Provide context-based answers
- Reduce the chance of generating unsupported information
- Demonstrate the practical use of RAG in finance

## 🔄 RAG Pipeline

```text
Financial PDF
     ↓
PDF Loading
     ↓
Text Chunking
     ↓
Hugging Face Embeddings
     ↓
FAISS Vector Database
     ↓
Similarity Search / Retriever
     ↓
Relevant Context
     ↓
Language Model
     ↓
Generated Answer
