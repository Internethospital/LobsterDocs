# 互联网产品技术开发平台介绍(Lobster)

![Lobster](images/shuoming.png)

> 1、如果开发一个新的互联网产品，就可以使用Lobster作为技术平台，快速开发Web系统、小程序、APP等。无需浪费太多时间再技术选型、技术架构搭建等上面，让团队立马进入产品业务功能开发。

> 2、Lobster包括Web开发、APP开发、小程序开发、Winform客户端开发等。
后端技术采用.netcore，支持微服务、分布式技术、Docker部署等。
前端技术，Web采用LayUI，小程序采用微信小程序，APP采用H5+SDK。
支持Docker部署。

> 3、团队开发管理建议采用敏捷开发，所以Lobster还提供一些敏捷指导，包括敏捷思维、敏捷实践和敏捷工具。

查看技术文档：[https://docs.efwplus.cn/](https://docs.efwplus.cn/)

从Github上获取Demo：[https://github.com/Internethospital/LobsterDemo](https://github.com/Internethospital/LobsterDemo)

## 互联网医院架构

![Lobster](images/互联网医院架构.png)

## 基础平台架构

![Lobster](images/基础平台架构.png)

## Lobster微服务技术架构

![Lobster](images/Lobster微服务技术架构.png)

Web：采用LayUI前端框架

APP：采用DCloud的H5+

小程序：微信小程序

API网关：采用Ocelot

服务注册与发现：采用Consul

服务分布式监控：采用SkyWalking

作业调度：采用Quartz

部署：Docker

Docker仓库：Harbor


## Lobster开发持续集成

开发人员将代码提交到Git，然后再Jenkins上点击构建，Jenkins就会自动完成后续的编译、发布、部署工作，你只要等构建成功后访问你的站点即可。

这样开发和测试之前就没有了发版本再测试这个环节，开发完成一个功能提交代码，测试构建就是用最新的代码验证的。这样开发和测试之间做到无缝衔接。

![Lobster](images/持续集成.png)
