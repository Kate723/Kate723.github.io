---
layout: post
title: "Linux-文件操作"
date: 2021-07-27 19:22:30
---
### 复制命令
cp dir1/a.doc dir2 表示将dir1下的a.doc文件复制到dir2目录下

cp -r dir1 dir2 表示将dir1及其dir1下所包含的文件复制到dir2下

cp -r dir1/. dir2 表示将dir1下的文件复制到dir2,不包括dir1目录

说明：cp参数 -i：询问，如果目标文件已经存在，则会询问是否覆盖；