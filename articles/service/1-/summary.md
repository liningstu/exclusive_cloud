# 产品概述

1. 产品简介：产品概述中最关键的部分，说明产品是什么，包括名词解释、用途、关键技术等的简要说明。

2. 产品特性：产品特性也是概述的一部分。

3. 产品主要技术性能指标：产品主要技术性能指标也是概述的一部分。

4. 产品的创新性：将新产品、新技术、新服务成功引入市场，改善或创造产品，进一步满足客户需求或开辟新的市场。

----------

## 1.产品简介： ##



用友云服务治理平台是云平台提供的针对微服务应用的统一管控和治理平台，以下简称服务治理平台。  

服务治理平台旨在提供适合用友云产品和其他业务线的统一微服务治理工具集，包括RPC开发框架、基础的组件和中间件、稳定性组件以及服务搜索和管控门户，已此来帮助云平台其他云产品及用友的业务和领域产品更合理的进行微服务的拆分、开发、管控，统一规范，简化开发。。


----------

## 2.产品特性： ##
服务治理平台包括：
- RPC框架

> 基础的微服务间RPC调用框架，支持多种序列化协议，提供token校验和心跳检查机制的服务注册中心，注册中心支持高可用架构集群部署；支持生成客户端代理Bean和动态代理；
- 基础中间件

> 包括基础的组件加载器，上下文初始化机制；提供包隔离机制的完整组件，包含可扩展的插件机制，支持通过插件方式在调用方和提供方不同时机接入业务处理；包含配置中心的支持，动态拉取关键配置文件；
- 稳定性组件

> 提供线程数和QPS方式的服务限流控制；提供服务链路追踪功能，可以查看服务调用层级和调用链路，调用的状态和成功率；提供应用级别和方法级别的权限控制；
- 开发适配组件

> 适配组件包含对spring工程的适配，兼容大多数的spring版本；包含对dubbo工程的适配，解析dubbo原生的配置文件并创建代理；包含对iuap工程的上下文传递功能的适配；
- 服务治理平台门户

>治理平台门户包含统一的管控面板、对认证秘钥的管理、应用的管理、服务调用的权限控制、链路查看、服务搜索、元数据管理等；


----------
## 3.产品的创新性 ##
服务治理平台致力于打造敏捷高效、安全、开放的服务于微服务全生命周期的平台。

- 简单易用：

> 极简配置的服务开发过程，通过注解方式实现微服务注册管理和通信路由等特性，运行期无感知的访问负载、服务优雅降级、服务监控、链路追踪等能力。

- 敏捷高效：

> 提供应用开发、运行、运维全生命周期的管理支持，基于敏捷开发，可以方便的进行产品改进迭代。

- 安全可靠：

> 平台通过用户身份验证，微服务应用级别的权限控制保证服务安全，在运行期通过限流、容错、监控等手段保证应用的稳定可靠。

- 开放先进：

> 基于云平台多年的技术积累，结合Netflix的SringCloud技术栈，在Docker和K8S的支持下，服务治理平台形成了特有的面向能力扩展微服务技术生态。
