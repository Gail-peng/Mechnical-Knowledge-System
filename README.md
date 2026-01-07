#   MeKS - 基于刀具产品数据的知识管理系统 🌌

基于加工刀具数据的知识系统。前端通过VUE2开发，后端通过Flask实现，数据库使用Neo4j。数据来源于多个知名的刀具数据厂家，在整理了多家刀具数据后，设计了一套面向刀具数据的知识图谱本体。所有的数据都是遵循本体的规则存储到图数据库中。最后系统实现了图谱可视化、数据管理、产品查询、知识图谱结合大模型的RAG等功能。

> 💡 **如果您觉得这个项目的想法对您有帮助，请给个 ⭐ Star 支持一下！谢谢~**


## 📖 项目介绍
MeKS 是一个基于刀具产品数据的知识管理系统，主要的功能包括：
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


## ✨ 核心功能
| 模块                | 核心能力                                                                 |
|---------------------|--------------------------------------------------------------------------|
| 📊  图谱可视化模块     | 直观操作知识图谱，提供高亮关系操作、节点信息展示及编辑、图统计数据计算、通过label显示/隐藏节点、图信息查询等功能  |
| 🔧 标准接口规则引擎         | 通过同一套标准规则模板构建面向不同场景的后端接口，无需对对接口代码进行修改，仅需要添加业务逻辑以及对应的YAML模板即可    |
| 🔍 标准Cypher生成模块    | 得益于面向刀具的知识图谱本体，通过标准的Cypher模板就能够查询面向不同类型的数据信息   |
| 🧠 GraphRAG 增强模块    | Langchain构建，支持多轮对话，通过结合本体的语义解析和Cypher生成模块，支持通过自然语言检索数据库中的刀具信息        |
| 🛡️ 容错模块         | 更加稳定的JSON解析、标准化的Cypher生成以及LLM中的Prompt纠错机制                   |

## 🏗️ 系统架构


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













