# JUnit 5 

**JUnit 5 = JUnit Platform + JUnit Jupiter + JUnit Vintage**

**Require** : Java 8 +

## JUnit Platform

JUnit Platform 是在 JVM 上启动测试框架的基础，不仅支持 JUnit 自制的测试引擎，其他猜测是引擎也都可以接入。

## JUnit Jupiter

JUnit Jupiter 提供了 JUnit 5 的新编程模型，是 JUnit 5 新特性的核心。内部包含了一个**测试引擎**，用于在 JUnit Platform 上运行。

~~~xml
<dependency>
    <groupId>org.junit.jupiter</groupId>
    <artifactId>junit-jupiter-engine</artifactId>
    <version>5.9.2</version>
    <scope>test</scope>
</dependency>
~~~



## JUnit Vintage

提供一个测试引擎， 向前兼容JUnit3, JUnit4的测试代码

