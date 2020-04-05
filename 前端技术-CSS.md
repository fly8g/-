# 前端技术-CSS

>**1) 如何修改 placeholder 的文字颜色？来自 stackoverflow 上面的一个高分回答，适合多种浏览器：**

```css
::-webkit-input-placeholder { /* WebKit, Blink, Edge */
    color:    #909;
}
:-moz-placeholder { /* Mozilla Firefox 4 to 18 */
   color:    #909;
   opacity:  1;
}
::-moz-placeholder { /* Mozilla Firefox 19+ */
   color:    #909;
   opacity:  1;
}
:-ms-input-placeholder { /* Internet Explorer 10-11 */
   color:    #909;
}
::-ms-input-placeholder { /* Microsoft Edge */
   color:    #909;
}
```

>**2) html文本移除应该如何进行隐藏并显示省略号呢？

单行文本溢出隐藏
```css
div {
	/* 单行溢出隐藏 */
	width: 150px;
	white-space: nowrap;
	overflow: hidden;
	text-overflow: ellipsis;
}
```
多行文本溢出隐藏
```css
div {
	/* 多行溢出隐藏 */
	width: 150px;
	display: -webkit-box;
	-webkit-box-orient: vertical;
	-webkit-line-clamp: 3;
	overflow: hidden;
}
```
