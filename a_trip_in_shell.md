##### What is Shell?

​	Shell 是一个用C语言编写的程序，它是用户使用Linux的桥梁。Shell既是一种命令语言，又是一种程序设计语言。

​	Shell脚本 （shell script），是一种为shell编写的脚本程序。

它虽然不是Unix/Linux系统内核的一部分，但它调用了系统核心的大部分功能来执行程序、建立文件并以并行的方式协调各个程序的运行。因此，对于用户来说，shell是最重要的实用程序，深入了解和熟练掌握shell的特性极其使用方法，是用好Unix/Linux系统的关键。

可以说，shell使用的熟练程度反映了用户对Unix/Linux使用的熟练程度。

**优缺点**

​	Shell需要依赖其他程序才能完成大部分的工作，这或许是它的缺陷，但它不容置疑的长处是：简洁的脚本语言标记方式，而且比C语言编写的程序执行更快、更有效率。

##### Why?

##### How?

- 基本语法

  - 开头

    - `#!/bin/sh` #! 用来告诉系统后面的参数是用来执行该文件的程序
    - chmod +x filename 使脚本可执行 
    - ./filename 执行文件

  - 注释

    - `#`开头表示注释

  - 变量

  - 命令

    - Unix命令
    - 管道
    - ​

  - 流程控制

    - case

    - select

    - loop

    - if…then

      > 通常用" [ ] "来表示条件测试。注意这里的空格很重要。要确保方括号的空格。

      > [ -f "somefile" ] ：判断是否是一个文件

      >[ -x "/bin/ls" ] ：判断/bin/ls是否存在并有可执行权限
      >
      >[ -n "$var" ] ：判断$var变量是否有值
      >
      >[ "$a" = "$b" ] ：判断$a和$b是否相等

  - ​

    - ​

- 函数

- Here Document

- ​





##### Reference

[Shell教程](http://www.runoob.com/linux/linux-shell.html)

[[详细介绍Linux shell脚本基础学习](http://www.cnblogs.com/xuejie/archive/2013/01/31/2886552.html)](http://www.cnblogs.com/xuejie/archive/2013/01/31/2886552.html)

[Linux Shell脚本教程](http://c.biancheng.net/cpp/shell/)