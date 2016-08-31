# README的语法

心血来潮，研究一下github，不然感觉自己很low，哈哈，今天看了一下，有点意思。

## 标题


```html
	# 一级标题
	## 二级标题
	###三级标题
	####四级标题
	#####五级标题
	######六级标题

```
# Hello Word
## Hello Word
###Hello Word
####Hello Word
#####Hello Word
######Hello Word

## 斜体 *Hello Word*
```html
可以使用 * 或 _ 包围文字，例如*Hello World*
```

## 加粗 **Hello Word**
```html
用两个 * 或 _ 包起来的话，达到加粗字体的左右，例如**Hello Markdown**

如果你的 * 和 _ 两边都有空白的话，它们就只会被当成普通的符号
```


## 引用 
```html
引用是使用类似 email 中用 > 的引用方式，例如：> 文字被些字符包围开始，可以在每行上加上“<”，也可以只在首行加上“<”能够达到一样的效果。区块引用可以嵌套（例如：引用内的引用），只要根据层次加上不同数量的 > ：

&gt; 这是第一层引用。

&gt;

&gt; &gt; 这是嵌套的引用块。

&gt;

&gt; 回到第一层。
```

##超链接 [ybkuncom](https://github.com/ybkuncom/)
```html
Markdown 支持两种形式的链接语法： 行内式和参考式两种形式。

不管是哪一种，链接文字都是用 [方括号] 来标记；要建立一个 行内式 的链接，只要在方块括号后面紧接着圆括号并插入网址链接即可，如果你还想要加上链接的 title 文字，只要在网址后面，用双引号把 title 文字包起来即可，例如： [This link](http://example.net/) has no title attribute

如果你是要链接到同样主机的资源，你可以使用相对路径： See my [About](/about/) page for details

参考式的链接是在链接文字的括号后面再接上另一个方括号，而在第二个方括号里面要填入用以辨识链接的标记： This is [an example][id] reference-style link

接着，在文件的任意处，你可以把这个标记的链接内容定义出来： [id]: http://example.com/ "Optional Title Here"

```
##图片：
```html
图片的语法和超链接非常相似。只显示图片：![github](http:// example.com /unicorn.png “github”)；点击图片进入另一个网页：[![image]](http://www. example .com/) [image]: http:// example .com/ example .png “ example “
```
