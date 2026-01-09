#   MeKS - 基于刀具知识图谱的知识管理系统 🌌

## 💡 项目亮点

专业领域应用: 针对机械加工刀具行业的专业知识管理系统

知识图谱可视化: 使用D3.js实现复杂的知识图谱交互展示

AI集成: 集成智能问答助手，提供自然语言交互

模块化设计: 清晰的组件划分，便于维护和扩展

现代化UI: 采用Element UI和自定义样式，界面美观专业

## 📖 项目介绍

MeKS (Mechanical Knowledge System)是一个基于刀具产品数据知识图谱的知识管理系统，主要的功能包括：
- 知识图谱数据查询和可视化：支持四种检索模式，分别为：
  - 节点检索：在图谱中对实体节点进行模糊检索，返回与其关联的信息
  - 厂商刀具检索：在图谱中检索刀具的生产厂家，返回厂家的刀具相关信息
  - 厂商产品检索：在图谱中检索刀具的生产厂家，返回厂家的相关刀具产品信息
- 数据检索及管理：图数据库的管理界面，支持三种类型数据的增删查改：
  -  刀具检索：通过查询刀具类型或是型号，检索图谱中的刀具数据，对刀具数据进行增删查改
  -  厂家数据检索：通过查询厂家名称，检索图谱中厂家的刀具数据，对刀具数据进行增删查改
  -  产品检索：通过查询厂家名称，检索图谱中厂家的产品数据，对产品数据进行增删查改
- 知识检索：结合刀具知识图谱的 GraphRAG 检索
- 刀具产品：标准界面查询所有的产品信息及其详细刀具数据

## ✨ 系统特色

🎨 现代化科技界面

- 低对比度配色方案 - 采用科技公司官网风格，视觉舒适
- 流畅动画效果 - 精心设计的过渡动画，提升用户体验
- 响应式布局 - 完美适配不同屏幕尺寸
  
🧠 智能知识检索

- AI对话助手 - 基于LangChain的智能问答系统
- 知识图谱可视化 - D3.js驱动的动态图谱展示
- 语义搜索 - 深度理解用户查询意图

📊 专业刀具知识库

- 多维度分类 - 涵盖车削、铣削、钻孔等各类刀具
- 参数化管理 - 完整的切削参数和材料信息
- 厂商数据 - 集成主流刀具厂商产品信息


## ✨ 核心功能
| 模块                | 核心能力                                                                 |
|---------------------|--------------------------------------------------------------------------|
| 🎨  图谱可视化模块     | 直观操作知识图谱，提供高亮关系操作、节点信息展示及编辑、图统计数据计算、通过label显示/隐藏节点、图信息查询等功能  |
| 🔧 标准接口规则引擎         | 通过同一套标准规则模板构建面向不同场景的后端接口，无需对对接口代码进行修改，仅需要添加业务逻辑以及对应的YAML模板即可    |
| 🔍 标准Cypher生成模块    | 得益于面向刀具的知识图谱本体，通过标准的Cypher模板就能够查询面向不同类型的数据信息   |
| 🧠 GraphRAG 增强模块    | Langchain构建，支持多轮对话，通过结合本体的语义解析和Cypher生成模块，支持通过自然语言检索数据库中的刀具信息        |
| 🛡️ 容错模块         | 更加稳定的JSON解析、标准化的Cypher生成以及LLM中的Prompt纠错机制                   |

## 🌟 核心优势

### 对于工程师
- 🛠️ 专业数据 - 完整的刀具参数数据库
- 📈 智能分析 - 基于AI的刀具和参数建议
- 🔄 实时更新 - 动态的知识图谱展示

### 对于管理者

- 📊 数据洞察 - 专业的知识图谱支持对刀具数据的分析
- 💰 成本优化 - 基于知识图谱为采购提供决策支持的数据基础
- 🎯 效率提升 - 基于图谱的快速的知识检索和共享

### 对于操作员
- 👆 简单易用 - 直观的界面操作
- 🔍 快速查询 - 秒级的知识检索速度
- 📱 移动友好 - 多设备适配的响应式设计

## 🏗️ 系统架构

<img width="2528" height="1696" alt="image" src="https://github.com/user-attachments/assets/aad7cefc-c432-42af-ae0c-23b2726bcbdb" />

## 🔗 开发流程

<img width="2528" height="1696" alt="image" src="https://github.com/user-attachments/assets/d360fb81-a56d-4375-94f1-7fac69d4b7e0" />

## 🗄️ 系统截图

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

> 💡 **如果您觉得这个项目的想法对您有帮助，请给个 ⭐ Star 支持一下！谢谢~**











