<!--
 * @Author: your name
 * @Date: 2020-06-20 11:08:17
 * @LastEditTime: 2020-06-21 21:48:05
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \react_Demo\readme.md
-->

## React 基础知识

### JSX 语法

JSX 语法:javascript + XML 语法(HTML)
解读 jsx 语法:遇到<>按照 HTML 语法解析,遇到{}按照 javascript 语法解析

### 元素渲染

### 组件

后缀可以是 js 也可以是 jsx
一个 React 项目,是由成千上万个组件组成

### props 属性

组件的复用性很重要

### 是

### React 的生命周期函数

随时我们对 react 理解和使用越来越多
函数列表
componentWillMount:在组件渲染之前执行
componentDidMount: 在组件渲染之后执行
shouldComponentUpdate: 返回 true 和 false,true 允许改变,false 不允许修改
componentWillUpdate:数据在改变之前执行(props,state);
componentDidUpdate:数据修改完成(state,props)
componentWillReceiveProps:props 改变执行;
componentWillUnmount:组件卸载前执行

之传父;
父传之;

### 关于 setState 更新是同步还是异步

1. setState 会引起视图的重绘
2. 在可控的情况下是异步,在非可控的情况下是同步

### 列表&key

key

### 表单

1. 受控组件
2. 非受控组件

### Refs and the DOM

1. 管理焦点,文本选择或媒体播放
2. 触发强制动画
3. 集成第三方 DOM 库
#   R e a c t _ s t u d y  
 