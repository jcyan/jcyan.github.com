---
layout: post
title: "如何在Heroku部署Obtvse"
description: ""
category: how-to
tags: [blog, heroku, obtvse]
---
{% include JB/setup %}

废话不多说，步骤如下：

1 . 进入[Heroku][1]注册账号。

2 . 下载[Obtvse][2]。

3 . 进入~/Obtvse，删除 .git 文件夹。

4 . 打开~/Obtvse/config/config.yml，改为自己的配置。将下面两句中的username和password设置成后台登录名和密码。

>  <%= ENV["obtvse_login"] ? ENV["obtvse_login"] : "username" %>
>
> <%= ENV["obtvse_password"] ? ENV["obtvse_password"] : "password" %>

5 . 打开git bash （[download][4]），cd到Obtvse的目录，输入以下指令：

> heroku login

> git init

> git add .

> git commit -m "my first commit"

> git remote add heroku git@heroku.com:your\_app\_name.git

> rake db:migrate

> heroku keys:add ~/.ssh/id_rsa.pub

> git push heroku master

>heroku open

6 .  大功告成。


[1]:https://www.heroku.com/
[2]:https://github.com/NateW/obtvse
[3]:https://github.com/NateW/obtvse/zipball/master
[4]:http://git-scm.com/