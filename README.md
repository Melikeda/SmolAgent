# SmolAgent - Agent Development with Local LLM and Smolagents

This project aims to build and test autonomous AI agents using Hugging Face's **`smolagents`** framework and the **Qwen 3.5** model running locally via **Ollama**.

Key concepts covered in this repository include local LLM integration, custom tool definitions (`@tool`), the differences between `ToolCallingAgent` and `CodeAgent`, and inspecting agent memory/step traces.

---

## 🛠️ Tech Stack

- **Python:** 3.10+
- **Package Manager:** `uv`
- **Agent Framework:** `smolagents`
- **Model Server:** Ollama (`ollama_chat/qwen3.5:9b`)
- **Model Interface:** `LiteLLMModel`

---

## 📂 Repository Structure

- `01_reasoning_yaklasimlari.ipynb`: Agent reasoning techniques and workflows.
- `02_agent_promptu.ipynb`: System prompts and agent instructions.
- `05_ToolCallingAgent.ipynb`: JSON/Tool-calling based agent implementation.
- `06_CodeAgent.ipynb`: Code-executing agent (`CodeAgent`) implementation.

---

## 🚀 Getting Started

1. Clone the Repository

git clone [https://github.com/Melikeda/SmolAgent.git](https://github.com/Melikeda/SmolAgent.git)
cd SmolAgent

2. Install Dependencies with

uv sync

3. Start Ollama

Ensure Ollama is running in the background and the model is pulled:
ollama run qwen3.5:9b

