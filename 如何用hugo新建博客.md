一、安装初始化hugo

1.  注意安装的版本和文件位置

2.  `echo blog/xxxx.github.io-creator`

3.  `hugo new site /xxxx.github.io-creator`

4.  cd /xxxx.github.io-creator

5.  git init

6.  git submodule add [https://github.com/budparr/gohugo-theme-ananke.git](https://github.com/budparr/gohugo-theme-ananke.git) themes/ananke

7.  echo 'theme = "ananke"' >> config.toml

8.  hugo new posts/xxxx.md

9.  hugo

二、创建仓库和连接仓库

1.  创建:用户名.github.io的仓库

2.  在xxxx.github.io-creator目录下，新建.gitignore文件，写入/public（将public加入忽略名单）。

3.  关联仓库并上传文件：git remote add origin <仓库地址> 、 git push -u origin master

4.  打开:用户名.github.io 即可看到效果
