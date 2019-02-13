---
title: linux常用命令梳理
date: 2019-02-13 22:27:05
tags:
---
#linux常用命令梳理

*常用：*

>ls：查看目录中的文件

>cat：查看文件中的文本

>mv：重命名/移动

>touch：新建文件/修改文件时间戳

#如何使用explainshell.com来检索命令的含义呢？

首先打开网站，在页面中间的文本框内输入你要查询的命令，如：cat，然后点击explain。

然后页面将跳转到对“cat”命令进行解释的页面，页面上将会提示：

>concatenate files and print on the standard output。

#其他常用命令：

cd /home 进入 '/ home' 目录'

cd .. 返回上一级目录

cd ../.. 返回上两级目录

cd 进入个人的主目录

cd ~user1 进入个人的主目录

cd - 返回上次所在的目录

pwd 显示工作路径

ls 查看目录中的文件

ls -F 查看目录中的文件

ls -l 显示文件和目录的详细资料

ls -a 显示隐藏文件

ls *[0-9]* 显示包含数字的文件名和目录名

tree 显示文件和目录由根目录开始的树形结构(1)

lstree 显示文件和目录由根目录开始的树形结构(2)

mkdir dir1 创建一个叫做 'dir1' 的目录'

mkdir dir1 dir2 同时创建两个目录

mkdir -p /tmp/dir1/dir2 创建一个目录树

rm -f file1 删除一个叫做 'file1' 的文件'

rmdir dir1 删除一个叫做 'dir1' 的目录'

rm -rf dir1 删除一个叫做 'dir1' 的目录并同时删除其内容

rm -rf dir1 dir2 同时删除两个目录及它们的内容

mv dir1 new_dir 重命名/移动 一个目录

cp file1 file2 复制一个文件

cp dir/* . 复制一个目录下的所有文件到当前工作目录

cp -a /tmp/dir1 . 复制一个目录到当前工作目录

cp -a dir1 dir2 复制一个目录

ln -s file1 lnk1 创建一个指向文件或目录的软链接

ln file1 lnk1 创建一个指向文件或目录的物理链接
