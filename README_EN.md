# Red-black-tree-visualization
Red black tree visualization in JS，Konva，TimelineLite，Vue3，Papercss

#### Introduction
- Feature：visualization of red black tree
- Function：complete insertion and deletion, and all tween animation version
- Language：Javascript es6
- Source：[Konva](https://github.com/konvajs/konva)，[TweenLite](https://greensock.com/tweenlite/)，[Vue3](https://github.com/vuejs/vue-next)，[Papercss](https://github.com/papercss/papercss)
- Other：judgment of nature 4 and 5 of red black tree，matrix operation of coordinate vector

#### Image
<p><img src="https://github.com/akinokoika/Red-black-tree-visualization/blob/main/image/Save_as.png" width="500px"></img></p>

#### Code
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
