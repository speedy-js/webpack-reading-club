---
sidebar_position: 0
---

# 指南

## 条件

本次活动会假设你已经完成相关要求或具有相关能力

- 阅读 Webpack 的 [CONTRIBUTING](https://github.com/webpack/webpack/blob/main/CONTRIBUTING.md) 文档
- 熟悉 Webpack 的 [基本概念](https://webpack.js.org/concepts/)
- 熟悉使用 VScode debugger

## 目的

- 这个俱乐部的最终目标是 **形成一套阅读 Webpack 源码的理论，并与实践相结合**。
- 我们目标是务实的。在完整参与了俱乐部活动后，只要 **你能够对 Webpack 特定的功能进行深入源码级别的研究，就算达成了目标**。至于在这个目标之外的收获，就不是本次俱乐部活动的责任了。
- PS： 希望大家在俱乐部解散的时候都能成为 Webpack 的贡献者。

## 准备工作

### 阅读方法

- 我们将同样采用 [Rust 代码阅读俱乐部建议](https://hackmd.io/@rustc-reading-club/S1xsDveDK#/8) 的 **广-深-广** 的阅读方法。
- 具体来说：
  - 广（ Broad ）： 整体了解模块。
  - 深（ Deep ）： 聚焦于某个函数或小片区域（你感兴趣的，或有疑问的）。
  - 广（ Broad ）： 重新回到整个模块中。 - 带着前两个阶段的理解

### 理解编程过程中的三类干扰

- 缺乏知识（Lack of knowledge，对应长期记忆 long-term memory ， LTM）。指开发者缺乏基本的编程语言的知识，无法使用或理解基本的语法，而造成的困扰。
- 缺乏信息（Lack of information，对应短期记忆， short-term memory， STM）。指开发者缺乏程序要处理的问题领域信息的了解，而造成的困扰。
- 缺乏处理能力（Lack of processing power ，对应工作记忆，working memory，WM）。指开发者缺乏对整个编程执行过程的处理能力，而造成的困扰。

## 流程

- 每一期的阅读活动都将
  - 有一个贯穿本期活动的深入点/主线问题
- 流程
  - 步骤一 (45 min)
    - 阅读主持人准备的 本期活动文档 的准备部分和了解本期的深入点/核心问题 (5 min)
    - 2 人一组针对深入点，自由阅读代码，在活动文档上记录发现的问题和有趣的代码 (10min)
      - 线上同学不方便分组，可以一个人自由发挥了
    - 小组分享是如何阅读的代码，发现的问题和有趣的代码 (10 min)
      - 线上同学也可以进行分享
    - 集体讨论小组讨论和阅读代码时提出的问题 (20 min)
  - 步骤二(45min)
    - 介绍 Webpack 的整体编译流程
    - 主持人讲解深入点
    - 介绍这个功能是如何嵌入到整个流程中
    - 回答步骤一提出的问题
- 大体上我们将按照 Webpack 的编译流程来选取每一期的深入点，在我们将整个流程全部介绍完，这个俱乐部就会解散。
- 这个阅读俱乐部也是偏实验性的，会根据每期的反馈对下期的内容和流程进行调整。

## FAQ

如果你有问题，可以在 [issue](https://github.com/speedy-js/webpack-reading-club/issues) 区里提

### 规模和形式？

线上+线下

### 会进行录制吗？

会

### 每一期的内容相互依赖吗？

我们倾向于每一期的内容都是独立的，你完全可以随意观看每一期的内容

## 参考

- 本次活动的组织借鉴了 Rust 社区的 [Code Reading Club](https://mojosd.medium.com/rust-code-reading-club-8fe356287049) 活动
- [Rust 源码阅读俱乐部 | 第一期 : 名称解析](https://rustmagazine.github.io/rust_magazine_2021/chapter_11/rust-reading-club-part1.html)
- [What does a Rustc Reading Club do?](https://mojosd.medium.com/what-does-a-rustc-reading-club-do-8c9f9b336ff4)