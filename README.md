#   MeKS - 基于刀具产品数据的知识管理系统 📊

基于加工刀具数据的知识系统。前端通过VUE2开发，后端通过Flask实现，数据库使用Neo4j。数据来源于多个知名的刀具数据厂家，在整理了多家刀具数据后，设计了一套面向刀具数据的知识图谱本体。所有的数据都是遵循本体的规则存储到图数据库中。最后系统实现了图谱可视化、数据管理、产品查询、知识图谱结合大模型的RAG等功能。

> 💡 **如果您觉得这个项目的想法对您有帮助，请给个 ⭐ Star 支持一下！谢谢~**

## 📖 项目介绍
MeKS 是一个基于刀具产品数据的知识管理系统，主要的功能包括：
- 知识图谱数据查询和可视化：支持四种检索模式，分别为：
  - 节点检索：
- 结构化 IR（中间表示）：统一的文档中间表示层，支持灵活的格式转换
- 多格式渲染：支持将 IR 渲染为 Markdown（兼容表格/图表/公式）、PDF（保留CSS样式+中文字体）
- 智能章节生成：基于LLM的章节内容生成、结构校验、容错修复
- 知识图谱增强：GraphRAG 构建知识图谱，提升报告内容的深度与关联性
- 鲁棒的容错机制：JSON解析修复、内容密度校验、跨引擎兜底生成

<div align="center" markdown="1">
   ![Readme Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&width=435&lines=Mechnical+Knowledge+System;Badge+Collection)
</div>

<hr>


### 一站式多引擎报告自动化生成系统，支持Markdown/PDF渲染、知识图谱增强、结构化章节生成

<div align="center">
<!-- 项目徽章 -->
<a href="https://github.com/your-username/BettaFish" target="_blank">
  <img src="https://img.shields.io/github/stars/your-username/BettaFish?style=social" alt="GitHub Stars"/>
</a>
<a href="https://github.com/your-username/BettaFish/fork" target="_blank">
  <img src="https://img.shields.io/github/forks/your-username/BettaFish?style=social" alt="GitHub Forks"/>
</a>
<img src="https://img.shields.io/github/issues/your-username/BettaFish" alt="GitHub Issues"/>
<img src="https://img.shields.io/github/license/your-username/BettaFish" alt="License"/>
<img src="https://img.shields.io/badge/Python-3.8+-blue.svg" alt="Python Version"/>
<img src="https://img.shields.io/badge/WeasyPrint-PDF%20Render-green.svg" alt="PDF Render"/>
</div>



## 📖 项目介绍
BettaFish 是一套面向深度研究报告的自动化生成引擎，核心能力包括：
- 多引擎协同：QueryEngine（查询引擎）、MediaEngine（媒体引擎）、InsightEngine（洞察引擎）三引擎数据融合
- 结构化 IR（中间表示）：统一的文档中间表示层，支持灵活的格式转换
- 多格式渲染：支持将 IR 渲染为 Markdown（兼容表格/图表/公式）、PDF（保留CSS样式+中文字体）
- 智能章节生成：基于LLM的章节内容生成、结构校验、容错修复
- 知识图谱增强：GraphRAG 构建知识图谱，提升报告内容的深度与关联性
- 鲁棒的容错机制：JSON解析修复、内容密度校验、跨引擎兜底生成

## ✨ 核心功能
| 模块                | 核心能力                                                                 |
|---------------------|--------------------------------------------------------------------------|
| 📝 报告布局设计     | 自动生成标题、目录、Hero设计，统一报告视觉与结构基调                     |
| 🔧 章节生成         | LLM驱动的章节内容生成，支持流式输出、JSON校验、跨引擎修复               |
| 📊 图表/词云处理    | 图表自动审查修复、SVG转换，词云生成图片，降级为表格保障数据不丢失        |
| 📄 多格式渲染       | Markdown渲染（兼容SWoT/PEST表格、Callout等）、PDF渲染（支持中文字体）|
| 🧠 GraphRAG 增强    | 基于日志构建知识图谱，支持关键词/类型/深度检索，提升报告内容质量        |
| 🛡️ 容错机制         | 鲁棒JSON解析、内容密度校验、占位符兜底、多LLM引擎降级                   |

## 🏗️ 系统架构
### 项目代码结构树

<img width="1918" height="904" alt="image" src="https://github.com/user-attachments/assets/a8cf52dd-8c9d-4bc4-bdd2-8a123322259b" />

<img width="1912" height="896" alt="image" src="https://github.com/user-attachments/assets/2a35fbce-2fda-4fe6-83ad-e5d3d967bfc7" />

<img width="1915" height="898" alt="image" src="https://github.com/user-attachments/assets/9fe97417-4b6e-4825-94ae-a6e6e25b6644" />

<img width="1906" height="859" alt="image" src="https://github.com/user-attachments/assets/ac4758a3-0754-4fb8-948e-0af29ac35e92" />

<img width="1906" height="890" alt="image" src="https://github.com/user-attachments/assets/10818bd6-7bcb-45eb-b4e3-dded96e367e7" />

<img width="1908" height="892" alt="image" src="https://github.com/user-attachments/assets/94917fe5-4c1d-49a1-85f6-2b855bbed3eb" />

<img width="1907" height="893" alt="image" src="https://github.com/user-attachments/assets/1c6eff98-d413-4ee8-a00d-047947f0deb9" />

<img width="1903" height="890" alt="image" src="https://github.com/user-attachments/assets/aecedffc-14a2-4bc9-bc53-dbfa8105ec4f" />

<img width="1888" height="896" alt="image" src="https://github.com/user-attachments/assets/78c4ae1d-d462-4a15-b7ca-c9a50d6a9660" />

<img width="1905" height="896" alt="image" src="https://github.com/user-attachments/assets/c624413f-a492-46fa-9202-733b998a8f66" />













