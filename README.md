# 问题集1
1. github是什么
>GitHub 是一个面向开源及私有软件项目的托管平台，因为只支持 Git 作为唯一的版本库格式进行托管，故名 GitHub。除了 Git 代码仓库托管及基本的 Web 管理界面以外，还提供了订阅、讨论组、文本渲染、在线文件编辑器、协作图谱（报表）、代码片段分享（Gist）等功能。目前，其注册用户已经超过350万，托管版本数量也是非常之多，其中不乏知名开源项目 Ruby on Rails、jQuery、python 等。
2. git是什么
>Git是一款免费、开源的分布式版本控制系统，用于敏捷高效地处理任何或小或大的项目。Git是一个开源的分布式版本控制系统，可以有效、高速的处理从很小到非常大的项目版本管理。[2]  Git 是 Linus Torvalds 为了帮助管理 Linux 内核开发而开发的一个开放源码的版本控制软件。
3. 学习github的5个理由
>技术大咖，
4. github的优势是什么
>GitHub 只支持 Git 格式的版本库托管，而不像其他开源项目托管平台还对CVS、SVN、Hg 等格式的版本库进行托管。GitHub 的哲学很简单，既然 Git 是最好的版本控制系统之一（对于很多喜欢 Git 和 GitHub 的人没有之一），没有必要为兼顾其他版本控制系统而牺牲 Git 某些独有特性。因此没有支持其他版本控制系统的历史负担，是 GitHub 成功的要素之一。  
GitHub 对 Git 版本库提供了完整的协议支持，支持 HTTP 智能协议、Git-daemon、SSH 协议。  
GitHub 提供在线编辑文件的功能，不熟悉 Git 的用户也可以直接通过浏览器修改版本库里的文件。  
将社交网络引入项目托管平台是 GitHub 的创举。用户可以关注项目、关注其他用户进而了解项目和开发者动态。  
项目的 Fork 和 Pull Request 构成 GitHub 最独具一格的工作模式。对提交代码的逐行评注及 Pull Request 构成 GitHub 特色的代码审核。  
GitHub 通过私有版本库托管、面向企业的版本库托管和项目管理平台、人员招聘等付费服务获得了商业上的成功，这种成功使得 GitHub 不必以页面中嵌入广告的方式维持运营，最大的受益者还是用户。  
GitHub 网站采用 Ruby on Rails 架构，在 Web 设计中运用了大量的 JavaScript、AJAX、HTML5 等技术，支持对使用 Markdown 等标记语言的内容进行渲染和显示等。关注细节使得 GitHub 成为了项目托管领域的后起之秀。  
5. 通过github年度报告让你记忆最深刻的信息有哪些
>最流行的开源项目；最爱用的编程语言；
6. github上有可以个人账号 还可以有（ ）账号
>组织
7. github上面的两个组成要素是什么
>仓库 个人组织
8. github上两个重要页面
>个人主页  数字仪表板
9. 主页菜单都包含什么概览 
>仓库 收藏
10. 仓库的心跳线代表什么
>活跃程度
11. star的作用是？
>持续关注别人项目更新就star一下    收藏
12. fork的作用是？
>想拷贝别人项目到自己帐号下就fork一下。   自己可以参与         
13. watch的作用是？ 
>watch是设置接收邮件提醒的。

# 问题集2
1. 个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？  
>new repository  创建仓库   
>import repository  
>new gist  代码片段  
>new organization 创建组织  
2. 如何能将仓库中的html文件直接解析成页面？  
>设置中source中将none改为master branch
3. 如何删除仓库    
>setting 里delete
4. Bash是什么操作系统的命令    
>git bash是linux下的命令行工具。  
5. Pwd是什么命令    
>打印当前工作目录
6. Cd是什么命令    
>改变目录
7. Echo是什么命令   
>在显示器上显示一段文字，一般起到一个提示的作用。

8. 配置git用户名的命令    
>git config --global user.name ""

9. 配置邮箱的命令  
>git config --global user.email ""

10. 命令行换行方式  
>\
11. 命令行终结方式  
>ctrl+c
12. 使用命令行比GUI方式有何优势  
>批处理
13. 提交到本地仓库时为什么有暂存区  
>如果有问题返回，如果没有问题提交
14. 新建代码仓库的命令  
>git init
15. git clne [url] 这个命令的作用是
>克隆仓库的命令格式
16. 添加指定文件到暂存区的命令
>git add
17. 删除工作区文件，并且将这次删除放入暂存区的命令
>git rm
18. 改名文件，并且将这个改名文件放入暂存区的命令
>git mv
19. 提交暂存区到仓库的命令  
>git commit-m
20. 直接从工作区提交到仓库的命令  
>git commit-a-m
21. 显示变更信息的命令  
>git status
22. 查看历史信息的命令  
>git log
23. Commit的意义是  
>提交
24. Pull的意义是  
>把远程放到本地
25. Push的意义是  
>把本地放到远程仓库

## 问题集3
1. MarkDown是什么？
>是一种轻量级的标记语言,过简单的标记语法，它可以使普通文本内容具有一定的格式。
2. MarkDown的特点？  
>纯文本内容，兼容所有的文本编辑器与字处理软件  
可以放到版本管理系统中，追踪历史变更  
轻松的到处HTML.PDF和本身的.MD文件  
简介。高效。可读直观。学习成本低  
专注你的文字内容而不是排版样式，安心写作  
3.MarkDown的用途？
>IT人士：写日志，技术文稿，记录代码片段,撰写文档  
科研人员/学生：撰写科技论文,记笔记  
求职者：制作求职简历  
4. MarkDown的编辑工具有哪些？ 
>MAC OS X:MOU   WINDOWS:MARKDOWNPAD。MARKPAD  
LINUX:RETEXT   WEB:简书。github。有道云笔记  
5. MarkDown的区块元素和区段元素分别包含哪些？
>>区块元素：  
- 段落和换行
- 标题
- 区块引用
- 列表
- 代码区块
- 分隔线
>>区段元素：
- 连接
- 强调
- 代码
- 图片
