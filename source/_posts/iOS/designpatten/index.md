---
title: iOS设计模式
date: 2017-09-15 11:26:39
tags: iOS设计模式
categories: 
- iOS
- iOS设计模式
---

## 一、编程中的六大设计原则？

### 1.单一职责原则
通俗地讲就是一个类只做一件事

* `CALayer`：动画和视图的显示。
* `UIView`：只负责事件传递、事件响应。

### 2.开闭原则

对修改关闭，对扩展开放。
要考虑到后续的扩展性，而不是在原有的基础上来回修改

### 3.接口隔离原则

使用多个专门的协议、而不是一个庞大臃肿的协议

* `UITableviewDelegate`
* `UITableViewDataSource`

### 4.依赖倒置原则

抽象不应该依赖于具体实现、具体实现可以依赖于抽象。
调用接口感觉不到内部是如何操作的

### 5.里氏替换原则

父类可以被子类无缝替换，且原有的功能不受任何影响

例如 KVO


### 6.迪米特法则

一个对象应当对其他对象尽可能少的了解，实现高聚合、低耦合


# 推荐文章
[面向对象设计的六大设计原则（附 Demo 及 UML 类图）- J_Knight_](https://juejin.im/post/5b9526c1e51d450e69731dc2)