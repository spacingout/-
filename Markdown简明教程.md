# Markdown简明教程
>本文摘抄于[Markdown 教程](https://hacpai.com/guide/markdown),如有侵权，请速联系，立刻删除。
## ATTENTION
  - `#`后面必须要有空格才会有效果否则就是单纯的井号。 
  - 如果想换行的话，在行尾敲2个以上的空格再敲回车。
  - 想在表格内换行的话只需要打上`<br>`即可，其实这玩意是强制换行符(继承html)在哪都能用。   
>引用文本：Markdown is a text formatting syntax inpired
##语法指导
###普通内容
这段内容展示了一些小的格式：比如:
- **加粗** - `**加粗**`  
-*倾斜* -`*倾斜*`  
-~~删除线~~ - `~~删除线~~`  
-[超链接](http://github.com) -`[超链接](http://github.com)`  
-[username@gmail.com](mailto:username@gmail.com)-
`[username@gmail.com](mailto:username@gmail.com)`
###提及用户
@Vanessa...通过@可以在发帖和回帖里面提及用户，信息提交之后，别提及的用户将会受到系统通知，以便让他来关注这个帖子或回帖。
>NOTE:
>1. @用户名之后需要有一个空格
>2. 新手没有艾特的功能权限 
### 表情符号 Emoji
支持大部分标准的表情符号，可使用输入法直接输入，也可手动输入字符格式。欢迎通过快捷键`Ctrl+/`自动完成输入，并在个人设置中设置常用的表情。  
### 一些表情的例子  
:smile: :laughing: :dizzy_face: :sob: :cold_sweat: :sweat_smile:  :cry: :triumph: :heart_eyes: :relaxed:
:+1: :-1: :100: :clap: :bell: :gift: :question: :bomb: :heart: :coffee: :cyclone: :bow: :kiss: :pray: :anger:  
### 大标题 -Heading 3  
你可以选择H1到H6，使用## (N)打头。  
> 别忘了，#后面需要有空格！！！！   
#### Heading 4
##### Heading 5
###### Heading 6
### 图片  
```
![alt 文本](http://image-path.png)
![alt 文本](http://image-path.png "图片 Title 值")
![设置图片宽度高度](http://image-path.png =300x200)
![设置图片宽度](http://image-path.png =300x)
![设置图片高度](http://image-path.png =x200)
```
### 代码块
#### 普通 
```
*emphasize*    **strong** 
_emphasize_    __strong__ 
var a = 1 
```
#### 语法高亮支持  
如果在`之后随意更改语言名称，可以有语法高亮的效果，比如：  
####演示python代码高亮
```python
import tensorflow as tf
import numpy as np
```
>Tip: 语言名称支持下面这些： `ruby`,`go`, `js`, `html`, `erb`, `css`, `coffee`, `bash`, `json`, `yml`, `xml` ...     
### 有序、无序列表    
#### 无序列表   
  - JAVA      
  - Spring     
  - IoC 
#### 有序列表 
1. Node.js         
    1. Express     
    2. Koa     
    3. Sails   
### 表格 

如果需要展示数据什么的，可以选择表格。       

| header 1 | header 3 |
| -------- | -------- |
| cell 1   | cell 2   |
| cell 3   | cell 4   |
| cell 5   | cell 6   |
  

### 段落

留空白的换行，会被自动转换成一个段落，会有一定的段落间距，便于阅读。     

请注意后面 Markdown 源代码的换行留空情况。

### 数学公式      
如下图，在codecogs中，输入公式然后把下面出现的html标签按照下面进行粘贴即可 (实际上还是html的语法)，别忘了多打几个空格。

![](http://latex.codecogs.com/gif.latex?\\frac{1}{1+sin(x)})      
