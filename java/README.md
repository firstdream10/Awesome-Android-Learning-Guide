
![](https://avatars3.githubusercontent.com/u/32798425?s=400&u=e2ad1a5a21fc71ff2f8511866395beca599656f9&v=4)

# Awesome-Android-Learning-Guide

努力打造一份系统、全面的安卓开发者进阶指南

# Java 部分

### [小伙伴们讨论自己对 Java 等的掌握情况](./summary/everyone_beginning_state.md)

## 决定学习内容

《Java 基础系列》初步整理大概有 12 篇：

### 1.抽象类和接口

文章地址：

- [初稿·抽象类与接口](抽象类与接口.md)
- [终稿·再谈抽象类和接口](1再谈抽象类和接口.md)

### 2. 内部类

文章地址：

- [初稿·深入浅出Java内部类](InnerClass.md)
- [终稿·内部类的字节码学习和实战使用场景](3内部类字节码分析及使用场景.md)

### 3. 修饰符
### 4. 装箱拆箱

文章地址：

- [全面理解自动装拆箱及常见风险点](4自动装拆箱.md)

### 5. 注解
### 6. 反射
### 7. 泛型
### 8. 异常

文章地址：

- [初稿·深入了解 Java 异常](2Java异常.md)



### 9. 集合
### 10. IO
### 11. 字符串
### 12. 其他

## 学习后对 Java 部分进行总结


每个人光写一个话题，可能对其他的掌握的不够深，趁此机会总结下你对这些知识点的认识，正好有不会的可以去看小伙伴的文章。

不是写文章，就当是模拟面试，对每个问题写出自己的理解即可，想深究的可以后面再深究。

问题就是我们上次开会的那些，[在这里](../开会记录/Java 基础分配.txt) 。

具体描述见 [Java 基础总结任务 #14](https://github.com/iwannabetop/Awesome-Android-Learning-Guide/issues/14)

> 2017.11.05 全部完成，赞！ 

提交内容：

- [Anonymous 的总结](./summary/总结-Anonymous.md)
- [shixinzhang 的总结](./summary/总结-shixinzhang.md)
- [金鑫 的总结](./summary/总结-金鑫.md)
- [知北游 的总结](./summary/总结-知北游.txt)
- [Cloud 的总结](./summary/总结-Cloud.md)
- [Milo 的总结](./summary/总结-Milo.pdf)
- [Struggle 的总结](./summary/总结-Struggle.md)
- [Wustor 的总结](./summary/总结-Wustor.md)
- [杨哲 的总结](./summary/总结-YangZhe.md)
- [ZHL 的总结](http://4ef4071d.wiz03.com/share/s/1eZ0st2p54A92lnhLO1ywy4Q2iXceY3EyQwP2ViW052Ss5o_)
- [麦田哥 的总结](http://note.youdao.com/share/?id=ce5f04bf77dcee1a7f6290f53ba7a1a3&type=note#/)
- [Alex_赵](http://www.jianshu.com/p/bbfbf8502620)

# 知识点任务表

军令状：

- 晚交稿一天在群里发 50 元红包。

> 表格限制，年数 “2017” 省略

|序号| 知识点 | 问题 | 解答 | 审核 | 开始时间 | 最晚交稿| 状态 |备注
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | 类、内部类、静态内部类、匿名内部类 | 创建一个类的时候，什么时候选择类、内部类、静态内部类、匿名内部类？设计框架时该如何选择？ | Cloud | Struggle, Alex_赵 | 10.17 | 10.24 | 已发布 | |
| 2 | 抽象类与接口 | 什么时候会创建一个抽象类，为什么不用接口？设计框架时该如何选择？| Milo | Struggle | 10.17 | 10.24 | 已发布 | |
| 3 | 常见的类、成员变量修饰符 | 类的成员变量修饰符有哪些？protected private 怎么选，什么时候用 final 修饰，什么时候会用 static ？| Alex_赵 | 麦田哥 | 10.17 | 10.31| 编辑中 |  |
| 4 | 自动装箱拆箱 | 什么时候会发生自动装箱拆箱？有什么需要注意的吗？对性能有什么影响？| 麦田哥 | shixinzhang, Struggle | 10.17 | 10.31 | 编辑中 | 项目紧，申请 2 周; 希望可以涉及 SparseArray  ArrayMap |
| 5 | 注解 | 注解是什么？有几种类型？分别的使用场景？| 知北游 | Milo, 张宏雷  | 10.17 | 10.24 | 编辑中 | |
| 6 | 反射 | 反射是什么？什么时候用反射？| 张宏雷 | shixinzhang| 10.17 | 10.31 | 编辑中 | 项目紧，申请 2 周时间 |
| 7 | 泛型| 泛型使用在什么场景，你有写过使用泛型的代码吗？| Struggle | 金鑫 | 10.17 | 10.24 |编辑中 | |
| 8 | 异常 | 异常有几种类型，OOM 属于哪种？catch finally 执行顺序？| 金鑫 | 杨哲, shixinzhang | 10.17 | 10.24 |已发布 | |
| 9 | 集合框架 | 集合你一般使用哪些？列表、哈希表都有哪些实现，优劣清楚吗？| Anonymous | 杨哲, wustor | 10.17 | 11.07 | 编辑中 | 内容比较多，时间延迟至 3 周 |
| 10 | IO | IO 你一般怎么用？| wustor | 杨哲, shixinzhang | 10.17 | 10.24 | 编辑中 | 最好可以结合装饰模式|
| 11 | 字符串 | String 为什么不可变，与 StringBuilder StringBuffer 区别？| wustor | shixinzhang | 10.17 | 10.24 | 编辑中 | |
| 12 | 工具类 Collections | 一些常用方法的实现原理| shixinzhang | shixinzhang | 10.17 | 10.24 | 编辑中 | |


