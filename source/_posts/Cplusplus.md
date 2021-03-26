---
title: C++实践记录
date: 2021-03-23 19:32:35
tags:
- C++
categories:
- 工作实践
---

C语言和C++有什么区别和联系？
`<>`引用系统头文件
`""`引用用户头文件
多个程序包含同一个头文件，而不用注重引用顺序。
```C++
//防卫式声明
#ifdef __COMPLEX__
#define __COMPLEX__


# endif
```