﻿#### v 1.0.0

##### 介绍
* 这是用express,mongodb编写的简单的一个 `web blog` 框架
* 用户的数据没有做加密处理
* 评论没有做安全处理
* 没有添加富文本编辑器

##### 注意
* 依赖node，自己的环境是 `node v6.2.0`
* 依赖mongodb储存用户数据， `mongodb v3.2.4`
* `默认连接数据库才能打开网站！！！`

##### 第一次使用
* `cnpm install` 淘宝镜像安装模块
* `node app.js`
* `localhost:8081`默认首页
* `mongodb` 使用27017默认端口[要先了解mongodb]()
* db目录是mongodb的数据库的数据路径，但是我把测试数据备份到这里了，
	* 恢复db下面的备份数据到blog表
	* 或者删除所有的数据，自己注册用户，(或者命令行添加一个管理员账户)但是要更改一个用户为管理员，才能打开后台

#### v 1.0.1
* 内容管理的内容主体支持markdown的写法了，

#### v 1.0.2
* 内容管理的内容主体如果markdown的代码块中间有回车换行，会出现bug分隔，影响正则额判断
* 在bug文件夹中，有一个markdown的文件，覆盖到自己的markdwon模块，就会解决这个bug

#### v 1.0.3
* 继续修复markdown正匹配问题

#### v1.0.4

* 一个完整版本

![首页截图](./public/images/panda_index.png)

![管理页截图](./public/images/panda_admin.png)

![管理页截图1](./public/images/panda_admin2.png)