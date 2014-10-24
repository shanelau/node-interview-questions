node-interview-questions
========================

nodejs 面试题精选

#NodeJs 工程师笔试题

1. 写出Math Array String 自带的方法，各五个  

2. 给String,添加一个 getLengt()方法，例如`var str ='sss'; str.getLength();  `，结果为 3  

3. 用 javascript 实现数组去重   

4. 书写正则表达式，匹配 浮点数   

5. 下列代码的输出结果  
 
  	```
 	var User = {
  	count: 1,

  	getCount: function() {
    	return this.count;
  	}
	};
 	console.log(User.getCount());
 	var func = User.getCount;
 	console.log(func());  
	 ```
 
6. 说说你对闭包的理解，闭包的好处

7. 编写代码实现，每隔一分钟异步读取一次 file.logs 文件 ，输出文件中的信息

8. 怎么解决 javascript 嵌套回调问题  

9. session 的原理，客户端禁用cookie后 怎么使用session

9. 遍历一个 javascript 对象，例如

	```
		{name:'lucy',age:15}
	```
10.  express 怎么获取，get 和post方式的传参
11. 完成一个函数,接受数组作为参数,数组元素为整数或者数组,数组元素包含整数或数组,函数返回扁平化后的数组

	```
	如：[1, [2, [ [3, 4], 5], 6]] => [1, 2, 3, 4, 5, 6]
	```