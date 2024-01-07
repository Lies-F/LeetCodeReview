# Git介绍

[TOC]

## Git原理
> git：基于快照的版本控制系统，完整，只增不减

> git的三种状态：已修改，已暂存，已提交

> 提交时，未修改的文件会直接指向之前的文件而不会修改

> hash算法：1.一个哈希算法，加密结果长度固定
## Git常用操作
> git init: 创建仓库 

> git status

> cd .git: 进入仓库

> cd ..: 返回上一级目录

## vscode终端常用命令
1. 清除终端
```
clear
```

2. 列出当前目录中的文件和文件夹
```
ls
```

3. 切换到指定的目录
```
cd <path>
```

4. 返回上一级目录
```
cd ..
```

5. 创建新文件夹
```
mkdir <folder name>
```

6. 创建新文件
```
touch <file name>
```

7. 打开文件
```
code <file name>
```

8. 删除文件夹
```
rm -r <folder name>
```

9.  删除文件
```
rm <file name>
```

10. 复制文件或文件夹
```
cp <origin folder/file> <target folder/file>
```

11. 移动文件或文件夹
```
mv <origin folder/file> <target folder/file>
```

12. 查看文件内容
```
cat <file name>
```

13. 查找文件
```
find <path> -name <file name>
```

14. 查找文件内容
```
grep <search content> <file name>
```

15. 压缩文件或文件夹
```
tar -czvf <zip file name.tar.gz> <file/folder>
```

16. 解压缩文件
```
tar -xzvf <zip file name.tar.gz>
```

17. 退出或关闭当前正在运行的程序或进程
```
:q
```

## 与 Git 版本控制系统相关的常用指令
1. 初始化 Git 仓库：
```
git init
```
2. 克隆远程仓库到本地：
```
git clone <远程仓库地址>
```
3. 添加文件到暂存区：
```
git add <文件名>
```
4. 添加所有修改的文件到暂存区：
```
git add .
```
5. 提交暂存区的文件到版本库：
```
git commit -m "提交信息"
```
6. 查看当前 Git 仓库状态：
```
git status
```
7. 查看文件修改的差异：
```
git diff <文件名>
```
8. 查看提交历史：
```
git log
```
9. 切换到指定提交版本：
```
git checkout <提交哈希值或分支名>
```
10. 创建新的分支：
```
git branch <分支名>
```
11. 切换到指定分支：
```
git checkout <分支名>
```
12. 合并指定分支到当前分支：
```
git merge <分支名>
```
13. 拉取远程仓库的更新：
```
git pull
```
14. 推送本地提交到远程仓库：
```
git push
```
15. 查看远程仓库地址：
```
git remote -v
```
16. 添加远程仓库：
```
git remote add <远程仓库名> <远程仓库地址>
```
17. 创建并切换到新的分支：
```
git checkout -b <分支名>
```
18. 删除分支：
```
git branch -d <分支名>
```