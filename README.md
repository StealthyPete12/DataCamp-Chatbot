# Automating Customer Support with OpenAI API 

This project was focused on building a automated customer support system built using the OpenAI API.  
It was developed as part of a practical exam for a DataCamp AI engineering project and refined for portfolio presentation.

The chatbot classifies customer queries, retrieves relevant responses using semantic search, and generates new answers when no suitable predefined response is found.

---

## Project Overview

ChatSolveAI aims to improve customer support response times and consistency by using NLP, including:

- Text embeddings for semantic similarity
- Cosine similarity based retrieval
- OpenAI GPT models for response generation
- Structured logging of chatbot interactions

The solution is designed to resemble a real world customer support automation pipeline.

---

## Key Features

- Converts a knowledge base into vector embeddings for efficient search
- Classifies and embeds customer queries
- Retrieves relevant responses using semantic similarity
- Generates new responses when no suitable match exists
- Computes confidence scores for responses
- Logs all chatbot interactions in structured JSON format

---

## Technology Stack

- **Python**
- **OpenAI API**
  - `text-embedding-3-small`
  - `gpt-3.5-turbo`
- **JSON** for structured data storage
- **CSV** for datasets
- Cosine similarity for semantic search

---

## Author
Developed by Timothy Deschamps  
