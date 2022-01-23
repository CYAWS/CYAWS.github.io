---
title: JAVA的基本程序结构
date: 2022-01-23 15:21:22
tags:
categories: 
 -JAVA笔记
 -JAVA的基本程序结构
---

# 一个简单的Java程序
下面来看一个最简单的java程序
```java
public class FirstSample{
public static void main(String[] args)
    {
        System.out.println("We will not use "hello word");
    }
}
```
首先有几个需要注意的点：
* Java区分大小写，如果出现了大小写拼写错误，程序无法运行
* public称为**访问修饰符**这些修饰符用于控制程序的其他部分对这段代码的访问级别
* 关键字**class**表示Java程序的全部内容都包含在类中
* 关键字class后面紧跟类名。类名必须以字母开头，后面可以跟字母和数字的任意组合，一般来说都定义类名的首字母为大写
* 源代码的文件名必须与公共类的名字相同，并用java作为扩展名

接下来我们来研究以下代码：
```java
{
    System.out.println("We will not use 'hello word'");
}
```
大括号表示方法体的开始与结束  
java中，每个句子必须使用分号结束  
这里使用了System.out对象并调用了它的println方法。注意点号用于调用方法。java的通用语法是`object.method(parameters)`,这等价于函数调用