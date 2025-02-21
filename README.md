# RAG from Scratch (Python Script)

## Overview

This Python notebook implements a **Retrieval-Augmented Generation (RAG)** pipeline. It processes documents, extracts meaningful text embeddings, and retrieves relevant information to generate responses using a language model.

## Features

- **PDF Processing:** Extracts and processes text from a PDF document.
- **Text Chunking:** Splits extracted text into smaller, meaningful chunks.
- **Embedding Creation:** Generates vector embeddings using sentence transformers.
- **Retrieval System:** Finds relevant document chunks for a given query.
- **Generative AI Integration:** Uses a transformer-based language model to generate responses.
- **Streamlit App:** Provides an interactive UI for querying documents.

## Requirements

To run this script, ensure you have the following installed:

- Python >=3.12
- Required Python libraries:
  numpy pandas torch fitz pymupdf sentence_transformers transformers faiss-cpu spacy tqdm streamlit


## Customization

- Modify the PDF file path to process different documents.
- Adjust text chunking size for different levels of granularity.
- Change the embedding model to experiment with different vectorization techniques.
- Integrate alternative retrieval mechanisms such as BM25.
- Swap out the generative model for other transformer-based models.  
