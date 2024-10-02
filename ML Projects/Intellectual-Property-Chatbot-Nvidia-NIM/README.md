

# **Intellectual Property Chatbot with NVIDIA-NIM Integration**

This project leverages **Streamlit** to create an interactive web application that allows users to query **intellectual property (IP)** documents using **NVIDIA's AI embeddings** and chatbot APIs. The chatbot provides answers based on the content of PDF documents uploaded into the system.

![chatbot_image](https://github.com/user-attachments/assets/2047402e-b52f-48f5-8e72-e51900927806)



## **Features**

- **Document Embedding**: Embeds documents for efficient retrieval using **FAISS** and **NVIDIA embeddings**.
- **PDF Loader**: Loads PDFs from a directory and splits the text into chunks for processing.
- **Custom UI**: Includes responsive buttons, sidebar PDF display with thumbnails, and enhanced user experience using **custom CSS**.
- **NVIDIA AI Integration**: Uses **NVIDIA's API** to generate embeddings and answer questions based on document context.
- **Efficient Querying**: Employs **FAISS** for vector store creation and document retrieval.
- **PDF Thumbnails**: Dynamically generates and displays thumbnails of PDFs in the sidebar.
- **Document Similarity Search**: Displays similar documents when a question is asked, allowing better understanding of the context.

## **Prerequisites**

- **Python 3.8+**
- **NVIDIA API Key** for access to NVIDIA AI services

## **Installation**

1. **Clone the repository**:

2. **Install the required dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

3. **Set up the NVIDIA API key**: Add your key in the `.env` file or directly in the environment variable in the code:

    ```python
    os.environ['NVIDIA_API_KEY'] = "your_nvidia_api_key_here"
    ```

## **Usage**

1. **Prepare your PDFs**: Place your PDF files in the `./IP_PDF` directory.
2. **Run the Streamlit App**:

    ```bash
    streamlit run app.py
    ```

3. **Open your browser** at `http://localhost:8501`
