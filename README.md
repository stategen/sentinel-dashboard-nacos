# sentinel-dashboard

#### 介绍
基于 sentinel-dashboard 改造，持久化流控、降级等规则至Nacos     

## 修改内容: 
- nacos-client 1.3.0 换成 nacos-client 1.3.3 ,原版本通信到 nacos-server-1.3.2有些问题
- 同步到nacos中的json原来是压缩的只有一行，不适合生成环境编辑，改为美化的json
- 最终文件名： sentinel-dashboard-nacos-1.8.0-jar

#### 软件架构
软件架构说明
- 原项目地址：https://gitee.com/francisoyc/sentinel-dashboard.git   
- 参见原修者文章：https://blog.csdn.net/oyc619491800/article/details/112206645     

