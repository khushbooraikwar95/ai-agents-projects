The repository is organized by weekly milestones, each focusing on a specific paradigm of AI engineering:

1_foundations: Core concepts of Agentic AI and setting up the development environment.

2_openai: Implementing structured outputs and custom agents using the OpenAI SDK.

3_crew: Multi-agent orchestration using CrewAI for role-playing and collaborative tasks.

4_langgraph: Building cyclic, stateful agent workflows with LangGraph.

5_autogen: Exploring Microsoft’s AutoGen for conversational agent patterns.

6_mcp: Implementing the Model Context Protocol (MCP) to connect agents to external data sources.

🛠 Tech Stack
Language: Python 3.12

Orchestration: CrewAI, LangGraph, AutoGen

Models: OpenAI (GPT-4o), Google Gemini, DeepSeek

Package Management: UV (for lightning-fast dependency handling)

IDE: Cursor

🧠 Key Learnings & Skill Gains
Through this project, I have mastered several critical aspects of AI engineering:

Agentic Design Patterns: Learned when to use a simple "Tool-use" agent versus a complex "Multi-agent" hierarchy.

State & Memory Management: Implemented persistence in agents, allowing them to "remember" context across multiple interactions.

Human-in-the-loop (HITL): Developed workflows in LangGraph that pause for human approval before executing sensitive actions.

Error Handling & Robustness: Handled API rate limits, hallucination checks, and "self-healing" loops where agents correct their own code.

Environment Optimization: Used uv and pyproject.toml to maintain a clean, reproducible production-ready environment.

🚀 How to Run
Clone the Repository:

Bash
git clone https://github.com/khushbooraikwar95/ai-agents-projects.git
cd ai-agents-projects
Environment Setup:
Create a .env file and add your credentials:

Code snippet
OPENAI_API_KEY=your_key
GOOGLE_API_KEY=your_key
Install via UV:

Bash
uv sync


📬 Let's Connect!
I’m always open to discussing AI Agents, LLM Ops, or potential collaborations.

Linkedin: https://www.linkedin.com/in/khushboo-raikwar-25a83291/

Course Reference: Inspired by the Master AI Agentic Engineering curriculum.
