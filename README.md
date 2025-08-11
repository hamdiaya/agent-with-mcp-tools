# Agent with MCP Tools

A simple AI agent built with [smolagents](https://github.com/huggingface/smolagents) that connects to external tools using the Model Context Protocol (MCP) and interacts through a [Gradio](https://www.gradio.app/) chat interface.  
The agent uses a Hugging Face Inference API model to answer questions, execute code, and leverage remote tools.

## ✨ Features
- **MCP Integration** – Connects to remote tools via Model Context Protocol.
- **Hugging Face Model** – Uses your HF API token to run an inference model.
- **Dynamic Code Execution** – The agent can execute Python code securely.
- **Gradio UI** – Simple and responsive web-based chat interface.

## 📦 Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/your-username/agent-with-mcp-tools.git
cd agent-with-mcp-tools
pip install -r requirements.txt
