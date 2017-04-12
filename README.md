# summary-of-HTML-CSS some notes for study ### HTML基本语法 ### HTML文档结构 1\. 声明文档类型 2\. 3\. a) <title>网页标题</title> b) <meta> 元数据 4\. a) Body属性：bgcolor 背景颜色 i. 颜色可以用关键字表示：red、green、blue…… ii. 可以用颜色值代码：#ff0000 十六进制的RGB颜色代码 R：red 红 G：green 绿 B：blue 蓝 三原色 # ff 00 00 1,2,3,....9,a,b,c...f R G B #ffffff #000000 #999966 #333333 形如 #AABBCC 的颜色值，可以在CSS中简写为#ABC #ff0000=#f00 #336699=#369 #f0f0f0 b) 转义字符用于表现网页中的特殊字符   空格 ® 注册商标 & &符号 XHTML推荐用转义字符表达页面中的特殊字符。 c) 文本样式：用于制作特殊样式的文本。
强制换行 强制不换行 、、、…… XTHML不推荐 XHTML推荐用、 标题字样式： n=1,2,3,4,5,6 正文：水平线：

* * *

width 宽 size 高 color 颜色 居中标签：XTHML不推荐 分区标签：块分区元素 <span></span>行内分区元素 预格式化标签：让网页中的文字与源代码中格式一样 d) 块元素：独占一行，与上下内容会自动换行 div、hn、p 行内元素：不会换行，一行中可以放多个行内元素 span、b、u、s、…… e) 文本样式标签： color 文字颜色 face 字体 size 字号 XTHML不推荐 f) URL：统一资源定位器，也就是路径 路径的表达方式有两种： （1）绝对路径 http:// www.sohu.com /images/1/ page.jpg 协议名+ 主机名 +目录名 +文件名 用于指向另一个主机上的文件或是互联网上的某个网址 （2）相对路径 在同一级目录下，直接写文件名 在子文件夹下，写“文件夹名/文件名”，例如images/page.jpg 在上一级目录，写../ 一个../表示向上一级。例如 ../../images/page.jpg 只能用来指向本站点内的文件 g) 图像： 属性：src 图像路径 width 宽度，可以为像素或百分比。只指定宽度表示定宽，高度会等比例自动调整 Height 高度，可以为像素或百分比。只指定高度表示定高，宽度会等比例自动调整 Alt 替代文字，当图像无法显示时，显示替代文字。会被搜索引擎抓取 Title 说明文字，鼠标指在图像上时显示。会被搜索引擎抓取 h) 链接：<a>添加链接的内容</a> 链接、超链接、连接 link、HyperLink 属性：href 链接到的路径 Target 链接打开的浏览器窗口，默认为_self，_blank为新开窗口 Name 命名，创建一个命名锚记，然后可以链接指向该锚点。 命名锚记 <a name="”name”"></a> 可以为空，中间不包含内容 使用href=#name 链接到命名锚记； 使用href=”page.html#name” 链接到指定页面的命名锚记 Title 为链接添加描述文字 链接可以指向图片、文档、压缩文件、多媒体文件等，也可以指向电子邮箱 邮件链接：mailto:xxxx@126.com?subject=hello! 空链接：# 会让页面自动跳到最顶端 Javascript:; 空javascript语句，可作为空链接使用。 i) 表格：

属性：width、 height、 bgcolor、 background、 Boder：边框宽度 Bordercolor：边框颜色 Bordercolordark 暗边框色 bordercolorlight 亮边框色 如果要实现边框凹陷，单元格突出的效果，需要将light设置为深色，dark为浅色。（仅支持旧版本的IE）、 Cellspacing：单元格间距 Cellpadding：单元格填充 Align：表格与浏览器的相对对齐方式 单元行： 属性：不推荐为tr加高、背景色等属性 单元格： 属性：width、height、bgcolor、background Align：单元格内容水平对齐方式 Valign：单元格内容垂直对齐方式 Colspan：跨列，即合并同一行的其它单元格 Rowspan：跨行，即合并同一列的其它单元格 表格标题：caption 只能有一个，并只能位于标记下方 表头：th 位于tr标签内，可替代td，文字会加粗 表格行分组标签：thead、tbody、tfoot 用于对表格内容进行分组管理 j) HTML5结构标记

<header></header>

页眉（头部内容） 可重复使用，利用率较高内容（内容分块） 可重复使用，利用率较高底部、页脚 可重复使用，利用率较高

<nav></nav>

导航

<aside></aside>

边栏、广告 <aticle></aticle>文章、注解、评论