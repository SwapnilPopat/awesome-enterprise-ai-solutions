# Local LLM Chatbot with Llama/Qwen + LangChain

A beginner-friendly tutorial to build a simple conversational AI that runs entirely locally using open-source LLMs and LangChain.

## What You'll Learn

- Set up and use open-source LLMs locally (Llama 3, Qwen, etc.)
- Build conversational chains with LangChain
- Create a simple CLI chatbot interface
- Understand memory and context management in LLMs

## Prerequisites

- Python 3.10+
- ~8GB RAM (for running local LLMs)
- Basic Python knowledge

## Architecture

```
User Input
   |
   v
LLM Model (Local - Llama/Qwen)
   |
   v
LangChain Conversation Chain
   |
   v
Chatbot Response
```

## Quick Start

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Download a local LLM:
   ```bash
   # Using Ollama (recommended)
   ollama pull llama2
   ollama serve
   ```

3. Run the chatbot:
   ```bash
   python chatbot.py
   ```

## Project Structure

```
.
├── chatbot.py              # Main chatbot application
├── requirements.txt        # Python dependencies
├── .env.example           # Configuration template
└── README.md              # This file
```

## Configuration

Create a `.env` file (copy from `.env.example`):

```env
LLM_MODEL=llama2
LLM_BASE_URL=http://localhost:11434
MAX_TOKENS=512
```

## Next Steps

- Add vector memory for long-term conversation context
- Integrate with RAG for knowledge base
- Deploy as a web service with FastAPI

## References

- [LangChain Documentation](https://python.langchain.com/)
- [Ollama](https://ollama.ai/)
- [Llama 2 Model](https://github.com/meta-llama/llama-2)
