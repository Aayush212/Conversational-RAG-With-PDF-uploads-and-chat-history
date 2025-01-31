# Conversational RAG with PDF Uploads and Chat History
This is a Conversational Retrieval-Augmented Generation (RAG) application built with LangChain, Streamlit, and Groq API. The application allows users to upload PDFs, engage in Q&A with the document contents, and maintain chat history for context-aware conversations.
The app integrates PDF document processing, question-answering (QA) with context, and chat history functionality for a rich, interactive user experience. It leverages the power of Groq for language model inference and Chroma for document vectorization.

## Features
1. PDF Upload: Allows users to upload multiple PDF files for processing.

2. Chat History: Retains the context of conversations, making the assistant more aware of past interactions.

3. Groq Integration: Uses the Groq API to run the language model and generate answers based on context.

4. Interactive Q&A: Engage in question-answering about the uploaded documents.

5. PDF Text Processing: Splits the PDF content into manageable chunks for efficient document querying.

## Requirements
Python 3.8+
Required Python packages are listed in the ```requirements.txt``` file.

## Installation

To set up the application locally, follow these steps:

## 1. Clone the Repository
```
git clone https://github.com/Aayush212/Conversational RAG with PDF Uploads and Chat History.git
cd Conversational RAG with PDF Uploads and Chat History
```

## 2. Install Dependencies
```
pip install -r requirements.txt
```

## 3. Set Up the Groq API Key
In order to use the Groq API for language model inference, you need a valid API key.
Create a ```.env``` file in the root directory and add your API key as shown below:
```HF_TOKEN=your_groq_api_key```

## 4. Run the Streamlit App
```
streamlit run main.py
```

## Usage
Upload one or more PDF files to the app.
Type your questions in the provided input box and click Submit to get answers based on the document's content.
Chat history will be saved and used for context in subsequent questions.

## Streamlit Hosting
The application is hosted on Streamlit. You can access it via the following link:

## Folder Structure
```
.
├── .env                  # API keys and environment variables
├── main.py               # Main Streamlit application code
├── requirements.txt      # List of dependencies
└── temp.pdf              # Temporary PDF files uploaded during runtime

```
## Technologies Used
### > LangChain: 
A framework for building language model-powered applications.
### > Streamlit: 
A web framework for building interactive data applications.
### > Groq API: 
A powerful language model API used for generating responses.
### > Chroma: 
A document vector store to store and retrieve document embeddings.
### > PyPDFLoader: 
A utility for extracting text from PDFs.
### > HuggingFaceEmbeddings: 
For generating document embeddings.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
