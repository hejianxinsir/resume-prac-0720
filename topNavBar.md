1. li 标签有时候没有包住 a 标签，给 a 标签一个 display: block; 就能解决这个 bug 。

2. img 标签的 alt 就是 alternative 的意思。

3. background-image: url()  背景图片

4. dl dt dd  list term definition

5. html 里 and 要用 &npm; 表示

6. 开发者工具里 network img 去找图片。

7. div 的高度由内部文档流高度总和决定。文档流就是文档内元素的流动方向。内联元素从左往右，块级元素从上往下独占一行。

8. 英文单词遇到阻碍不会换行，此时可以用 word-break: all ;

9. 高度与文档流课程里，有 span 高度由什么决定的相关的解释。

10. 不要给元素高度。由内部元素撑起来就行了。

11. 如果给宽度 100% ，可能导致 div 超过 body 宽度，因为你的 div 可能有 padding 。此时你可以再加一个子元素，包裹其中所有元素。

12. 给背景图加一个 div ，当做遮罩，给 rgba(0,0,0,0.3).

13. 图片居中
```
background: center center; //分别是水平和垂直方向上居中。

background-size: cover; //图片大小自适应
```

14. max-width: 940px;  最大宽度。一般不写具体宽度，但可以写最大宽度。

15. div 的水平居中
```
margin-left: auto;
margin-right: auto;
```