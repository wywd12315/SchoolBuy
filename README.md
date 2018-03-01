项目介绍
======
本项目是我在暑假期间学习Django后制作的一个校园二手交易平台，旨在帮助同学们将自己无用的东西交易给他人。
信心满满的以为大家都会使用，然而学校里没人鸟我，桑心～～
但是本项目当作一个学习项目应该还是很棒的！！

背景介绍
=======
本项目基于python3.5开发，所需的库以记录在requirements.txt中。

前置信息
=======
提前预览 http://flycold.cn
直接克隆仓库，`python3 manage.py runserver` 即可启动。
后台管理地址：127.0.0.1:8000/admin/
后台管理密码：root
            rootisgad

我的邮箱：1041984720@qq.com,欢迎大家学习交流～～

具体功能
=======
###用户注册
提供用户注册功能，并将注册的帐号密码发给管理员的邮箱（settings.ADMIN_EMAIL）。
###用户登陆
对已注册的用户提供登陆功能。
###浏览商品
浏览当前发布的商品，并且可以进行一些简单的条件搜索。
###发布商品
对于已登陆的用户，提供发布商品功能。默认的商品类型为空，需要使用管理员帐号进入后台添加。
###绑定/解绑邮箱
绑定邮箱，忘记密码可以根据邮箱找回。
###发布留言
给商品发布留言，可以收到系统的提示。
###重置密码
基于邮箱来重置。
###修改个人信息
对用户的头像，用户名之类进行修改。

###更多细节，自己体验哦。

设置内容介绍
========
正常来说，以下内容您可以根据自己的需要进行修改：
- settings中的ADMIN_EMAIL,它决定了用户注册的信息发向谁。
- settings中的邮箱信息。您可以修改为自己的邮箱。
