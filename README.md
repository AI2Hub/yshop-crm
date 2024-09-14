

## 平台简介

yshop-crm意象客户关系管理系统，专门为企业销售团队量身定制的工具，能够有效的管理跟进客户提供销售业绩，无缝斜街打通YSHOP单商户系统！技术： SpringBoot3、Spring Security OAuth2、MybatisPlus、SpringSecurity、jwt、redis、Vue3的前后端分离的系统

官网地址：[https://www.yixiang.co/](https://www.yixiang.co/)



## 演示地址

| 后台登陆：  | https://crm.yixiang.co/   账号/密码：admin/admin123  |
|---|---|
|  关注右边公众号提前知晓系统更新日志 | ![输入图片说明](77a93e8c07a913b838a756abadb383b9.png) |

## 功能列表
| 待办事项 | 统计、待审核事项                    |
|------|-----------------------------|
| 客户管理 | 客户列表、客户跟踪、联系人、公海、客户查重、客户领取、批量导入、转移客户、发邮件等 |
| 商机管理 | 商机需求、跟进、产品添加、查看详情、发邮件、发短信等          |
| 线索管理 | 线索列表、跟进、线索池、转客、批量导入等             |
| 合同管理 | 合同列表、商品录入、详情、审核、收款回款、打印合同等       |
| 发票管理 | 添加发票、开具、审核等                 |
| 审核流程 | 合同、回款、发票等审流程配置              |
| 商品管理 | 商品分类、商品规格、商品列表              |



## 视频资料
如果对您有帮助，您可以点右上角 "Star" 支持一下，这样我们才有继续免费下去的动力，谢谢！ QQ交流群 (入群前，请在网页右上角点 "Star" )，群里有视频教程哦！！

交流QQ群：544263002

## 项目说明
    
```
    yshop-crm.             Java工程
    yshop-crm-vue          后台前端vue3工程
```

## 本地快速启动
  ##### 1、环境要求
   
    ```
        jdk17
        mysql8
        redis6+
        node16+
        maven3.8+
    
    ```
  ##### 2、开发工具
   
    ```
        idea
        vscode
    
    ```
 ##### 3、后端启动

-   3.1 请使用idea打开Java工程，自动会安装依赖
-   3.2 创建数据库且导入工程目录下sql/yshop-crm.sql 文件
-   3.3 找到项目下的yshop-server 的yml,修改数据库相关信息和redis相关信息，如图：
     ![输入图片说明](3344.png)
-   3.4 工程下输入
    ``` 
    mvn clean install package '-Dmaven.test.skip=true'
    ```
-   3.5 启动项目

##### 4、后台vue启动

 - 4.1 vscode 打开vue工程，在目录下输入命令: 
    ``` 
    pnpm install
    ```
 - 4.2 配置api如图
 ![输入图片说明](3355.jpg)
 - 4.3 本地启动:
    ```
     npm run dev
    ```

## 后台截图

| ![输入图片说明](1.png)  | ![输入图片说明](2.png)  |
|---|---|
| ![输入图片说明](3.png)  |  ![输入图片说明](4.png) |
|  ![输入图片说明](5.png) | ![输入图片说明](6.png)  |
| ![输入图片说明](7.png)  | ![输入图片说明](8.png)  |
| ![输入图片说明](9.png)  |  ![输入图片说明](10.png) |
| ![输入图片说明](11.png)  |  ![输入图片说明](12.png) |
| ![输入图片说明](13.png)  |  ![输入图片说明](14.png) |



## 技术栈
- Spring Boot3

- Spring Security oauth2

- MyBatis

- MyBatisPlus

- Redis

- lombok

- hutool

- Vue3

- Element UI

- uniapp(vue3)

## 特别鸣谢


- ruoyi-vue-pro:https://gitee.com/zhijiantianya/ruoyi-vue-pro
- element-plus:https://element-plus.gitee.io/zh-CN/
- vue:https://cn.vuejs.org/
- pay-java-parent:https://gitee.com/egzosn/pay-java-parent


## 使用须知

- 1.允许用于个人学习、毕业设计、教学案例、公益事业等商业使用;
- 2.如果商用必须保留版权信息，请自觉遵守;
- 3.禁止将本项目的代码和资源进行任何形式的出售，产生的一切任何后果责任由侵权者自负。

