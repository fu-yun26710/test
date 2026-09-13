# test
练习git

git 命令
主机->git缓冲区 ： git add "文件名"
git缓冲区->本地仓库 ：git commit -m "说明"
本地仓库->服务器 ： git push origin "分支"

使用git remote 创建 ssh 别名
git remote add origin "shh"
删除别名
git remote remove origin

查看缓冲区
git status

commit 提交
用户每次提交，commit都会进行代码的备份，进行对比

删除云端文件
在本地删除后覆盖云端
不推荐直接修改云端代码，会导致版本不一致导致的分枝异常
可通过 git pull -- rebase origin master 命令同步本地和云端

下载开源项目
所有以git仓库为单位的操作都与开发有关
只是打包下载开源项目和资源文件
1、网站打包(VPN)
2、命令下载：git clone "HTTPS地址"
