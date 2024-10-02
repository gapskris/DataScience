Intellectual Property Chatbot with NVIDIA-NIM Integration
This project uses Streamlit to create an interactive web application that allows users to query intellectual property (IP) documents using NVIDIA's AI embeddings and chatbot APIs. The chatbot answers user questions based on PDF documents uploaded into the system.

Features
Document Embedding: Automatically embeds documents for efficient retrieval using FAISS and NVIDIA embeddings.
PDF Loader: Loads PDFs from a designated directory and splits the text into chunks for processing.
Custom UI: Responsive buttons, sidebar PDF display with thumbnails, and enhanced user experience with custom CSS.
NVIDIA AI Integration: Utilizes NVIDIA's API for generating embeddings and answering questions based on document context.
Efficient Querying: Uses FAISS for vector store creation and document retrieval.
PDF Thumbnails: Dynamically generates and displays PDF thumbnails in the sidebar.
Document Similarity Search: Expands on results to show similar documents when a question is asked.
Prerequisites
Python 3.8+
NVIDIA API Key for using the NVIDIA AI services
