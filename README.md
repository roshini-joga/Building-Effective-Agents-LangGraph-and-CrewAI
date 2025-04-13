# Building Effective Agents: LangGraph and CrewAI Implementations

This repository contains two Google Colab notebooks demonstrating agent design patterns from "Building Effective Agents" using LangGraph and CrewAI frameworks.

## Notebooks

1. **LangGraph Agent Patterns with LangSmith Tracing**
   - Demonstrates prompt chaining, tool augmentation, and multi-agent collaboration.
   - Integrates LangSmith Studio for tracing and debugging.
   - [Colab Notebook](https://colab.research.google.com/github/langchain-ai/langsmith-cookbook/blob/main/tracing-examples/rest/rest.ipynb)

2. **CrewAI Agent Patterns**
   - Implements role-based agents with specific goals and backstories.
   - Showcases task orchestration and collaborative workflows.
   - [Colab Notebook](https://colab.research.google.com/github/crewAIInc/crewAI/blob/main/examples/agent_patterns.ipynb)

## Video Walkthroughs

- **LangGraph Implementation:** [LangGraph Crash Course #23 - LangSmith Tracing](https://www.youtube.com/watch?v=TwSDe7ydpTg)
- **CrewAI Implementation:** [AI Agent Design Patterns with CrewAI | Ingenium Academy](https://www.youtube.com/watch?v=hXjDDKQnf-A)

## Setup Instructions

### LangGraph Notebook

1. Install dependencies:
   ```bash
   pip install langchain_openai langgraph
