# react-study


npx create-react-app [name]


react 生命周期
componentDidMount()   挂载,会在组件已经被渲染到 DOM 中后运行
componentWillUnmount()  卸载，会在不需要使用这个组件时运行


状态提升
在父组件内，创建对应的state变量与对应的方法，通过调用子组件并传参的方式。
子组件通过props获得只读的变量并赋值，通过事件调用自身方法，在自身方法内调用父组件的对应房吗  
git测试