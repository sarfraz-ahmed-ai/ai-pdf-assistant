# AI PDF Assistant

A free, local AI-powered PDF question-answering prototype built using Python, PyMuPDF, Ollama, and Qwen2.5.

## Overview

AI PDF Assistant extracts text from PDF documents and uses a locally running language model to answer questions about their contents.

The project was developed in Google Colab as a learning and experimentation project.

## Features

- Extract text from PDF documents using PyMuPDF.
- Combine text from multiple PDF pages.
- Split extracted text into smaller chunks.
- Search chunks using case-insensitive keyword matching.
- Select a chunk based on keyword frequency.
- Generate answers using Ollama and Qwen2.5 (1.5B).
- Ask questions interactively in a notebook.

## Technologies

- Python
- Google Colab
- PyMuPDF
- Ollama
- Qwen2.5:1.5b

## Current Limitations

- Retrieval uses basic keyword matching, not semantic search.
- The retrieval demonstration uses a manually chosen keyword.
- Answer quality depends on the selected text and language model.
- Model inference can be slow in Google Colab.
- The project is a notebook prototype, not a deployed web application.

## Project Status

**Prototype — Work in Progress**

The core PDF extraction, local AI answering, and basic retrieval workflow have been tested.

## Cost

No paid AI API is required. The project uses a local Ollama model, although running it requires computing resources.

## Notebook

Open `AI_PDF_Assistant_Public.ipynb` to explore the implementation.
