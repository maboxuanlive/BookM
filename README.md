
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
