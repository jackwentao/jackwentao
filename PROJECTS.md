# 项目导航

围绕 Agent、RAG 和大模型应用的项目、实验与学习记录。

[返回主页](https://github.com/jackwentao) · [所有公开仓库](https://github.com/jackwentao?tab=repositories)

## 应用项目

| 项目 | 做什么 | 技术与入口 |
| --- | --- | --- |
| [Agentic-ChemRAG-v1](https://github.com/jackwentao/Agentic-ChemRAG-v1) | 上传文献、后台索引、范围问答与页码引用 | Python、FastAPI、LangGraph、pgvector、Celery、React |
| [VoiceCanvas](https://github.com/jackwentao/VoiceCanvas) | 通过语音创建、编辑和导出分镜草图 | Python、FastAPI、LangGraph、Canvas；支持本地 Demo |
| [企业微信招聘 AI 助手](https://github.com/jackwentao/wecom-recruitment-ai-demo) | 消息与简历抽取、候选人看板和 Excel 导出 | TypeScript、Express、React；默认 JSON 演示 |
| [Git Weekly Insight](https://github.com/jackwentao/Git-Weekly-Insight) | 从本地 Git 提交与笔记生成 Markdown 周报 | TypeScript、CLI、Next.js、DeepSeek；支持无密钥预演 |

各项目的配置、快速开始、测试命令与能力边界见对应 README。

## ChemRAG 实现路线

三个仓库使用独立源码与数据配置，分别记录原型、应用和架构实验：

| 仓库 | 定位 | 适合看什么 |
| --- | --- | --- |
| [Agentic-ChemRAG](https://github.com/jackwentao/Agentic-ChemRAG) | 本地 PDF + ChromaDB 原型 | PDF 解析、向量构建、流式问答 |
| [Agentic-ChemRAG-v1](https://github.com/jackwentao/Agentic-ChemRAG-v1) | 文献问答应用 | 上传、异步索引、存储、检索与引用 |
| [Multi_Agent_ChemRAG](https://github.com/jackwentao/Multi_Agent_ChemRAG) | 模块化后端与编排实验 | contracts、共享仓储、导入队列；Agent 业务节点仍在完善 |

## 写作与学习

| 仓库 | 内容 |
| --- | --- |
| [blog](https://github.com/jackwentao/blog) | 大模型应用开发笔记与文章索引 |
| [ML Learning Journey](https://github.com/jackwentao/ML-Learning-Journey) | 学习记录，目前为两道 C++ 算法练习 |
| [github-slideshow](https://github.com/jackwentao/github-slideshow) | GitHub Learning Lab 的早期入门练习 |

## 上游项目 Fork

以下仓库保留上游实现、README 与署名。需要了解官方功能或最新版本时，优先进入上游；Fork 的差异以实际提交记录为准。

| Fork | 上游 |
| --- | --- |
| [claude-cookbooks](https://github.com/jackwentao/claude-cookbooks) | [anthropics/claude-cookbooks](https://github.com/anthropics/claude-cookbooks) |
| [hindsight](https://github.com/jackwentao/hindsight) | [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight) |
| [ragflow](https://github.com/jackwentao/ragflow) | [infiniflow/ragflow](https://github.com/infiniflow/ragflow) |
| [claude-code](https://github.com/jackwentao/claude-code) | [anthropics/claude-code](https://github.com/anthropics/claude-code) |
| [claude-code-best](https://github.com/jackwentao/claude-code-best) | [claude-code-best/claude-code](https://github.com/claude-code-best/claude-code) |
| [cc-haha](https://github.com/jackwentao/cc-haha) | [NanmiCoder/cc-haha](https://github.com/NanmiCoder/cc-haha) |
| [claw-code](https://github.com/jackwentao/claw-code) | [ultraworkers/claw-code](https://github.com/ultraworkers/claw-code) |
| [dsh-purge](https://github.com/jackwentao/dsh-purge) | [YuJunZhiXue/dsh-purge](https://github.com/YuJunZhiXue/dsh-purge) |
| [old-dsh-purge](https://github.com/jackwentao/old-dsh-purge) | [qqb521/dsh-purge](https://github.com/qqb521/dsh-purge) |

`dsh-purge` 与 `old-dsh-purge` 来自不同上游；`claw-code` 包含本地独有提交，保留各自记录。
