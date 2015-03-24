#其他属性


####border-radius

用来设置元素的圆角，非常的方便，他的值为`0`的时候表示没有圆角，值为1px表示圆角的水平半径为1px，并且垂直半径也为1px。例如`#circle{width:100px;height:100px;border-radius:50px]}`就是一个圆了。

####font
和字体相关的样式也是经常用到的，特别是英文类型的网站。

+ 使用`font-family`设置字体的类型，比如微软雅黑等
+ 使用`font-size`设置字体的大小
+ 使用`font-weight`设置字体的粗细
+ 使用`line-height`设置行高


####z-index
表示网页元素的曾层叠，当出现元素之间的覆盖时，`z-index`数值越大的，处在覆盖数值较小的。


#伪类

####::after

表示在某个元素后面填充**虚拟**的元素

    div::after{content:"some";display:block;}
    li::before{contet:url(img.png)}

> 注意，::after标签产生的是虚拟内容，虽然可以显示，但是并不会出现在DOM中，因此无法对其进行进一步的操作。

