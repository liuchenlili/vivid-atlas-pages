# Display name
title: 刘琛琛

# Name pronunciation (optional)
name_pronunciation: ''

# Full name (for SEO)
first_name: Chenchen
last_name: Liu

# Pronouns (optional)
pronouns: she/her

# Status emoji
status:
  icon: 💻

# Is this the primary user of the site?
superuser: true

# Highlight the author in author lists? (true/false)
highlight_name: true

# Role/position/tagline
role: 后端开发工程师 / AI开发方向

# Organizations/Affiliations to display in Biography block
organizations:
  - name: 浙江工商大学
    url: https://www.zjgsu.edu.cn/

# Social network links
profiles:
  - icon: at-symbol
    url: '23020100082@pop.zjgsu.edu.cn'
    label: E-mail Me
  - icon: brands/github
    url: https://github.com/
  - icon: brands/linkedin
    url: https://www.linkedin.com/
  - icon: academicons/orcid
    url: https://orcid.org/

interests:
  - 后端开发
  - 分布式系统
  - 人工智能应用
  - 数据可视化与知识图谱

education:
  - area: 硕士研究生（软件工程）
    institution: 浙江工商大学
    date_start: 2023-09-01
    date_end: 2026-06-30
    summary: |
      主修课程：软件理论与工程、数据科学与工程、计算理论、高级计算机体系结构、高级人工智能、嵌入式系统软硬件协同设计等。
  - area: 本科（计算机科学与技术）
    institution: 浙江工商大学
    date_start: 2019-09-01
    date_end: 2023-06-30
    summary: |
      主修课程：计算机网络、操作系统、数据结构、深度学习、软件工程、编译原理等。

work:
  - position: 实习后端开发工程师
    company_name: 浙大网新软件有限公司（人社业务部）
    date_start: 2025-06-01
    date_end: 2025-09-01
    summary: |2-
      参与省社保国统项目的功能开发与维护。
      **技术栈**：Spring、SpringMVC、MyBatis、Oracle、Dubbo、Vue、Element UI、FineReport  
      **核心工作**：
      - 独立完成城乡居民养老业务流程的接口设计、参数校验与数据处理模块；
      - 使用 Vue + Element UI 进行前端开发，实现业务需求联调与数据可视化；
      - 优化复杂 SQL 脚本与索引策略，使核心报表查询效率提升约 30%；
      - 开发与调试 Dubbo RPC 接口，实现跨模块数据交互；
      - 使用 FineReport 设计动态报表，实现业务指标的可视化监控。

projects:
  - title: 麦麦票 - 赛事演出购票平台（后端开发）
    summary: |
      基于 SpringBoot 的购票平台，支持票务秒杀、热度榜单、社交互动等功能。
      **核心技术**：SpringBoot、MyBatis-Plus、Redis、MySQL、Nginx、WebSocket、Redisson、RabbitMQ  
      **亮点工作**：
      - 使用多级缓存与布隆过滤器防止缓存穿透，动态TTL防止雪崩；
      - 基于 Redisson 分布式锁与 Lua 脚本实现秒杀库存原子扣减；
      - 利用 RabbitMQ 构建异步削峰队列，应对万级并发；
      - 实现订单一致性（乐观锁机制）与热点数据治理；
      - 实现演出热度排行（ZSet）与用户关系管理（Set + Bitmap）。

  - title: 精选商城 - 微服务架构电商系统
    summary: |
      微服务商城项目，实现商品管理、购物车、支付、降价提醒等功能。
      **核心技术**：SpringCloud、MyBatis、Elasticsearch、Sentinel、Seata、RabbitMQ、Nacos  
      **亮点工作**：
      - 基于 Elasticsearch 优化商品搜索，响应时间从220ms降至60ms；
      - 通过 Sentinel 实现流控与熔断，防止系统雪崩；
      - 使用 Seata AT 模式保障分布式事务一致性；
      - 利用 RabbitMQ 延时队列实现订单超时自动取消；
      - 基于 Nacos 和 OpenFeign 完成服务治理与接口调用。

  - title: AI智能知识库系统（后端开发）
    summary: |
      基于大语言模型（LLM）的RAG知识库系统，通过MCP协议实现自动化数据采集与内容发布。
      **核心技术**：Spring Boot、Spring AI、PostgreSQL、Redis、Docker、Ollama  
      **亮点工作**：
      - 构建文档向量库，基于TokenTextSplitter实现语义检索；
      - 集成JGit实现代码仓库自动拉取与知识库构建；
      - 基于@Tool注解实现LLM与多源数据交互框架；
      - 实现CSDN、公众号等平台发帖自动化工作流。

skills:
  - name: 技术栈
    items:
      - name: Java / SpringBoot / SpringCloud / MyBatis
        percent: 95
      - name: Redis / RabbitMQ / Nginx / Docker
        percent: 90
      - name: SQL优化 / Oracle / MySQL
        percent: 90
      - name: 分布式系统与微服务架构
        percent: 85
      - name: PyTorch / AI 应用开发
        percent: 75
  - name: 工具与开发
    color: '#eeac02'
    color_border: '#f0bf23'
    items:
      - name: Git / Maven / Linux
        percent: 90
      - name: FineReport / Element UI / Vue
        percent: 85
      - name: Dify / Cursor / RAG / Agent
        percent: 80

languages:
  - name: 中文
    percent: 100
  - name: 英语
    percent: 70

awards:
  - title: 全国二等奖
    awarder: “华为杯”中国研究生数学建模竞赛
    date: '2024-12-01'
    summary: |
      因创新性算法设计与模型优化获得全国二等奖。
  - title: PAT甲级认证
    awarder: 浙江大学计算机等级考试中心
    date: '2022-08-01'
  - title: Kaggle 铜牌
    awarder: Kaggle - MAP: Charting Student Math Misunderstandings
    date: '2023-10-01'
  - title: IEEE Big Data 2025 论文收录（第一作者）
    awarder: IEEE
    date: '2025-11-01'
    summary: |
      论文《Multi-Feature Fusion Strategies for Enhancing Knowledge Graph Embedding》被接收（CCF-C类会议）。

---

刘琛琛，浙江工商大学硕士研究生，专注于后端开发与AI智能系统构建。拥有扎实的Java开发基础与分布式系统经验，熟悉Spring全家桶、微服务、缓存优化与高并发场景设计。  
参与多个项目的核心开发，包括RAG知识库系统与高并发购票平台。曾获华为杯全国二等奖与IEEE会议论文收录。热衷于人工智能与软件工程的融合探索。
