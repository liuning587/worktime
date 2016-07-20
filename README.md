worktime
========

定位为项目管理，BUG管理。特点是容易安装，使用方便，界面简单友好。

[使用 laravel 重新写的worktime2](https://github.com/aoktian/worktime2)

序
----

在做项目的时候，想找一个项目管理软件，使用了redmine、bugzilla等，感觉太大了，
而且安装很不方便，大部分功能也不是我们想要的

所以自己实现了这个，现在我们团队有20多个人，使用的很好。
开发人员可以很清楚的知道自己要干什么

使用这个软件的心得是：团队中必须有两个关键的角色，项目负责人和技术负责人。
项目负责人主要是整理需求
技术负责人主要是分配需求

环境要求
----

* php5.3

安装方法
----

* 修改Config/Config_Common.php 中的配置，应用名称和数据库名
* 修改upload文件夹的可写权限，用来保存上传的图片
* 在浏览器中访问 http://.../worktime/index.php
* 执行安装操作

