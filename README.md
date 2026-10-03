# Local-LLM-on-RX6600XT

## Main idea

- Use `llmfit` to find out which models can be run on the RX6600XT card
- Download the model(s) from HuggingFace 
- Use `llama.cpp` or `vllm` for hosting the models
- Use `uv` for environment and package management

## Setup

```bash
uv venv
uv init
```

```bash
winget install llama.cpp
uv pip install huggingface_hub
```

