---
# 语言 （可选）
lang: zh-cn
# 网页关键词和描述
keywords: 简历,Java高级开发,杭州
description: 这是一份Java开发简历。
# 简历标题
resume_title: Winter Chen's Resume
# 应聘者姓名
name: 陈冬华
# 联系方式
contact:
  - icon: fas fa-globe-asia
    text: blog.winterchen.com
    url: https://blog.winterchen.com
  # 邮箱
  - icon: fas fa-envelope
    text: i@winterchen.com
    url: mailto:i@winterchen.com
  # 电话号码
  - icon: fas fa-phone-alt
    text: 15258800630
    url: tel:15258800630
# PDF下载链接
download:
  title: 下载PDF版
  icon: fas fa-download fa-fw
  url: http://img.winterchen.com/Java%E9%AB%98%E7%BA%A7%E5%BC%80%E5%8F%91-%E9%99%88%E5%86%AC%E5%8D%8E-15258800630-v1.1.pdf
---

{% raw %}
<grid>
<avatar><img src="http://img.winterchen.com/20200711221115-1.png"></avatar>
<h1>个人简历</h1>
<center>
<a href='https://blog.winterchen.com'>Blog</a> | <a href='https://github.com/WinterChenS'>Github</a>
</center>
<br>
</grid>
{% endraw %}



## <i class="fa fa-id-badge"></i> 个人简介

男 | 27岁 | 本科 | 浙江杭州 | 5年经验

拥有良好的编码规范以及开发能力；
良好的数据库调优的经验；
主导过架构缺陷的改进；
对前沿技术的热衷；
喜欢开源与技术分享，开源以及技术社区资深用户；
对技术问题非常执着；

## <i class="fa fa-coffee"></i> 求职意向

Java高级开发工程师 | 浙江杭州 | 20K-25K | 1个月内到岗


## <i class="fas fa-user-tie"></i> 工作经验


#### 2018.1 ~ 至今：吉利控股集团   Java开发一级工程师

1. 主导了线上交易中台订单模块和支付模块的开发和技术选型 
  • 根据当前的业务模型，订单相关的流程使用了saga模式分布式事务，支付流程选型RabbitMQ保证最终一致性； 
  • 负责Nacos集群的搭建，解决了系统单节点的安全隐患； 
  • 使用工厂和策略等模式，抽象了支付功能，以便于后续不同支付渠道的接入，增强了代码的可拓展性； 
2. 负责吉利C端业务（吉利APP，领克APP，几何APP）的开发 
  • 负责项目脚手架的开发并提供给多个项目，保证了项目快速稳定的开发； 
  • 编写了基于MDC的日志链路追踪的组件，方便线上问题定位，并且解决了Hystrix创建子线程导致traceId无法传递的问题； 
  • 使用搜索引擎解决了由于底层中心架构设计缺陷，导致数据无法分页的问题； 
  • 根据k8s的特性，解决了线上无法滚动发布的问题； 
  • 负责了线上问题定位以及jvm调优； 
3. 负责吉利B端业务（经销商管理系统、G助手等）的开发 
  • 负责报表模块的开发和调优； 
  • 负责了数据库调优，优化原本2分钟查询报表的时间为10s；



#### 2017.3 ~ 2017.12：杭州三重奏科技有限公司   Java开发工程师

1. 负责SaaS平台的代码编写和维护 
  • 编写了独立的定时任务服务跑报表数据，解决了查询等待时间过长的问题； 
  • 预研了SpringBoot等新技术，并且推动了在新的项目中的使用；拆箱即用，快速开发的特性，让开发人员更专注于业务代码的开发，减少了繁杂的配置，极大的提升了开发的效率；


> 离职原因：公司倒闭

#### 2016.4 ~ 2017.2：江西美和科技有限公司   Java开发工程师

1. 负责ERP系统的开发 
  • 负责业务代码的编写，在开发中很好的使用到缓存的技术，对重构有实际的经验,并对面向对 象开发有全面的实战经验。 
  • 了解java数据结构的使用场景,掌握了数据结构,对于并发和阻塞等有自己的见解。

> 离职原因：想来杭州发展

## <i class="fas fa-award"></i> 精选项目


{% raw %}
<btns rounded>
<a href='https://apps.apple.com/cn/app/lynkco/id1305517667'>
  <img src='http://img.winterchen.com/lynkco-logo.png'>
  Lynkco
</a>
<a href='https://apps.apple.com/cn/app/geometry/id1456960408'>
  <img src='http://img.winterchen.com/geometry-logo.png'>
  GEOMETRY
</a>
<a href='#'>
  <img src='http://img.winterchen.com/geely-logo.png'>
  吉利APP
</a>
</btns><br>
{% endraw %}


### 交易/商品中台

#### 2020.6 ~ 至今：后端开发

##### 技术栈

SpringCloud/Mybatis/Nacos/Apoll/Redis/RabbitMQ/Seata/Azure Devops/Docker/K8s

##### 项目描述

商品/交易中台目前主要提供吉利旗下精品商城和整车商城等电商模型的支持，对下层的订单和商品中心的服务进行编排和和流程的控制，并且控制了主要流程的分布式事务；并且该项目改进了数字营销生态项目群项目架构的缺陷；

#### 主要职责

1.参与交易，商品中台的架构设计和技术选型； 
2.负责交易中台订单模块的开发和流程的分析，以及分布式事务的实现；
3.负责支付模块的开发，使用策略模式对多渠道支付进行抽象，让支付模块后续的拓展性更好； 
4.负责线上问题定位以及调优；
5.对电商模型和中台的概念更加清晰和深入；
6.对领域驱动模型有了一定的理解；

### 数字营销生态项目群项目

#### 2019.3 ~ 2020.5：核心后端开发

##### 技术栈

SpringCloud/Mybatis/Apoll/Redis/RabbitMQ/Azure Devops/Docker/K8s 

##### 项目描述

数字营销生态项目群项目帮助吉利构建面向消费者的全面触达、交易、运营的营销数字化平台与服务 ；业务中台不仅可以将原本不同系统相同功能的服务聚合起来，统一标准，统一规范，统一出口，实现企业业务的整合；还可以通过服务的聚合实现资源与能力共享，支撑新应用与新业务的快速开发与迭代，以满足快速变更的用户需求。通过数字中台构建的客户触点体系，可以帮助企业客户实现业务数据化、数据业务化，赋能企业智能化，全面实现数字营销。

##### 工作职责

1.主要负责业务中台的领克APP管理端,几何APP，对接内容中心，用户中心等模块， 以及公共组件的开发；  
2.主导线上环境Docker，k8s等容器化技术的落地； 
3.编写日志全链路追踪公共组件，用于线上问题快速定位； 
4.主导优化架构设计缺陷带来的技术难题；
5.使用Redis和Solr等中间件对消费者业务进行缓存，减少了50%数据查询时间； 
6.负责线上问题定位以及调优；
7.负责公司技术文档的编写和维护，定期团队共同学习以及成长。

### G助手

#### 2018.12 ~ 2019.2：后端开发

##### 技术栈

SpringBoot/Dubbo/Oracle/Mybaits/RabbitMQ/Redis

##### 项目描述

项目主要功能是经销商对于客户看车、购车的整个流程的协作，包含了潜在客户跟进，试乘试驾，面容识别，驾驶证录入、第三方媒体信息的流入等等；

##### 工作职责

1.负责业务功能模块的代码编写和优化；
2.优化sql和索引，提高了50%的查询速度；
3.线上bug的定位和修复；
4.使用消息队列批量修复了3百万条的潜客历史问题数据；

### 经销商营销平台

#### 2018.7 ~ 2019.2：后端开发

##### 技术栈

Spring/Mybatis/Oracle/RabbitMQ

##### 项目描述

该项目是吉利汽车最核心的项目，也是最悠久的项目，涵盖了吉利汽车经销商一整套销售业务，包括：售前、售中、售后等，系统经过多次升级改造和优化，仍然是无法替代的系统；

##### 工作职责

1.潜客业务、报表业务等模块的功能编写；
2.数据库分表的功能以及逻辑的编写，将单表上亿的数据进行拆分，实现了报表查询速度由2分钟以上降低到10s；
3.数据库SQL的调优；

### CEP广宣核销系统

#### 2018.8 ~ 2018.11：后端开发

##### 技术栈

SpringCloud/Springboot/mysql/Mybatis/RabbitMQ/Redis

##### 项目描述

该项目主要是解决了集团对于经销商活动的策划以及活动开展的全生命周期的管理；涵盖了流程的审核，财务报销API的接入，主要接入API：财务报销API、业务流程审核API；云盘存储API

##### 工作职责

负责服务端从零开始的项目选型以及搭建、业务代码的编写、数据库SQL的调优、相关内部系统API的接入；

### PQMS项目管理平台

#### 2018.1 ~ 2018.7：Java后端开发

##### 技术栈

SpringCloud/Springboot/mysql/Mybatis/RaabitMQ/Redis

##### 项目描述

项目主要功能是对公司所有项目的生命周期和节点审计的管理；接入集团的其它系统实现数据集中化管理；

##### 工作职责

负责服务端代码的编写，数据库的调优，客户端API的接入、第三方API的接入；

### 九邑SaaS线上分销平台

#### 2017.3 ~ 2017.12：Java后端开发

##### 技术栈

SpringBoot/hibernate/mysql/redis

##### 项目描述

Saas服务，为线上的房地产提供分销解决方案，解决了传统房地产与房产中介之间的痛点，同时解决了案场的客户数据的集中和分析。项目主要功能为ERP的管理系统，实现了版本管理，用户管理，案场管理，审核管理，客户数据分析，以及日志的分析。我负责了案场的注册、审核、数据分析。而且单独搭建了一个对各个案场的客户数据进行归集的系统，实现了数据源的实时生成，数据表的实时创建，并且实现了每个案场不一样的数据源切换，然后将其数据进行归并和存储，还有集团管理平台的所有编码以及调试。

##### 工作职责

1.负责项目业务代码的编写；
2.主导了使用独立的服务进行复杂报表数据的定时生成，解决了查询报表等待1分钟以上的问题；
3.推进了新的技术落地，将学习到的新框架应用在新的服务中；


## <i class="fab fa-github"></i> 开源贡献


### my-site

#### 2018/5 ~ 至今，一个Docker+SpringBoot2.0+Mybatis+thymeleaf实现的个人主页网站

- 风格简约，对萌新友好
- 移动端优化
- 源码：https://github.com/WinterChenS/my-site

### trace-spring-boot

#### 2020/03 ~ 至今，MDC 实现的日志链路追踪组件

- 基于MDC
- 为springboot starter组件，开箱即用。
- 实现了常用的rpc常用组件如dubbo、feign，以及http调用，并且对熔断器提供了支持。
- 源码：https://github.com/WinterChenS/trace-spring-boot

### delay-server

#### 2020/05 ~ 至今，基于RabbitMQ实现的延迟服务

- 基于RabbitMQ私信队列实现
- 设计为一个可以拓展并且公共的延迟回调服务。
- 消息的可靠性极高。
- 源码：https://github.com/WinterChenS/delay-server


## <i class="fas fa-rss-square"></i> 社区贡献

### CSDN

- 原创作品：92篇
- 浏览量：   140W+
- 获赞：   597
- 粉丝：   1757
- 总排名： 5275
- 地址：https://blog.csdn.net/Winter_chen001


<!-- <fancybox>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot01.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot02.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot03.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot04.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot05.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot06.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot07.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot08.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot09.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot10.png'>
</fancybox> -->

## <i class="fas fa-phone-alt"></i> 与我联系

目前状态为：在职，考虑换工作，1个月内可到岗。

<i class="fas fa-envelope fa-fw"></i> i@winterchen.com
<i class="fas fa-phone-alt fa-fw"></i> 15258800630


## <i class="fas fa-user-graduate"></i> 教育背景

**南昌航空大学 模具设计与制造 15年毕业**


