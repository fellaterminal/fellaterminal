## System Architecture

fellaterminal's system architecture consists of the following key components:

1. **User Interface**: A web-based chat interface for interacting with fellaterminal, viewing project files, and monitoring the agent's state.
2. **Agent Core**: The central component that orchestrates the AI planning, reasoning, and execution process. It communicates with various sub-agents and modules to accomplish tasks.
3. **Large Language Models**: fellaterminal leverages state-of-the-art language models like **Claude**, **GPT-4**, and **Local LLMs via Ollama** for natural language understanding, generation, and reasoning.
4. **Planning and Reasoning Engine**: Responsible for breaking down high-level objectives into actionable steps and making decisions based on the current context.
5. **Research Module**: Utilizes keyword extraction and web browsing capabilities to gather relevant information for the task at hand.
6. **Code Writing Module**: Generates code based on the plan, research findings, and user requirements. Supports multiple programming languages.
7. **Browser Interaction Module**: Enables fellaterminal to navigate websites, extract information, and interact with web elements as needed.
8. **Knowledge Base**: Stores and retrieves project-specific information, code snippets, and learned knowledge for efficient access.
9. **Database**: Persists project data, agent states, and configuration settings.

Read [ARCHITECTURE.md](https://github.com/stitionai/fellaterminal/Docs/architecture/ARCHITECTURE.md) for the detailed architecture of fellaterminal.
Read [UNDER_THE_HOOD.md](https://github.com/stitionai/fellaterminal/Docs/architecture/UNDER_THE_HOOD.md) for the detailed working of fellaterminal.
