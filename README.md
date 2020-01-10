# 大前端之Kubernetes与微服务

## 什么是K8S

- Kubernetes，希腊文导航家，因为首尾字母中间有8个字符，所以被简写成K8s。
- K8s是底层资源（部署那些容器的机器）与容器间的一个抽象层，如果和单机架构类比，可以算是一个分布式时代的Linux
- K8s 是Google开源的容器集群管理系统。在docker技术的基础上，为容器化的应用提供部署运行、资源调度、服务发现（需要什么功能要能找得到）和动态伸缩等一系列完整功能，提高了大规模容器集群管理的便捷性。微服务可以横向纵向扩展，横向就是同样的功能，复制多份拷贝做负载均衡。纵向扩展就是把一个业务串起来，一个业务步骤弄成一个微服务打包到docker里。尽管docker减轻了运维的很多工作，但仍是架不住“多”，容器也需要管理，于是k8s应运而生。

## K8S的特性

- k8s是一个管理容器的工具，也是**管理应用整个生命周期的一个工具，从创建应用，应用的部署，应用提供服务，扩容缩容应用，应用更新**，而且可以做到故障自愈。
- 可移植：支持公有云，私有云，混合云；
- 可扩展：模块化，热插拔，可组合；
- 自愈：自动替换，自动重启，自动复制，自动扩展；

### 源码编译安装方式

## K8S的安装与配置

### 安装

### 配置文件结构

### 常用配置方法

## 搭建一个Node.js集群
