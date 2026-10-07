# AI 产品研究笔记

> 关于 Agent、评测、上下文工程、AI Coding 与 AI Native 产品工作的持续记录。

这些文章不是概念整理，也不追求把每个术语解释得面面俱到。我更关心一个问题：当 AI 真正进入产品流程，产品经理应该如何定义任务、判断结果、处理失败，并把一次经验变成可复用的方法。

## 第一辑：从“能回答”到“能交付”

| # | 文章 | 核心问题 |
| --- | --- | --- |
| 01 | [为什么 Agent 评测不能只看回答质量](notes/01-agent-evaluation.md) | 文本正确为什么仍可能交付失败？ |
| 02 | [为什么 RAG 不是企业 Agent 的终点](notes/02-rag-and-context.md) | AI 缺的是资料，还是完整工作环境？ |
| 03 | [Agent 什么时候应该自主决策，什么时候应该使用固定工作流](notes/03-agent-vs-workflow.md) | 自主性应该放在哪一层？ |
| 04 | [AI Coding 真正改变的不是写代码速度](notes/04-ai-coding.md) | 产品经理为什么也应该做可运行原型？ |
| 05 | [AI 产品从“能用”到“可靠”需要什么](notes/05-reliable-ai-product.md) | 如何让结果可相信、可追溯、可控制？ |
| 06 | [AI Native 团队中，产品经理的角色正在发生什么变化](notes/06-ai-native-pm.md) | 产品工作如何从文档向实验与交付延伸？ |

## 对应实践

- [Agent 评测实验室](https://github.com/ljj24681379-png/agent-evaluation-lab)：把工具、产物、稳定性和修复纳入端到端评测。
- [AI 上下文工程实验](https://github.com/ljj24681379-png/ai-context-engineering)：让 Agent 逐步寻找资料、查询数据并验证结论。
- [一人 AI 产品团队](https://github.com/ljj24681379-png/ai-product-team)：探索多个 Agent 的任务拆分、交接与验收。
- [AI 产品可靠性实验](https://github.com/ljj24681379-png/reliable-ai-agent)：设计双路校验、可信等级、追溯和异常接管。
- [多 Agent 产品研究工作流](https://github.com/ljj24681379-png/multi-agent-research)：把研究过程拆成搜集、分析、对比、报告与审核。

## 写作原则

- 从具体产品问题出发，不堆术语；
- 区分事实、推断与个人判断；
- 不用未经验证的数据包装结论；
- 尽量给出能够落到产品流程的动作。

当前 6 篇为第一版，会随着对应项目推进继续补充案例、反例与验证结果。
