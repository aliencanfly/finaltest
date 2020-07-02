# Markdown的使用
## 1.标题
使用一个或多个（至多6个）# ，来定义标题等级。
## 2.引用
使用>表示引用
## 3.清单列表
输入1. 表示创造一个有序列表

输入* ，-，+等表示创造一个无序列表
## 4.程序代码块
输入```创造一个程序代码块

输入：`创造一行代码`
## 5 .数学符号
输入$$创造数学公式
## 6.分隔符
输入***，+++，---等创造一个分割符
## 7.表格
输入|第一列|第二列|...创造一个表格
## 8.脚注
输入[^脚注]插入脚注
## 9.目录
输入[toc]插入一个目录
## 10.链接
如，输入[]()：[git](https://github.com/)
## 11.图片
输入![]()
## 12.斜体和加粗
输入*斜体字*

输入**加粗字**


# Linux的使用
## 1.磁盘管理命令
+ pwd：显示当前所在目录位置

+ cd 目录名：切换目录

+ ll,ls ：列出当前目录下目录及文件
## 2.文件管理命令
+ mkdir 目录名：创建目录

+ rm 删除文件：删除文件

+ rm -rf 删除目录：删除目录

+ cp 复制文件 新文件名：复制文件

+ cp -rf 复制文件夹 新文件夹名：复制文件夹

+ cat 文件路径：显示一个文件的所有内容

+ more 文件路径：空格一页一页展示，enter一行一行展示

+ head -n 数字 文件名：显示文件头部，默认10行

+ tail -n 数字 文件名：显示文件尾部，默认10行

+ grep [参数] 搜索的字符串内容 文件名1 [文件n]：文件搜索（区分大小写）
## 3.管道
+ echo "内容">文件名：将内容写到该文件中（覆盖原内容）

+ echo "内容">>文件名：将内容写到该文件中（追加内容）

+ 命令1|命令2|命令3...
## 4.系统命令
date ：显示当前系统时间

​	clear：清屏

​	reboot：重启linux

​	shutdown：关机

​	ps -ef：查看当前系统进程

​	kill -pid ：结束一个进程，pid是由ps -ef查出来的
