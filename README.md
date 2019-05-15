# demo-git
This is a demo for git test


## Attention

注意不要修改 master 上的任何内容，请 获取 dev 分支上的内容，然后在本地新建自己的分支，修改的内容在合并到 dev 分支上

## Dev

- 操作步骤如下，请务必遵守
- git commit 提交格式，请按照这个文档来，[传送门](https://github.com/C-FED/base-common-tools/blob/master/development-specification/git-commit.md#commit-message-%E7%9A%84%E6%A0%BC%E5%BC%8F)

```bash

$ git status # 先查看本地暂存区是否有未提交的，如果没有，直接跳到 git pull 那步

$ git add -A # 添加所有修改到暂存区

$ git commit -m "fix(xxx):xxx"  # 提交到本地仓库   

$ git pull # 拉取远程仓库

$ git push # 同步到远程仓库


```

## 测试文字
测试文字