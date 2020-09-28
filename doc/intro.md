# 真实世界的PostgreSQL

本书主要介绍 —— 真实使用场景下的PG。基于pigsty项目，演示如何在真实生产环境中部署、管理与维护大规模PostgreSQL集群。



[TOC]

## 第一部分：上手

### 快速开始

* 集群概览
* 基本概念
* 上手指南
* 客户端工具
* 连接方式

### 观察

* 监控概览
* 节点监控
* 实例监控
* 集群监控
* 慢查询
* 其它



## 第二部分：部署

### 系统规划

* 容量评估
* 硬件规划
* 硬件性能评测
* 选择合适的环境
* 构建本地开发测试环境
* Vagrant快速上手

### 基础设施

* Ansible快速上手
* 本地源
* 本地CA
* 离线安装部署
* DNS服务部署
* NTP服务部署
* DCS服务部署
* 监控服务部署

### 数据库

* Postgres单机部署
* Postgres主从部署
* Pgbouncer部署
* Patroni部署
* 使用Patroni初始化集群
* 定制数据库模板
* 针对业务模式优化

### 接入层

* 选择合适的接入方式
* 直连使用Pgbouncer
* DNS服务
* Haproxy接入
* 



## 第三部分：监控

#### 监控系统

* 架构概览
* Prometheus快速上手
* node_exporter快速上手
* pg_exporter快速上手
* 服务发现

#### 监控指标

* 操作系统指标
* 数据库指标
* 连接池指标
* 负载均衡器指标
* 聚合指标
* 预计算规则

#### 报警系统

* 基于Grafana的简易报警系统
* 基于Altermanager的生产级报警系统
* 报警规则概览
* 阈值调优

#### 系统目录

* 初识PG Catalog



## 第四部分：管理

### 



### 监控



4. **监控**

* 
  * 

1. 日志

   * PostgreSQL日志格式
   * PostgreSQL日志配置选项
   * 使用mtail收集日志监控指标
   * 使用filebeat收集PG日志
   * 使用PgBadger提取日志摘要

   * PG日志中的重要信息
   * PG日志可视化
   * 使用SQL处理分析PG日志

2. 

   * 洞察

   * 方法论
   * 故障定位
   * 性能分析

3. 维护

   * 监控系统
   * 报警系统
   * 日志系统
   * 日常维护
   * 扩容缩容
   * 变更管理

4. 容灾
   * 备份
   * 恢复
   * 延迟备库
   * 校验和与Rewind

5. 代理、服务发现与负载均衡
   * DNS LB
   * 服务发现
   * Haproxy
   * Pgbouncer
   * 应对过载
   * 处理雪崩

6. 高可用
   * Patroni
   * 常见案例
   * 保障DCS的可用性

7. 安全性

   * 配置SSL
   * 基本权限模型
   * 基本HBA配置策略
   * Pgbouncer安全加固
   * Patroni安全加固
   * Consul安全加固
   * ETCD安全加固

  

**第三部分：故障演练**

* 第十章：故障诊断与处理
* 第十一章：应用层故障诊断与处理
* 第十二章：管理制度


