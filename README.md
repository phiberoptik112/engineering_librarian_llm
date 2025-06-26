# Engineering Librarian

## Overview
Engineering Librarian is an AI-powered knowledge management system that transforms static technical documentation into an intelligent, conversational database. It enables engineering teams to interact with their accumulated knowledge through natural language queries, making expertise more accessible and organizational learning more efficient.

## Key Features
- **Document Ingestion Pipeline**: Supports .txt, .docx, .xlsx, .pdf, .csv with smart processing and metadata extraction
- **Conversational Interface**: Natural language queries, contextual memory, source attribution, and multi-modal responses
- **AI Model Flexibility**: Switch between Anthropic API (cloud) and Ollama (local) for privacy and cost optimization
- **Intelligent Dashboard**: Real-time processing monitor, knowledge mapping, usage analytics, and AI-generated insights
- **Vector Database Management**: Local Chroma-based vector DB with semantic and hybrid search

## Technology Stack
- **Backend**: Python 3.10+, LangChain, FastAPI
- **Vector Database**: Chroma
- **Document Processing**: Unstructured, PyPDF2, pandas, python-docx
- **LLM Integration**: Anthropic API, Ollama
- **Frontend**: Streamlit (MVP), React (production)
- **Analytics**: Custom engine with structured logging

## Getting Started
1. **Clone the repository**
   ```bash
   git clone <repo-url>
   cd engineering_librarian_llm_project
   ```
2. **Set up Python environment**
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   pip install -r requirements.txt
   ```
3. **Configure environment variables**
   - Add API keys for Anthropic, Ollama, etc. in a `.env` file (see documentation for details)
4. **Run the application**
   - Instructions for running backend, frontend, and dashboard will be provided as components are implemented.

## Contribution Guidelines
- Follow PEP 8 for Python code style
- Use clear, descriptive commit messages
- Add tests for new features and bug fixes
- Document major changes in the `/docs` directory
- Open issues for feature requests and bug reports

## License
MIT License

---
For more details, see the full Product Requirements Document in `prd.txt`.
