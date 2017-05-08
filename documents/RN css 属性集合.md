## RN css 属性集合 ##
react native中可以使用的css属性为 web css属性的子集，对css进行了一定程度的阉割，保留了开发者经常使用的属性，设计上实现了简洁，然而辩证的来看，这样设计也导致很多web开发者初入react native 领域写样式的时候感觉很不舒服！但是本人还是很支持 '属性阉割' 这种设计的，因为它的设计理念和react的理念一致！下面让我们一起看一下在RN中合法的css属性有那些吧！  

1. 定位属性

```css
position: absolute | relative;
top: <number>;  
left: <number>;  
right: <number>;  
bottom: <number>; 
```

2. 边框属性 

```css
borderLeftWidth: <number>;
borderBottomWidth: <number>;
borderRightWidth: <number>;
borderTopWidth: <number>;
borderWidth: <number>;
borderColor: <String>;
borderLeftColor: <String>;
borderRightColor: <String>;
borferTopColor: <String>;
borderBottomColor: <String>;
borderTopLeftRadius: <number>;
borderTopRightRadius: <number>;
borderBottomLeftRadius: <number>;
borderBottomRightRadius: <number>;
borderRadius: <number>;
```

3.边距属性  

```css
marginBottom: <number>;
marginLeft: <number>;
marginRight: <number>;
marginTop: <number>;
marginVertical: <number>;
marginHorizontal: <number>;
margin: <number>; 
paddingLeft: <number>;   
paddingRight: <number>;   
paddingTop: <number>;   
paddingVertical: <number>; 
paddingHorizontal: <number>;   
padding: <number>;  
```
	
4.基本属性
	
```css
backgroundColor: <String>;
width: <number>;
height: <number>;
```
5.flex属性

```css
flex: <number>; 
flexDirection: enum('row', 'column');
flexWrap: enum('wrap', 'nowrap'); 
alignItems: enum('flex-start', 'flex-end', 'center', 'stretch'); 
alignSelf: enum('auto', 'flex-start', 'flex-end', 'center', 'stretch');
justifyContent: enum('flex-start', 'flex-end', 'center', 	'space-between', 'space-around');
```

6.字体相关属性

```css
color: <number>;
fontFamily: <String>;
fontSize: <number>;
fontStyle: enum('normal', 'italic')等;
fontWeight: enum("normal", 'bold', <number>);
letterSpacing: <number>;
lineHeight: <number>;
textAlign: enum("auto", 'left', 'right', 'center', 'justify')
textDecorationLine: enum("none", 'underline', 'line-through', 'underline line-through');
textDecorationStyle: enum("solid", 'double', 'dotted', 'dashed');
textDecorationColor: <string>;
writingDirection: enum("auto", 'ltr', 'rtl');
```

7.图片相关

```css
resizeMode: enum('cover', 'contain', 'stretch');
overflow: enum('visible', 'hidden');
tintColor: <String>;
opacity: <number>
```

8.变换

```css
scaleX: <number>;
scaleY: <number>;
rotation: <number>;
translateX: <number>;
translateY: <number>;
```

9.阴影

```css
shadowColor: <String>;
shadowOffset: <number>;
shadowOpacity: <number>;
shadowRadius: <number>;
```
	

