# demo6_advanced_aspectj_01
Spring 高级49讲 AOP 实现之 ajc 编译器
###  AOP 实现之 ajc 编译器

代码参考项目 **demo6_advanced_aspectj_01**

#### 收获💡

1. 编译器也能修改 class 实现增强
2. 编译器增强能突破代理仅能通过方法重写增强的限制：可以对构造方法、静态方法等实现增强

> ***注意***
>
> * 版本选择了 java 8, 因为目前的 aspectj-maven-plugin 1.14.0 最高只支持到 java 16
> * 一定要用 maven 的 compile 来编译, idea 不会调用 ajc 编译器

ajc 编译器的切换： IDEA -> 文件 -> 设置 -> 构建、执行、部署 -> 编译器 -> Java编译器
    使用编译器： Ajc（下拉选择）
