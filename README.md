﻿gt-php-sdk
============

GtWeb Php Demo

文件描述
==========

1. lib/geetestlib.php
	极验的PHP SDK库
#. VerifyLogin.php
	调用Sdk的示例Servlet
#. login.php
	使用验证码的前端示范页面  

发布日志（由新到旧）
======================

15.1.28.1
-----------------------------------------
1. SDK加入了自主生成id的接口
#. 前端src引用有了加强版
#. SDK的版本编号规则发生变化

14.8.28
-----------------------------------------
1. login.php里面的`gt`替换成自己验证码的id 
     http://api.geetest.com/get.php?gt=a40fd3b0d712165c5d13e6f747e948d4" 
2. VerifyLogin.php里面的`$PRIVATE_KEY`替换成自己验证码的key值


联系作者：
Email:tanxu1993@gmail.com