---
title: git常用命令
date: 2023-05-28 14:37:22
tags:
---

## 1. 修改分支名
1. 修改本地分支名称
`git branch -m oldBranchName newBranchName`



1. 将改名后的本地分支推送到远程，并将本地分支与之关联
`git push --set-upstream origin newBranchName `


## 删除分支

1. 将本地分支的远程分支删除
`git branch -D localBranchName

2. 删除远程分支
git push origin --delete remoteBranchName`

## 2. 代码回退

1. 查看commit信息列表
    ` git log`
2. 截取部分commit的id，用来回退
  `git reset --hard 992a5088`
3. 强制提交
`git push --force`
