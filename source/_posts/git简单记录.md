title: git简单记录
date: 2016-01-17 19:36:24
tags: git
categories: 博客
---

## 简单的记录git的使用方法

1. 初始化git, git init

2. 添加到git库, git add <file>, git commit -m "description"

3. 查看状态 , git status

4. 比较修改过得文件, git diff <file>

5. 版本回退, 查看提交历史git log, 产看命令历史git reflog, git reset --hard HEAD^/ HEAD~ / commit_id

6. 丢弃工作区的修改, git checkout -- file

7. 丢弃工作去和暂存区的修改, gti reset HEAD file        

8. 删除文件, rm file , (git rm  git commit)/ (git checkout -- file)

9. 关联远程库, git remote add origin git@server-name:path/repo-name.git


10. 关联后第一次推送master分支的所有内容: git push -u origin master 之后推送, git push origin master

11. 创建并切换到分支: git checkout -b dev 等价于 git branch dev, git checkout dev

12. 查看分支: git branch

13. 合并分支到当前分支 git merge dev

14. 删除分支: git branch -d dev

15. 分支合并图: git log --graph




