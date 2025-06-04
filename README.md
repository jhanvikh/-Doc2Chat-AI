# Doc2Chat AI

Doc2Chat AI is an interactive Streamlit app that lets you upload multiple PDF documents and chat with their content using natural language. It uses LangChain and HuggingFace models to extract, embed, and retrieve information from PDFs, enabling a conversational question-answering experience.

---

## Features

- Upload multiple PDFs at once  
- Extract text and split into manageable chunks  
- Generate semantic embeddings with HuggingFace InstructorEmbeddings (`hkunlp/instructor-xl`)  
- Store vectors using Chroma vector database  
- Conversational interface powered by Google Flan-T5-XXL LLM  
- Maintains chat history for context-aware responses  
- Clean and intuitive Streamlit UI with chat bubbles

---

## How It Works

1. Upload PDFs in the sidebar and click **Process**  
2. The app extracts text and splits it into chunks  
3. Chunks are embedded into vectors and stored for retrieval  
4. Ask questions in the chatbox about your documents  
5. Get relevant, contextual answers from the model

---

## Tech Stack

- Python 3  
- Streamlit  
- PyPDF  
- LangChain  
- HuggingFace Instruct Embeddings  
- Chroma vector store  
- HuggingFaceHub LLM (Google Flan-T5-XXL)  
- dotenv for environment variables

---

## Usage
Upload PDFs using the sidebar uploader

Click Process to prepare the documents for chat

Ask questions in the input box

View answers in a conversational chat format

## Future Improvements
Support additional document formats

Add user authentication and document management

Fine-tune models for domain-specific knowledge

Improve UI/UX and add more interactive features

## Setup and Installation

1. Clone this repository  
2. Create and activate a Python virtual environment  
3. Install dependencies:

```bash
pip install -r requirements.txt




