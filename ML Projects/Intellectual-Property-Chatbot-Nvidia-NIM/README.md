<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Intellectual Property Chatbot</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 900px;
            margin: auto;
            padding: 20px;
        }

        h1, h2, h3 {
            color: #333;
        }

        h1 {
            font-size: 36px;
            margin-bottom: 10px;
            color: #76B900;
        }

        h2 {
            font-size: 28px;
            margin-bottom: 10px;
            color: #5a9b00;
        }

        h3 {
            font-size: 22px;
            margin-bottom: 10px;
        }

        p {
            margin: 15px 0;
        }

        code {
            background-color: #f4f4f9;
            color: #333;
            padding: 3px 5px;
            border-radius: 5px;
        }

        pre {
            background-color: #333;
            color: #fff;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }

        .code-block {
            background-color: #eee;
            border-left: 4px solid #76B900;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
        }

        strong {
            font-weight: bold;
        }

        ul {
            list-style-type: square;
            padding-left: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Intellectual Property Chatbot with NVIDIA-NIM Integration</h1>

        <p>This project leverages <strong>Streamlit</strong> to create an interactive web application that allows users to query <strong>intellectual property (IP)</strong> documents using <strong>NVIDIA's AI embeddings</strong> and chatbot APIs. The chatbot provides answers based on the content of PDF documents uploaded into the system.</p>

        <h2>Features</h2>
        <ul>
            <li><strong>Document Embedding:</strong> Embeds documents for efficient retrieval using <strong>FAISS</strong> and <strong>NVIDIA embeddings</strong>.</li>
            <li><strong>PDF Loader:</strong> Loads PDFs from a directory and splits the text into chunks for processing.</li>
            <li><strong>Custom UI:</strong> Includes responsive buttons, sidebar PDF display with thumbnails, and enhanced user experience using <strong>custom CSS</strong>.</li>
            <li><strong>NVIDIA AI Integration:</strong> Uses <strong>NVIDIA's API</strong> to generate embeddings and answer questions based on document context.</li>
            <li><strong>Efficient Querying:</strong> Employs <strong>FAISS</strong> for vector store creation and document retrieval.</li>
            <li><strong>PDF Thumbnails:</strong> Dynamically generates and displays thumbnails of PDFs in the sidebar.</li>
            <li><strong>Document Similarity Search:</strong> Displays similar documents when a question is asked, allowing better understanding of the context.</li>
        </ul>

        <h2>Prerequisites</h2>
        <ul>
            <li><strong>Python 3.8+</strong></li>
            <li><strong>NVIDIA API Key</strong> for access to NVIDIA AI services</li>
        </ul>

        <h2>Installation</h2>
        <ol>
            <li><strong>Clone the repository:</strong></li>
            <pre><code>git clone https://github.com/milind2thakur/The-Grand-Complete-Data-Science-Materials.git</code></pre>

            <li><strong>Install the required dependencies:</strong></li>
            <pre><code>pip install -r requirements.txt</code></pre>

            <li><strong>Set up the NVIDIA API key:</strong> Add your key in the <code>.env</code> file or directly in the environment variable in the code:</li>
            <pre><code>os.environ['NVIDIA_API_KEY'] = "your_nvidia_api_key_here"</code></pre>
        </ol>

        <h2>Usage</h2>
        <ol>
            <li><strong>Prepare your PDFs:</strong> Place your PDF files in the <code>./IP_PDF</code> directory.</li>
            <li><strong>Run the Streamlit App:</strong></li>
            <pre><code>streamlit run app.py</code></pre>
            <li><strong>Open your browser:</strong> Go to <code>http://localhost:8501</code> to start interacting with the chatbot.</li>
        </ol>

        <h2>Key Components</h2>
        <ul>
            <li><strong>Document Embedding:</strong> Processes PDFs using <strong>PyPDFDirectoryLoader</strong> and splits them into smaller chunks for efficient retrieval and embedding using <strong>NVIDIAEmbeddings</strong> and <strong>FAISS</strong>.</li>
            <li><strong>NVIDIA Chatbot:</strong> A chatbot that processes user questions and queries the document vectors for the most relevant response.</li>
            <li><strong>Custom UI:</strong> A clean and user-friendly interface with responsive buttons, PDF thumbnails, and download options.</li>
        </ul>
    </div>
</body>
</html>
