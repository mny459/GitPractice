# GitPractice
练习使用 Git

> 和 SVN 的区别：
>
> - SVN 的版本控制是中央式的（只有服务器中存在）；而Git 的是分布式的（本地和远程都可以存在）
> - SVN 适合带有媒体文件的版本控制；Git 适合纯代码的

## 

- `git log` 查看日志

```bash
GitPractice % git log
commit ea7bcb3f35d856230980730ec94e06666d6d65c2 (HEAD -> master, origin/master, origin/HEAD)
Author: mny459 <mny9@outlook.com>
Date:   Sat Apr 4 19:22:56 2020 +0800

    Initial commit
```

- `git add`

```bash
git add . // 提交所有的改动文件
git add filename // 提交文件
```

