# Multi-Agent_Memory_Pool_Harness
A structured long-term memory system for multi-agent collaboration using hierarchical catalog + timeline + AI compilation.

# 多智能体记忆池

**为多智能体协作设计的结构化长期记忆系统。**  
受Karpathy“LLM即编译器”理念启发，解决大模型多轮对话中的上下文溢出、记忆丢失、信息冲突问题。

## 核心设计

- **分级目录（本体）**：树状结构存放长半衰期知识单元（概念、决策、原理）。
- **时间轴（复线）**：线性记录计划、执行与里程碑，与本体双向链接。
- **AI编译**：原始聊天记录 → `AGENTS.md`规则 → 结构化Wiki笔记，带来源追溯与冲突处理。

## 主要特性

- **人在回路**：人工筛选 + AI编译，保证知识质量。
- **版本控制**：完整Git历史，支持回滚，防止记忆污染。
- **多智能体就绪**：为共享记忆池设计，支持基于角色的访问控制（规划中）。

## 使用场景

- 个人AI助手（如“贾维斯”）的长期对话记忆
- 多个专家智能体（学督、健身教练等）的协作记忆池
- 考研/学习/健康管理的知识库

## 当前状态

- 编译规则已定义（`AGENTS.md`）
- 已整理50万+ token真实聊天语料
- 与Obsidian + Git联动，日常可用

## 路线图

- [ ] MVP：手动编译单个话题
- [ ] 半自动编译脚本
- [ ] 接入Hermes Agent实现对话检索
- [ ] 多智能体权限隔离

## 链接

- 技术报告（待补充）
- 编译示例：`/examples`

## 许可证

MIT
