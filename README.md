# RxJava2-Note
RxJava2学习笔记   
RxJava是一个基于数据流或事件流，并且可以优雅的处理异步调用，减少接口回调的响应式编程规范。    

**RxJava使用流程：**
>要使用RxJava，首先你需要创建Observable（它们发射数据序列），使用Observable操作符变换那些Observables，获取严格符合你要求的数据，然后观察并处理对这些>数据序列（通过实现观察者或订阅者，然后订阅变换后的Observable）。

[1.创建被观察者](https://github.com/chenbo-boy/RxJava2-Note1_Creating-Observables/blob/master/README.md "创建被观察者")
2.Flowable,Observable,Maybe,Completable区别
4.操作符
异步
闭塞
结合
条件和布尔值
连接
创建
错误管理
过滤
数学和聚合
并行流动
串
转型
效用
.热发射和冷发射



















# 参考
[Creating Observables](https://github.com/ReactiveX/RxJava/wiki/Creating-Observables)   
[RXJava使用示例](https://mcxiaoke.gitbooks.io/rxdocs/content/topics/How-To-Use-RxJava.html)  
