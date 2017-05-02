##flex布局与传统布局##

* css中最重点的内容莫过于layout, css布局基于[盒模型](http://baike.baidu.com/link?url=pHH5DTPKpgl0NlSCstelGkFUNoSV_j7MuOjXhTMc_-xla04PWz3IqeHLtS0GbpEk3vn4oICmkfWxdmO8hhOvTdOra-OyVgEQjXzdiJLYo08BtKhwGqZ6_BHNBmfJSONP)；
* 布局有文档流布局、定位布局、浮动布局、表格布局、flex布局5种；
* flex布局是 **高效·简单·响应式** 的布局方案，为移动而生；

flex布局的诞生是W3C于2009年提出的一种新的布局方案，意在解决传统布局中的痛点问题，flex解决垂直居中更是小菜一碟，而且flex可以更方便地实现各种页面布局，废话不多说，让我们一起去见证一下它的神奇之处吧。

-----------

小插曲：下面简单介绍下盒模型，详情请看[W3C官方文档](http://www.w3school.com.cn/css/css_boxmodel.asp)。

盒模型有标准盒模型 和IE盒模型之分，2种盒模型的主要区别在于元素的width 和height 上（**W3C盒模型认为**：*元素的with和height属性仅仅指content area。*  
**IE盒模型认为**：*元素的with和height属性 由content area + padding + border组成*）

**W3C盒模型：**  
元素宽 = width + left padding + right padding + left border + right border + left margin + right margin  
元素高 = height + top padding + bottom padding + top border + bottom border + top margin + bottom margin  
**IE盒模型：**  
元素宽 = left margin + width + right margin  
元素高 = +top margin + height + bottom margin

css3.0中新增了一个属性(box-sizing)，可以对盒模型进行定义。  
`box-sizing: content-box`(W3C的标准盒模型)   `box-sizing: border-box` (IE盒模型)




