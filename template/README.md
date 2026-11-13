# Agent name

One sentence on what it does and who it is for.

## Run it

How to run it on the maava platform, and locally.

## Environment variables

| Name | Purpose |
| --- | --- |
| `EXAMPLE_API_KEY` | What it is for |

## Data

What the agent collects, where it goes and when it is deleted.

## Team and libraries

`src/graph.py` runs a LangGraph team (planner, researcher, writer, reviewer) from `sub_agents/`. Real agent repos also carry `libs/langgraph` and `libs/langchain` as submodules (`git submodule add --depth 1 https://github.com/langchain-ai/langgraph.git libs/langgraph`).
