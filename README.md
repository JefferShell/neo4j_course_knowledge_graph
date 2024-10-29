## 项目简介

这款手机数据检索系统基于neo4j图数据库和Flask框架，旨在方便用户对手机数据的搜索和筛选。

## 主要功能

- 基于关键词搜索手机模型和配置信息
- 按时间段、价格和品牌筛选手机数据
- 展示手机之间共有的特征


## 技术架构

- 前端：Flask框架
- 后端：neo4j图数据库
- 代码库：py2neo


## 使用说明

1. 启动项目：
   - 运行 `python app.py` 以启动开发服务器


2. 数据初始化：
- 将 `datas` 目录下所有 CSV 文件移动到 `neo4j` 的 `import` 目录下。
- 运行 `init.cypher` 以构建手机知识图谱。


3. 访问系统：
- 访问 `http://127.0.0.1:5000` 以使用系统。


## 联系方式

微信号：zt745324325