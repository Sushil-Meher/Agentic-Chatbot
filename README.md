# Ollama LangGraph Agent

An Agentic AI development project exploring local LLM inference, stateful workflows, tool calling, and graph-based agent orchestration using Ollama, LangChain, and LangGraph.

## Project Goal

Build an agent that can interpret user requests, maintain conversation state, decide when tools are needed, execute appropriate actions, and generate responses using a locally hosted language model.

## Tech Stack

- **Python** — application development
- **Ollama** — local LLM inference
- **Qwen3 4B** — language model
- **LangChain** — model and tool integrations
- **LangGraph** — agent workflow orchestration
- **Jupyter Notebook** — experimentation and prototyping

## Current Progress

- [x] Python virtual environment configured
- [x] Core dependencies installed
- [x] Ollama model integration tested
- [x] Basic LangGraph workflow executed
- [x] Initial message-state handling explored
- [ ] Tool calling and tool execution
- [ ] Conditional routing between graph nodes
- [ ] Multi-step agent workflows
- [ ] Persistent conversation memory
- [ ] Automated tests and evaluation

## Architecture

The intended workflow is:

User Input → Agent Node → Tool Selection → Tool Execution → Agent Response

The graph will be extended with conditional transitions and additional nodes as the project develops.

## Setup

### 1. Install prerequisites

Install Python and Ollama. Download the model:

```bash
ollama pull qwen3:4b
```

### 2. Clone the repository

```bash
git clone YOUR_REPOSITORY_URL
cd ollama-langgraph-agent
```

### 3. Create a virtual environment

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

### 4. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 5. Run the notebook

Open `notebooks/chatbot.ipynb` in VS Code, select the `.venv` kernel, and execute the cells.

## Planned Extensions

- LangGraph tool calling and conditional routing
- External tool integration
- Retrieval-augmented generation (RAG)
- Persistent state and conversation memory
- FastAPI deployment
- Integration with an agentic e-commerce application

## Learning Focus

This repository documents the progression from a basic local LLM workflow to a tool-using agent with explicit state management, controlled execution, and measurable evaluation.
