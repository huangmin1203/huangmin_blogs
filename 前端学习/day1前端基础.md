1、按盒子布局 .html
1）div 代表一盒子
    也可以控制整个盒子的位置，例如，直接定义类名，描述一个样式
2）span :放小东西，小图标
eg:<span class="sep">|</span>

3）标签 a:盒子里的内容，加链接直接在a标签里面加
eg: <a href="url">标签名</a>

4）添加图片
作为一个独立的盒子
格式：<img class="car_left" src="./picture/car_left.png" />


2、css样式
1）浏览器的盒子是带默认的样式
处理方式：把涉及到的样式均清空，自己写样式，兼容不同浏览器的显示
html, body, div, p, span, a, li, ul, ol {
    margin: 0; 
    padding: 0;
    text-decoration: none;
    color: #333;
}

2)定义单个标签/一组标签
.类名{

}

3)伪类   在任何选择器后加类名
eg:    a:hover{

       }
4)布局 flex
 {
    display: flex;#表明是弹性布局
    flex-direction: row;#盒子整体表示布局从左到右显示，可替换多值
    justify-content:space-between;
    #盒子水平对齐方式，可替换多值
    align-items: center;
    #盒子里垂直对齐
        
 }


 5）.类名a:hover 类名b {

 }

 类名a像一个盒子，里面有很多元素，当我鼠标移入里面的b标签时，会显示hover设置的样式格式
:hover代表鼠标移入

3、常用操作键
option+shift+f 格式化
command+d    选中所有相同的内容

Flex布局
https://www.w3school.com.cn/css/css3_flexbox.asp
可以代替inline-block、浮动等布局方式


![](./../assets/images/day1_pic.png)