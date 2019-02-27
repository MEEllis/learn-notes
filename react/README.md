虚拟DOM：

1. 数据（state,props）
2. JSX （模板）
3. 根据 数据和 JSX 生成 虚拟DOM （js对象）
4. 根据虚拟DOM生成 真实DOM
5. 数据发生改变
6. 根据 数据和 JSX 生成 虚拟DOM （js对象）
7. 对比两次的虚拟DOM（同级比较，如果不一样，替换这个节点下的所有节点）,分析不同的地方，更新不同的地方， 生成真实的dom 
   优点：
8. 性能提升，
9. 他是的跨端应用得以实现。 虚拟DOM 解释成相对应的 原生组件 。 React Native

 React 生命周期函数

1. Initialization(初始化，setup props and state)   
2. Mounting (挂载) [componentWillMount,render,componentDidMount]
3. Updation (修改状态 props , state):
   props: componentWillReceiveProps-->shouldComponentUpdate-->componentWillUpdate-->render-->componentDidUpdate
     state: shouldComponentUpdate-->componentWillUpdate-->render-->componentDidUpdate
4. Unmounting (卸载)[componentWillUnmount]



redux-thunk :  redux 的中间件， 对 redux扩展，增加了接受函数的能力(异步执行的能力)，  redux 本身只能解析对象，无法解析函数，详情请看 actionCreator.js
redux-saga :  redux 的中间件， 对 redux扩展，异步执行的能力

