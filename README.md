# 基本结构

    <!doctype html> #必要的
    <html>
      <head>
      #添加标题内容
      </head>
      <body>
      #添加主体内容
      </body>
    </html>

# 元素种类
块元素(block element)和内联元素(inline element)  
块元素独立成块，与其他内容自带分界
内联元素嵌入在其他内容中
# 具体元素
功能|实现
---|---
插入图片|<img hred = *aim_address*">
# 类
        <h1 class= "class1 class2 class3">
可以为元素指定类，为一类元素，或为元素中的一类统一设置属性  
越靠后列出的规则优先级越高（在类优先级相同的情况下）  

文本属性
文字属性名称|功能|备注
---|---|---
font-family|指定字体|sans : 表否定  serif : 衬线  monospace : 等宽 
font-size|字体大小|单位px/small类/%/em
color|文本颜色|
font-weight|字体粗细|
text-decoration|文本风格|上下划线、删除线
line-height|行高|

边框属性
文字属性名称|功能|备注
---|---|---
line-height|行高|长度型
border-color|边框颜色|
border-width|边框宽度|
border-style|边框风格|
padding-left|只在左边设置内边距|连写四个距离，顺序为上右下左
margin-right|只在右边设置外边距|与padding互通，连写两个距离，顺序为(上下)(左右)
border-radium|圆角半径|
border-top-left-radius|左上角半径|

背景属性
文字属性名称|功能|备注
---|---|---
background-image|背景图片|url=()
background-repeat|背景重复|
background-position|背景位置|
||
||
||
||

# 在父类中选取子类的写法
父类 子类 子类 ... {}

# 链接样式
在style中把a:链接属性 当成一个整体
a:link  链接平时
a:selected  鼠标放在链接上时  
a:visited  点击过的链接  

# 浮动元素
用float属性控制元素浮动，用clear属性控制是否允许浮动
margin和border都可以设置为auto  
postion:absolute 绝对位置。针对布局而言的，总是处在相对布局的某一个位置。  
postion:fixed 相对位置。针对窗口而言的，总是处在相对窗口的某一个位置。


# 表格
display属性的取值： table表示表元素  table-row表示行元素  table-cell表示单元格  
border-spacing表示单元格间距，注意这个间距与margin不会折叠
