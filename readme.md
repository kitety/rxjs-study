学习RXJS
===
https://blog.jerry-hong.com/series/rxjs

- RXJS介绍
- 函数式编程Functional Programming
- 常用的FP方法
  - ForEach
  - Map
  - Filter等
- 什么是Observable
- 建立Observable(一)
- 建立Observable(二)
  - create
  - of
  - from
  - fromEvent
  - fromPromise
  - never
  - empty
  - throw
  - interval
  - timer

相关资源
===

https://rxmarbles.com/


笔记
===
今天讲了Iterator 跟Observer 两个Pattern，这两个Pattern 都是渐进式的取得元素，差异在于Observer 是靠生产者推送资料，Iterator 则是消费者去要求资料，而Observable 就是这两个思想的结合！

订阅一个Observable 就像是执行一个function

Observer 是一个物件，这个物件具有三个方法，分别是next , error , complete

订阅一个Observable 就像在执行一个function

Operator
- create
- of
- from
- fromEvent
- fromPromise
- never
- empty
- throw
- interval
- timer
