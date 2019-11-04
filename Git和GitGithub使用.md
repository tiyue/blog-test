## Git初始化配置
1. git config --global user.name 你的英文名
2. git config --global user.email 你的邮箱
3. git config --global push.default simple
4. git config --global core.quotepath false
5. git config --global core.editor "code --wait"
6. git config --global core.autocrlf input
## Git基本指令
- git clone <仓库地址> 下载仓库到本地
- git init 初始化仓库
- git remote add origin git@XXXXXX 关联远程仓库
- git push -u origin master 上传至远程仓库
- git pull origin master  -f  强制拉取远程仓库到本地
- git add 路径 添加文件到Git仓库
- git status -sb 查看当前变更(简化)
- git commit -V 提交到仓库并描写提交原因
- git log 查看当前版本的更改记录
- git reflog 查看所有版本的更改记录
- git reset --hard xxxxx 跳转到指定版本
- git branch x 新建分支
- git checkout x 跳转到x分支
- git merge 合并分支
- git branch -d x 删除x分支
## Git简写设置
- touch ~/ . bashrc
- code  ~/ . bashrc（根据已有的格式仿写）
##  Git和Github关联
1. ssh-keygen -t rsa  4096  -C  <邮箱地址>
2. 打开公钥并上传至Github
![上传公钥](https://github.com/tiyue/blog-test/raw/master/images/git_and_github.png)