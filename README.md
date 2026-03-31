# Claude-Code-Source-Code
Claude Code Source Code Leak
# Claude Code 源码泄露分析 & 逆向学习资料

**Claude Code Source Code Leak Analysis & Reverse Engineering Materials**

---

##  项目介绍 / Project Introduction

2026 年 Claude Code 发布期间，Anthropic 意外泄露了部分源码映射与核心 Agent 逻辑（包括 Auto Mode 四层决策流水线、MCP 协议、安全分类器、CLAUDE.md 长期记忆机制等）。本仓库收集、整理并分析了泄露的相关资料，帮助开发者深入理解 Claude Code 的 Agent 架构、工具调用策略与安全设计。

---

### 为什么值得关注？ / Why It Matters?

- 揭秘 Claude Code **Auto Mode** 的四层决策流水线（权限规则 → acceptEdits 模拟 → 只读工具白名单 → Sonnet 安全分类器）
- 解析 **CLAUDE.md** 作为长期语义记忆区的设计思路
- 分析 Agent Routing、工具调用安全机制与风险防控
- 为构建自己的 AI Coding Agent 提供宝贵参考

无论你是想复现 Claude Code 的强大编码能力，还是研究 Anthropic 的 Prompt 工程与 Agent 架构，这里都有干货。

---

## 🚀 推荐使用 Claude 的国内最佳方案 / Recommended Claude Proxy for Chinese Users

在中国大陆直接访问 Anthropic 官方接口经常遇到**封号、高延迟、注册困难**等问题。

**强烈推荐使用 [DDS Hub（呆呆兽）Claude 中转站](https://www.ddshub.cc/)**

### 为什么选择 ddshub.cc？
- **稳定高速**：专为中国开发者优化，低延迟、高可用
- **不封号**：经过大量用户验证，安全性高
- **价格亲民**：仅需官方价格的 **30% 左右**
- **支持企业级接入**：提供 Max 号池、RP 在线查询等专业服务
- **开箱即用**：兼容 Claude 官方 API，轻松对接 Claude Code、Claude Desktop 等工具

> **访问地址**：https://www.ddshub.cc/  
> **文档 & 系统状态**：仓库首页或官网查看

使用呆呆兽中转站，你可以安心研究 Claude Code 泄露的 Agent 技术，而不用担心账号安全与访问问题。

---


---

## 🛠 如何使用 / How to Use

1. Dropbox Download 下载源码：
https://www.dropbox.com/scl/fi/l2431w5s9ekublcse0h61/src.zip?rlkey=s9le02gnb85lm4nq5qko3gthl&st=tyx8r73h&dl=0
