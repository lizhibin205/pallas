
## 适用人群

Elasticsearch是一款优秀的开源分布式搜素引擎。对于即将使用ES和已经在使用ES的个人和团队，Pallas为其提供一套完整的行业解决方案。

### 即将使用ES：

Elasticsearch本身的使用、管理门槛较高，Pallas为使用者提供一套易用、完善的解决方案。

#### 1 集群管理、监控、路由功能

  - ES本身并没有提供集群的可视化管理及监控功能
  
  - x-pack虽然提供了集群的可视化管理，但其不支持多集群，且需要插件

#### 2 在线管理索引

  - 支持在线增删改查索引
  
  - 索引版本切换
  
  - 审计功能

#### 3 基于索引粒度的模板管理

  提供模板管理、在线调试、可视化管理等功能。与kibana（与ES协作的一款开源数据分析与可视化平台）相比，Pallas具有如下优势：

  - 采用Search Template的请求方式，统一各业务方的请求格式，便于管理

  - 模板批量导入与导出功能

  - 模板中公共的部分支持以宏文件的形式管理

  - 模板版本控制、对比、审批功能

#### 4 ES代理功能
  
  基于Netty，Pallas search提供以下服务治理功能：

  - 鉴权

  - 动态路由，提供集群和索引级别的动态路由

  - 负载均衡

  - 超时重试

  - 流量录制

  - 调用链跟踪

#### 5 插件在线更新

  与ES原生插件相比，Pallas插件不需要重启节点即可生效。除此之外，提供一套完整的插件管理方案，包括：
  
  - 插件按域管理、版本管理、发布审批
  
  - 插件启用、禁用、降级、回滚
  
  - 插件监控
  
### 已在使用ES：

  只需在Pallas Console配置集群地址，便可使用可视化管理监控功能。
  
### 数据同步

  对于使用Mysql数据源，并将数据同步到ES的个人和团队而言，Pallas index提供自动同步MySQL数据到ES的功能，包括全量、增量以及对账功能。
  
  计划2019年Q1开源。


  
  








  
  
  