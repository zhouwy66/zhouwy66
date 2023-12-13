# 一、基础语法

## 1.数据类型

**基本数据类型：** 数字（number）、字符串（string）、布尔（boolean）、空（null）、未定义（undefined）。

**复合数据类型：** 对象（object）、数组（array）、函数（function）、正则(RegExp)、日期(Date)、 Map 、Set等

- **数据类型一般就三大类：数、文字、逻辑**
- **对象是变量的容器**
- **typeof运算符：检测值和变量的类型**

![1702275720764](C:\Users\hp\AppData\Roaming\Typora\typora-user-images\1702275720764.png)

```javascript
typeof 5;
typeof '慕课'
```



### （1）声明变量

```javascript
//数字类型
var x1=34.00; 
var z=123e-5;

//字符串类型
var carname="Volvo XC60";
var carname='Volvo XC60';

//布尔类型
var x=true;
var y=false;

//数组类型
var cars=new Array();
cars[0]="Saab";
cars[1]="Volvo";
cars[2]="BMW";
var cars=new Array("Saab","Volvo","BMW");

//对象类型
var person={
firstname : "John",
lastname  : "Doe",
id        :  5566
};
//对象属性有两种寻址方式：
name=person.lastname;
name=person["lastname"];

//Undefined 和 Null:Undefined 这个值表示变量不含有值;可以通过将变量的值设置为 null 来清空变量。
person=null;
```

### （2）字符串  

![1702278447018](C:\Users\hp\AppData\Roaming\Typora\typora-user-images\1702278447018.png)

![1702278631815](C:\Users\hp\AppData\Roaming\Typora\typora-user-images\1702278631815.png)

```javascript
//声明字符串类型变量
var carname="Volvo XC60";
var carname='Volvo XC60';
```

### （3）数字

![1702279483704](C:\Users\hp\AppData\Roaming\Typora\typora-user-images\1702279483704.png)

![1702279456610](C:\Users\hp\AppData\Roaming\Typora\typora-user-images\1702279456610.png)

### （4）数据类型转换

**强制类型转换—string**

将其他数据类型转换为String

![1702280422528](C:\Users\hp\AppData\Roaming\Typora\typora-user-images\1702280422528.png)

**强制类型转换—number**

将其他数据类型转换为Number

![1702280788221](C:\Users\hp\AppData\Roaming\Typora\typora-user-images\1702280788221.png)

![1702280829101](C:\Users\hp\AppData\Roaming\Typora\typora-user-images\1702280829101.png)

![1702281104958](C:\Users\hp\AppData\Roaming\Typora\typora-user-images\1702281104958.png)

**其他进制数字**

![1702281342299](C:\Users\hp\AppData\Roaming\Typora\typora-user-images\1702281342299.png)

![1702281359340](C:\Users\hp\AppData\Roaming\Typora\typora-user-images\1702281359340.png)

![1702281456588](C:\Users\hp\AppData\Roaming\Typora\typora-user-images\1702281456588.png)

**强制类型转换—boolean**

![1702281729364](C:\Users\hp\AppData\Roaming\Typora\typora-user-images\1702281729364.png)

### （5）运算符

![1702281893181](C:\Users\hp\AppData\Roaming\Typora\typora-user-images\1702281893181.png)

算术运算符