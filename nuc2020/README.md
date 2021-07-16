***
***
***
<h1>本页所有内容均已优化后存放于本人网站中，待备案审核通过后会在此展示网址，谢谢</h1>
***
***
***

# Lesson5 - 周三 （7.16）
***
## 其它
1  如果用Bootstrap，所有地方都用，建议不要混用
2  web前端要深学CSS
3  Java开发，对CSS要求不高
《CSS权威指南》，CSS要学好的，多临摹，要经验
4  网页中图片位置为服务器相对路径/外链[图床]
大学学习=大学技术+公司技术+社会行业信息
c语言基础不足怎么办
《c Primer Plus》 5th
***
## 一. Bootstrap表格
## 二. 任务:个人存款计算软件界面




***
##






# Lesson4 - 周三 （7.15）
***
## 其它
CSS开发心理：边写边预览
1. CSS选择器[标记选择器,id选择器,class选择器]
2. 代码位置[页内样式，行内样式，外部样式]
3. 边框样式[边框变红border: 1px solid red]
***
## 一. CSS显示
1. display[隐藏释放区域]
2. visibility [隐藏，不释放区域]
***
## 二. CSS浮动[float]
1. 主要用于：网页布局[CSS+DIV]
2. 不浮动为竖的，浮动为横的
3. CSS+DIV做网页布局离不开浮动
***
## 三. Bootstrap技术
### 1. 介绍
- Twitter公司发明的技术
- 用Bootstrap技术做的网页，屏幕大小自适应
- 移动优先[随智能手机而来]
- Bootstrap技术基于HTML,JS,CSS
- Bootstrap本质：CSS样式库
- Bootstrap不是编程语言，是一种技术
### 2. 如何用
- 把Bootstrap下载后，复制到自己项目中
- 直接用CDN[内容分发]
- 必须联网用
### 3. 如何学
- 看官方文档
### 4. 原理
- 网格系统[屏幕分为12列，使用者可以自己组合]
- 使用Bootstrap后，CSS不用自己写
### 5. 如何在github上搭建网站
略，详见本人博客：https://xuegao-tzx.top（备案中，暂时无法访问）
***
***
# Lesson3 - 周三 （7.14）
***
## 0
前端：
设计工程师： PS UI
开发工程师： JS CSS HTML
***
## 一.CSS是什么
1. 层叠式样式表，简称为样式(Cascading Style Sheets)
2. 由W3C制订，最新版CSS3
3. CSS由浏览器执行
4. 美化网页(HTML不具备美化功能)
***
## 二.CSS选择器(*****)
1. 标记选择器
2. id选择器
3. class选择器

***
## 三.CSS代码放置位置
1. 页内样式：head之间，用style标记
2. 行内样式：标记style属性里(优先级最高)
3. 外部样式：放在单独CSS文件中，用link标记引入
***
## 四. 开发常用样式
1. 背景颜色(background-color)
2. 文本样式(color\text-align\text-decoration)
3. 字体样式(font-family\font-size)
网页上文字默认16px;工程上是12px/14px
4. 超链接样式(:hover)
5. 表格样式(细线边框border-collapse,collapse)
6. 边框样式(边框变黑border: 1px solid black;)
***
## 五. 盒子模型
1. 与网页布局有关
2. 外边距margin，内边距padding,内外边距相对，看在哪，4方向
***
## 六.登录网页
1. 用到盒子模型
2. HTML表单元素
***
***
# Lesson2 - 周二 （7.13）
***
## 一.昨日总结
HTML标记：成对出现<br>
head头部<br>
form表单<br>
table表格<br>
body‘身体’<br>
name‘定义名字（可以重复，单选按钮不可以重复）’<br>
HTML本身不区分大小写<br>
checked默认选择（单选）<br>
selected默认选择（多选）<br>
value="默认值"<br>
align="位置"（center居中）<br>
input后为标记的属性<br>
网页动态变化：JS<br>
字变色：CSS<br>
***
## 二.HTML表格(*****)
```html
	<table></table>表格标记
	<tr></tr>表格行
	<td></td>表格列
	在<table>里放<tr>，在<tr>里放<td>
	合并单元格使用：<td colspan="合并单元格数目">你的信息</td>
```
***
## 三.HTML超链接
1. 链接可以到自己本机的网页，也可以是外部网站
2. 语法
```html
	<a href="网址">介绍</a>
```
***
## 四.HTML图片
1. 语法
```html
	<img width="宽" heigh="高" src="图片名字">图片介绍
```
2. 图片带链接
```html
	<a href="https://xxx" ><img width="宽" heigh="高" src="图片名字">图片介绍</a>
```
***
## 五.HTML列表
有序列表无序列表
```html
	有序列表<ol></ol> 无序列表<ul></ul> 列表项<li></li>
```
***
## 六.标题
HTML共6级标题：H1-H6
```html
<hn>n级(1<=n<=6)</hn>
```
***
## 七.段落和DIV块
```html
	<p>这是个段落</p>
	<div>这是个块</div>
	<span>用户名不为空！</span>
	<span>密码为6位！提示</span>
	<label>这是个标签</label>
```
***
## 八.HTML颜色
颜色表示2种：颜色名，颜色值（16进制，以#开头）
颜色是由3种色调配成：RGB
```html
<body bgcolor="#3B99FC"></body>
```
***
## 九.字符实体
HTML中空格表示：&nbsp;
HTML中人民币表示：&yen;
HTML中版权号表示：&copy;
HTML中大于号表示：&gt;
***
## 十.iframe框架
‘套用’
```html
<iframe width="800" height="1000" src="https://xxx" name="mycontent"></iframe>
```
***
## POST与GET区别？
1. post方式提交表单，表单数据在地址栏不显示，较安全
	get方式提交表单，表单数据在地址栏显示，不安全
2. post提交数据，大小不限；get一般为2K
	一般用post
***
***
# Lesson1 - 周一 （7.12）
***
## 问题总结
[学习链接](https://www.runoob.com/)
***
##手写笔记
![图1](https://z3.ax1x.com/2021/07/12/WFKQfg.png)
![图2](https://z3.ax1x.com/2021/07/12/WFK1pQ.png)
![图3](https://z3.ax1x.com/2021/07/12/WFK3lj.png)
***
## 一.Maekdown学习
1. 是什么
写软件文档

2. 什么时候用
记笔记，写介绍
***
## 二.HTML介绍
1. 是什么
叫做：超文本标记语言
HTML5(H5)

2. 执行软件
浏览器(Chrome,Firefox,Opera,Safari,Edge)

3. 为什么
做web项目，界面用

4. 谁来用
后端开发，web前端，网页美工(UI)

5. 什么时候用
需要时

6. 用在哪
用在网页上，搭建网页结构/元素

7. 怎么用
实际使用
***
## 三.HTML标准
	W3C(国际万维网组织)制订
	最新：HTML5
***
## 四.HTML表单开发(*****)
1. 表单怎么写
```html
<form action="此处写要跳转的网页名字">
	<!--写详细内容-->
</form>
```
2. 文本框怎么写
```html
文本框<input type="text" placeholder="此处为文本框占位字符，不写为空">
```
3. 密码框怎么写
```html
密码<input type="password" placeholder="请输入密码，此处为密码框占位字符，不写为空">
```
4. 单选按钮怎么写
```html
单选按钮<input type="radio" name="gender">单选按钮详情
```
5. 下拉选择怎么写
```html
下拉选择<select>
<option>1</option>
<option>2</option>
<option>3</option>
<option>写下拉选择内容</option>
</select>
```
6. 复选框怎么写
```html
复选框<input type="checkbox">1
<input type="checkbox">2
<input type="checkbox">3
<input type="checkbox">写复选框内容
```
7. 文本域怎么写
```html
文本域<textarea rows="你的行数" cols="你的列数">
	我是田梓萱，Hello WEB!此处为占位字符，不写为空
</textarea>
```
8. 文件上传怎么写
```html
上传简历<input type="file">
```
9. 提交按钮怎么写
```html
<input type="submit" value="注册提交">
```
10. 重置按钮怎么写
```html
<input type="reset" value="清空重填">
```
11. 跳转网页怎么写
```html
<form action="此处写要跳转的网页名字">
```
***
## 五.任务
写12306注册表单,见12306zy.html