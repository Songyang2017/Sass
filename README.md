# Sass基础知识  
一、安装ruby  

二、sass语法   

1，变量以$开头  

2，计算功能    
```css 
font-size:(30px/2)  
```
3,标签嵌套  
```css
ul{  
background-color:black;  
li{  
color:red;  
}  
}  
```
4,伪类使用  
```css
&:hover{  
color:white;  
}  
```
5，继承  
```css
@extend .left;  
```

6,外部文件的插入 
```css
@import "../css/base.css";  
```

7,关于注释  
```css
// 不会出现在css中 ctrl + /  
/* 不会出现在css中 */  ctrl+shift + /  
/* 不会出现在css中 */  注释出现在css中 
```
在路径：  
c:Ruby\lib\ruby\gems\2.3.0\gems\sass3.4...\lib\sass中找到engine.rb打开，在所有的require之后添加代码  
   
Encoding.default_external = Encoding.find('utf-8')  
