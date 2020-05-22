# MarkDown 基础语法
## 标题
```
# 一级标题
## 二级标题
....
```
注意符号和内容之间要空格

## 字体
  *斜体* &emsp; `*斜体*`

  **加粗** &emsp;  ` **加粗**`


  ***粗斜体*** &emsp;  ` ***粗斜体***`

## 引用

`> 这是引用`
> 这是引用
`>> 这也是引用`
>> 这也是引用
`>>>这也也是引用`
>>>这也也是引用

## 分割线
`**** or ------`

--------
## 删除线
`~~这是一句将要删除的话~~`

~~这是一句将要删除的话~~

## 图片
`![图片名](地址)`

例如：`![MarkDown](https://upload-images.jianshu.io/upload_images/13516495-334fb1677e9e9fba.png?imageMogr2/auto-orient/strip|imageView2/2/w/900/format/webp)`
![MarkDown](https://upload-images.jianshu.io/upload_images/13516495-334fb1677e9e9fba.png?imageMogr2/auto-orient/strip|imageView2/2/w/900/format/webp)

## 超链接

`[超链接名](超链接地址)`

`[简书](http://jianshu.com)`
[简书](http://jianshu.com)

或者
`<a href="超链接地址" target="_blank">超链接名</a>`

示例：
<a href="https://www.jianshu.com/u/1f5ac0cf6a8b" target="_blank">简书</a>

## 列表
`- or + or * or 数字. 内容`

`+ 内容`
+ 内容

`1. 内容`
1. 内容
   
上下级通过三个空格控制

```
+ 上级
   +下级

```
+ 上级
   + 下级 

## 表格
```
| 表头 | 表头  | 表头 |
| ---- | :---: | ---: |
| 内容 | 内容  | 内容 |
| 内容 | 内容  | 内容 |

第二行分割表头和内容


文字默认居左
-两边加：表示文字居中
-右边加：表示文字居右
注：原生的语法两边都要用 | 包起来。此处省略
```
| 表头 | 表头  | 表头 |
| ---- | :---: | ---: |
| 内容 | 内容  | 内容 |
| 内容 | 内容  | 内容 |

## 代码

<code>
`代码` 
or
&#96;&#96;&#96;
代码内容
&#96;&#96;&#96;
</code>

## 流程图

<code>
```flow      

st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```
</code>

```flow      

st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```