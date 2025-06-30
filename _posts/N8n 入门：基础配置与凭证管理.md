---
layout: post
title: n8n的基础配置
date: 2025-06-30 15:30:00 -0400
categories:
  - 入门
  - 博客
tags:
  - 欢迎
  - Jekyll
  - 教程
---
---
layout: post
title: "N8n 入门：基础配置与凭证管理"
date: 2025-06-30 15:30:00 -0400
categories: [n8n, 自动化, 教程]
tags: [n8n, 配置, 凭证, Docker, 入门]
---

# N8n 入门：基础配置与凭证管理

大家好，我是 Chao！很高兴能在这里分享我的第一篇博客文章。今天，我们将一起探索一个强大的开源工作流自动化工具—— n8n。如果你想让你的日常工作、数据处理或服务间协作自动化起来，n8n 绝对值得一试！

## 什么是 n8n？

n8n (发音为 "en-eight-en") 是一个免费且开源的工作流自动化平台。它允许你连接各种应用程序和 API，通过拖拽式的界面构建复杂的自动化流程。从发送电子邮件通知到同步数据库数据，n8n 几乎可以实现任何你想要的自动化。

## n8n 凭证

### Deepseek API:
sk-16d587680def4da081f6cb55719a07cf

### Openrouter API:
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
调用时候选择任意的尾缀为free的模型，推荐DeepSeek或QWEN

### SMTP服务：
需在「Google Accounts-安全」中搜索「应用密码」，创建独立的应用密码
SMTP服务器：smtp.gmail.com
SMTP服务端口：465
SMTP用户名：你的谷歌邮箱
SMTP密码：上述创建的应用密码