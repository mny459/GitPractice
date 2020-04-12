# GitPractice
练习使用 Git

> 和 SVN 的区别：
>
> - SVN 的版本控制是中央式的（只有服务器中存在）；而Git 的是分布式的（本地和远程都可以存在）
> - SVN 适合带有媒体文件的版本控制；Git 适合纯代码的

## 概念补充

1. commit：每一次的 commit 其实就是一个快照
2. Working Tree：工作空间，其本质就是你 Git 仓库的目录，也就是 Git 变动检测的范围
3. Staging Area（暂存区）：存储所有要被 commit 的地方

> Working tree -> add -> Staging area -> commit 

4. 引用

## 常用命令

- `git clone`

```
git clone url [local_folder_name]
```

- git log` 查看日志

```bash
GitPractice % git log
commit ea7bcb3f35d856230980730ec94e06666d6d65c2 (HEAD -> master, origin/master, origin/HEAD)
Author: mny459 <mny9@outlook.com>
Date:   Sat Apr 4 19:22:56 2020 +0800

    Initial commit
```

- `git add`：将变动的文件添加到暂存区 

```bash
git add . // 提交所有的改动文件
git add filename // 提交文件
```

- `git commit`

```bash
git commit
git commit -m "message body"
```
> 

- `git push origin`

```
git push origin [branch_name] // branch_name 可以省略  
```

- `git pull origin` 

```

```

## 概念补充

```shell
commit ea7bcb3f35d856230980730ec94e06666d6d65c2 (HEAD -> master, origin/master, origin/HEAD)
```

> HEAR：指向的是当前工作目录所在的位置
>
> master：表示分支

