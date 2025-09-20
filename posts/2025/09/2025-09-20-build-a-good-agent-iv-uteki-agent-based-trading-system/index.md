---
title: "Build A Good Agent IV. Uteki: Agent-based Trading System"
date: "2025-09-20"
tags: []
categories: []
author: "Muses"
summary: ""
---

<h1>导读</h1><p>在本篇文章中和大家分享自己在Agent上的实践，交易投资系统Uteki</p><p>测试1</p><p></p><img src="https://raw.githubusercontent.com/Rain1601/rain.blog.repo/main/assets/images/imported_20250919_223552_39670b66.png" alt="" isuploading="false"><p>所有的交易系统不外乎去回答这个问题：如何实现扩大盈利，如何缩小避免损失。</p><p>对于这个问题，有丰富多样且历经时间刷洗的经验和智慧。</p><h1>功能演示</h1><h2>Research Chatbot</h2><h2>Strategy Assistant</h2><h2>Agentic Trader</h2><p>重试 对比 功能 的开发</p><p>mail warning</p><p>auto trade</p><h2>Key Feature Demonstration</h2><p>新闻fetch history record（可信性，白盒）</p><h1>系统设计</h1><h2>架构设计</h2><img src="https://raw.githubusercontent.com/Rain1601/rain.blog.repo/main/assets/images/image_20250920T021835_twdb6q.svg" isuploading="false"><p></p><p></p><h2>业务设计</h2><h2>模块设计</h2><h3>Agent Module</h3><h4>Trade Agent (Single-Agent)</h4><p></p><img src="https://raw.githubusercontent.com/Rain1601/rain.blog.repo/main/assets/images/imported_20250919_223554_071f4a71.png" alt="" isuploading="false"><h4>Research Agent (Multi Agent)</h4><h3>Evaluate Platform</h3><h2>UI设计</h2><h3>设计理念</h3><p>（关于UI设计，因为自己不是设计出身，也搞不出什么专业的词汇，就说说自己的核心设计理念，大白话。）</p><h3>使用过的Prompt</h3><p>页面简洁美观，整体一致性减少页面给人的块状感，特别注意块的嵌套case；</p><p>按钮和布局合理，尽可能地减少用户下一个操作时的鼠标移动距离（保持美观设计的同时鼠标移动距离越短越好）；</p><p>避免一味使用默认的颜色配置更关注系统当前风格样式；</p><p>Flex布局和Grid都是优秀的选项，实现的同时对于同效果使用简单稳定性强，定制化程度高的选择；</p><h1>小结</h1><p></p>