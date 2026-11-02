# hello-github

我的第一个 GitHub 练习仓库 —— 用来熟悉 git 的日常操作流程。

## 这个仓库是干嘛的

2026-11-02 重新捡起一年前注册的 GitHub 账号，走一遍完整流程：
本地改代码 → add → commit → push → 云端能看到。

## 日常四件套

```bash
git status                    # 先看现在什么状态（最常用！）
git add .                     # 把改动放进暂存区
git commit -m "说明改了什么"   # 存档
git push                      # 推到 GitHub
```

开机干活前先 `git pull`，避免版本落后。

## 常用查询

```bash
git log --oneline        # 看提交历史
git diff                 # 看还没提交的改动
git remote -v            # 看远程仓库地址
```
