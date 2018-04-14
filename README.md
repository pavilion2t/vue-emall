# vue-emall  

前置知识：html+css+js+npm+es6

内容包括：
vue实例、vue组件、vue指令、内置组件、实例方法、实力选项、实例属性。
模板渲染、条件渲染、组件交互、标签属性、事件绑定、计算属性、属性监听、表单、动画。
vue-cli项目搭建、路由、vuex。

数字产品售卖平台（首页售卖页列表页）。  
首页--头部底部采用通用布局。登录弹窗，表单制定规则验证用户名密码。点击走马灯幻灯片可以跳转到具体产品说明页面。点击立即购买，出现确认弹窗，银行列表，验证支付状态。购买完成后，进入产品列表页面，第三方控件时间筛选。

模板渲染的前端框架，于2016.10发布了Vue2.0版本。它实现了数据渲染/数据同步、组件化模块化、路由/ajax/数据流

组件<my-component>通过特定方法注册成为组件，是vue的一个实例，组件之间可以进行数据交换，事件传递等等。

主要特点：1响应式，数据双向绑定。2组件化。3单文件组件，js/css/html存在同一个文件里，webpack+vue loader。

每个 Vue 应用都是通过用 Vue 函数创建一个新的 Vue 实例开始的：  
```
var vm = new Vue({
  // 选项
})  
```

要注册一个全局组件，可以使用 Vue.component(tagName, options)
不必把每个组件都注册到全局。可以通过某个 Vue 实例/组件的实例选项 components注册仅在其作用域中可用的组件。

构造 Vue 实例时传入的各种选项大多数都可以在组件里使用。只有一个例外：data 必须是函数。

事件：
可以用 v-on 指令监听 DOM 事件
v-on:click="counter += 1"

Vue.js 为 v-on 提供了事件修饰符。修饰符是由点开头的指令后缀来表示的。
.stop
.prevent
.capture
.self
.once

标签属性：v-bind 动态地绑定一个或多个特性，或一个组件 prop 到表达式。在绑定 class 或 style 特性时，支持其它类型的值，如数组或对象。
<!-- 绑定一个属性 -->
<img v-bind:src="imageSrc">

<!-- 缩写 -->
<img :src="imageSrc">

条件渲染：v-show 根据表达式之真假值，切换元素的 display CSS 属性。v-if 根据表达式的值的真假条件渲染元素。在切换时元素及它的数据绑定 / 组件被销毁并重建。

高阶功能：过渡、动画
Vue 提供了 transition 的封装组件，在下列情形中，可以给任何元素和组件添加 entering/leaving 过渡：
条件渲染 (使用 v-if)
条件展示 (使用 v-show)
动态组件
组件根节点     

Install and Init  
```    
vue init webpack bookstore   
yarn install   
yarn start  
yarn add vue-router   

```   
 

