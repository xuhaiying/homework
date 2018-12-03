## 基本选择器
- 通配符选择器 *
- 元素选择器 E
- 类选择器 .class
- id选择器 #id
- 后代选择器 E F 
- 子元素选择器 E > F
- 相邻兄弟选择器 E + F
- 通用兄弟选择器 E ~ F

### 优先级  
- !important > 行内样式 > ID选择器 > 类选择器 > 标签 > 通配符 > 继承 > 浏览器默认属性

## 属性选择器
- E[attr]
- E[attr="value"]
- E[attr^="value"] 以value开头
- E[attr$="value"] 以value结尾
- E[attr*="value"] 包含value
- E[attr~="value"] 以空格分割的
```
    <a tittle="hello world"></a>
    a[tittle~="world"]
```
- E[attr|="value] 以value或value - 开头

```
    <div class="home-container"></div>
    div[class|="home"]
```

## 伪类和伪元素选择器
- :link,:visited,:hover,:active,:focus
- :enabled,:disabled,:checked
- :first-child
- :last-child
- :nth-child()  (2n) (2n-1) (even) (odd)
- :nth-last-child()
- :nth-of-type()
- :nth-last-of-type()
- :first-of-type
- :last-of-type
- :only-child
- :only-of-type
- :empty
- :not()

- :first-line,:first-letter,:before,:after


