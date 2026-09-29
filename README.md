# nave_for_learning

个人学习资料与练习代码的版本管理仓库。

## 仓库信息

- 远端地址（SSH）：`git@github.com:luonave1/nave_for_learning.git`
- 远端地址（HTTPS）：`https://github.com/luonave1/nave_for_learning.git`
- 默认分支：`main`

## 日常用法

```bash
# 查看当前改动
git status

# 把改动加入暂存区并提交
git add .
git commit -m "说明这次改了什么"

# 推送到 GitHub
git push
```

## 说明

- `.gitignore` 已排除系统垃圾文件、IDE 配置、编译产物（Keil/C/Python/MATLAB 等）、
  大体积归档文件，以及密钥等敏感信息。
- 如果需要强制提交某个被忽略的文件，用 `git add -f <文件名>`。
- 不要把私钥、密码、API Key、Token 提交到仓库里。
