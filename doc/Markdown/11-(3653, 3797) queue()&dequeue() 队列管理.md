**1 目标**
* 熟悉 `queue() & dequeue()` 队列管理

**2 笔记**
* 知识点
  1. 对外接口：
    ```js
    jQuery.extend({
      queue
      dequeue
      _queueHooks // 作用：出队结束后清理data中所有的缓存的key
    })
    ```  

  2. 实例方法：
    ```js
    jQuery.fn.extend({
      aqueue
      dequeue
      delay // 延迟队列的执行
      clearQueue // 清楚队列
      promise // 队列结束后调用
    })
    ``` 


**3 问题库**
* <mark>队列中存储的都是函数</mark> 
* <mark>queue针对多个异步，Deferred针对一个异步</mark> 

