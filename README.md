# Zhongyuan Zou

**Software Engineering · Xiamen University Malaysia**

我关注推荐系统的离线评测、智能体工具调用与记忆，以及后端工作流中的状态设计。

[作品集](https://zou-zhongyuan.github.io/) · [交互评测图表](https://zou-zhongyuan.github.io/#ranklab) · [技术笔记](https://zou-zhongyuan.github.io/#writing)

## Featured experiment · RankLab

在 MovieLens Latest Small 与 1M 上对比召回、重排、全候选与抽样候选评测。用逐用户记录复算了两个数据集的 28 组 NDCG@10 均值。

MovieLens 1M 上，同一对模型的排序随候选池变化。每列是独立评测口径，均为 3 个随机种子的均值。

| 模型 | 全候选 NDCG@10 | 抽样候选 NDCG@10 |
| :--- | ---: | ---: |
| BPR-MF | 0.26695 | **0.76598** |
| BPR-MF + HistGBDTRerank | **0.28819** | 0.72407 |

[查看两个数据集的完整对比](https://zou-zhongyuan.github.io/#ranklab)

## Project index · 项目索引

| 项目 | 方向 | 已有证据 |
| :--- | :--- | :--- |
| [ToolForge](https://zou-zhongyuan.github.io/#toolforge) | 工具调用评测协议 | 120 道组合任务通过参考策略和无动作反例核验，属非模型流水线验证 |
| [AgentMemoryLab](https://zou-zhongyuan.github.io/#agentmemorylab) | 对话记忆与 token 预算 | 68 道合成题 × 4 种方法逐项复现 |
| [ForgePilot](https://zou-zhongyuan.github.io/#forgepilot) | 工作流、审批与状态管理 | 20 项本地后端测试通过，工作流采用模拟配置 |
| [Agent Review](https://zou-zhongyuan.github.io/#agent-review) | 软件工程智能体研究综述 | 21 篇纳入的筛选账本，草稿尚未投稿 |
| [Career Research](https://zou-zhongyuan.github.io/#career-research) | 技术主题与岗位研究 | 46 条公开岗位核验记录与 6 项技术主题的日期快照 |
| [Campus Checkout](https://github.com/Zou-Zhongyuan/campus-checkout-workflow) | Python 结账状态机 | 16 项单元测试，覆盖重放、错序重试与退款 |

这些项目使用 Antigravity 等工具辅助开发。作品集里的项目详情记录了数据来源、验证范围与待完成步骤。

## Writing · 技术笔记

- [支付成功之后，订单为什么还要等商家接单？](https://zou-zhongyuan.github.io/#article-payment-acceptance)
- [用 49、50、51 检查边界条件](https://zou-zhongyuan.github.io/#article-bva-49-50-51)
