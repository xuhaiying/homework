## 清除浮动的方法

1. 添加空标签
```
<div style="clear:both"></div>
```
2. 给父元素添加overflower

3. 让父元素也浮动 （不推荐使用）

4. 使用伪元素

```
.clearfix:before, /* 防止margin叠加 */
.clearfix:after{
    content: "";
    display: table;
}
.clearfix:after{
    clear: both;
}
.clearfix{
    zoom: 1; /* 兼容IE6 7 */
}
```
