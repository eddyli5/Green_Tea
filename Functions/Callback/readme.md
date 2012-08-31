回调函数

示例：
上下文作用域：1、call & apply 2、jQuery 
事件处理：3、Node.js 4、事件 
超时处理：5、setTimeout()
自定义类库

回调模式是一种简单而又强大的模式，当设计一个库时它可以派上用场。
进入软件库的代码应该尽可能地通用和可复用的代码，而回调可以帮助实现这种通用化。不需要预测和实现能想到的每一项功能。
相反，可以专注于核心功能并提供‘挂钩’形式的回调函数，这将使类库很容易地构建、扩展，以及自定义库方法