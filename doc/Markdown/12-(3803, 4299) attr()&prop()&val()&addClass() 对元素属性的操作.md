**1 目标**
* 熟悉 `attr() & prop() & val() & addClass()` 对元素属性的操作

**2 笔记**
* 简化

```js
jQuery.fn.extend({
  attr        //
  removeAttr  //
  prop        //
  removeProp  //
  addClass    //
  removeClass //
  toggleClass //
  hasClass    //
  val         //
})
```

* 知识点
  1. 工具方法:
    ```js
    // 基本上是内部是用
    jQuery.extend({
      valHooks    //
      attr        //
      removeAttr  //
      attrHooks   //
      propFix     //
      prop        //
      propHooks   //
    })
    ```  

  2. 实例方法:
    ```js
    jQuery.fn.extend({
      attr        //
      removeAttr  //
      prop        //
      removeProp  //
      addClass    //
      removeClass //
      toggleClass //
      hasClass    //
      val         //
    })
    ``` 


**3 问题库**
* <mark></mark>  

