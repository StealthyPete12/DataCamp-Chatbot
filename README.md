# Automating Customer Support with OpenAI API 

This project builds an automated customer support system using the OpenAI API.  
Developed as part of a practical exam for a DataCamp AI engineering project and refined for portfolio presentation.

The chatbot classifies customer queries, retrieves relevant responses using semantic search, and generates new answers when no suitable predefined response is found.

---

## Architecture

![System Architecture](assets/architecture.svg)

**How it works:**

1. A **customer query** is received as text input
2. The query is converted into a vector using **OpenAI Embeddings** (`text-embedding-3-small`)
3. **Cosine similarity** search finds the closest match in the knowledge base
4. If a match is found above the confidence threshold, the **predefined response** is returned
5. If no match is found, **GPT-3.5-turbo** generates a new response
6. Every interaction is **logged** with timestamps and confidence scores

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
- **Cosine similarity** for semantic search

---

## Author
Developed by Timothy Deschamps  
