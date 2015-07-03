#AppCms部署说明
---------------------------
##.打开myeclipse (eclipse雷同)   全部编码 utf-8 包括数据库
右键 ->  Import -> 选择如图 –> 选择解压的源码 – finish
![导入说明](https://raw.githubusercontent.com/fengzyz/appCms/master/image001.png)  
##.检查jdk配置(别用myeclispe自带的jdk)
这个报错原因，是使用的myeclipse自带的jdk
![导入说明](https://raw.githubusercontent.com/fengzyz/appCms/master/image005.png)  
右键项目 -> Build Path -> Configure Build Path... 
![导入说明](https://raw.githubusercontent.com/fengzyz/appCms/master/image007.png)
不能出现[unfound]字样, 你的jdk哪个版本，引入对应的版本，支持jdk 6 7 8
项目编码 utf8  （右键项目 –> properties）
 
##.数据库链接配置
 ![导入说明](https://raw.githubusercontent.com/fengzyz/appCms/master/image011.png)
##.开发工具环境检查
###1．Tomcat的jdk是否配
##导入数据库(编码都是utf8) 数据库编码如何设置？(请百度)
###1．Mysql
 
建议用第三方链接数据库工具软件操作，例如：navicat 已提供下载地址,可破解
> * 新建数据库名为 numysql 
> * 右键，运行SQL ,选择numysql.sql 执行 
> * oracle  步骤与mysql 雷同需要新建用户和授权
 

