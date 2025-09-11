LangGraph
 extends LangChain by letting you build agentic AI systems as graphs — where each node is a step (tool, reasoning, memory) and edges define how the agent flows between them.

Why LangGraph?
    🕸️ Graph-based control – Explicit reasoning & workflows
    🔄 Customizable loops – Add retries, guardrails, or feedback
    🧩 Composable – Mix tools, memory, and LLMs
    🛠️ Debuggable – Visualize agent flow step by step

Core Components
    Nodes → Building blocks (LLMs, tools, condition checks, memory)
    Edges → Define transitions (deterministic or dynamic)
    State → Data passed across nodes (like memory/context)
    Graph Executor → Runs the workflow until completion