﻿---
layout: page
title: 七大面向对象设计原则
category: 
    - blogs
---

**七大面向对象设计原则**
--------------

***开闭原则***：面对需求，对程序的改动是通过**增加新代码**进行的，而不是改变原来的标题 

***依赖倒转原则***：高层模块不应该依赖底层模块，两个都应该依赖与抽象；抽象不应该依赖于细节，细节应该依赖于抽象。所以要**针对接口编程**，不要针对实现编程。

***里氏代换原则***：由于使用基类对象的地方都可以使用子类对象，因此在程序中尽量使用基类类型来对对象进行定义，而在运行时再确定其子类类型，用**子类对象来替换父类对象**

***单一职责原则***：一个对象应该只包含单一的职责，并且该职责被完整地封装在一个类，就一个类而言，应该仅有一个引起它变化的原因

***接口隔离原则***：接口隔离原则是指使用多个专门的接口，而不使用单一的总接口。**每一个接口应该承担一种相对独立的角色**，不多不少，不干不该干的事，该干的事都要干

***合成复用原则***：合成复用原则就是指在一个新的对象里通过关联关系（包括组合关系和聚合关系）来使用一些已有的对象，使之成为新对象的一部分；新对象通过委派调用已有对象的方法达到复用其已有功能的目的。简言之：**要尽量使用组合/聚合关系，少用继承**

***迪米特法则***：一个软件实体应**当尽可能少的与其他实体发生相互作用**。在类的结构设计上，每一个类都应当尽量降低其成员变量和成员函数的访问权限