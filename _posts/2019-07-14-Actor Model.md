---
layout:     post   				    # 使用的布局（不需要改）
title:      Actor Model 				# 标题 
subtitle:   Actor随手记（1） #副标题
date:       2019-07-14 				# 时间
author:     lrb 						# 作者
header-img: img/post-bg-2015.jpg 	#这篇文章标题背景图片
catalog: true 						# 是否归档
tags:								#标签
    - Actor,软件设计
---# 随手记
> 将Actor模型与对象模型区分开的一个因素是，Actor对象能够以动态代理方式更新本身的行为。与对象的状态实现代码相比，使用Scala语言和Akka框架更容易实现这种设计模式。通过使用ActorContext对象，Actor对象能够通过接收代码块从一种行为切换到另一种行为。 --《Reactive Messaging Patterns With the Actor Model》
