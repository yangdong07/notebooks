

与python相关的所有问题。

这样分类先：

1. python基本用法
    1. 版本问题
    2. 其他基本用法
2. python高阶用法，每个用法一个专题
    1. 某些模块： numpy、sklearn、tensorflow、keras之类的
    2. 某些框架的基础用法
    3. 并发、异步之类
    4. 其他专题
3. 算法类（用python实现，或者python使用的方法）
4. 设计模式类


### python解释器是如何工作的？

我的理解：python解释器，cpython实际上是一个C程序（C++？），读取 py文件，然后顺序执行。

参考 <https://softwareengineering.stackexchange.com/questions/313254/how-does-the-python-runtime-actually-work>

其实python解释器类似于编译器， 不过是将python代码编译好，放到内存中直接运行罢了。

编译器的工作也是很复杂的：  脚本语言 -> 中间语言 -> AST（语法树）-> 可执行文件。


### python中的对象在内存中到底是什么样的存在？

参考

- <https://stackoverflow.com/questions/4062752/in-what-structure-is-a-python-object-stored-in-memory>
- <http://spyhce.com/blog/cpython-data-structures>
- <https://docs.python.org/2.7/c-api/index.html>


### python程序执行的完整过程。。。

### python里面 object什么作用，声明类的时候要不要加上？


### python 对象的构成？以及与内存的交互


### python 解释器的原理？
