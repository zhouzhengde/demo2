# 如何使用GIT

## 一、初始化工程
```shell
$ git init          # 初始化工程
$ git add [文件]     # 添加一个文件在本地仓库
$ git commit [文件] -m "提交内容备注"  # 提交[指定文件]变更到本地仓库
$ git push -u origin [分支]    # 推送变更到远程仓库
$ git pull origin [分支]       # 从远程仓库拉取最新变更
$ git remote add origin [git@github.com:zhouzhengde/demo2.git]  # 绑定本地仓库与远程仓库。
$ git remote rm origin  # 删除本地仓库与远程仓库的绑定，其不是物理删除远程仓库。
$ git clone https://github.com/zhouzhengde/demo2.git    # 从远程仓库中拉取项目，本地没有项目的资源，通过从远程拉取创建项目。
```

## 二、将本地变更指定提交到本地仓库中与远程仓库中
```shell
$ git pull origin [分支]    # 每天开始工作或要修改时或提交之前应先从远程更新本地代码
$ git commit [文件] -m '提交的备注'  # 提交到本地仓库中
$ git push -u origin [分支]  # 提交到远程仓库中
```

## 三、多人协同开发，消除提交冲突
```shell
$ git pull origin [分支]   # 提交之前，应先执行更新
$ git status      # 查看哪些文件有冲突
$ 【手工合并冲突点】
$ git add [冲突的文件]
$ git commit [冲突的文件] -m 'fix conflict: 备注'
$ git push -u origin master
```

# 四、如何进行合并
```shell
# TODO

```

## 五、分支管理与创建分支
- 1
- 2
- 4
- 7