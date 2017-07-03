---
title: 大数据技术学习路线
date: 2017-06-23 15:24:20
tags:
- 大数据
- Hadoop
categories:
- 大数据
---

## 背景
近年来大数据BigData、人工智能AI、物联网Iot等行业发展迅猛，很多人都想要从事大数据技术开发工作，但是，请问要`怎么做`，`路线是什么？从哪里开始学？学哪些？`这是一个大问题。对于我自己来说，最近也在学一些大数据开发相关的技术，所以之前整理了一份`《大数据技术学习路线》`，希望对你有所帮助。

<!-- more -->

## 学习规划
总共分为五大部分，分别是：
* 大数据技术基础
* 离线计算Hadoop
* 流式计算Storm
* 内存计算Spark
* 机器学习算法

目前我学完了约60%的内容，但还有很多需要多实践、和深研的地方，我也在继续学习，和摸索当中。希望你早日能成为大数据技术开发中的一员，然后大家一起学习，和技术交流。

## 技术说明
这里我只列举了`技术点`，给你提供了一个学习方向，具体实现内容可以借助网络去学习了，相信这方面你应该懂得了如何借助网络力量，然后进行自我学习了。

### 大数据技术基础

#### linux操作基础
 - linux系统简介与安装
 - linux常用命令--文件操作
 - linux常用命令--用户管理与权限
 - linux常用命令--系统管理
 - linux常用命令--免密登陆配置与网络管理
 - linux上常用软件安装
 - linux本地yum源配置及yum软件安装
 - linux防火墙配置
 - linux高级文本处理命令cut、sed、awk
 - linux定时任务crontab

#### shell编程
 - shell编程--基本语法
 - shell编程--流程控制
 - shell编程--函数
 - shell编程--综合案例--自动化部署脚本

#### 内存数据库redis
 - redis和nosql简介
 - redis客户端连接
 - redis的string类型数据结构操作及应用-对象缓存
 - redis的list类型数据结构操作及应用案例-任务调度队列
 - redis的hash及set数据结构操作及应用案例-购物车
 - redis的sortedset数据结构操作及应用案例-排行榜

#### 布式协调服务zookeeper
 - zookeeper简介及应用场景
 - zookeeper集群安装部署
 - zookeeper的数据节点与命令行操作
 - zookeeper的java客户端基本操作及事件监听
 - zookeeper核心机制及数据节点
 - zookeeper应用案例--分布式共享资源锁
 - zookeeper应用案例--服务器上下线动态感知
 - zookeeper的数据一致性原理及leader选举机制

#### java高级特性增强
 - Java多线程基本知识
 - Java同步关键词详解
 - java并发包线程池及在开源软件中的应用
 - Java并发包消息队里及在开源软件中的应用
 - Java JMS技术
 - Java动态代理反射

#### 轻量级RPC框架开发
 - RPC原理学习
 - Nio原理学习
 - Netty常用API学习
 - 轻量级RPC框架需求分析及原理分析
 - 轻量级RPC框架开发


### 离线计算Hadoop

#### hadoop快速入门
 - hadoop背景介绍
 - 分布式系统概述
 - 离线数据分析流程介绍
 - 集群搭建
 - 集群使用初步

#### HDFS增强
 - HDFS的概念和特性
 - HDFS的shell(命令行客户端)操作
 - HDFS的工作机制
 - NAMENODE的工作机制
 - java的api操作
 - 案例1：开发shell采集脚本

#### MAPREDUCE详解
 - 自定义hadoop的RPC框架
 - Mapreduce编程规范及示例编写
 - Mapreduce程序运行模式及debug方法
 - mapreduce程序运行模式的内在机理
 - mapreduce运算框架的主体工作流程
 - 自定义对象的序列化方法
 - MapReduce编程案例

#### MAPREDUCE增强
 - Mapreduce排序
 - 自定义partitioner
 - Mapreduce的combiner
 - mapreduce工作机制详解

#### MAPREDUCE实战
 - maptask并行度机制-文件切片
 - maptask并行度设置
 - 倒排索引
 - 共同好友

#### federation介绍和hive使用
 - Hadoop的HA机制
 - HA集群的安装部署
 - 集群运维测试之Datanode动态上下线
 - 集群运维测试之Namenode状态切换管理
 - 集群运维测试之数据块的balance
 - HA下HDFS-API变化
 - hive简介
 - hive架构
 - hive安装部署
 - hvie初使用

#### hive增强和flume介绍
 - HQL-DDL基本语法
 - HQL-DML基本语法
 - HIVE的join
 - HIVE 参数配置
 - HIVE 自定义函数和Transform
 - HIVE 执行HQL的实例分析
 - HIVE最佳实践注意点
 - HIVE优化策略
 - HIVE实战案例
 - Flume介绍
 - Flume的安装部署
 - 案例：采集目录到HDFS
 - 案例：采集文件到HDFS

### 流式计算Storm

#### Storm从入门到精通
 - Storm是什么
 - Storm架构分析
 - Storm架构分析
 - Storm编程模型、Tuple源码、并发度分析
 - Storm WordCount案例及常用Api分析
 - Storm集群部署实战
 - Storm+Kafka+Redis业务指标计算
 - Storm源码下载编译
 - Strom集群启动及源码分析
 - Storm任务提交及源码分析
 - Storm数据发送流程分析
 - Storm通信机制分析
 - Storm消息容错机制及源码分析
 - Storm多stream项目分析
 - 编写自己的流式任务执行框架

#### Storm上下游及架构集成
 - 消息队列是什么
 - Kakfa核心组件
 - Kafka集群部署实战及常用命令
 - Kafka配置文件梳理
 - Kakfa JavaApi学习
 - Kafka文件存储机制分析
 - Redis基础及单机环境部署
 - Redis数据结构及典型案例
 - Flume快速入门
 - Flume+Kafka+Storm+Redis整合

### 内存计算Spark

#### scala编程
 - scala编程介绍
 - scala相关软件安装
 - scala基础语法
 - scala方法和函数
 - scala函数式编程特点
 - scala数组和集合
 - scala编程练习（单机版WordCount）
 - scala面向对象
 - scala模式匹配
 - actor编程介绍
 - option和偏函数
 - 实战：actor的并发WordCount
 - 柯里化
 - 隐式转换

#### AKKA与RPC
 - Akka并发编程框架
 - 实战：RPC编程实战

#### Spark快速入门
 - spark介绍
 - spark环境搭建
 - RDD简介
 - RDD的转换和动作
 - 实战：RDD综合练习
 - RDD高级算子
 - 自定义Partitioner
 - 实战：网站访问次数
 - 广播变量
 - 实战：根据IP计算归属地
 - 自定义排序
 - 利用JDBC RDD实现数据导入导出
 - WorldCount执行流程详解

#### RDD详解
 - RDD依赖关系
 - RDD缓存机制
 - RDD的Checkpoint检查点机制
 - Spark任务执行过程分析
 - RDD的Stage划分

#### Spark-Sql应用
 - Spark-SQL
 - Spark结合Hive
 - DataFrame
 - 实战：Spark-SQL和DataFrame案例

#### SparkStreaming应用实战
 - Spark-Streaming简介
 - Spark-Streaming编程
 - 实战：StageFulWordCount
 - Flume结合Spark Streaming
 - Kafka结合Spark Streaming
 - 窗口函数
 - ELK技术栈介绍
 - ElasticSearch安装和使用
 - Storm架构分析
 - Storm编程模型、Tuple源码、并发度分析
 - Storm WordCount案例及常用Api分析

#### Spark核心源码解析
 - Spark源码编译
 - Spark远程debug
 - Spark任务提交行流程源码分析
 - Spark通信流程源码分析
 - SparkContext创建过程源码分析
 - DriverActor和ClientActor通信过程源码分析
 - Worker启动Executor过程源码分析
 - Executor向DriverActor注册过程源码分析
 - Executor向Driver注册过程源码分析
 - DAGScheduler和TaskScheduler源码分析
 - Shuffle过程源码分析
 - Task执行过程源码分析

### 机器学习算法

#### python及numpy库
 - 机器学习简介
 - 机器学习与python
 - python语言--快速入门
 - python语言--数据类型详解
 - python语言--流程控制语句
 - python语言--函数使用
 - python语言--模块和包
 - phthon语言--面向对象
 - python机器学习算法库--numpy
 - 机器学习必备数学知识--概率论

#### 常用算法实现
 - knn分类算法--算法原理
 - knn分类算法--代码实现
 - knn分类算法--手写字识别案例
 - lineage回归分类算法--算法原理
 - lineage回归分类算法--算法实现及demo
 - 朴素贝叶斯分类算法--算法原理
 - 朴素贝叶斯分类算法--算法实现
 - 朴素贝叶斯分类算法--垃圾邮件识别应用案例
 - kmeans聚类算法--算法原理
 - kmeans聚类算法--算法实现
 - kmeans聚类算法--地理位置聚类应用
 - 决策树分类算法--算法原理
 - 决策树分类算法--算法实现


 ## 尾记
 看完有信心能坚持学习吗？如果你的答案是肯定的，那就当下开始行动吧！Fighting~
 推荐两个相关的学习博客地址：

 * [Hadoop学习教程](http://blog.csdn.net/hemin1003/article/category/6985523/)
 * [Hadoop家族系列文章](http://blog.fens.me/series-hadoop-family/)
 * [Hadoop使用教程](http://www.powerxing.com/tag/hadoop/)