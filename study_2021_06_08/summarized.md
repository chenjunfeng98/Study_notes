# 学习总结

## 隐式转换规则
1. 逻辑运算符(&&、||、!);
2. 运算符(+、-、*、/);
3. 关系操作符(<、>、<=、>=);
4. 相等运算符(==);
5. if/while条件;

***PS***
1、如果其中一个操作值是null或者undefined，那么另一个操作符必须为null或者undefined才会返回true;<br>
2、如果一个操作值为object,且一方为string、number，就会把object转化为原始类型(valueof)再进行判断

## ES6构造函数(class)


## 面向对象方法
1. hasOwnProperty()方法返回一个布尔值，判断对象是否包含特定的自身（非继承）属性。<br>
***PS***:对于原型对象本身来说，这些原型属性又是原型对象的自有属性，所以返回值是 true。


## tranform
tranform:translate(x,y),该方法可覆盖其他元素，不影响元素布局。

