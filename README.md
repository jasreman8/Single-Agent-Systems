# Single-Agent-Systems
This repository contains various single-agent projects that were created using tools like CrewAI and LangGraph:

Project 1: Built a single-agent customer support system using CrewAI, tool calling, and ReAct
  - Implemented a single-agent e-commerce support workflow using CrewAI and ReAct,
  - Define tools for handling orders, products, returns, and escalations,
  - Connected tools to a support agent that autonomously reasons, selects tools, and responds to customer queries within a sequential crew setup.

Project 2: Implement ReAct-based e-commerce customer support agent using pre-built and custom ReAct workflows,
  - Added pre-built ReAct agent using `create_react_agent` from LangChain,
  - Implemented a custom ReAct agent by wiring functions/tools into a LangGraph workflow,
  - Demonstrated use of functions as tools in a single-agent conversational system,
  - Included examples for handling orders, products, returns, and escalation scenarios,
  - Documented differences between high-level and custom ReAct approaches.

Project 3: Implement SQL ReAct agent using LangGraph and LangChain SQL toolkit
  - Added AI agent using LangGraph's `create_react_agent` pre-built workflow,
  - Integrated LangChain SQLDatabaseToolkit for schema inspection, table listing, and SQL execution,
  - Enabled natural language → SQL translation with automated query validation,
  - Implemented tool-driven ReAct loop for reasoning and action selection,
  - Created a simple conversational interface that executes SQL queries safely,
  - Demonstrated how LangGraph can serve as a lightweight NL-to-SQL agent framework,
  - Added documentation explaining workflow, tool use, and example queries.

Project 4: Implement a self-reflective RAG agent using LangGraph
  - Built a LangGraph RAG workflow with explicit decision nodes for context relevance,
  - Added a reflection step to check retrieved chunks against the user’s question,
  - Implemented query rewriting and retrieval retry when context is insufficient,
  - Wired the agent to generate precise answers only when relevant context is found,
  - Documented the workflow to highlight how self-reflection improves reliability
