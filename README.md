# 🤖 rockstone-agents

Organization for agent R&D and experiments. Building requirement-analysis, tool-calling and workflow-orchestration agents around the **LangGraph / LangGraph4j** ecosystem.

## Repository Guide

| Repository | Visibility | About |
|------------|------------|-------|
| [req-agent](https://github.com/rockstone-agents/req-agent) | 🔒 Private | LangGraph requirements-analysis agent: three-layer gatekeeper (format → provenance → adversarial review) + two-axis honest export (provenance × confirmed) |
| [langgraph-java-guide](https://github.com/rockstone-agents/langgraph-java-guide) | 🔒 Private | LangGraph4j hands-on guide (Java 21 / Maven): StateGraph basics → Studio visualization → tool-calling agent with DeepSeek |
| [agent-sandbox](https://github.com/rockstone-agents/agent-sandbox) | 🌍 Public | Public playground for agent experiments |
| [agent-internal](https://github.com/rockstone-agents/agent-internal) | 🔒 Private | Internal agent workspace |

## Focus Areas

- **LangGraph ecosystem** — dual-stack practice in Python (LangGraph) and Java (LangGraph4j)
- **Agent quality** — gatekeeper validation, provenance loops, eval harnesses, adversarial samples
- **LLM integration** — DeepSeek (OpenAI-compatible API) as the primary model
