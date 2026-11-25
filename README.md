# git-github

Git / GitHub 练习仓库。

## 这是什么

一个用于熟悉 Git 工作流的仓库：初始化、提交、远程关联、推送、拉取、分支与合并。

## 快速开始

```bash
# 查看状态
git status

# 暂存 + 提交
git add .
git commit -m "描述这次改了什么"

# 推送到远程
git push
```

## 常用命令速查

| 目的 | 命令 |
| --- | --- |
| 查看当前状态 | `git status` |
| 查看改动内容 | `git diff` |
| 提交历史（单行图形） | `git log --oneline --graph --all` |
| 撤销工作区改动 | `git restore <文件>` |
| 撤销暂存 | `git restore --staged <文件>` |
| 新建并切换分支 | `git switch -c <分支名>` |
| 合并分支 | `git switch main && git merge <分支名>` |
| 关联远程仓库 | `git remote add origin <仓库地址>` |
| 首次推送并建立跟踪 | `git push -u origin main` |
| 拉取远程更新（变基） | `git pull --rebase` |

## 目录说明

```
.
├── README.md     本文件
└── .gitignore    忽略规则
```

## 备注

- 默认分支：`main`
- 提交信息用中文描述改动意图即可，不必追求格式。
