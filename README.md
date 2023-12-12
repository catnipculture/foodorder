# 项目介绍

基于Spring Boot架构设计开发系统，综合运用MySQL、Layui、Vue、Element、ECharts等技术进行项目系统的开发。开发网上订餐系统，为顾客线上订餐提供便利。主要实现了顾客模块和管理员模块两大部分，

这两大模块具体功能如下：

（1）顾客模块：

①顾客登录系统进行菜单浏览

②可以输入食材进行菜品的模糊查询

③顾客进行菜品的选择添加，对已选菜品进行数量的增减或者取消

④选择完毕后提交订单到后台并进行结账功能

⑤顾客注册成为会会员可以对自己的个人信息进行更改，例如送餐地址、联系电话、账号密码等

⑥对于点过餐的顾客，再次登录系统可以为其推荐“可能想点的菜肴”



（2）管理员后台模块：

①管理员登录后台，可以创建管理员账号

②管理员可以对菜单进行增加、删除和修改，例如菜品的图片、价格、描述等

③管理员对提交到后台的订单进行审核管理，确定订单生成

④管理员可以查询管理历史订单，并导出Excel表格

⑤管理员可以根据时间段等条件统计营业额、成本，还可以统计出菜品的销售量整理排行榜

⑥可以统计顾客消费情况并以次为依据提升顾客会员等级并进行优惠打折（这个打折力度可以由管理员定期进行调整）



# 环境要求

1.运行环境：最好是java jdk1.8,我们在这个平台上运行的。其他版本理论上也可以。 

2.IDE环境：IDEA,Eclipse,Myeclipse都可以。推荐IDEA; 

3.tomcat环境：Tomcat7.x,8.X,9.x版本均可 

4.硬件环境：windows7/8/10 4G内存以上；或者Mac OS; 

5.是否Maven项目：是；查看源码目录中是否包含pom.xml;若包含，则为maven项目，否则为非maven.项目 

6.数据库：MySql5.7/8.0等版本均可；

# 技术栈

后台框架：Spring Boot、MyBatis

前端：VUE

数据库：MySQL

环境：JDK8、TOMCAT、IDEA

# 使用说明

1.使用Navicati或者其它工具，在mysql中创建对应sq文件名称的数据库，并导入项目的sql文件； 

2.使用IDEA/Eclipse/MyEclipse导入项目，修改配置，运行项目； 

3.将项目中config-propertiesi配置文件中的数据库配置改为自己的配置，然后运行；

# 运行指导

idea导入源码空间站顶目教程说明(Vindows版)-ssm篇：

http://mtw.so/5MHvZq 

源码看好后直接在网站付款下单即可，付款成功会自动弹出百度网盘链接，网站地址：[http://codegym.top](http://codegym.top/)。 

其它问题请关注公众号：**IT小舟**,关注后发送消息即可，都会给您回复的。若没有及时回复请耐心等待，通常当天会有回复



## 论文截图

![QQ浏览器截图20231202234815](https://gulimallcativen.oss-cn-shenzhen.aliyuncs.com/bishe/QQ%E6%B5%8F%E8%A7%88%E5%99%A8%E6%88%AA%E5%9B%BE20231202234815.jpg)



## 用户界面

![QQ浏览器截图20231202234333](https://gulimallcativen.oss-cn-shenzhen.aliyuncs.com/bishe/QQ%E6%B5%8F%E8%A7%88%E5%99%A8%E6%88%AA%E5%9B%BE20231202234333.png)

![QQ浏览器截图20231202234351](https://gulimallcativen.oss-cn-shenzhen.aliyuncs.com/bishe/QQ%E6%B5%8F%E8%A7%88%E5%99%A8%E6%88%AA%E5%9B%BE20231202234351.png)

![QQ浏览器截图20231202234417](https://gulimallcativen.oss-cn-shenzhen.aliyuncs.com/bishe/QQ%E6%B5%8F%E8%A7%88%E5%99%A8%E6%88%AA%E5%9B%BE20231202234417.png)

![QQ浏览器截图20231202234443](https://gulimallcativen.oss-cn-shenzhen.aliyuncs.com/bishe/QQ%E6%B5%8F%E8%A7%88%E5%99%A8%E6%88%AA%E5%9B%BE20231202234443.png)

![QQ浏览器截图20231202234513](https://gulimallcativen.oss-cn-shenzhen.aliyuncs.com/bishe/QQ%E6%B5%8F%E8%A7%88%E5%99%A8%E6%88%AA%E5%9B%BE20231202234513.png)



## 管理员界面

![QQ浏览器截图20231202234528](https://gulimallcativen.oss-cn-shenzhen.aliyuncs.com/bishe/QQ%E6%B5%8F%E8%A7%88%E5%99%A8%E6%88%AA%E5%9B%BE20231202234528.png)





![QQ浏览器截图20231202234540](https://gulimallcativen.oss-cn-shenzhen.aliyuncs.com/bishe/QQ%E6%B5%8F%E8%A7%88%E5%99%A8%E6%88%AA%E5%9B%BE20231202234540.png)

![QQ浏览器截图20231202234604](https://gulimallcativen.oss-cn-shenzhen.aliyuncs.com/bishe/QQ%E6%B5%8F%E8%A7%88%E5%99%A8%E6%88%AA%E5%9B%BE20231202234604.png)

![QQ浏览器截图20231202234613](https://gulimallcativen.oss-cn-shenzhen.aliyuncs.com/bishe/QQ%E6%B5%8F%E8%A7%88%E5%99%A8%E6%88%AA%E5%9B%BE20231202234613.png)
