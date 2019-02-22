# -
造作前端首页
总结知识

理清页面版心

ul 如何在 div 里面显示居中
 有两种方法
 第一 可以将ul 设置成 display: inline-block; 然后给 ul 的父元素添加 text-align: center样式;
 第二 设置 ul 的宽度，并且让 ul 的margin-left和margin-right都为auto

如何让 a标签在 div 中水平居中
  水平居中我们可以使用text-align: center;
	在a标签里面转换成display: inline-block;
	再者 margin:0px 5px;
	最后在父类里面添加text-align:center;
	这样可以实现多个a标签并排实现居中
