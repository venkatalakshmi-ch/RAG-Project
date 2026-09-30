# RAG Project

A Retrieval-Augmented Generation (RAG) project built with Python, ChromaDB, vector embeddings, and LLM APIs. The project demonstrates both foundational and advanced RAG techniques for improving document retrieval and generating context-aware responses.

## Features

- Retrieval-Augmented Generation (RAG)
- Semantic document retrieval
- Vector storage and retrieval using ChromaDB
- Sentence Transformer embeddings
- PDF document ingestion and text extraction
- Recursive and token-based document chunking
- Query expansion and multi-query retrieval
- Answer expansion
- Document reranking
- Dense Passage Retrieval (DPR)
- Retrieval result deduplication
- LLM-based response generation and summarization
- Environment variable management using `python-dotenv`

## Advanced RAG Techniques

### Query Expansion

Generates multiple related queries from the original user question and retrieves relevant documents for each variation to improve retrieval coverage.

### Answer Expansion

Uses answer-based expansion to provide additional semantic context and improve document retrieval.

### Reranking

Reranks retrieved documents to prioritize the most relevant context before generating the final response.

### Dense Passage Retrieval (DPR)

Explores dense retrieval techniques for identifying semantically relevant passages using vector representations.

## Project Structure

```text
RAG-Project/
├── app.py
├── dpr_technique.py
├── expansion_answer.py
├── expansion_queries.py
├── helper_utils.py
├── reranking.py
├── requirements.txt
├── data/
│   └── microsoft-annual-report.pdf
├── news_articles/
├── chroma_persistent_storage/
├── .gitignore
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/venkatalakshmi-ch/RAG-Project.git
```

Navigate to the project directory:

```bash
cd RAG-Project
```

### Using Conda

This setup requires Anaconda or Miniconda.

Create a Conda environment inside the project directory:

```bash
conda create --prefix ./env
```

Activate the environment:

```bash
source activate ./env
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

> If you are not using Conda, you can create and activate a Python virtual environment using your preferred environment management tool and then install the dependencies from `requirements.txt`.

## Environment Variables

Create a `.env` file in the project directory and add your OpenAI API key:

```text
OPENAI_API_KEY=your_api_key_here
```

Do not commit the `.env` file to GitHub.

## Run the Application

Run the main RAG application:

```bash
python app.py
```

## Advanced RAG Examples

The advanced RAG techniques can be explored through the individual scripts:

```bash
python expansion_queries.py
python expansion_answer.py
python reranking.py
python dpr_technique.py
```

## Technologies

- Python
- ChromaDB
- OpenAI API
- LangChain
- Sentence Transformers
- PyPDF
- Vector Embeddings
- Retrieval-Augmented Generation (RAG)

## Author

Venkat Lakshmi Chinthalapudi
