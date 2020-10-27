### 1. 谈谈你对Web标准的理解。

```
WEB标准不是某一个标准，而是一系列标准的集合。

•   网页主要由三部分组成：

•   1. 结构（Structure）结构化标准语言主要包括XHTML和XML

•   2. 表现（Presentation）表现标准语言主要包括CSS

•   3. 行为（Behavior）

•       行为标准主要包括对象模型（如W3C DOM）、ECMAScript

•       并要求这三部分分离。

•       这些标准大部分由W3C起草和发布，也有一些是其他标准组织制订的标准，比如ECMA（European Computer Manufacturers Association）的ECMAScript标准。
```

### 2、<img/>标签上title与alt属性的区别是什么?

```
alt 图片非正常加载时的提示性文字

title 鼠标控制时提示性文字
```

### 3、锚点的作用是什么？如何创建锚点？

```
锚点是文档中某行的一个记号，类似于书签，用于链接到文档中的某个位置。

当定义了锚点后，我们可以创建直接跳至该锚点（比如页面中某个小节）的链接，

这样使用者就无需不停地滚动页面来寻找他们需要的信息了。

在使用<a> 元素创建锚点时，需要使用name 属性为其命名，代码如下所示：

<a name=”锚点名”>锚点一</a>

然后就可以创建链接，直接跳转到锚点，代码如下所示：

<a href=”#锚点名”>回到锚点一</a>
```

### 4、link和@import的区别是？

```
（1）link属于XHTML标签，而@import是CSS提供的;

（2）页面被加载的时，link会同时被加载，而@import引用的CSS会等到页面被加载完再加载;

（3）import只在IE5以上才能识别，而link是XHTML标签，无兼容问题;

（4）link方式的样式的权重 高于@import的权重.
```

### 5、cellpadding与cellspacing有何区别？

```
cellpadding：代表单元格边框到内容之间的距离（留白）---单元格边距



cellspacing：代表单元格间距，以及和table边框之间的距离
```

### 6、命名格式

```
1、可以由字母、数字、下划线、连接符组成

2、必须是以字母开头，

3、不可以出现中文

4、见名知意，驼峰命名法（除首字母以外的所有字母的首单词，均大写：xiaoKeAi）
```

### 8、元素分类

```
块级元素--block---独占一行，可设置宽高

    - address - 地址

    - blockquote - 块引用

    - div - 常用块级容易，也是 css layout 的主要标签

    - dl - 定义列表

    - ul-无序列表

    - ol- 有序列表

    - li- 列表项

    - dd- 自定义列表项

    - dt - 列表描述项

    - fieldset - form 控制组---表单分组

    - form - 交互表单

    - h1 - 大标题

    - h2 - 副标题

    - h3 - 3 级标题

    - h4 - 4 级标题

    - h5 - 5 级标题

    - h6 - 6 级标题

    - hr - 水平分隔线

    - p - 段落

    - pre - 格式化文本

    - table - 表格

  行内元素----在一行内显示，没有宽度和高度

    - a - 锚点

    - b - 粗体 (不推荐)

    - code - 计算机代码 (在引用源码的时候需要)

    - em - 强调，倾斜

    - font - 字体设定 (不推荐)

    - i - 斜体

    - label - 表单标签

    - small - 小字体文本

    - big  - 放大字体

    - span - 常用内联容器，定义文本内区块

    - strike - 中划线

    - s - 删除线

    - strong - 粗体强调

    - sub - 下标

    - sup - 上标

    - u - 下划线

 行内块元素

 可以在一行显示的，可设置宽高的容器

    - img - 图片

    - input - 输入框

    - textarea - 多行文本输入框

    - td - 单元格

    - select - 项目选择
```

### 9、隐藏元素的方法

```
1、display:none 不生成盒子，影响其他盒子的布局

2、visibility:hidden  生成盒子，不影响其他盒子的布局，只是从视觉上移除盒子

        等于留出了一块空白区域，而 display:none属性会使这个对象彻底消失
```

### 10、溢出文本以省略号显示

```
<!DOCTYPE html>

<html>

    <head>

        <meta charset="UTF-8">

        <title>文本溢出以省略号显示</title>

        <style type="text/css">

            p{

                width: 200px;

                height: 100px;

                border: 1px solid chartreuse;

                /*文本一行显示*/

                white-space: nowrap;

                /*溢出文本隐藏*/

                overflow: hidden;

                /*溢出文本省略号显示*/

                text-overflow: ellipsis;

            }

        </style>

    </head>

    <body>

        <p>

            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste asperiores               nisi quae mollitia maiores amet exercitationem nam ullam ipsam architecto               liberoper

        </p>

    </body>

</html>
```

### 11、在块级元素里使行内元素垂直居中

```
块级元素设置

    height：；

    line-height：；

    此处行高的值需等于高
```

### 12、简述display的值和作用

```
display--转换元素显示方式

    block  块级元素

    inline 行内元素

    inline-block 行内块

    none   元素隐藏
```

### 13、浏览器的内核分别是什么?

```
IE浏览器的内核Trident、Mozilla的Gecko、Chrome的Blink（WebKit的分支）、Opera内核原为Presto，现为Blink；
```

### 14、HTML5 新的 DocType 和 Charset 是什么？

```
<！DOCTYPE html>----声明文件

<meta charset=”UTF-8”>---编译语言
```

### 15、HTML5中canvas是什么？

```
Canvas 元素用于在网页上绘制图形，该元素标签强大之处在于可以直接在 HTML 上进行图形操作
```

### 16、iframe有那些缺点？

```
*iframe会阻塞主页面的Onload事件；

*iframe和主页面共享连接池，而浏览器对相同域的连接有限制，所以会影响页面的并行加载。

使用iframe之前需要考虑这两个缺点。如果需要使用iframe，最好是通过javascript

动态给iframe添加src属性值，这样可以可以绕开以上两个问题。
```

### 17为什么建议设置背景图像的同时还设置背景颜色？

```
一般建议在使用背景图像的同时提供background-color属性，并且将其设置为和图像主要颜色类似的颜色。这样，如果正在加载页面，或者因为各种原因无法显示背景图像时，页面可以使用这种颜色作为背景色。
```

### 18、内联元素可以实现浮动吗？

```
在CSS 中，任何元素都可以浮动。浮动元素会生成一个块级框，而不论它本身是何种元素。因此，对于内联元素，如果设置为浮动，会产生和块级框相同的效果。
```

### 19、哪些属性可以继承？

```
CSS中可以继承的属性如下：



1）文本相关属性：font-family、font-size、font-style、font-variant, font-weight、font、letter-spacing、line-height、text-align、text-indent、text-transform、word-spacing、color；

2）列表相关属性：list-style-image、list-style-position、list-style-type、list-style；

3）表格相关属性：border-collapse、border-spacing、caption-side、table-layoute；

4）其他属性：Cursor、visibility。
```

### 20、清除浮动的几种方式

```
1.使用空标签清除浮动 clear:both（理论上能清楚任何标签，，，增加无意义的标签）



2.使用overflow:auto（空标签元素清除浮动而不得不增加无意代码的弊端,,使用zoom:1用于兼容IE）



3.是用afert伪元素清除浮动(用于非IE浏览器)
```

​    "