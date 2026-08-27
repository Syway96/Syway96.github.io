---
permalink: /
title: "个人简历"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---



## 基本情况

1. 哈尔滨工业大学（威海） · 本科在读（2025级）
2. 计算机学院 · 人工智能专业

## 学习情况

1. **学分绩**：80.25
	- 微积分(1) 84.5、线性代数 88、微积分(2) 82
2. **英语**：四级 598，六级 607
3. **网课**：【斯坦福】CS329A：自改进 AI Agents（2025）、【李宏毅】机器学习（2025 及 2026）
4. **论文阅读**：重点阅读了近两年 **持续学习、Agent** 相关的顶会论文
5. **编程&工具**：熟练使用 Codex、Trae，熟悉 Python、C++、PyTorch、Git

## 实践经历

1. **ReTA：基于 RAG 的 AI 知识库问答系统（大一年度项目 · 组长）**
    - 项目链接：[https://github.com/Syway96/ReTA](https://github.com/Syway96/ReTA)
    - 使用 LangChain 搭建问答流程，MinerU 将 PDF 教材转为 Markdown 原始文档，分块后以 Qwen3-Embedding-0.6B 构建 Chroma 向量库，初步实现对多本教材的章节级检索问答。
2. **AiTA：轻量级 AI 学习助手**
	- 项目链接：[https://github.com/Syway96/AiTA](https://github.com/Syway96/AiTA)
	- 基于 React 18 + FastAPI 的轻量级本地 AI 学习助手，含**教材阅读、笔记管理、常用资源**三模块。
	- **笔记管理**：基于 Agent 循环 + 工具调用接入笔记库（如 Obsidian Vault）选择、阅读、编辑笔记；支持通过输入 GitHub 链接安装 skill。 
	- **教材阅读**：将 Markdown 教材（MinerU 将 PDF 转换为 Markdown，AI Agent 校准标题层级）切分为最小单元，由大模型两阶段路由（先选书、再选章）自动定位内容，也支持目录树手动选章并预览原文。对于 50 个测试问题，检索准确率 96%（单本书 39/40，跨书 9/10）。检索内容与对话历史分离，支持单章节、跨章节与跨教材问答，引用可点击回查原文。
	- **常用资源**：汇聚常用链接与可复用提示词为卡片簿。
3. **SywayClaw：面向长期交互的轻量级个人 AI Agent**
	- 项目链接：[https://github.com/Syway96/SywayClaw](https://github.com/Syway96/SywayClaw)
	- 基于 Express + React 实现 Agent 循环：支持 SSE 流式输出、工具调用、多会话持久化、Skill 安装及上下文压缩。
	- 实现"时间流"上下文层：注入当前时刻、消息间隔与网页数据时效。
	- 采用结构化记忆，摘要自动注入、全文按需读取。
	- 每次请求记录 JSONL 交互轨迹，用于分析工具调用、记忆检索与自我修正行为。

## 科研兴趣

1. **持续学习、元认知、推理**（Continual Learning, Meta-Cognition, Reasoning）
2. **新一代 AI Agent：长期记忆、自进化、多智能体**（Long-term Memory, Self-Improving, Multi-Agent）


