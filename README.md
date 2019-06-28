# Jquery-SourceCode-Analysis
## 一、项目说明：
### 1.主要用来记录学习和研究JQuery源码的学习笔记及知识点


## 二、每小结知识点总结
> 目录
>> 001 知识点(码梳理)
>>> 1.js面向对象编程

>>> 2.js原型和原型链

>>> 2.js闭包

>> 002 知识点((21, 94) 定义了一些变量和函数)
>>> 1.传递window的优势：查找速度和优化压缩

>>> 2.传递undefined作用: 防止修改undefined

>>> 3."use strict": 严格模式

>>> 4.rootjQuery ==> document :优化压缩和可维护

>>> 5.readyList: 跟DOM加载有关

>>> 6.core_strundefined = typeof undefined ==> 'undefined'

>>> 7._jQuery / _$: 放冲突

>>> 8.class2type = { '[Object String]' : 'string', '[Object Array]' : 'array} : 类型检测

>>> 9.jQuery对象定义

>>> 10.正则表达式定义

>> 003 知识点((96, 283) 给JQ对象，添加一些方法和属性)
>>> 1.jQuery: 版本

>>> 2.constructor: 修正指向问题

>>> 3.init(): 初始化和参数管理

>>> 4.selector: 存储选择字符串

>>> 5.length: this对象的长度

>>> 6.toArray(): 转数组

>>> 7.get(): 转原生集合

>>> 8.pushStack(): JQ对象入栈

>>> 9.each(): 遍历集合

>>> 10.ready(): DMO加载的接口

>>> 11.slice(): 集合的截取

>>> 12.first(): 集合的第一项

>>> 13.last(): 集合的最后一项

>>> 14.eq(): 集合的指定项

>>> 15.map(): 返回集合

>>> 16.end(): 返回集合前一个状态

>>> 17.push(): (内部使用)  
>>> 18.sort(): (内部使用)  
>>> 19.splice(): (内部使用)  
