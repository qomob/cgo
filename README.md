# AI CGO — AI Chief Growth Officer

AI驱动的企业增长操作系统。增长决策系统 + AI工作流编排器 + 自动优化引擎。

## 架构：Router + 3 模式

```
User Input → Router → Diagnoser (增长问题诊断)
                    → Designer (机会探索 / 工作流设计)
                    → Optimizer (审计与优化)
```

**v2 升级要点：**
- **Router 路由架构** — 根据输入信号精确分类，路由到专用模式
- **3 模式分工** — Diagnoser 诊断瓶颈 / Designer 设计方案 / Optimizer 优化现有系统
- **输入校验** — 结构化 intake schema，缺失字段自动追问
- **Fallback 容错表** — 7 种异常场景的恢复策略
- **Session Memory** — 跨轮对话上下文跟踪
- **触发器分级** — 一级精确匹配 / 二级上下文判断 / 排除场景负向路由

## Diagnoser 模式（增长问题）

六段式输出：诊断 → 机会 → 工作流 → 自动化 → KPI → 实验循环

Focus: 识别一个核心瓶颈，量化影响，给出可执行方案。

## Designer 模式（机会探索 / 工作流设计）

- **机会探索**：机会地图 + Use Case + 优先级矩阵
- **工作流设计**：Agent 架构 + 组件规格 + 实施路线图 + 成本模型

## Optimizer 模式（审计与优化）

审计现有漏斗/系统 → 优先级修复计划 → AI 改造点 → 预期改善度量

## 参考文档

| 文档 | 用途 |
|------|------|
| [capability-model.md](references/capability-model.md) | 6层CGO能力模型：增长策略→AI系统能力→执行→数据飞轮→组织→进阶 |
| [harness-engineering.md](references/harness-engineering.md) | Harness工程框架：R.E.S.T.模型 + PPAF Agent循环 + 安全约束 |
| [workflow-design.md](references/workflow-design.md) | AARRR各阶段工作流模式 + Agent编排模式 |

## 触发场景

- 分析业务增长瓶颈并制定AI增长策略
- 设计AI驱动的工作流和自动化增长系统
- 用AI重构营销、销售、转化流程
- 建立增长数据飞轮和KPI体系
- 规划Multi-Agent增长系统架构
- 企业AI转型增长落地咨询

## 安装

将 `ai-cgo` 目录导入 Trae / OpenClaw / Hermes Agent 等即可使用。

## License

Apache-2.0
