# AI-Powered Document Q&A Assistant

An AI-powered Question & Answer (Q&A) assistant that allows users to upload PDF documents and ask questions about their content in natural language. Built using **LlamaIndex**, **HuggingFace Transformers**, and **Sentence Transformers**, this tool extracts text from PDFs, understands it, and provides intelligent answers—similar to ChatGPT but fully customizable and open-source.

## Features
- Upload and analyze PDF documents.
- Ask questions in natural language and get AI-generated answers.
- Uses **Mistral-7B-Instruct** for text generation and **all-MiniLM-L6-v2** for embeddings.
- Secure handling of API keys via `.env` file.
- Optimized for performance with GPU support (if available).

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/ai-document-qa.git
   cd ai-document-qa
