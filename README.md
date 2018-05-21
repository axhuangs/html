# html
html面试题

**1.你做的页面在哪些流览器测试过？这些浏览器的内核分别是什么?**
- IE: trident内核 
- Firefox：gecko内核 
- Safari:webkit内核
- Opera:以前是presto内核，Opera现已改用Google Chrome的Blink内核
- Chrome:Blink

**每个HTML文件里开头都有个很重要的东西，Doctype，知道这是干什么的吗？**
>doctype声明不是html标签，它提示浏览器针对于当前页面，使用那个HTML版本进行编写的指令。

在HTML4.01中，doctype声明引用DTD，因为HTML4.01基于SGML。DTD规定了语言的规则，让浏览器能正确渲染页面。而HTML5不基于SGML，所以不需要引用DTD。

**div+css的布局较table布局有什么优点？**
- 记载速度快，结构清晰，页面简洁
- 表现与结构分离，所以在改版时只需要修改CSS文件即可
- 单个页面代码减少，容易优化(seo)，针对搜索引擎更加友好

**img的alt与title有何异同？**
alt ： 当图片不能正常显示时，用alt中的内容，提示图片代表的内容,但是alt属性字符长度必须少于100个英文字符
title : 可以为图片添加提示信息，当鼠标移动到图片上时显示，比alt字符更长，
>当然title还可以用在除了meta,html,head,title,script,base,basefont,param之外的所有标签上。


