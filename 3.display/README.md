## html元素
- HTML元素指的是从开始标签到结束标签的所有代码
- 在html中，元素主要分为行内元素和块级元素
- 还有一种特殊的元素叫行内块元素

## 行内元素
- 行内元素指的不会自动换行，并且元素没有宽和高
```
    lable span a em b i strong  ...
```

## 块级元素
- 自动换行，有宽高

```
    h1-h6 div p ul button  from  table ...
```

## 行内块元素

```
    img input td
```

## 行内、块级元素的区别
1. 块级元素会独占一行，其宽和高自动填满其父元素宽度 行内元素不会独占一行，相邻的行内元素会排列在同一行里，直到一行排不下，才会换行，其宽度随元素的内容而变化
2. 块级元素可以设置width、height属性，行内元素设置width、height无效
3. 块级元素可以设置margin、padding。行内元素margin仅设置左右方向有效，上下无效、padding上下左右都有效

## display属性
1. block 
2. inline
3. inline-block