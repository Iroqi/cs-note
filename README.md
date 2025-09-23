

# 学习任务

- [x] [Markdown语法](#Markdown基本语法)
- [x] [git使用](#git的使用)
- [x] [vim](#vim)
- [x] [Linux指令](# linux指令)
- [ ] MySQL PHP 及服务器的使用   
- [ ] workflow n8n   
- [ ] web3

---



## Markdown基本语法

| 关键字 | 说明     |
| :---: | :--: |
| `\`  | 转义字符 |
| `#` | 一级标题 |
| `##` | 二级标题 |
| `###` | 三级标题 |
| `+ `or` -` | 无序项目号 |
| `1.` | 有序项目号 |
| `\|字段\|` | 表格 |
| `\|---\|` | 表头分隔 |
| `\|:---\|` | 左对齐 |
| `\|---:\| | 右对齐 |
| `\|:---:\|` | 居中对齐 |
| `---` | 分割线 |
| `\*text\*  `  （`*`可以用`-`代替） | *斜体* |
| `\*\*text\*\*` | **粗体** |
| `\*\*\*text\*\*\*` | ***粗斜体*** |
| `\~\~text\~\~` | ~~删除线~~ |
| `\<u>text\</u>` | <u>下划线</u> |
| \`code\` | 行内代码 `code` |
| \`\`python<br/>  print('hello world')  <br/>\`\` | 代码段```python <br/>  print("hello world")  <br/>``` |
| `\<br/>` | 换行 |
| `>` | 引用块 |
| \[连接名词](连接地址 )<br>\[连接名词](连接地址 “可选标题”)<br>\<连接地址> | 链接<br>[google](google.com)<br>[google](google.com "这是谷歌")<br><https://google.com> |
| `\!\[代替文字](图片路径 “图片标题”)` | 图片<br><img src="C:\Users\Hopper\Pictures\profile.jpg" alt="加载失败" title="头像" style="zoom:5%;" /> |
| $\alpha$ <br/> $$  <br />\alpha  <br />$$ | 公式块 |




---
## git的使用


| 指令                                                         | 说明                                           |
| ------------------------------------------------------------ | ---------------------------------------------- |
| **git init**                                                 | repository初始化                               |
| **git clone \<repository-url>**                              | 克隆远程repository                             |
| git config --global user.name 'your name'<br>git config --list | 配置信息<br>查看配置                           |
| git status                                                   | 查看当前状态                                   |
| git add \<file><br>**git add . **<br>git add -A              | 添加某个文件到暂缓区                           |
| git reset                                                    | 取消暂存的file                                 |
| **git commit -m “提交信息”**                                 | 提交到仓库                                     |
| **git remote add origin \<remote_repository_url>**           | 添加一个remote repository别名为origin          |
| **git remote -v**                                            | 查看remote repository URL                      |
| **git push**                                                 | 推送到remote repository                        |
| **git pull**                                                 | 拉取远程到本地并merge                          |
| git fetch                                                    | 拉取远程不自动merge                            |
| git branch                                                   | 列出所有branch                                 |
| **git branch \<branch_name>**                                | 创建一个branch                                 |
| **git switch \<branch_name><br>**git checkout <branch_name>  | 切换branch                                     |
| **git merge \<branch_name>**                                 | merge指定branch到当前branch                    |
| git branch -d  \<branch_name><br>git branch -D <branch_bane><br>git push origin --delete \<branch_name> | delete指定branch                               |
| **git log**<br>git log --oneline                             | 查看提交history                                |
| git tag v1.0                                                 | 创建标签                                       |
| get reset  <hash or tag>                                     | 重置到某版本（会移除之后的提交）               |
| get revert <hash or tag>                                     | 移除某提交并新建一个提交（不会移除之前的提交） |
| get restore <file>                                           | 恢复某文件                                     |

---


## vim

| 指令    | 说明           |
| ------- | -------------- |
| esc     | 指令模式       |
| i       | 插入模式       |
| :q      | 退出           |
| :w      | 保存           |
| :wq     | 保存并退出     |
| :q!     | 强制退出       |
| dd      | 删除行         |
| u       | undo           |
| yy      | 复制行         |
| p       | 粘贴行         |
| /关键词 | 搜索           |
| n       | 下一个搜索结果 |



---

## linux指令

| 指令                                                        | 说明                 |
| ----------------------------------------------------------- | -------------------- |
| cd                                                          | 切换目录             |
| whoami                                                      | 获取用户名           |
| pwd                                                         | 输出当前路径         |
| ls                                                          | 查看当前目录下文件   |
| ps<br />top<br />jobs                                       | 查看进程             |
| mv                                                          | 移动                 |
| cp                                                          | 复制                 |
| rm                                                          | 移除                 |
| touch                                                       | 创建空文件           |
| mkdir                                                       | 创建文件夹           |
| free                                                        | 查看内存             |
| df                                                          | 查看磁盘             |
| du                                                          | 硬盘使用率           |
| find                                                        | 查找文件             |
| ln                                                          | 链接文件             |
| man<br />help<br />info                                     | 帮助                 |
| su                                                          | 切换用户             |
| sudo                                                        | 超级管理权限         |
| chmod                                                       | 文件权限             |
| chown                                                       | 文件所有者           |
| chgrp                                                       | 文件用户组           |
| tar                                                         | 解压文件             |
| kill \<uid><br>pkill\<description>                          | 停止某进程           |
| ssh -p port user@ip                                         | ssh连接              |
| \|                                                          | 命令管道             |
| <<br /><<(多行输入 bash有 cmd 、powershll无)                | 重定向输入符         |
| >                                                           | 重定向输出符         |
| >>                                                          | 追加输出             |
| 文件描述符<br />标准输入 0 <br />标准输出 1<br />标准错误 2 |                      |
| 2>&1                                                        | 错误重定向到标准输出 |
| apt                                                         | 包管理器             |
| npm                                                         | node.js 包管理器     |
| nano <br />vim                                              | 文本编辑器           |



### 常见的通用参数

以 `-` (短选项)或 `--` (长选项) 开头 

| 参数                     | 含义         | 参见命令             |
| ------------------------ | ------------ | -------------------- |
| `-h`/`--help`            | 显示帮助     | 所有命令             |
| `-V` `--version`         | 显示版本     | grep, tar, ls 等     |
| `-v`/`--verbose`         | 详细输出     | cp, rm, rsync        |
| `-q`/`--quiet`           | 静默模式     | wget, apt, curl      |
| `--dry-run`/`-n`         | 试运行       | rsync, make          |
| `-f`/`--force`           | 强制执行     | rm, cp, mv           |
| `-i`/ `--interactive`    | 交互确认     | rm, mv, cp           |
| `-r`/`-R`/ `--recursive` | 递归操作     | cp, rm, chmod, chown |
| `--color`                | 颜色输出     | ls, grep, diff       |
| `-o FILE`                | 指定输出文件 | gcc, wget, curl      |



### Linux常用命令英文全称与中文解释

#### 命令缩写释义

apt： Advanced Packaging Tool 高级包装工具  
cp: Copy file 复制文件  
cat: Concatenate 串联  
cd：Change directory 切换目录  
chmod Change mode 改变模式  
chown: Change owner 改变所有者  
chgrp: Change group 改变用户组  
df: Disk free 空余硬盘  
du: Disk usage 硬盘使用率  
dd: 本来应根据其功能描述“Convert an copy”命名为“cc”，但“cc”已经被用以代表“C Complier”   
fg: Foreground 前景  
fsck：File system check 文件系统检查  
insmod：Install module 安装模块  
ln: Link files 链接文件  
lsmod: List module 列表模块  
ls：List files 列出目录下的文件  
ldd：List dynamic dependencies 列出动态相依  
mv: Move file 移动文件  
mkdir：Make directory 建立目录  
mkfs: Make file system 建立文件系统  
man: Manual  意思是手册，可以用这个命令查询其他命令的用法。  
ps：Process Status 进程状态  
pwd：Print working directory  显示当前工作路径。  
rm: Remove file 删除文件  
rmmod：Remove module 删除模块  
rmdir：Remove directory 移动目录  
su：Swith user 切换用户，切换到root用户  
tar：Tape archive 解压文件  
umount: Unmount 卸载  
uname: Unix name 系统名称  

#### 文件夹缩写释义

/bin = BINaries   
/dev = DEVices   
/etc = editable text configurationChest 存放配置文件的地方,配置文件的目录  
/opt = Optional application software packages 可选应用软件包  
/lib = library 库  
/proc = processes 进程  
/sbin = Superuser binaries 超级用户的二进制文件  
/tmp = temporary  临时文件存放  
/usr = Unix shared resources   Unix共享资源  
/var = Variable  是储存各种变化的文件，比如log等等   
