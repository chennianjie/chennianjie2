# 20180815学习总结
## git常用命令：
- git config --global user.name "名字"/git config --global user.email "邮箱"---**配置用户名和邮箱**<br />
- git config --global user.name/git config --global user.email---**查看名字或邮箱**<br />
- git config --list---**查看git配置信息**<br />
- mkdir或者cd C:\Users\15732\Desktop\GitResposiry---**创建/进入文件夹**<br />
- git init---**初始化该文件夹为git本地仓库**<br />
- git status---**查看git本地仓库的状态**<br />
- git clone---**[SSH地址]，在当前目录下下载x.git文件**<br />
- pwd查看文件目录----git add .把文件添加进缓冲区---git commit -m "提交到本地仓库写日志"<br />
- git push "http方式(github账号上查看)" master将文件推送到远程仓库<br />
## git安装与基本配置：
- 1.按网上教程从git官网下载并安装git<br />
- 2.安装成功并配置环境变量C:\Program Files\Git\cmd(cmd命令窗口检测)<br />
- 3.配置邮箱和名字(git config --global user.name "名字"/git config --global user.email "邮箱" )<br />
- 4.github无密钥登陆配置(git bash下)：SSH授权或HTTPS<br />
   - 4.1.生成ssh key：ssh-keygen -t rsa -b -C "<15663456952@163.com>"（一直回车接下来）<br />
   - 4.2.C:/Users/15732/.ssh/id_rsa.pub查看公钥，添加到：[github官网](http://github.com)<br />
   - 4.3.使用ssh -T git@github.com命令查看是否连接成功
## 学习使用markdown基本语法
   - **标题**：#一级标题   ##二级标题   ###三级标题 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;依此类推<br/>
   - **引用**：\>+空格+引用内容&nbsp;&nbsp;&nbsp;强调加粗：** 强调内容 ** &nbsp;&nbsp;&nbsp;* 斜体 * &nbsp;&nbsp;&nbsp; *** 加粗且斜体 ***
   - \&nbsp;空格&nbsp;&nbsp;&nbsp; \-无序列表 &nbsp;&nbsp;&nbsp;1.有序列表
   - **文字链接**：[链接文字] (链接地址)
   - **图片链接**：！[图片描述] (图片地址)
   - **代码**：  一行' ' &nbsp;&nbsp;&nbsp;多行'''  '''
## 配置Maven与创建Maven工程，熟悉idea开发工具。
