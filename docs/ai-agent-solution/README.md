# AI / Agent 文档总览

本目录用于承载“任务分配与自动检核系统”的 AI / Agent 分层文档。

## 文档结构

1. [总体方案蓝图](/Users/zhouzhixiong/code/zuozhanV2/docs/ai-agent-solution/01-overall-blueprint.md)
说明：
用于描述系统的整体目标、能力地图、数据架构、Agent 设计、评估体系、风控与中长期路线图。

2. [基于现状的 V2 落地实施方案](/Users/zhouzhixiong/code/zuozhanV2/docs/ai-agent-solution/02-v2-implementation-plan.md)
说明：
用于描述在当前已有成熟方案基础上，下一步如何演进，以及版本规划和实施顺序。

3. [自然语言计划生成的数据准备与存储设计](/Users/zhouzhixiong/code/zuozhanV2/docs/ai-agent-solution/03-nl-plan-data-design.md)
说明：
用于描述自然语言计划生成所需的 6 类核心数据、表设计建议、存储分层和使用方式。

4. [自然语言计划生成的时序流程设计](/Users/zhouzhixiong/code/zuozhanV2/docs/ai-agent-solution/04-nl-plan-sequence-design.md)
说明：
用于描述自然语言计划生成的主链路、校验点、降级策略和推荐实施顺序。

5. [自然语言计划生成的意图理解设计](/Users/zhouzhixiong/code/zuozhanV2/docs/ai-agent-solution/05-nl-plan-intent-understanding.md)
说明：
用于描述术语归一化、槽位抽取、缺失项识别、候选筛选意图以及如何映射到商家服务字段/标签/枚举。

## 阅读建议

1. 管理层：
先看 [总体方案蓝图](/Users/zhouzhixiong/code/zuozhanV2/docs/ai-agent-solution/01-overall-blueprint.md)，再看 [基于现状的 V2 落地实施方案](/Users/zhouzhixiong/code/zuozhanV2/docs/ai-agent-solution/02-v2-implementation-plan.md)

2. 产品经理：
优先看 [基于现状的 V2 落地实施方案](/Users/zhouzhixiong/code/zuozhanV2/docs/ai-agent-solution/02-v2-implementation-plan.md)，需要补自然语言能力时再看 [自然语言计划生成的数据准备与存储设计](/Users/zhouzhixiong/code/zuozhanV2/docs/ai-agent-solution/03-nl-plan-data-design.md)

3. 技术和数据团队：
先看 [基于现状的 V2 落地实施方案](/Users/zhouzhixiong/code/zuozhanV2/docs/ai-agent-solution/02-v2-implementation-plan.md)，再看 [自然语言计划生成的数据准备与存储设计](/Users/zhouzhixiong/code/zuozhanV2/docs/ai-agent-solution/03-nl-plan-data-design.md)、[自然语言计划生成的时序流程设计](/Users/zhouzhixiong/code/zuozhanV2/docs/ai-agent-solution/04-nl-plan-sequence-design.md) 和 [自然语言计划生成的意图理解设计](/Users/zhouzhixiong/code/zuozhanV2/docs/ai-agent-solution/05-nl-plan-intent-understanding.md)

## 采用原则

1. 中长期架构和能力边界，以 [总体方案蓝图](/Users/zhouzhixiong/code/zuozhanV2/docs/ai-agent-solution/01-overall-blueprint.md) 为参考
2. 真实排期和实施顺序，以 [基于现状的 V2 落地实施方案](/Users/zhouzhixiong/code/zuozhanV2/docs/ai-agent-solution/02-v2-implementation-plan.md) 为准
3. 自然语言计划生成相关的开发实现，以 [自然语言计划生成的数据准备与存储设计](/Users/zhouzhixiong/code/zuozhanV2/docs/ai-agent-solution/03-nl-plan-data-design.md) 和 [自然语言计划生成的时序流程设计](/Users/zhouzhixiong/code/zuozhanV2/docs/ai-agent-solution/04-nl-plan-sequence-design.md) 为专项设计依据
4. 涉及“自然语言如何理解并映射到商家筛选 DSL”的实现细节，以 [自然语言计划生成的意图理解设计](/Users/zhouzhixiong/code/zuozhanV2/docs/ai-agent-solution/05-nl-plan-intent-understanding.md) 为准
