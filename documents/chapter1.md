## 为什么要学习flex

1.flex是什么？  

flex是Flexible Box的简称，指`弹性布局`其实flex也只是一种布局方式而已，和float布局，position布局一样，服务于前端开发的css。

* flex是一种基于盒模型的布局方式，与传统布局有着天壤的差别；
* flex为移动端布局而生；
* flex解决人们的痛点问题，特别是在水平居中垂直居中方面大显神通；

----------------  

2.谁需要学习flex? 

- 致力于前端开发的开发工程师  
- 致力于sass less 等css开发  
- 致力于移动端开发  
- 致力于react native 项目开发

3.flex的兼容性问题  

 * [关于flex的W3C规范](http://dev.w3.org/csswg/css-flexbox-1/)
 * [浏览器兼容性问题](http://caniuse.com/#feat=flexbox)

 > ####总结如下：   
 > IE10+ 完全支持 IE10需要`-ms-`前缀  
 > Android 4.3以下 需要 `-webkit-` 前缀
 > Safari8 以下需要 `-webkit` 前缀
 > IOS8.3 以下 需要`-webkit` 前缀
 
 所以flex兼容性写法也很简单，加上 *浏览器前缀* 即可。  
 
 ```css
 .flex-box-demo {
 		display: -ms-flexbox;	 
		display: -webkit-flex;  
		display: flex;
		-webkit-flex-wrap: wrap;
		-moz-flex-wrap: wrap;
		-ms-flex-wrap: wrap;
		-o-flex-wrap: wrap;
		flex-wrap: wrap;
 }```
 

 
 
 
