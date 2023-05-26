# learn_jvm

## 我是Java程序猿，我骄傲

从语言学习的门槛来看，Java 是很容易上手的。
适合刚毕业，Java 的生命力和生态，在管理类应用、银行支付交易业务行业的应用。

1. “一次编写，到处运行”
2. 相对安全的内存管理和访问机制，避免了大多数的内存泄漏和指针越界问题
3. 热点代码检测和运行时编译及优化

> 为什么要学习JVM，因为想停止恐惧😱

1. 逃不掉，避不开：到高级开发工程师阶段，Java 虚拟机原理是必须知道的，是了解 Java 程序如何被执行和优化的基础。
2. 教别人时能装x：用中国古话讲，是要“知其然”，还要“知其所以然”；
3. 记八股文就你我自己学数学时，只记公式（Java 类库 API）没有用，容易忘记； 只有理解公式推导的过程才是最重要的
4. 有追求：能更好理解 Java 语言特性，写出简洁、高效代码； 比如说为什么使用异常捕获的代码为什么比较耗费性能，为什么要避免使用异常捕获来控制程序流程。

## Java 虚拟机知识框架图

1. Java 程序语言设计
2. Class 文件格式
3. Java类库 API
4. 三方库 API

## 注意区分 JDK 和 JRE

JDK 包含 JRE，JRE 仅包含运行 Java 程序的必须组件（也就是说有 JRE 就可以开发和运行Java程序了）

···shell···
java -XX:+PrintFlagsFinal -XX:+UnlockDiagnosticVMOptions -version
···

学了一段时间的 JVM 的体会：横看成岭侧成峰，远近高低各不同。
技术方面更有自信，学会看指令后，能从更底层了解并发编程、反射、异常……
学过JVM对比没学过的，简直就是降维打击

【墨问便签】每日一语音+图+文字，帮你每天进步一点点