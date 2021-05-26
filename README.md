招聘平台/找工作/找企业/简历/用人单位/发布岗位
# 招聘平台介绍
## 平台介绍
本平台分为PC和App两端，pc端分为普通用户\企业端以及管理员端，根据角色来区分；App为普通用户使用。同时支持公众号。普通用户可完善自己的简历，并根据模板导出简历。可在线投递简历，筛选意向公司；查看相关人事资料、流程；可报名参加线上线下招聘会；用户端功能大致分为：找工作、找企业、线上线下招聘会、个人中心、完善简历信息等。App端功能只有普通用户端。

## 联系方式
tel/wx：15513131088
## 技术选型

### 1. 环境

* Java SDK 1.8
* Apache Maven 3.6+
* 支持Docker、k8s等
### 2. 主框架

* Spring Boot 2.2
* Spring Websocket
* Apache Shiro 1.6
* Flowable
* Webpack
* Jwt
* Swagger
### 3.持久层

* Apache Mybatis 3.5
* Alibaba Druid 1.1
* Hibernate Validation 6.0（服务端验证）
* Sharding JDBC 4.0（读写分离、分库分表）
### 4.视图层

* Spring MVC 5.2
* Beel 3.1（视图模板引擎、替换JSP）
* CSS框架：
    * Bootstrap 3.3
    * AdminLTE 2.4
* JS框架及组件
    * Jquery 1.12
    * layer 3.1
    * zTree 3.5
    * jqGrid 4.7
    * jquery-validation
    * wdScrollTab
    * webuploader
    * uediter
    * toastr
###  5.工具组件

* Logback 1.2
* Apache Commons
* 对象序列化：FST 2.57
* JSON序列化：Jackson 2.10
* Office工具：POI 4.1
* 分布式任务调度：Quartz 2.3
* 全文检索引擎：ElasticSearch、Lucene
* 阿里云/极光短信
### 6.存储

* 数据库：mysql
* 缓存：Redis/ehcache
## 主要功能
### 1、PC端

* 普通用户端
    * 查询企业信息
    * 查询岗位信息
    * 查询最新招聘资讯
    * 查看人事档案资源
    *  参加线上/线下招聘会
    *  导出简历模板（模板可供选择）
    *  投递简历
* 企业用户端
    * 完善企业信息，提交至管理端审核
    * 发布岗位
    * 找人才
    * 线下招聘会选择展位入驻
    * 参加入驻线上招聘会
    * 查看简历
    * 发布职位相关资讯
* 管理员端
    * 管理、审核企业信息资质
    * 管理求职者信息
    * 发布线上招聘会
    * 发布线下招聘会
    * 人事档案办公流程管理
    * 发布新闻公告
    * 发布劳务输出相关信息
    * 配置简历模板
    * 大屏统计信息
    * app端轮播图、资讯管理
    * pc首页弹窗管理、栏目管理等
### 2、移动端（app/公众号，注：只有普通用户端）

* 注册、登录
    * 通过手机号+验证码/密码的方式注册/登录
* 完善个人信息、简历
* 找工作、多条件查询意向岗位
* 投递简历
* 导出个人简历
* 线上联系招聘方
* 参加线上招聘会
* 查看职说
* 简历被查看提醒
## 平台截图
### 1、PC用户端

### 2、PC管理员端

### 3、APP端
