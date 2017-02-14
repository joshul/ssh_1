###实现员工管理系统
####参考
慕课网SSH员工管理的视频教程重新总结了自己使用SSH开发项目的经历。
####开发环境
win7+IDEA+SSH框架。
####写在前面的话
之前在学习了jsp、servlet、jdbc和mysql数据库相关技术之后就做过相关的客户员工之类的练习，初步学习了Struts2、Hibernate、Spring框架之后呢,就想使用ssh框架实现下类似的系统,对比一下使用框架和使用jsp、servlet 的好处优点。
这里做一个使用三个框架整合的案例,也算是对相关技术的复习运用，加深理解吧。详细过程请[ 请点击这里 ]( http://www.jianshu.com/u/0cb624d78376 )或前往我的[ 简书地址 ]( http://www.jianshu.com/u/0cb624d78376 )观看吧。
####页面展示


登录页
![](https://github.com/joshul/image/blob/master/index.png)

详情页
![](https://github.com/joshul/image/blob/master/page1.png)

详情页
![](https://github.com/joshul/image/blob/master/page2.png)

编辑页面
![](https://github.com/joshul/image/blob/master/page5.png)

数据表department
![](https://github.com/joshul/image/blob/master/department.png)

数据表emproyee
![](https://github.com/joshul/image/blob/master/employee.png)


####功能简述
1.首先是登陆页面，管理员登陆权限设定只能是人事部员工的才可以登陆
2.登陆只能可以在部门管理栏和员工管理，部门管理可以进行添加新部门、删除旧部门和编辑操作，员工管理同样也可以进行编辑、删除、添加新员工。

####相关技术介绍
- MySQL：1. 这里我们采用手写代码创建相关表，掌握这种能力对我们以后的项目二次上线会有很大的帮助；2.SQL技巧；3.事务和行级锁的理解和一些应用。
- hibernate：1.DAO层的设计与开发。2.hibernate的合理使用，使用配置xml实体与数据表实现ORM映射，实现进行数据库的访问。3.hibernate和Spring框架的整合。
- Spring：1.Spring IOC帮我们整合Service以及Service所有的依赖。2.声明式事务。对Spring声明式事务做一些分析以及它的行为分析。
- Struts2：1.Action处理请求控制。2.Struts2标签库。

####项目代码编写

####1.创建项目项目工程
工程目录
![工程目录](https://github.com/joshul/image/blob/master/page3.png)

所需的jar包
![工程目录](https://github.com/joshul/image/blob/master/page4.png)
在这并没有使用maven（ :)之前还没学会 ）
####2.业务分析
在这就不在太详细介绍了，对github编辑还不太熟，网咯慢，具体说明请前往我的简书博客，或直接查看源码
####3.代码编写
包括sql
在这就不在太详细介绍了，对github编辑还不太熟，网咯慢，具体说明请前往我的简书博客，或直接查看源码
