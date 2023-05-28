---
title: git常用命令
date: 2023-05-28 14:37:22
tags:
---

## 1. 修改分支名
1. 修改本地分支名称
`git branch -m oldBranchName newBranchName`

2. 将本地分支的远程分支删除
`git push origin :oldBranchName`

1. 将改名后的本地分支推送到远程，并将本地分支与之关联
`git push --set-upstream origin newBranchName `