# RAG-from-Scratch
This repo is a collection of Retrieval-Augmented Generation (RAG) experiments—from basic setups to more advanced optimizations.

1. Implemented Advanced RAG Pipeline with Wikipedia Data
I've built a complete Retrieval-Augmented Generation (RAG) system from the ground up to thoroughly understand each component of the architecture. Using Elon Musk's Wikipedia page as my knowledge base, I gained hands-on experience with document processing, vector database construction using FAISS, semantic retrieval, context engineering, and response generation with Google's Gemini Pro LLM.
I documented my learning journey [in this Medium article](https://medium.com/@mahipalimkar12/understanding-retrieval-augmented-generation-rag-ab18b74db0cc), explaining RAG concepts, implementation details, and best practices for others building similar systems. This project demonstrates how RAG enhances LLM responses with factual information while reducing hallucinations.

2. I built a RAG based chatbot that answers legal queries related to the constitution of India.
   Features

a. Document Retrieval: Efficiently searches through legal documents to find relevant information
b. Semantic Search: Uses sentence embeddings to understand the meaning behind queries
c. Contextual Response Generation: Generates human-like responses based on retrieved legal context
d. Interactive UI: Provides a clean, intuitive interface for querying the system
e. PDF Support: Extracts text from legal PDFs for knowledge base creation

Technologies Used

Language Model: TinyLlama-1.1B-chat-v1.0 for text generation
Embeddings: Sentence-Transformers (all-MiniLM-L6-v2) for semantic search
Vector Database: FAISS for efficient similarity search
Text Processing: PyPDF for document parsing
UI: IPython widgets for the interactive interface
![image](https://github.com/user-attachments/assets/26913270-f7a6-42a9-a40b-9e6373271a59)

To improve the queality of response, we can tune the generation parameters in the generate_response method.

I have used TinyLllama here because of its low computational requirements and faster inference speed.
