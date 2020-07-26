# SVG-Learning

# 文档

* [SVG元素参考](https://developer.mozilla.org/zh-CN/docs/Web/SVG/Element)
* [国外大佬总结](http://tutorials.jenkov.com/svg/index.html)

# Tips

* 画图的效果是使用stroke-dasharray和stroke-dashoffset实现
  * stroke-dasharray - 虚线，当值(path可以通过getTotalLength())设置过大的时候，图形也是完整显示的
  * stroke-dashoffset - 设置偏移量，和上述的值一致，这样图形就不见了
  * 设置css动画，把stroke-dashoffset的值to0，这样就有画图的效果了
* line线宽为1，不容易被`cursor:pointer`选中，可以创建一条线宽更粗的，颜色为透明的线，提升用户体验
* text元素innerHTML在IE不支持，可以使用textContent
* 贝塞尔曲线文字居中可以使用textPath元素，配合偏移量属性startOffset，详细可见11章的源码案例

# 记录学习的过程

  * [1-介绍](./1-介绍/1-介绍.md)
  * [2-引入svg](./2-引入svg/2-引入svg.md)
  * [3-基本图形](./3-基本图形/3-基本图形.md)
  * [4-组合,文字,图片](./4-组合,文字,图片/4-组合,文字,图片.md)
  * [5-小案例](./5-小案例/5-小案例.md)
  * [6-JS创建元素](./6-JS创建元素/6-JS创建元素.md)
  * [7-数据驱动视图](./7-数据驱动视图/7-数据驱动视图.md)
  * [8-数学公式绘制节点](./8-数学公式绘制节点/8-数学公式绘制节点.md)
  * [9-交互效果](./9-交互效果/9-交互效果.md)
  * [10-动态创建折线](./10-动态创建折线/10-动态创建折线.md)
  * [11-初识path](./11-初识path/11-初识path.md)
  * [12-简单饼图原理](./12-简单饼图原理/12-简单饼图原理.md)
