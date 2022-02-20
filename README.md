# Markdown
> 一种轻量级标记语言，在 2004 由约翰·格鲁伯（John Gruber）创建。
> Markdown 编写的文档可以导出 HTML、Word、图像、PDF、Epub 等多种格式的文档。




<br />
<br />

[markdown-cheatsheet](https://github.com/tchapi/markdown-cheatsheet)

<br />


# 标题
文字下方使用 = ， - 标记一级，二级标题
# 一级标题
## 二级标题
使用 # 号加空格表示 1-6 级标题，级别等同个数
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题


# 段落
段落没有特殊的格式，段落的换行是两个以上空格加上回车
# 字体
文字两侧成对加* 或 _表示粗斜体

<br />

_一对符号_

<br />

_斜体文本_

<br />

**两对符号**

<br />

**粗体文本**

<br />

**_三对符号_**

<br />

**_粗斜体文本_**

<br />

文字两侧各2个==

<br />

高亮
# 删除线
文字的两端加上两个波浪线~

<br />

~~删除~~
# 下划线
文字的两端加上两个+

<br />

下划
# 分割线

---

一行中用三个以上的*、-、底线来建立一个分隔线，行内不能有其他东西，可以在中间插入空格

---


---


---

# 脚注
格式：[^脚注名]

<br />

带有脚注的文本[[1]](#fn1)。
# 列表
无序列表使用星号(*)、加号(+)或是减号(-)作为列表标记：

- 第一项
- 第二项
- 第三项
- 第一项
- 第二项
- 第三项
- 第一项
- 第二项
- 第三项

有序列表使用数字并加上 . 号来表示

1. 第一项
1. 第二项
1. 第三项

列表嵌套只需在子列表中的选项添加四个空格即可：

1. 第一项：
   - 第一项嵌套的第一个元素
   - 第一项嵌套的第二个元素
2. 第二项：
   - 第二项嵌套的第一个元素
   - 第二项嵌套的第二个元素
# 引用
符号 > 加空格：
> 区块
> 引用

可嵌套
> 最外层
> 第一层嵌套
> 第二层嵌套

# 代码格式
一个函数或片段的代码可以用反引号（`）把它包起来

<br />

C语言的 `printf()` 函数

<br />

代码区块使用 4 个空格或者一个制表符（Tab 键）
```
int a,b;
```
也可用 ``` 包裹一段代码（可以指定一种语言）
```
string s("markdown");
```
# 链接
格式：[链接名称](链接地址)

<br />

或

<br />

<链接地址>

<br />

这是一个链接 [markdown](https://www.appinn.com/markdown/index.html#html)

<br />

链接也可以用变量来代替，文档末尾附带变量地址：

<br />

这个链接用 1 作为网址变量 [Google](http://www.google.com/) ([Google][1])

<br />

这个链接用 runoob 作为网址变量 [菜鸟教程](http://www.runoob.com/)

<br />

然后在文档的结尾为变量赋值（网址）
# 图片
格式：![属性文本](图片地址)

<br />

或

<br />

![属性文本](图片地址 "可选标题")

<br />

![](http://static.runoob.com/images/runoob-logo.png#crop=0&crop=0&crop=1&crop=1&id=oyzLH&originHeight=39&originWidth=258&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)

<br />

![](http://static.runoob.com/images/runoob-logo.png#crop=0&crop=0&crop=1&crop=1&id=rraRe&originHeight=39&originWidth=258&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)RUNOOB
# 表格
用 | 来分隔不同的单元格

<br />

用 - 来分隔表头和其他行

| 表头 | 表头 |
| --- | --- |
| 单元格 | 单元格 |
| 单元格 | 单元格 |

可以设置表格的对齐方式：

<br />

-: 设置内容和标题栏居右对齐

<br />

:- 设置内容和标题栏居左对齐

<br />

:-: 设置内容和标题栏居中对齐

| 左对齐 | 右对齐 | 居中对齐 |
| --- | --- | --- |
| 左 | 右 | 中 |
| 单元格 | 单元格 | 单元格 |

# 任务清单
未完成事项 - [ ]

<br />

已完成事项 - [x]

-  未完成事项
-  已完成事项
# 转义
使用反斜杠(\)转义特殊字符

<br />

支持以下符号前面加上反斜杠来帮助插入普通的符号：

<br />

\   反斜线

<br />

`    反引号

<br />

*   星号

<br />

_   下划线

<br />

{}   花括号

<br />

[]   方括号

<br />

()   小括号

<br />

#   井号

<br />

+   加号

<br />

-   减号

<br />

.    英文句点

<br />

!    感叹号
# 流程图
一段流程图语法以 ```  开头，以 ``` 结尾

<br />

在 ``` 后另起一行，书写graph XX，用以确定将要绘制的流程图及其类型（XX表示流程图类型）。

<br />

流程图分为竖向和横向两大类，竖向包括自上而下和自下而上两种顺序，横向包括从右到左和从左到右两种顺序。

<br />

其对应语法分别为：graph TB/graph BT/graph RL/graph LR。

<br />

A---B 无箭头

<br />

A-->B 有箭头

<br />

A-->|插入文本|B

<br />

TB - top bottom（自上而下）
```
graph TB
A-->B
```
BT - bottom top（自下而上）
```
graph BT
A-->B
```
RL - right left（从右到左）
```
graph RL
A-->B
```
LR - left right（从左到右）
```
graph LR
A[A]---|插入文本|B[B]
B-->|插入文本|Y
```
圆形(())
```
graph TB
A((圆))
```
长方形[]
```
graph TB
A[长方形]
```
菱形{}
```
graph TB
A{菱形}
```
# 甘特图
甘特图能够将你最近的计划直观地显示出来

<br />

以 ```  开头，以 ``` 结尾

<br />

在 ``` 后另起一行，书写gantt

<br />

用dateFormat YYYY-MM-DD规定时间轴，title （标题文本）表示甘特图标题。

<br />
<br />


---

1. 对脚注的说明 [↩︎](#fnref1)
多词典查询谷歌翻译
