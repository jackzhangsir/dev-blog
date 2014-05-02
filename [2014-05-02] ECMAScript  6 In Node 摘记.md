### 块级作用域之let和const命令

let命令
- 可保存局部变量作为循环中函数的参数
- 可替代立即执行函数的写法

const命令
- 复制以后变不可改变

### 多变量的模式复制

- Node(v0.11)暂不支持

### 数组推导

- Node(v0.11)暂不支持

### 字符串的扩展

- Node(v0.11)暂不支持

### 数值的扩展

- Number/Math对象扩展

### 对象的扩展

- 略(支持)

### 函数的扩展

- 函数拦截Proxy对象	(访问对象之前所处的一层拦截)
	注：直接Proxy()创建，而非new Proxy();

- 其他特性均不支持(默认参数，reset运算符，剪头函数等)

### Set和Map

- Set不支持

- Map支持(强大)

### 迭代器和for...of循环

- 可自定义迭代器(支持)

- for...of支持迭代器的遍历

- 数组和字符串原生都具备iterator接口(不支持)

### Generator函数

- 可用于异步操作(支持)

### Promise对象

- 流程控制(不支持)

### Class和Module

- 不支持


###参考

- [ECMAScript 6 入门](http://es6.ruanyifeng.com/)
- [ECMAScript 6 in Node.JS](https://github.com/JustinDrake/node-es6-examples)