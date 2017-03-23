---
title: Markdown语法
---

## Markdown

> * 什么是Markdown
> * Markdown语法
> * 例文

你可以使用vim工具直接编辑md文件，也可以用记事本打开md文件编辑你的文章，也可以Markdown的编辑器编写，有很多在线的编辑器，更有不少客户端的编辑器，我是Mac系统，用的是Vim编辑器。，还比较好使。Windows系统下，你可以自己找一下，应该也会有很好用的编辑器。

### 什么是Markdown

Markdown 是一种轻量级标记语言，创始人为约翰·格鲁伯和亚伦·斯沃茨。它允许人们“使用易读易写的纯文本格式编写文档，然后转换成有效的XHTML文档”。 ——维基百科 

先简单介绍一下，Markdown的语法，具体怎么用，我相信大家一看例文就马上明白了。

### Markdown语法

> 1、分段： 两个回车
> 2、换行 两个空格 + 回车
> 3、标题 #~###### 井号的个数表示几级标题，即Markdown可以表示一级标题到六级标题
> 4、引用 >
> 5、列表 *，+，-，1.，选其中之一，注意后面有个空格
> 6、代码区块 四个空格开头
> 7、链接 ``[文字](链接地址)``
> 8、图片 ``[图片说明](图片地址)``，图片地址可以是本地路劲，也可以是网络地址
> 9、强调 **文字**，__文字__，_文字_，*文字*
> 10、代码 ``，``
> 11、代码块 
``` css
.modal-open {
  &, body {
    overflow: hidden;
    height: 100%;
  }
}
```
> 12、高效绘制流程图
```flow
st=>start: Start
op=>operation: Your Operation
cond=>condition: Yes or No?
e=>end

st->op->cond
cond(yes)->e
cond(no)->op
```
> 13、代码高亮 payth
```python
@requires_authorization
class SomeClass:
    pass

if __name__ == '__main__':
    # A comment
    print 'hello world'
```
> 14、js语法高亮
```js
/*注释*/
function module() {
	var path = [];
	for(var i = 0; i < arguments.length; i++) {
		path.push(arguments[i]);
	}
	return path;
} 
```

### 例子
> 在线编辑器例文:[在线编辑器](https://www.zybuluo.com/mdeditor)
> Mou编辑器:[Mou下载地址](http://mouapp.com/)
