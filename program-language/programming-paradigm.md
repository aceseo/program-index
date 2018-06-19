---
description: Programming paradigm
---

# 编程范式

[https://zh.wikipedia.org/wiki/编程范型](https://zh.wikipedia.org/wiki/编程范型)

指编程的风格和方式。有时候一种语言会对应多种范式，范式并不是互斥的。

### [过程式  Procedural programming](https://zh.wikipedia.org/wiki/%E8%BF%87%E7%A8%8B%E5%BC%8F%E7%BC%96%E7%A8%8B)

主要使用函数调用来控制流程。

如C语言。

### [面向对象  OOP（Object-oriented programming）](https://zh.wikipedia.org/wiki/%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E7%A8%8B%E5%BA%8F%E8%AE%BE%E8%AE%A1)

主要使用`class`关键字，将调用对象抽象为类，封装属性与方法。

如C\#，C++，Python。

### [面向方面 AOP （Aspect-oriented programming）](https://zh.wikipedia.org/wiki/%E9%9D%A2%E5%90%91%E4%BE%A7%E9%9D%A2%E7%9A%84%E7%A8%8B%E5%BA%8F%E8%AE%BE%E8%AE%A1)

又叫剖面导向程序设计。将一段过程划分为多个切面，针对阶段进行处理。

如Python中的装饰器，C\#中的DispatchProxy，JavaScript中Promise的调用链。

### [元编程  Metaprogramming](https://zh.wikipedia.org/wiki/%E5%85%83%E7%BC%96%E7%A8%8B)

指“程序可以编写程序”。

如C语言的宏与C++中的模板。

#### 程序自己操纵自己代码的能力称为“[反射](https://zh.wikipedia.org/wiki/%E5%8F%8D%E5%B0%84_%28%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%A7%91%E5%AD%A6%29)”（reflection）。

### [函数式  **functional programming**](https://zh.wikipedia.org/wiki/%E5%87%BD%E6%95%B8%E7%A8%8B%E5%BC%8F%E8%AA%9E%E8%A8%80)

将函数作为语言第一公民，主要强调函数调用无副作用，只关注输入和输出。（当然真正实践中一定会和环境交互）

如Haskell，F\#，Lisp。

