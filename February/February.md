


> Written with [StackEdit中文版](https://stackedit.cn/).
>
> **测**了*一次*小**试**  
> **测试** ~~使用~~  
> + ***环境***  
> + 呼叫

>  # 正文开始  
>   ## 章节标题  
>   使用 # 来添加标题（记得#后带空格）
>   **问题** ：是否在标题那一行均是标题的格式？能否写入正文格式的内容。  
>   
>  ## 分割线  
>  使用 *** 或者 - - - ，然后换行。
>  
>  ## 粗体、斜体、删除线  
>  加粗用 **，斜体用* ，删除线用~。（注意不要带空格）
>  
>  ## 引用  
>  >  一层应用：使用>
>  >>二层引用：使用>>  
>  仍在应用中 
> >
> >退回一层引用  
> 退出引用

## 列表  
使用 + ，- ，* 生成标签 （要带空格）怎么更改标签的间距？
* 标签1  
+ 标签2  
- 标签3  

1. 标签1
2. 标签2

*** 
 
### 列表多层嵌套  
+ 一级1
+ 一级2  
  * 二级1  
    - 三级1  
      + 四级1  
   * 二级2 
+ 一级3  （很麻烦，每层标签必须对齐，增加空行数可以调整标签的行距）

## 超链接 
* 普通超链接：< http: //+具体网址 >  例如：<https://stackedit.cn/app#>  
* 带标题的超链接：[ 标题 ]（http: //+ 具体网址）例如 [StackEdit](https://stackedit.cn/app#)
* 文档之间的链接（一般建议是Markdown文件）：
	+ **绝对路径**：[ 标题 ]（文件夹1/.../文件）例如 [Readme](/README.md) 
	+ **相对路径**：[ 标题 ]（.././文件）使用`/ ./ ../`来显示路径 
	<font color = red>注意1：描写该链接时，整个部分必须在一行上，换行的话会不起作用，可能是添加了空格的原因
	注意2：括号是英文括号，不要写成中文括号
	注意3：相对链接更便于用户克隆仓库。 绝对链接可能无法用于仓库的克隆，**建议使用相对链接引用仓库中的其他文件**。</font>
* 自定义位点：可使用标准 HTML 定位点标记 (`<a name="unique-anchor-name"></a>`) 为文档中的任何位置创建导航定位点。 为了避免不明确的引用，请对定位点标记使用唯一的命名方案，例如向 name 属性值添加前缀。
	```
	
	```

## 代办事项列表  
 - [ ] 第一行  
 - [ ] 第二行
 - [x] 第三行 

## 创建表格
|Option | Description |
|:--:|:--:|
|data|data|
|path|path|

## 灰色底框  
```代码环境：`code` ```  （类似verb）
``` 
多行代码环境：```code``` 指定代码语言可以高亮，例如Python
具体形式：```python <br/> code ```
```
## 文本标记  
``` markdown 
<u>文本</u>	或者 <ins>文本</ins>	添加下划线 
<mark>文本</mark>				文字标黄
<font color = red>文本</font> 	字体颜色
<sub>文本</sub>					下标文字
<sup>文本</sup>					上标文字
```
<u>文本</u>  <ins>文本</ins> <mark>文本</mark> <font color = red>文本</font> <sub>文本</sub> <sup>文本</sup>

## 数学环境
下面的所有语法都是在数学环境中的（注意不要多加空格）：
### 盒子 
$\boxed{文本}\colorbox{red}{文本}$

## 字体样式、大小、颜色 
```
<font face ="楷体" size = "15"> 例子 </font>
<font size="10" color = violet>例子 </font>
```
``<font face ="楷体" size = "15"> 例子 </font>``
<font face ="楷体" size = "5"> 例子 </font>   
<font size="3" color = violet>例子</font><font size="6" color = violet>例子</font> <font size="7" color = violet>例子</font><font size="8" color = violet>例子</font>  
**字号参数应该从1到7，7之后的数都视作7。**  

## 对齐与换行
```
---该行的内容全部都以这种方式对齐
<p align = "left">		左对齐  
<p align = "center">	居中对齐  
<p align = "right">		右对齐
```
<p align = "right">		左对齐 
<p align = "center">	居中对齐  
<p align = "left">		右对齐  

`<br/>`为强制换行符 ，例如：<br/>换行


## 问题
1. 怎么调整空格的距离大小？ $\qquad$  
2. latex数学环境``\)
 

 

<!--stackedit_data:
eyJkaXNjdXNzaW9ucyI6eyJrZ0drUlVmbk4xUGI1WVBkIjp7In
RleHQiOiLmoIfpopgiLCJzdGFydCI6MTQyLCJlbmQiOjE0NH0s
IktoR256cTVaa01McGlJbGsiOnsic3RhcnQiOjMyMSwiZW5kIj
ozMjMsInRleHQiOiLlvJXnlKgifX0sImNvbW1lbnRzIjp7Imkx
WHpRbU5OdHhjc0RCdVoiOnsiZGlzY3Vzc2lvbklkIjoia2dHa1
JVZm5OMVBiNVlQZCIsInN1YiI6ImdoOjIwMTA3OTk0OCIsInRl
eHQiOiLmnIDlpJo25LiqIyIsImNyZWF0ZWQiOjE3NDA3NDE5OD
g0MTl9LCJDczlhZURpN0dDc2N4MkxXIjp7ImRpc2N1c3Npb25J
ZCI6IktoR256cTVaa01McGlJbGsiLCJzdWIiOiJnaDoyMDEwNz
k5NDgiLCJ0ZXh0Ijoi6KaB5Lil5qC85rOo5oSP57yp6L+b57qn
5YirIiwiY3JlYXRlZCI6MTc0MDc0MzU4MzkxM319LCJoaXN0b3
J5IjpbLTI5NzQwMTg3NCwtMTkyNzU1NDk1OSwtODk3NTgzNTk5
LDE4NTE4MDgxMzAsLTEyOTIyNzM3MDksOTczMDY0NTEsLTEzND
czNDk0MywxOTgzMTA5MTQsNjY3Njk1NDY1LDE3MDQ3MjAyNjUs
MTQyOTIwMDA1MSwtMTEwMzA0MDQ2MSwxOTMzOTE0NTE0LDE3OT
M3NTcyNTcsMTMxNTE2ODQxMiwxMjEyMjk0MDgsLTExNzIxMTYy
MDMsMTU2MTg3OTI1LDEwNzc3MTMzOTksMTM5NjU0NTYzMF19
-->