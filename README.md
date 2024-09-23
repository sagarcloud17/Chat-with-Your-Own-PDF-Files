# Chat-with-Your-Own-PDF-Files
This project provides a web-based interface for uploading PDF documents and interacting with them via a chatbot using LangChain, OpenAI, and Streamlit. It allows users to ask questions about the contents of their uploaded PDFs, and the chatbot will retrieve and respond with relevant information.

# Features
1. PDF Uploading: Upload one or more PDF files.
2. Conversational Retrieval: Ask questions about the uploaded PDF content, and the app provides context-aware answers based on the contents of the documents.
3. Chat History: Manages session-based chat history for better interaction continuity.

# Technologies Used
1. Streamlit for building the web UI.
2. LangChain for conversational AI and document retrieval.
3. Chroma for document embedding storage.
4. OpenAI for language models and embeddings.

# Prerequisites
Make sure you have Python 3.8 or higher installed.

# Installation
1. Clone the repository
2. install requirements.txt - pip install -r requirements.txt
3. Set up environment variables: You need to provide your OpenAI API key in a .env file.

# Usage
1. Run the Streamlit app - streamlit run app.py
2. Upload your PDFs: Open your browser and go to the local Streamlit server. You will be prompted to upload your PDF files.

Ask questions: Once the PDFs are uploaded, use the input box to ask questions about the content of the documents. The application will retrieve relevant content and provide concise answers.




