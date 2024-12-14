# Magic Unicorn Presents... Cognitive Companion

Cognitive Companion is a fork of AnythingLLM reimagined as an advanced interface for modular AI systems. This project integrates Open Interpreter, Retrieval-Augmented Generation (RAG), and Magic Control Protocol (MCP) for seamless and extensible AI-driven workflows.

## Features
1. **Open Interpreter Integration**: Effortlessly run code snippets, process commands, and interact with various APIs, all through a natural language interface.
2. **Retrieval-Augmented Generation (RAG)**: Modular RAG pipeline using tools like txtai for contextual information retrieval. Supports local LLaMA models (7B and 13B quantized) for fast, efficient query responses.
3. **Magic Control Protocol (MCP)**: Centralized orchestration of connected AI modules, making complex task automation easier and more efficient. Real-time AI-to-AI communication and modular task management.
4. **Enhanced User Interface**: Intuitive UI built on the robust foundations of AnythingLLM. Customizable dashboards for tracking workflows and AI interactions.
5. **Open Source Philosophy**: Fully open-source with modularity at its core, allowing users to adapt, extend, and innovate.

## Installation Instructions
### Requirements
- Python 3.10+
- Node.js 18+
- Tesla P40 GPU (Optional): Recommended for GPU-accelerated model inference.

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/MagicUnicornInc/Cognitive-Companion.git
   cd Cognitive-Companion
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   npm install
   ```
3. Configure the environment:
   - Add your RAG data source (e.g., txtai or custom embeddings).
   - Connect Open Interpreter via interpreter.config.json.
   - Set up MCP modules in mcp.config.json.
4. Run the application:
   ```bash
   npm run dev
   ```

## Use Cases
- **AI Research Companion**: Summarize papers, generate code, or analyze data with Open Interpreter.
- **Enterprise AI**: Build intelligent document workflows with RAG and scalable AI.
- **Creative Automation**: Use MCP to orchestrate complex AI pipelines for content generation, task management, and more.
- **Personal Productivity**: Organize schedules, retrieve personal data, and manage projects effortlessly.

## Documentation
- Setup Guide: docs/setup.md
- Customizing Pipelines: docs/pipelines.md
- Extending MCP: docs/mcp.md

## Contributions
We welcome contributions that align with our mission of creating a fully modular and extensible AI platform. Check out the contributing guidelines to get started.

## Acknowledgments
This project is based on the excellent work of AnythingLLM. Credit goes to the original authors for laying the groundwork.
