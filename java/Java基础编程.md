# 编程

Java是面向对象的语言，面向对象的语言的程序的组成单位就是“类”；

使用关键字class可以声明类；可运行的Java类的基本结构如下：

```java
public class op {
    public static void main(String[] args) {
        System.out.println("hello world");
    }
}
```

`public`：用来修饰`class`，成为公共类，即使不在一个类中，其他类也可以访问它。且一个`.java`文件中最多有一个公共类。可以没有

`class`：类关键字。

`op`：自定义的类名，如果其命名的类为`public class`，那这个文件要跟类同名。

`public static void main(String[] args)`：main方法，是程序的入口。可以理解成`python`中的主函数语段。