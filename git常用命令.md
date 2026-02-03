# git常用命令

| 场景             | 命令                                               |
| ---------------- | -------------------------------------------------- |
| 克隆远程仓库     | git clone 远程仓库地址                             |
| 初始化本地仓库   | git init                                           |
| 关联远程仓库     | git remote add origin 远程仓库地址                 |
| 产看工作状态     | git status                                         |
| 加入暂存区       | git add . / git add 文件名                         |
| 提交到版本库     | git commit -m "说明原因"                           |
| 拉取远程最新代码 | git pull origin 分支名                             |
| 推送到远程仓库   | git push origin 分支名 / git push -u origin 分支名 |
| 查看简介提交历史 | git log --oneline                                  |



### git核心流程：

​	[拉取最新代码→修改→暂存→提交→再拉取→推送]