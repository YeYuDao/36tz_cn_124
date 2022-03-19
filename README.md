# 36tz_cn_124
性能优化+架构迭代升级，Go读书社区web开发与架构优化
性能优化+架构迭代升级，Go读书社区web开发与架构优化
👇👇👇👇👇👇👇👇点击下载地址👇👇👇👇👇👇👇
[![download](https://51xueit.vip/muke_img/5fce0f4109668ab205400304.jpg "下载地址")](http://www.36tz.cn "下载地址")
### 第1章 课程介绍 

#### 本章简要介绍项目功能，并介绍怎样通过实践项目学习到开发和架构思路。同时介绍了课程编排的特点和提供了学习本课程的一种思路。
1-1 课程介绍 (05:48)

1-2 大家平时可能关心的问题汇总（助你更好的使用课程）


### 第2章 环境搭建 

#### 本章主要介绍开发环境的准备工作。包括如何安装Go编译环境、Beego框架、Bee开发工具、MySQL等工具和组件。
2-1 项目所需组件简介 (02:44)

2-2 go开发环境搭建 (10:01)

2-3 【扩展】Go开发环境搭建之Windows篇

2-4 Beego框架初体验 (06:29)

2-5 基于Beego搭建Web应用框架 (12:18)

2-6 MySQL安装及应用 (07:38)

2-7 Beego之ORM初实践（上） (09:33)

2-8 Beego之ORM初实践（下） (10:38)

2-9 【扩展】Beego ORM 应用小结

2-10 【总结】知识点回顾


### 第3章 V1.0 : Beego快速搭建Web应用【业务快速迭代】 

#### 本章主要讲解一个典型的Web应用，从设计到开发再到打包部署的全过程。在开发之前，整体讲解了Web应用架构的思路和路线，并实战开发首页分类模块、搜索模块、评论模块等功能。项目开发期间不只是关注快速开发业务逻辑，中间也会穿插讲解后期可能需要扩展的点。...
3-1 大型Web架构设计概要 (14:34)

3-2 读书社区需求分析 (05:18)

3-3 Web应用框架搭建技巧（上） (11:41)

3-4 Web应用框架搭建技巧（中） (11:41)

3-5 Web应用框架搭建技巧（下） (06:53)

3-6 Web应用搭建技巧之重构dbinit (03:52)

3-7 项目整体分析到Controller结构 (10:26)

3-8 添加view资源 (07:53)

3-9 【笔记】View构建及其资源准备

3-10 【扩展】Beego之View基础实践

3-11 一切从model定义开始 (16:17)

3-12 首页Controller实践 (07:53)

3-13 分类逻辑开发（上） (10:13)

3-14 分类逻辑开发（中） (11:56)

3-15 分类逻辑开发（下） (04:01)

3-16 图书详情、编辑模块设计思路讲解 (08:29)

3-17 图书管理、分类管理模块设计分析 (05:39)

3-18 生成图书内容数据 (07:51)

3-19 构造搜索查询 (09:19)

3-20 搜索功能逻辑实现（上） (09:22)

3-21 搜索功能逻辑实现（中） (06:43)

3-22 搜索功能逻辑实现（下） (08:25)

3-23 登录注册验证设计思路简介 (04:59)

3-24 社区功能浅析 (04:35)

3-25 构建社区功能（1） (08:17)

3-26 构建社区功能（2） (04:53)

3-27 构建社区功能（3） (05:34)

3-28 构建社区功能（4） (10:16)

3-29 构建社区功能（5） (10:43)

3-30 个人主页剩余模块设计思路讲解 (04:09)

3-31 打包部署 (08:42)

3-32 项目回顾与总结 (04:32)


### 第4章 V1.1 : 补齐短板【MySQL基础优化】

#### 通常而言，Web应用最先遇见的瓶颈就是数据库。本章从实际项目角度出发，介绍几种最常见造成慢查询的情况，并针对性的从建立数据表，创建索引，再到查询语句，逐步优化MySQL数据库。
4-1 数据库基础优化导读 (04:48)

4-2 【扩展】ab(Apache Bench)基础使用教程

4-3 ab压测评估整体并发能力 (08:01)

4-4 为什么查询会慢 (08:10)

4-5 【扩展】MySQL查询执行计划详解

4-6 项目开发中怎样设计数据表 (10:24)

4-7 数据表设计实战 (04:29)

4-8 实战数据库索引优化 (13:33)

4-9 索引优化实战 (09:58)

4-10 优化改造数据查询语句 (17:35)

4-11 查询优化性能测试 (06:49)

4-12 【总结】数据库基础优化


### 第5章 V1.5 : 优化数据层并发【MySQL并发优化】

#### 随着用户增多，Web应用并发持续增大，数据库并发能力还将是最常见的瓶颈。本章将讲解最常见的几种高并发情况下数据库的优化方法，包括数据库连接池、主从分离、分表分库等。
5-1 数据库并发优化背景简介 (06:33)

5-2 数据库连接池讲解 (05:55)

5-3 【笔记】Go 连接池分析

5-4 Comments分表设计思路与配置 (04:52)

5-5 Comments分表与程序重构 (09:04)

5-6 MySQL binlog初识 (07:03)

5-7 docker基础操作简介 (10:57)

5-8 基于binlog搭建MySQL主从服务 (09:58)

5-9 【笔记】Docker搭建MySQL主从

5-10 基于应用层的MySQL读写分离实践 (11:00)

5-11 设计模块分库思路讲解 (05:08)

5-12 数据库垂直拆分应用实践 (09:51)


### 第6章 V1.8 : 搜索模块优化【搜索模块接入ElasticSearch】

#### 数据库MySQL并不擅长做全文检索，搜索模块我们引入了搜索引擎ElasticSearch。这一章和大家一起学习ElasticSearch基础应用，并将其嵌入到我们的搜索功能中。
6-1 MySQL全文搜索性能评估 (06:18)

6-2 Elasticsearch简介 (02:38)

6-3 安装ES搜索引擎 (04:36)

6-4 Elasticsearch使用基础 (07:29)

6-5 搭建Elasticsearch模块框架 (13:26)

6-6 Elasticsearch创建索引 (20:52)

6-7 搜索模块分析 (07:12)

6-8 搜索模块开发实现 (23:55)


### 第7章 V2.0:静态缓存优化【页面静态化与伪静态化】

#### 本章主要介绍静态化和伪静态化的背景知识，并在应用层实施首页静态化方案。
7-1 页面静态化与伪静态化简介 (07:29)

7-2 页面静态化方案分析 (09:00)

7-3 filecache包使用简介 (06:32)

7-4 搭建页面静态化框架 (07:58)

7-5 实现pagecache逻辑封装（上） (12:25)

7-6 实现pagecache逻辑封装（下） (05:11)

7-7 在BaseController中实现页面静态化 (06:19)

7-8 页面静态化性能测试 (03:47)

7-9 Beego 伪静态化实践 (07:59)

7-10 清理过期缓存文件 (17:46)

7-11 分类缓存改造 (12:07)


### 第8章 V2.1:动态缓存优化【基于Redis的动态缓存实践】

#### 动态缓存是一种常用的提升数据读写并发能力的手法。本章应用Redis组件对动态数据按一定策略进行缓存，有效减轻数据库压力。
8-1 动态缓存应用简介 (09:23)

8-2 安装redis服务 (15:47)

8-3 redis基础应用简介 (15:05)

8-4 【笔记】Redis安装以及基础使用

8-5 Go实战Redis基础（上） (07:48)

8-6 Go实战Redis基础（下） (15:14)

8-7 初始化动态缓存 (10:58)

8-8 封装redis的Do方法 (03:23)

8-9 dynamicache工具方法封装 (15:45)

8-10 实现图书详情页动态缓存逻辑 (09:56)

8-11 实现社区化个人主页动态缓存逻辑 (19:38)


### 第9章 V2.2 : 文件下载优化【文件服务拆分与CDN接入】

#### 本章中主要是对文件下载进行优化。通过介入阿里云的CDN服务，来和大家一起实践CDN服务的应用，并穿插讲解使用CDN服务时常遇到的一些问题。
9-1 CDN简介 (06:24)

9-2 开通阿里云ECS服务- (06:51)

9-3 开通阿里云OSS服务 (03:42)

9-4 开通阿里云CDN服务 (03:20)

9-5 配置CDN回源OSS (19:48)

9-6 OSS基础应用简介 (10:41)

9-7 图书附件CDN改造 (21:25)


### 第10章 V2.5 : Web服务并发优化【基于Nginx的负载均衡实践】

#### 在解决了数据层的瓶颈以后，我们把焦点集中在服务本身的性能提升上。如果我们的服务是无状态的，那我们可以对服务进行平行扩展。本章将和大家一起应用Nginx搭建双机负载均衡架构。
10-1 负载均衡背景简介 (07:28)

10-2 安装Nginx (05:55)

10-3 基于Nginx配置反向代理与负载均衡 (18:28)

10-4 多机部署Session同步问题讲解 (13:25)

10-5 总结与回顾 (12:14)


[下载地址](http://www.36tz.cn "下载地址")
