# Promise

##Promise模式学习记录

###一个promise有下面三个不同状态：

>pending待承诺 		- 初始状态
>fulfilled实现承诺  - 一个承诺成功实现状态
>rejected拒绝承诺 	- 一个承诺失败的状态

###promise必须实现 then 方法
>then必须返回一个promise
>可以调用多次
> then方法接受两个参数
