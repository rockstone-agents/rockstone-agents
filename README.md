# 🤖 rockstone-agents

Agent 研发与实验的组织仓库。围绕 **LangGraph / LangGraph4j** 生态构建需求分析、工具调用与工作流编排类 Agent。

## 仓库导航

| 仓库 | 可见性 | 简介 |
|------|--------|------|
| [req-agent](https://github.com/rockstone-agents/req-agent) | 🔒 Private | LangGraph 需求分析 Agent：三层 Gatekeeper（格式 → 溯源 → 对抗评审）+ 双轴诚实导出（provenance × confirmed） |
| [langgraph-java-guide](https://github.com/rockstone-agents/langgraph-java-guide) | 🔒 Private | LangGraph4j 上手指南（Java 21 / Maven）：StateGraph 基础 → Studio 可视化 → DeepSeek 工具调用 Agent |
| [agent-sandbox](https://github.com/rockstone-agents/agent-sandbox) | 🌍 Public | Agent 实验的公开游乐场 |
| [agent-internal](https://github.com/rockstone-agents/agent-internal) | 🔒 Private | 内部 Agent 工作区 |

## 核心关注

- **LangGraph 生态** — Python（LangGraph）与 Java（LangGraph4j）双栈实践
- **Agent 质量** — Gatekeeper 校验、溯源闭环、eval 测评、对抗样本
- **LLM 接入** — DeepSeek（OpenAI 兼容协议）为主力模型
