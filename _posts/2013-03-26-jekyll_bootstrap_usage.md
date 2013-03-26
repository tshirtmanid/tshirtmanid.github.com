---
layout: post
title: "博客搭建成功"
description: ""
category: github
tags: [jekyll, github, heroin, blog, bootstrap]
---
{% include JB/setup %}
按照jekyll bootstrap的教程，慢慢搭建起了在github上的博客。我这个人还是比较笨的，中间走了一些弯路。 
大家按照教程搭建，问题应该不会太大。  
#如何美化博客
我的办法就超级简单了，直接git clone了http://heroin.so/作者的github blog:

    git clone https://github.com/heroin/heroin.github.com.git

然后自己倒腾一下便好了，非常感谢heroin!
#jekyll的一个恶心的地方  
你在post里写文章的时候，如果category:github, 中间没有空格的话，那么就完蛋了，貌似jekyll里整个都不响应了，我花了半个小时才找到原因。


