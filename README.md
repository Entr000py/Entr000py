# 姜飞

做 Agent 应用：把用户的一句话变成可执行的推荐、检索和任务状态。

下面四篇笔记各讲一个机制，场景来自实习里的真实问题。

## 笔记

1. [关键词匹配失败之后，课程推荐怎么收成 Function Calling 条件](notes/01-function-calling-course-recommend.md)
2. [法律咨询检索为什么要向量加关键词回退](notes/02-hybrid-legal-search.md)
3. [多轮文书修订里，修改要求为什么不能只靠滑动窗口](notes/03-revision-state-not-sliding-window.md)
4. [健身助手的偏好数据从哪来：对话、工具结果、人工打回](notes/04-preference-pairs-from-traces.md)

## 代码

- [Legal_Rule_Search](https://github.com/Entr000py/Legal_Rule_Search)：法条语义检索 + 关键词回退，FastAPI / Milvus / Docker。第 2 篇笔记里的 RRF 评测没有放进这个仓库。
- [LLM-From-Scratch](https://github.com/Entr000py/LLM-From-Scratch)：从零把 GPT-like 模型的数据、训练和采样跑通。学习项目。

## 论文

Polaris: A Polar-Aware Spectral-Temporal Model for Long-Horizon Multivariate Time Series Forecasting. *Studies in Nonlinear Dynamics & Econometrics*.

邮箱：[j1310654263@gmail.com](mailto:j1310654263@gmail.com)
