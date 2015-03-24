#原型、继承以及作用域


http://atleeon.com/code/2013/10/05/javascript-prototype/

###作用域
JavaScript的作用域与C不同，并不是以`{}`块来进行区分的，而是根据函数而确定，所以下面代码会打印5。

    if(true){
        var a  = 5;
    }
    log.console(a); //output 5

###全局作用域

+ 在所有函数之外定义的变量拥有全局作用域
+ 没有使用`var`定义的变量拥有全局作用域

###函数作用域

指在某个函数内部定义的变量，只具有函数内的访问权限

[JavaScript Scoping and Hoisting](http://atleeon.com/code/2014/03/06/javascript-scoping-hoisting/)



