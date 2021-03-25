# 基本概念

## 派发器 dispatch 

* 根据一个又一个的事情 -> type -> type对应的事情 -> 触发对应的方法执行
* type -> 每一件事对应的方法集合
* 派发器 -> type -> method
* dispatch -> action type -> method
  store -> state = {
      count: 0
  }

  store.dispatch

  PLUS -> plus (() => store.state.count + 1)
  MINUS -> minus (() => store.state.count - 1)