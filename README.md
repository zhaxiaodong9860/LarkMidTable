# LarkMidTable

[![License](https://img.shields.io/badge/license-Apache%202-4EB1BA.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)

中文 | [English](README_EN.md)

Lark中文名称 云雀，云代表大数据，雀代表平凡和自由。

LarkMidTable 是一站式开源的数据中台，实现元数据管理，数据仓库开发，数据质量管理，数据的可视化，实现高效赋能数据前台并提供数据服务的产品。



# **产品愿景**

1.满足许多的小企业，提供一站式的解决方案。

2.做出世界级别，能够媲美BAT大厂的产品。

3.创造价值，产生价值，让世界变得更加美好。



# 技术选型

| 框架名称                                                     | 框架用途           | 主要功能                                                     |
| ------------------------------------------------------------ | ------------------ | ------------------------------------------------------------ |
| [Atlas](http://atlas.apache.org/)                            | 元数据管理         | 包括 数据分类、集中策略引擎、数据血缘、安全和生命周期管理在内的元数据治理核心能力 |
| [Dolphin](https://github.com/apache/incubator-dolphinscheduler) | 任务调度           | 可视化DAG工作流任务调度系统                                  |
| [Flink](https://github.com/apache/flink)                     | 离线和实时计算框架 | 基于Flink，一站式解决批流处理问题                            |
| [Hive](https://github.com/apache/hive)                       | 数据存储           | 基于MR的数据仓库工具                                         |
| [Kylin](https://github.com/apache/kylin)                     | 分析数据库         | 开源的、分布式的分析型数据仓库                               |
| [Kafka](https://github.com/apache/kafka)                     | 消息中间件         | LinkedIn用Scala语言实现，支持hadoop数据并行加载              |
| [K8S](https://github.com/kubernetes/kubernetes)              | 容器部署           | 部署容器化的应用简单并且高效                                 |
| [Zookeeper](https://github.com/apache/zookeeper)             | 分布式协调服务     | 统一命名服务、配置管理、集群管理、队列管理                   |



# 产品架构图

![系统架构图](https://img2020.cnblogs.com/blog/622382/202009/622382-20200930001500385-1504321257.jpg)



## 目前支持的数据库

| 数据库类型 | 读取类型 | 写入类型 |
| ---------- | -------- | -------- |
| Mysql      | 支持     | 支持     |
| PostgreSql | 支持     | 支持     |
| Mongodb    | 支持     | 支持     |
| SqlServer  |          |          |
| ClickHouse |          |          |
| Hive       |          |          |
| Hbase      |          |          |



# **快速开始**

请点击      [快速开始](https://github.com/wxgzgl/flinkx-web/blob/master/userGuid.md)

前端代码  [前端代码](https://github.com/wxgzgl/LarkMidTableUI)

资源库      [研发资源库]( https://github.com/wxgzgl/flinkx-web/blob/master/docs/list.md )

开发规范  [唯品会开发规范](https://vipshop.github.io/vjtools/#/standard/)



# 特别鸣谢

本项目在[datax-web](https://github.com/WeiYe-Jing/datax-web)代码的基础上进行二次重构开发，在此特别感谢datax-web团队。



# **技术交流**

搜索QQ群号[678097205]或者扫描下面的二维码进入LarkMidTable 社区的QQ群，目前正是开源的初期阶段，群里达到85人

**![QQ群](https://img2020.cnblogs.com/blog/622382/202009/622382-20200907124358049-997953244.png)**