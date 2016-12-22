> JavaScript 是一种面向对象的动态语言，它包含类型、运算符、标准内置（ built-in）对象和方法。它的语法来源于 Java 和 C，所以这两种语言的许多语法特性同样适用于 JavaScript。需要注意的一个主要区别是 JavaScript 不支持类，类这一概念在 JavaScript 通过对象原型（object prototype）得到延续（有关 ES6 类的内容参考这里Classes）。另一个主要区别是 JavaScript 中的函数也是对象，JavaScript 允许函数在包含可执行代码的同时，能像其他对象一样被传递。

## 类型
- Number 数值
- String 字符串
- Boolean 布尔值
- null 空
- undefined 未定义
- Oject 对象
	1. Function（函数）
	2. Array（数组）
	3. Date（日期）
	4. RegExp（正则表达式）
- Symbol（符号）（第六版新增）

> JavaScript 还有一种内置Error（错误）类型，这个会在之后的介绍中提到；现在我们先讨论下上面这些类型。

## 数值
- 二进制 
- 八进制 0[0-7]*
- 十进制
- 十六进制 0x[0-9a-f];
```

```

### 运算符
> +、-、*、/、%；加减乘除模；ps：模是取余数
> 复合运算符 +=、-=、*=、/=、%=； example: x += y; (=>) x = x+y;

### 数学对象Math
- sin 正弦值 对边/斜边
- cos 余弦值 邻边/斜边
- tan 正切值 对边/邻边
- random 0~1的随机小数

### parseInt、parseFloat
> parseInt 是将字符串转换成数字的工具函数
```
//parseInt(string, radix);将字符串转成数字 radix：一个2到36之间的整数值，用于指定转换中采用的基数。 radix正常可以忽略
parseInt('0xF',16);//print 15
parseInt('11111',2);//print 15
```