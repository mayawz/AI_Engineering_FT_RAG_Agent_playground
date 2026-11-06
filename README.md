# RAG and Agentic AI playground
### Host a series of RAG, Agentic, multimodal projects for learning and practicing purpose
- Agentic RAG with LlamaIndex
- Job search assistant for learning about the company
- Multimodal chatbot with Gradio

### Environment Setup
Use [uv](https://docs.astral.sh/uv/) to create and sync the shared Python 3.12 environment from the repository root:

```sh
uv sync
```

This creates `.venv` and installs the dependencies for all projects in this playground. Run Python commands in that environment with `uv run`, or select `.venv/bin/python` as the interpreter/kernel in your editor or notebook.

The shared environment uses OpenAI 2.x, Gradio 6.x, and protobuf 5.x to reconcile conflicting versions in the source setup files.
