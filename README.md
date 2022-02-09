# Red-black-tree-visualization
Red black tree visualization in JS，Konva，TimelineLite，Vue3，Papercss，Big
###### Readme english version: [README_EN](README_EN.md)

#### 介绍
- 效果：红黑树的可视化
- 功能：完整的插入和删除，以及全部补间动画版本
- 语言：Javascript es6
- 开源：[Konva](https://github.com/konvajs/konva)，[TweenLite](https://greensock.com/tweenlite/)，[Vue3](https://github.com/vuejs/vue-next)，[Papercss](https://github.com/papercss/papercss)，[Big](https://github.com/MikeMcl/big.js)
- 其他：红黑树性质4和5的判断，坐标向量的矩阵运算

#### 在线
<a href="https://akinokoika.github.io/Red-black-tree-visualization/project/Rbtree.html">红黑树可视化在线测试</a>

#### 图片
<p><img src="https://github.com/akinokoika/Red-black-tree-visualization/blob/main/image/Save_as.png" width="500px"></img></p>

#### 代码
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
