# JavaScript基础

### 变量

**创建变量:**

```javascript
//1、声明变量
var str1 = 'hello word'
//或者
var str2
str2 = 'hello word'
//声明变量的方法 var、let、const
//var为声明全局变量，let和const为块级变量
```

**弹窗练习:**

```javascript
//弹窗练习
let name = prompt('输入名字');
document.write(name)
```

**交换变量值:**

```javascript
//交换变量值
//创建变量
let num1 = 20;
let num2 = 30;

//1创建临时变量temp
let temp
//交换变量值
temp = num1;
num1 = num2
num2 = temp
//打印到控制台
console.log('num1:',num1);
console.log('num2:',num2);
```

*练习案例:*

<img src="https://raw.githubusercontent.com/1542608903/images/main/Snipaste_2024-02-04_20-09-30.png" title="" alt="" style="zoom:50%;">

```javascript
//创建prompt弹窗
let uname = prompt('输入您的姓名')
let age = prompt('输入您的年龄')
let gender =prompt('输入您的性别')
//显示到页面
document.write('name:'+ uname)
document.write('age:'+age)
document.write('gender:'+gender)
```

**数组（Array）:**

<img src="https://github.com/1542608903/images/blob/main/Snipaste_2024-02-04_20-31-45.png?raw=true" title="" alt="" style="zoom:33%;">

```javascript
//创建数组
let arr = []
//赋值
arr = ['Tom','Ameliy','jane']
//重点数组的排序是从0开始,也叫索引或者下标
console.log(arr[0])
//数组有一个重要的属性length,获取数组的长度
console.log(arr.length)
```

*数组练习:*

<img src="https://github.com/1542608903/images/blob/main/Snipaste_2024-02-04_20-40-23.png?raw=true" title="" alt="" style="zoom:50%;">

```javascript
let dateArr = ['星期一','星期二','星期三','星期四','星期五','星期六','星期日']
console.log(dateArr[6])
```



### 常量

1.常量的基本使用：

- <font color="red">**概念：** </font>使用const声明的变量叫“常量”。

- **使用场景：** 当某个变量永远<font color="red" face="逐浪新宋">**不会改变**</font>的时候，就可以使用const来声明。

### 数据类型

> 值类型(基本类型)：
> 
> 1. 字符串(String)
> 2. 数字(Number)
> 3. 布尔(Boolean)
> 4. 空(Null)
> 5. 未定义(Undefined)
> 6. Symbol

> 引用数据类型(对象类型)
> 
> 1. 对象(Object)
> 2. 数组(Array)
> 3. 函数(Function)

# JavaScript进阶


