### 前端常见问题收集
1. gulp和webpack是什么？有什么区别？
2. angular常用指令
3. angular双向绑定实现原理
4. ie8常见兼容性问题
5. 如何通过webpack构建多页应用
6. display:flex 6大属性是什么？子元素如何垂直居中
7. js闭包使用场景
8. js递归深度限制
9. js堆栈原理
10. js map的参数有哪些
11. js 原型和原型链
12. js 实现继承方式有哪些
13. 如何只用css实现一个自适应的正方形（不固定宽高，随屏幕宽度而定）
14. 如何用css实现水平并且垂直居中
15. 列举less或者sass常用函数
16. es5的函数和es6的箭头函数区别
17. es6中合并两个对象怎么做
18. js 数组的操作方法有哪些
19. js 对象的浅拷贝和深拷贝

vue或者react
1. 一般在循环的时候（v-for, map）会提示需要加上key,那么绑定key到底有什么好处呢？不绑定又会造成什么影响？
2. vue中ref的用法
3. vue中nextTick用法
4. vue路由中, 如果路由定义了这么两个,/user/:username/,/user/:username/:id,意思就是可传1个或者2个参数, 但是如果通过/user/:username/可以匹配到正确的组件，如果加上id，就会出现白屏匹配不到的情况，不知道原因是什么, 重新定义个一个路由交换位置就可以了。
5. 对象中的数据给了另一个对象变量，改变一个对象的值，另一个对象也变化！？ 实际在vue中  this.A = this.B,没有进行深层赋值，只是把this.A的地址指向了与this.B相同的地址，所有对于A的修改会影响到B
解决方法this.A=JSON.parse(JSON.stringify(this.B))，还有一种方法,如果只是把另一个对象中的属性和值copy过来可以直接用解构赋值，this.A={...this.B}
但是需要注意的是，解构赋值的拷贝也是浅拷贝，即如果其中一个键的值是复合类型的值（数组、对象、函数）、那么解构赋值拷贝的是这个值的引用，而不是这个值的副本。

6. vue如何注册全局的js方法或者对象
7. export default 和 export 区别

uniapp
1. 不支持标签中属性绑定方法
2. 不支持过滤器
3. canvas需要固定写好Id,不支持动态方式
4. 隐藏tabbar闪烁不流畅
5. chart图绘制不流畅卡顿，ios错位
6. textarea ios真机不支持双向绑定
7. 小程序中不支持this.$store.state获取，必须用mapState获取
8. 小程序中组件定义了名称，在important时必须跟名称一致，不然无效

