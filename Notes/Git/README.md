# GIT 常用命令

```bash

# 查看所有分支 

git branch -a 

# 强制删除分支

git branch -D develop

# 刷新远端分支

git remote update origin --prune

# git clone 最新提交的版本

git clone --depth 1 https://github.com/freeCodeCamp/freeCodeCamp

# git clone 携带用户名密码

git clone https://account:password@gitUrl

# 撤销本地commit

git reset HEAD~ 

# git 配置代理

git config --global http.proxy http://127.0.0.1:58591

# git 撤销代理

git config --global --unset http.proxy

```