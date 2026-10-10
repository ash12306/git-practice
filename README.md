# git-practice

我的第一个 Git 仓库，用来练习 `init` / `commit` / `push`。

## 本机环境

- Windows + Git for Windows 2.56.0.2（装在 `C:\Program Files\Git`）
- 远程走 SSH：`github.com` 在 `~/.ssh/config` 里被指向 `ssh.github.com:443`
  （因为本机 22 端口被封，直连不通）
- Git 使用 Windows 原生 OpenSSH：`core.sshCommand = C:/Windows/System32/OpenSSH/ssh.exe`

## 常用命令

```bash
git status              # 看当前状态
git add .               # 把改动加入暂存区
git commit -m "说明"     # 提交
git push                # 推送到 GitHub
git log --oneline       # 看提交历史
```

这一行用来验证中文是否正常：中文、标点（，。！）、emoji ✅
