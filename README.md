# README

学了HTML+CSS基础，写一个百度搜索首页的静态页面，不能做任何的动态交互。

在这个过程中验证自己的所学。以及发现自己的一些小问题：

对html行内元素和内联元素的概念和特点不够清晰，导致对标签设置css样式时达不到自己想要的效果。

以下对行内元素和内联元素的总结如下：

- 块级元素：总是占据一行。高度、行高、外边距、内边距都可控。
  	宽度是 它容器的100%，但可通过css样式改变。可容纳内联元素和其他元素。
  	常见的块级元素：div dl form h1-h6 hr ol ul p table
- 内联元素：和其他元素在同一行，并不自己占据一行。高度、宽度不可控。
  	外边距margin只有左右能起作用。内边距可以起作用。
  	宽度就是它的文字或它图片的大小，不可改变。它只能容纳文本或者其他内联元素。
  	常见的内联元素：a b br em i img input lable span strong textarea

写完之后在Chrome浏览器运行显示的页面如:

![](https://github.com/sisi-yuan/BaiduSearch/raw/master/final.png)



