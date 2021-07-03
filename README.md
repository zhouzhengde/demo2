# 如何使用GIT

## 一、初始化工程
```shell
$ git init          # 初始化工程
$ git add [文件]     # 添加一个文件在本地仓库
$ git commit -m "提交内容备注"  # 提交变更到本地仓库
$ git push -u origin [分支]    # 推送变更到远程仓库
$ git pull origin [分支]       # 从远程仓库拉取最新变更
$ git remote add origin [git@github.com:zhouzhengde/demo2.git]  # 绑定本地仓库与远程仓库。
$ git remote rm origin  # 删除本地仓库与远程仓库的绑定，其不是物理删除远程仓库。
$ git clone https://github.com/zhouzhengde/demo2.git    # 从远程仓库中拉取项目，本地没有项目的资源，通过从远程拉取创建项目。
```