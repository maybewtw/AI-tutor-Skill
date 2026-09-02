# Harness 学习导航

这是 AI Tutor 基于公开权威资料整理的学习导航，不是任何一家公司的原始白皮书。涉及具体产品和版本时，以 `INDEX.md` 中的原始来源为准。

## 工作定义

在 Agent 场景中，**Harness 是包围模型的运行与控制系统**：它决定模型能看到什么、能调用哪些工具、如何保存状态、如何获得环境反馈、何时重试或暂停、怎样评估结果，以及如何在安全边界内继续执行。

不要把 Harness 等同于 Prompt，也不要把它等同于模型本身。模型提供推理能力；Harness 提供任务循环、上下文、工具、状态、资源预算和验证机制。

## 建议学习顺序

1. **模型、Agent、Workflow、Harness 的边界**
   - 阅读 Anthropic 的 [Building effective agents](https://www.anthropic.com/engineering/building-effective-agents)。
2. **最小 Agent Loop**
   - 理解：观察环境 → 组织上下文 → 调用模型 → 执行工具 → 获取结果 → 再循环，直到完成或触发停止条件。
3. **上下文与状态**
   - 区分上下文窗口、会话状态、长期记忆、压缩、检查点和恢复。
   - 阅读 Anthropic 的 [Effective context engineering](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents)。
4. **工具与 MCP**
   - 学习工具 schema、参数设计、错误返回、MCP、工具发现和按需加载。
   - 阅读 [Advanced tool use](https://www.anthropic.com/engineering/advanced-tool-use) 与 [Code execution with MCP](https://www.anthropic.com/engineering/code-execution-with-mcp)。
5. **长时任务与增量进展**
   - 学习 initializer、progress artifact、feature list、clean state 和多上下文窗口衔接。
   - 阅读 Anthropic 的 [Effective harnesses for long-running agents](https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents)。
6. **安全、沙箱与权限**
   - 分析 Prompt Injection、凭证隔离、工具权限、网络边界和人工确认。
7. **评估 Harness**
   - 区分模型能力、脚手架诱发出的能力和端到端系统能力。
   - 阅读 OpenAI 的 [Agent 评估说明](https://openai.com/index/trustworthy-third-party-evaluations-foundations/)。
8. **产品与平台视角**
   - 比较一次性 Workflow、可复用 Agent Runtime 和平台能力的收益、成本、可观测性与治理问题。

## 掌握标准

- 能用自己的话画出组件和数据流；
- 能说明一个设计为什么需要或不需要 Harness；
- 能指出至少两个失败模式及其控制点；
- 能把技术选择映射到质量、成本、延迟、风险和用户体验指标；
- 能分析一个新案例，而不是只复述原文。

