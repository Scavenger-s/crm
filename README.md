# 客户关系模块(crm)
### Introduction
* 本项目为[bos物流项目客户模块](https://github.com/Scavenger-s/BosDemo.git)
* 本项目采用`apache cxf分布式框架`进行远程调用
---
### Quick Start
1. 向本项目clone到本地
2. 在数据库中运行t_customer.sql文件，搭建数据库环境
3. 将项目发布到tomcat中
4. 复制发布后的网址，cmd-->打开终端-->输入wsimport -s . + 生成的网址，解析代码
5. 将生成的ICustomerService接口放到[bos物流项目](https://github.com/Scavenger-s/BosDemo.git)中的bos-utils/src/main/java/com/cusx/crm



