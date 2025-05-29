# Agentic Workflow using LangGraph (Simulated with Groq API)

## Overview
This project implements an agentic workflow that:
1. Splits a user query into sub-tasks using a PlanAgent
2. Solves each sub-task with a ToolAgent
3. Improves results using reflection

Built using:
- Groq API (LLaMA 3)
- Python (Colab Notebook)
- LangGraph workflow style (simulated)

## How to Run
1. Open the notebook in Google Colab
2. Paste your Groq API key
3. Run all cells

## Demo Query
> "Explain how Data Science is used in Legal Practice and give two examples."

## Output
- Subtasks planned
- Each subtask solved
- Results reflected and improved
