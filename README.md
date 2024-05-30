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
 % git-fast-push-for-mac % push
[error]：需要提交消息
```

**正确的**

```shell
 % push docs: 更新文档
[master d728e1b] docs:
 1 file changed, 32 insertions(+)
Counting objects: 3, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 664 bytes | 664.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To github.com:Tyh2001/git-fast-push-for-mac.git
   f7f3b2f..d728e1b  master -> master
[success]：已提交并随消息推送: 'docs:'
```
