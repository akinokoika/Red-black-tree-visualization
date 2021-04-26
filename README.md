# Red-black-tree-visualization
Red black tree visualization in JS，Konva，TimelineLite，Vue3，Papercss

#### 介绍
- 效果：红黑树的可视化
- 功能：完整的插入和删除，以及全部补间动画版本
- 语言：Javascript es6
- 开源：[Konva](https://github.com/konvajs/konva)，[TweenLite](https://greensock.com/tweenlite/)，[Vue3](https://github.com/vuejs/vue-next)，[Papercss](https://github.com/papercss/papercss)
- 其他：红黑树性质4和5的判断，坐标向量的矩阵运算

#### 图片
<p><img src="" width="500px"></img></p>

```js
var t = init()
var x = Number(handle.info)
t = insert(x, t)
t = del(x, t)
insert_cartoon(x, root)
del_cartoon(x, root)
draw(t,0,0)
drag(t)
judge_nature_4(t)
judge_nature_5(t)
```
