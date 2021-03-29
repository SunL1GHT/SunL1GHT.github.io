---
title: Qt学习实践
date: 2021-03-28 19:33
tags:
- Qt
- C++
categories:
- 实验室
---

> 之前接触过了Pyqt(PySide2)，我觉得大概布局、控件都类似，具体地还得多做项目实践，比如局域网聊天室什么的。

# 学习笔记

```C++
#include <QApplication>
#include <QLabel>

int main(int argc, char *argv[])
{
    QApplication app(argc, argv);
    QLabel *label = new QLabel("Hello Qt!");
    label -> show();
    return app.exec();
}
```

## 基础知识

什么是Qt？
* Qt是1991年由奇趣科技开发的跨平台C++图形用户界面应用程序开发框架。

QMainWindow、QWidget、QDialog三个基类：
1. **QMainWindow**
    QMainWindow 类提供一个有菜单条、锚接窗口（例如工具条）和一个状态条的主应用程序窗口。

2. **QWidget**
    QWidgt 类是所有用户界面对象的基类。 窗口部件是用户界面的一个基本单元：它从窗 口系统接收鼠标、键盘和其它事件，并且在屏幕上绘制自己。

3. **QDialog**
    QDialog 类是对话框窗口的基类。对话框窗口是主要用于短期任务以及和用户进行简要通讯的顶级窗口。

**<center>信号和槽</center>**

**<center>布局</center>**

