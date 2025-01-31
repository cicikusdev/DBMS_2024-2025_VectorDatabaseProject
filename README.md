# DBMS_2024-2025_VectorDatabaseProject
2024-2025 Fall Term Database Management Systems | Vector Database and Chatbot Integration Project for FORD Otosan Eskişehir 
--

# Ford Otosan - AI-Powered Production Data Management System

# Project Overview

This project was developed for Ford Otosan to enhance their production line data management system. 
The company faced challenges due to unstructured, inconsistent, and error-prone data entries, 
which negatively impacted their chatbot’s ability to retrieve accurate information. 
To solve these issues, our team designed a solution that:

- Migrates the existing database to a vector database for optimized search capabilities.
- Performs extensive data cleaning, categorization, and structuring to eliminate inconsistencies.
- Implements a semantic search mechanism with cosine similarity to improve query accuracy.
- Develops an AI chatbot using Gemini LLM, enabling smarter and context-aware responses.

# Key Features

## Advanced Data Cleaning & Structuring
- Standardized inconsistent entries to improve search accuracy.
- Removed redundant, incomplete, and erroneous data.
- Categorized and restructured the database for optimized retrieval.
## Vector Database Implementation
- Converted unstructured text data into high-dimensional vectors for fast and precise retrieval.
- Used ChromaDB for efficient vector-based search.
## Semantic Search & Cosine Similarity
- Enabled meaning-based queries rather than strict keyword matching.
- Enhanced accuracy by comparing similarity scores between queries and stored data.
## AI Chatbot Integration
- Utilized Gemini LLM for intelligent, context-aware responses.
- Provided dynamic answers based on vectorized database information.
## Google OAuth Authentication
- Implemented secure login via Google accounts for user authentication.
## Data Privacy Compliance
- No personally identifiable information (PII) is stored or processed.
- The system adheres to KVKK/GDPR regulations by working only with structured business data.

# Technologies Used

- Vector Database: ChromaDB
- Data Cleaning & Preprocessing: Python, Pandas, Regex
- Semantic Search & Cosine Similarity: Sentence Transformers, Scikit-learn
- LLM Integration: Gemini API
- Backend Development: Flask, FastAPI
- Frontend UI: Tkinter (Python GUI)
- Authentication: Google OAuth
- Database Management: PostgreSQL, DuckDB

# Results & Impact
- This project significantly improved data reliability, search accuracy, and chatbot efficiency, 
reducing response errors and enhancing user experience. 
- By integrating AI-powered search and structured data management, we created a more intelligent, 
fast, and effective production data system for Ford Otosan.
