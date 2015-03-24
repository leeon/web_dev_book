#选择器

css的选择器构成了其语法的基本形式，最常用的主要有：

1. 元素选择器 `p{color:rgb(0,0,0);}` 设置p标签的样式
2. 类选择器  `.menu{ color:#FFF;}` 设置menu类的样式
3. ID选择器  `#sidebar{}` 设置ID为sidebar的属性
4. 后代选择器 `.main p{color:#444}` 将main类下的所有p标签设置样式
5. 群组选择器 `h1,h2{color:#222}` 将h1 h2设置样式

不同的选择器可以组合在一起，例如 `div.sidebar p>strong{color:blue;}`表示的是 具有sidebar类的div中 所有的P标签下的子元素 strong颜色为蓝色。 其中空格 和 `>`的区别是，空格表示后代元素，而`>`必须是直接的子元素，嵌套的子元素是无效的。

css拥有继承的特性，即子元素会继承父元素的css属性。

> 伪类 是一种常见的用法，比如`a:hover{color:red;}`，表示链接在鼠标经过时的状态。




