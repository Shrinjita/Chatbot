# Chatbot

This repository provides scripts to build a chatbot using the LLaMA model from Hugging Face. The chatbot generates responses based on user inputs, demonstrating the capabilities of the LLaMA language model.

## Features
- Embedding function generation.
- Database population for storing chatbot context.
- Query processing using the RAG framework.

## Usage
1. Add your PDF files to the `data` directory.
2. Populate the database:  
   ```bash
   python populate_database.py
   ```
3. Query the chatbot:  
   ```bash
   python query_data.py "Your question here"
   ```

## Requirements
Install dependencies with:  
```bash
pip install -r requirements.txt
```

## Files
- **get_embedding_function.py**: Embedding generation script.
- **populate_database.py**: Adds data to the database.
- **query_data.py**: Processes user queries.
- **test_rag.py**: RAG model testing.
