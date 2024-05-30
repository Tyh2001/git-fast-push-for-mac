# Git Fast Push for Mac

## 介绍

使用一行命令即可提交代码。

一行命令来实现 git 提交代码，无需每次执行 `git add .、git commit -m 'xxx'、git push`

## 安装

下载仓库，将 `push.sh` 文件放到 `/usr/local/bin` 目录下

## 使用

在项目跟目录下执行 `push xxx` 即可实现提交代码，例：

```
push fix：修复问题
```

## 日志

**错误**

如果未添加提交信息，将会报错：

```shell
git-fast-push-for-mac % push
[error]：需要提交消息
```

**正确的**
