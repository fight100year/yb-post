# 设计

## 有运行时吗

有，运行时实现了gc，并发，栈管理等

Go的运行时不包含虚拟机

## 如何处理unicode字符

## 为啥没有xx功能

Go更多专注于易编程，编译速度，概念的正交性，以及并发/gc。

## 为啥没有范型

现在是v1.13，v2.0就会支持范型

## 为啥没有异常

Go使用了其他方式

多返回值，让错误处理变得容易

内置函数recover()可从异常处恢复

## 为啥没有断言

断言是方便，但程序员掌握不了，就不提供了

## 为啥并发基于CSP

多线程编程，奠定了复杂的基础，但CSP机制非常好的解决了很多复杂问题，
重要的是其他程序试水了CSP且成功了，所以CSP就被吸收了

## 为啥不用线程而是协程

协程让并发更容易，代价更小

## 为啥map操作不是原子的

使用协程并发访问map

读时，只有新增或删除会引起不安全，其他时候都是安全的

主要是因为map加锁会导致性能下降，尽量不要在读的时候进行增删操作

## 接收变更吗

只要不影响兼容性，可以考虑
