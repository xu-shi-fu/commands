# GDB 命令速查手册






# 功能

    todo
    ### 运行 ### 代码  ### 断点 



# 命令

## backtrace (bt)

查看当前线程的调用堆栈


## break (b)

添加断点

    (GDB) b


## continue (c)

让暂停的程序继续运行

    (GDB) c


## delete (d) 

删除断点

    (GDB) d


## disable 

禁用某个断点

    (GDB) disable


## enable 

启用某个断点

    (GDB) enable

## info (i)

查看断点 / 线程等信息

    (GDB) i

## list(l)

显示源码

    (GDB) l

## next(n)

运行到下一行

    (GDB) n

## print (p)

打印变量或寄存器值

    (GDB) p

## ptype

查看变量类型


## return 

## run(r)

运行一个待调试的程序


## show args

查看设置的命令行参数



## step (s)

单步执行，遇到函数会进入

    (GDB) s


## tbreak (tb)

添加临时断点

    (GDB) tb

## thread 

切换到指定线程


## until (u)

运行到指定行停下来

    (GDB) u

## watch

监视某一个变量或内存地址的值是否发生变化


# 参考文献

todo ...
