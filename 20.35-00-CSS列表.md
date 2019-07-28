**CSS 列表属性允许你放置、改变列表项标志，或者将图像作为列表项标志。**

## CSS 列表

从某种意义上讲，不是描述性的文本的任何内容都可以认为是列表。人口普查、太阳系、家谱、参观菜单，甚至你的所有朋友都可以表示为一个列表或者是列表的列表。

由于列表如此多样，这使得列表相当重要，所以说，CSS 中列表样式不太丰富确实是一大憾事。

### 列表类型

要影响列表的样式，最简单（同时支持最充分）的办法就是改变其标志类型。

例如，在一个无序列表中，列表项的标志 (marker) 是出现在各列表项旁边的圆点。在有序列表中，标志可能是字母、数字或另外某种计数体系中的一个符号。

要修改用于列表项的标志类型，可以使用属性 [list-style-type](http://www.w3school.com.cn/cssref/pr_list-style-type.asp)：

```
ul {list-style-type : square}
```

上面的声明把无序列表中的列表项标志设置为方块。

### 列表项图像

有时，常规的标志是不够的。你可能想对各标志使用一个图像，这可以利用 [list-style-image](http://www.w3school.com.cn/cssref/pr_list-style-image.asp) 属性做到：

```
ul li {list-style-image : url(xxx.gif)}
```

只需要简单地使用一个 url() 值，就可以使用图像作为标志。

### 列表标志位置

CSS2.1 可以确定标志出现在列表项内容之外还是内容内部。这是利用 [list-style-position](http://www.w3school.com.cn/cssref/pr_list-style-position.asp) 完成的。

### 简写列表样式

为简单起见，可以将以上 3 个列表样式属性合并为一个方便的属性：[list-style](http://www.w3school.com.cn/cssref/pr_list-style.asp)，就像这样：

```
li {list-style : url(example.gif) square inside}
```

list-style 的值可以按任何顺序列出，而且这些值都可以忽略。只要提供了一个值，其它的就会填入其默认值。

## CSS 列表实例：

- [在无序列表中的不同类型的列表标记](http://www.w3school.com.cn/tiy/t.asp?f=csse_list-style-type)

  本例演示在CSS中不同类型的列表项标记。

- [在有序列表中不同类型的列表项标记](http://www.w3school.com.cn/tiy/t.asp?f=csse_list-style-type2)

  本例演示在CSS中不同类型的列表项标记。

- [所有的列表样式类型](http://www.w3school.com.cn/tiy/t.asp?f=csse_list-style-type_all)

  本例演示在CSS中所有不同类型的列表项标记。

- [将图像作为列表项标记](http://www.w3school.com.cn/tiy/t.asp?f=csse_list-style-image)

  本例演示如何将图像作为列表项标记。

- [放置列表标记](http://www.w3school.com.cn/tiy/t.asp?f=csse_list-style-position)

  本例演示在何处放置列表标记。

- [在一个声明中定义所有的列表属性](http://www.w3school.com.cn/tiy/t.asp?f=csse_list-style)

  本例演示将所有针对列表的属性设置于一个简写属性。

## CSS 列表属性(list)

| 属性                                                         | 描述                                                 |
| ------------------------------------------------------------ | ---------------------------------------------------- |
| [list-style](http://www.w3school.com.cn/cssref/pr_list-style.asp) | 简写属性。用于把所有用于列表的属性设置于一个声明中。 |
| [list-style-image](http://www.w3school.com.cn/cssref/pr_list-style-image.asp) | 将图象设置为列表项标志。                             |
| [list-style-position](http://www.w3school.com.cn/cssref/pr_list-style-position.asp) | 设置列表中列表项标志的位置。                         |
| [list-style-type](http://www.w3school.com.cn/cssref/pr_list-style-type.asp) | 设置列表项标志的类型。                               |
| marker-offset                                                |                                                      |