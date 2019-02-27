Redux： 数据管理模块          【redux 本身只能解析对象】
原则：

1. 唯一性
2. 只有store能够改变自己的内容
3. reduces必须是纯函数 （解释：给固定的输入，就有一定固定的输出，而且不会有任何副作用）
   核心API：
   createStore
   store.dispatch     执行active   
   store.getState     获取数据
   store.subscribe    订阅 数据发放改变
   combineReducers    合并多个reduces