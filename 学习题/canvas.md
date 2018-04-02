### Canvas 和 SVG

- Canvas 是用JavaScript 操作动态生成的， SVG 则是使用XML静态描述生成的
- Canvas 基于位图 简单来说就是图片放大会影响到显示的效果，造成不好的影响，SVG 基于矢量图 图形放大不会影响到显示效果
- 发生修改事件的时候，canvas必须重绘，SVG不需要

### 设置 width 和 height

- Canvas 是一个行内块元素 需要的属性一般是三个： id , width , height ，定义在CSS中的宽高 在我们使用JS 操作Canvas时是获取不到的

### canvas坐标

canvas中的坐标是从左上角开始，x轴沿着水平方向（按像素）向右延伸，y轴沿垂直方向向下延伸。
最左上角坐标为 (0,0) 的点为原点

### 接口
getContext("2d") 对象是内建的 HTML5 对象，拥有多种绘制路径、矩形、圆形、字符以及添加图像的方法
