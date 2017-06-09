# 语法3内容
* 语法3
  * [表格]
  * [水平分隔线]
  * [HTML语法]
  * [GFM语法]
## 表格 demo
#### MarkDown不支持表格，但是表格比较常用，表格是由GFM提供支持的。
##### 用｜号来分开单元格，第二行的横线很重要，听说能设置居中问题。表格里面也能增加MD的其他格式。
- 全表格

|这|表|头|
|----|----|----|
|姓名|年龄|性别|
|张三|10000000|男|
|李四|20000000|女|
- 精简表格  
这|表|头|
----|----|  
姓名|年龄|性别   
张三|10000000|男  
李四|20000000|女  
## 水平分隔线 demo
```HTML
<hr> Horizontal Rule三个减号，三个减号前如果有文字就会变成标题2，解决的方法是空一行
```
---
```HTML
<hr> Horizontal Rule三个星号
```
***
```HTML
<hr> Horizontal Rule三个下划线
```
___
## HTML语法 demo
#### 在MarkDown文件中可以直接识别HTML代码。
<p align="center">我居中了</p>   

```HTML
<!-- 注释也能用 -->
<!--如果MarkDown提供的文本处理格式不够，可以通过HTML代码来实现 -->
```  

## GFM语法 demo
#### github提供支持的特色的md格式

1.task list(勾选的样式)
  - [x] task 1
  - [x] task 2
  - [ ] task 3  
  
2.emoji(markdown支持的表情表示)
  - :floppy_disk:
  - :moneybag:
  - [代码大全]

[表格]: demo3.md#表格-demo
[水平分隔线]: demo3.md#水平分隔线-demo
[HTML语法]: demo3.md#HTML语法-demo
[GFM语法]: demo3.md#GFM语法-demo
[代码大全]: https://github.com/guodongxiaren/README/blob/master/emoji.md