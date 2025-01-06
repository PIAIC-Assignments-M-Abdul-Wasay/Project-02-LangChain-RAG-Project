# Project Overview

This project implements a Retrieval-Augmented Generation (RAG) system using Pinecone for vector storage, Google Generative AI for embeddings and language generation, and LangChain for chaining components. The steps include:

1. **API Initialization**: Fetched and validated API keys for Pinecone, Google Generative AI, and OpenAI.  
2. **Pinecone Indexing**: Created a vector index and stored document embeddings.  
3. **Data Preparation**: Processed a text file into chunks and converted them into document objects.  
4. **Embeddings**: Used Google Generative AI to embed queries and documents.  
5. **RAG Setup**: Initialized a RetrievalQA chain combining Pinecone and LangChain.  
6. **Query Execution**: Ran queries to retrieve and generate answers using stored documents and the LLM.  


### 7. **Query Execution**  
- Executed the following query using the RAG setup:
  ```text
  input:
  What is my full name?  
  What is my brother's full name?

  Response:
  Your full name is Muhammad Abdul Wasay Abid.  
  Your brother's full name is Uzair Abid.
