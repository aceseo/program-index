# MV\*框架

程序可以分为数据层（如读写数据库、处理业务的部分），和表现层（各种各样的UI）。

各种各样的MV\*模式，指数据（model）和视图（view）之间的关系、连接方式。

## [MVC（Model View Controller）](https://zh.wikipedia.org/wiki/MVC)

控制器（Controller）负责转发请求，对请求进行处理。本身不包含处理逻辑，而是用于分离视图和数据。

## [MVVM（Model–view–viewmodel）](https://zh.wikipedia.org/wiki/MVVM)

利用绑定，实现M和V之间的同步，而省去编写控制代码。

如微软的XAML，或Vue.js。

优点：只需定义如何绑定，而无需操心具体的数据同步过程。

缺点：难于调试，及内存消耗相对大一些。

