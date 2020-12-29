描述：

java+mysql数据库实现的图书管理系统，实现了图书添加，图书删除，图书修改，图书查看，图书列表查看等，用户增加，用户删除。用户修改，用户查看等

功能：

图书管理功能：图书添加，图书删除，图书修改，图书查看，图书列表

用户管理功能：用户增加，用户删除。用户修改，用户查看等，用户列表

图书借阅归还：图书借阅，图书归还

管理员添加：添加管理员

关于系统：关于系统  退出系统

登录：首页登录功能


安装步骤

1.首先确保自己本地的java环境正确，mysql服务启动正确（如果用navicat连接mysql就说明正确）

2.创建一个名字是db_book的数据库

3.在这个db_book库中创建两张表,sql语句如下

/*第一张表*/

CREATE TABLE `t_book` (
  `id` varchar(20) NOT NULL,
  `name` varchar(255) NOT NULL,
  `num` int(11) NOT NULL,
  `price` float(10,2) NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8;

/*第二张表*/

CREATE TABLE `t_user` (
  `accout` varchar(255) NOT NULL,
  `pass` varchar(255) NOT NULL,
  PRIMARY KEY (`accout`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8;

4.在Idea中导入代码

运行代码

