Python 教程
***********

Python 是一种易于学习又功能强大的编程语言。它提供了高效的高层次的数据
结构，还有简单有效的面向对象编程。Python 优雅的语法和动态类型，以及解
释型语言的本质，使它成为在很多领域多数平台上写脚本和快速开发应用的理想
语言。

多数平台上的 Python 解释器以及丰富的标准库的源码和可执行文件，都可以在
Python 官网 https://www.python.org/ 免费自由地下载并分享。这个网站
上也提供一些链接，包括第三方 Python 模块、程序、工具等，以及额外的文档。

Python 解释器易于扩展，可以使用 C 或 C++（或者其他可以从 C 调用的语言
）扩展新的功能和数据类型。Python 也可用作可定制化软件中的扩展程序语言
。

这个教程非正式地介绍 Python 语言和系统的基本概念和功能。最好在阅读的时
候有一个 Python 解释器做一些练习，不过所有的例子都是相互独立的，所以这
个教程也可以离线阅读。

有关标准的对象和模块，参阅 Python 标准库。Python语言参考 提供了更正式
的语言定义。要写 C 或者 C++ 扩展，参考 扩展和嵌入 Python 解释器 和
Python/C API 参考手册。也有不少书籍深入讲解 Python。

这个教程并不试图完整包含每一个功能，甚至常用功能可能也没有全部涉及。这
个教程只介绍 Python 中最值得注意的功能，也会让你体会到这个语言的风格特
色。学习完这个教程，你将能够阅读和编写 Python 模块和程序，也可以开始学
习更多的 Python 库模块，详见 Python 标准库。

术语对照表 也很值得一读。

* 1.课前甜点

* 2.使用 Python 解释器

  * 2.1. 调用解释器

    * 2.1.1. 传入参数

    * 2.1.2. 交互模式

  * 2.2. 解释器的运行环境

    * 2.2.1. 源文件的字符编码

* 3.Python 的非正式介绍

  * 3.1. Python 作为计算器使用

    * 3.1.1. 数字

    * 3.1.2. 字符串

    * 3.1.3. 列表

  * 3.2. 走向编程的第一步

* 4.其他流程控制工具

  * 4.1. "if" 语句

  * 4.2. "for" 语句

  * 4.3. "range()" 函数

  * 4.4. "break" 和 "continue" 语句，以及循环中的 "else" 子句

  * 4.5. "pass" 语句

  * 4.6. 定义函数

  * 4.7. 函数定义的更多形式

    * 4.7.1. 参数默认值

    * 4.7.2. 关键字参数

    * 4.7.3. 任意的参数列表

    * 4.7.4. 解包参数列表

    * 4.7.5. Lambda 表达式

    * 4.7.6. 文档字符串

    * 4.7.7. 函数标注

  * 4.8. 小插曲：编码风格

* 5.数据结构

  * 5.1. 列表的更多特性

    * 5.1.1. 列表作为栈使用

    * 5.1.2. 列表作为队列使用

    * 5.1.3. 列表推导式

    * 5.1.4. 嵌套的列表推导式

  * 5.2. "del" 语句

  * 5.3. 元组和序列

  * 5.4. 集合

  * 5.5. 字典

  * 5.6. 循环的技巧

  * 5.7. 深入条件控制

  * 5.8. 比较序列和其他类型

* 6.模块

  * 6.1. 更多有关模块的信息

    * 6.1.1. 以脚本的方式执行模块

    * 6.1.2. 模块搜索路径

    * 6.1.3. “编译过的”Python文件

  * 6.2. 标准模块

  * 6.3. "dir()" 函数

  * 6.4. 包

    * 6.4.1. 从包中导入 *

    * 6.4.2. 子包参考

    * 6.4.3. 多个目录中的包

* 7.输入输出

  * 7.1. 更漂亮的输出格式

    * 7.1.1. 格式化字符串文字

    * 7.1.2. 字符串的 format() 方法

    * 7.1.3. 手动格式化字符串

    * 7.1.4. 旧的字符串格式化方法

  * 7.2. 读写文件

    * 7.2.1. 文件对象的方法

    * 7.2.2. 使用 "json" 保存结构化数据

* 8.错误和异常

  * 8.1. 语法错误

  * 8.2. 异常

  * 8.3. 处理异常

  * 8.4. 抛出异常

  * 8.5. 用户自定义异常

  * 8.6. 定义清理操作

  * 8.7. 预定义的清理操作

* 9.类

  * 9.1. 名称和对象

  * 9.2. Python 作用域和命名空间

    * 9.2.1. 作用域和命名空间示例

  * 9.3. 初探类

    * 9.3.1. 类定义语法

    * 9.3.2. 类对象

    * 9.3.3. 实例对象

    * 9.3.4. 方法对象

    * 9.3.5. 类和实例变量

  * 9.4. 补充说明

  * 9.5. 继承

    * 9.5.1. 多重继承

  * 9.6. 私有变量

  * 9.7. 杂项说明

  * 9.8. 迭代器

  * 9.9. 生成器

  * 9.10. 生成器表达式

* 10.标准库简介

  * 10.1. 操作系统接口

  * 10.2. 文件通配符

  * 10.3. 命令行参数

  * 10.4. 错误输出重定向和程序终止

  * 10.5. 字符串模式匹配

  * 10.6. 数学

  * 10.7. 互联网访问

  * 10.8. 日期和时间

  * 10.9. 数据压缩

  * 10.10. 性能测量

  * 10.11. 质量控制

  * 10.12. 自带电池

* 11.标准库简介 —— 第二部分

  * 11.1. 格式化输出

  * 11.2. 模板

  * 11.3. 使用二进制数据记录格式

  * 11.4. 多线程

  * 11.5. 日志记录

  * 11.6. 弱引用

  * 11.7. 用于操作列表的工具

  * 11.8. 十进制浮点运算

* 12.虚拟环境和包

  * 12.1. 概述

  * 12.2. 创建虚拟环境

  * 12.3. 使用pip管理包

* 13.接下来？

* 14.交互式编辑和编辑历史

  * 14.1. Tab 补全和编辑历史

  * 14.2. 默认交互式解释器的替代品

* 15.浮点算术：争议和限制

  * 15.1. 表示性错误

* 16.附录

  * 16.1. 交互模式

    * 16.1.1. 错误处理

    * 16.1.2. 可执行的Python脚本

    * 16.1.3. 交互式启动文件

    * 16.1.4. 定制模块
