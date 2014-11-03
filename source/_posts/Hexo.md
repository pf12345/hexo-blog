title: Hexo的使用
date: 2014-11-03 00:02:29
categories: 其他
tags: Hexo
---
#Hexo 自己使用

coney主题介绍： <a href="http://gengbiao.me/2014/10/13/coney%E4%B8%BB%E9%A2%98%E4%BB%8B%E7%BB%8D/">http://gengbiao.me/2014/10/13/coney主题介绍/</a>	

Hexo常用指令：

常用命令：
<pre>
hexo new "postName" #新建文章<br>
hexo new page "pageName" #新建页面<br>
hexo generate #生成静态页面至public目录<br>
hexo server #开启预览访问端口（默认端口4000，'ctrl + c'关闭server）<br>
hexo deploy #将.deploy目录部署到GitHub
</pre>

常用复合命令：
<pre>
hexo deploy -g<br>
hexo server -g
</pre>
简写：
<pre>
hexo n == hexo new<br>
hexo g == hexo generate<br>
hexo s == hexo server<br>
hexo d == hexo deploy
</pre>