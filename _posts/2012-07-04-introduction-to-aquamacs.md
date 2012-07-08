---
layout: post
title: "Aquamacs速查手册"
description: ""
category: 振导社会
published: true
tags: [emacs, 简介, 工具, 速查, 程序, lisp]
---
{% include JB/setup %}

[Aquamacs](http://Aquamacs.org)是[GNU Emacs](http://www.gnu.org/software/emacs/)在OSX系统的一个发行版，除了支持Emacs标准快捷键外，也支持与OSX系统兼容的快捷键。因此，本文的大多数内容对Emacs也实用。

>While the useful Emacs key bindings are supported and Emacs packages usually just work, Aquamacs is adapted to be comparable to younger text editors (than Emacs). It also comes with a range of packages that give you greater comfort in editing certain types of files.

##基础知识

###键盘对应关系

Emacs | Mac | PC
----|----|----
META | esc/option | Alt
CTRL | command | Ctrl

###获取帮助的快捷键

快捷键 | 功能
---- | ----  
`C-h t` | emacs tutorial 
`C-h i` | emacs info 
`C-h r` | emacs manual  
`C-h f <函数名>` | 函数的帮助信息  
`C-h v <变量名>` | 变量的帮助信息  
`C-h k <快捷键>` | 快捷键的帮助信息

Emacs最常用功能可通过简明的[GNU Emacs Reference Card](http://www.damtp.cam.ac.uk/user/eglen/ess11/resources/emacs-refcard.pdf)学习。

###info的快捷键

功能 | 快捷键 | 快捷键 | 功能
----: | ----: | :---- | :----
上一节点 | `p` | `n` | 下一节点   
上一菜单 | `[` | `]` | 下一菜单（菜单前标有*）
交叉引用跳转 | `f` | `l` | 交叉引用返回
向上翻页 | `DELETE` | `SPACE` | 向下翻页   
||`C-l` | 当前节点循环翻页
||`b` | 回到节首   
||`u` | 上级菜单
||`m` | 菜单 
||`g` | 跳到指定节点
||`t` | 回到顶层菜单
||`d` | 回到info总目录
||`h` | info tutorial 

info兼容Emacs快捷键。

<!--
###Emacs戏法

 快捷键 | 功能
---- | ----
`C-u <数字> 快捷键`| 为快捷键传送参数
`M-<数字> 快捷键`| 执行快捷键`<数字>`次

如何输入`<数字>`个数字？

拼写检查：   
ispell、flyspell-mode

Tabs and Windows：
一个tab对应于一个buffer，OSX切换tab的快捷键是command+数字
Aquamacs配置文件的位置

可用C-h v load-path查看  
-->

###OSX系统和Emacs术语对应关系 

OSX Term | Emacs Term     
:--------|----------  
Window    | Frame      
Tab/pane  | Window    
Document  | Buffer    
Cursor    | Point    
Mouse pointer     | Pointer  
Keyboard shortcut | Key (binding)  

###Aquamacs相关文件 
插件目录： 
{% highlight bash %}
~/Library/Application Support/Aquamacs Emacs/myPlugin
{% endhighlight %}

配置文件目录：
{% highlight bash %}
/Library/Application Support/Aquamacs Emacs/  
/Library/Preferences/Aquamacs Emacs/  
~/Library/Preferences/Aquamacs Emacs/  
{% endhighlight %}

用户自定义配置文件：
{% highlight bash %}
~/.emacs
~/Library/Preferences/Aquamacs Emacs/Preferences.el
{% endhighlight %}

当然，用户可以在配置文件中指定目录和相关文件位置。





 