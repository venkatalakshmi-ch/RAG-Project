# RAG Project

A Retrieval-Augmented Generation (RAG) application built with Python and ChromaDB. The project retrieves relevant information from a local knowledge base and uses the retrieved context to generate more grounded responses.

## Features

- Retrieval-Augmented Generation (RAG)
- Semantic document retrieval
- Vector storage using ChromaDB
- Persistent vector database
- Environment variable management with python-dotenv
- Python-based implementation

## Project Structure

RAG-Project/
├── app.py
├── requirements.txt
├── news_articles/
├── chroma_persistent_storage/
├── .gitignore
└── README.md

## Installation

Clone the repository:

git clone https://github.com/venkatalakshmi-ch/RAG-Project.git

Navigate to the project:

cd RAG-Project

Create a virtual environment:

python3 -m venv env

Activate it on macOS/Linux:

source env/bin/activate

Install dependencies:

pip install -r requirements.txt

## Environment Variables

Create a `.env` file in the project directory and add the required API keys.

Example:

API_KEY=your_api_key_here

Do not commit the `.env` file to GitHub.

## Run the Application

python3 app.py

## Technologies

- Python
- ChromaDB
- Retrieval-Augmented Generation (RAG)
- Vector Embeddings
- LLM APIs

## Author

Venkat Lakshmi Chinthalapudi