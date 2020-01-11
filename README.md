# HTMLElementAbsolutePositionOfScreenTest
Js脚本 获取网页元素相对于屏幕的位置测试

##原理
通过鼠标点击事件定位网页左上角绝对位置（基准）：
(e.screenX-e.clientX, e.screenY-e.clientY)
将获取到的元素相对于网页的位置加上基准位置即为该元素绝对位置：
(element.offsetLeft+bodyOffsetLeft, element.offsetTop+bodyOffsetTop)


[预览](https://exsper.github.io/HTMLElementAbsolutePositionOfScreenTest/index.html)
