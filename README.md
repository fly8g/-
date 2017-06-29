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
