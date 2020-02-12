---
layout:     post
title:      Mastering Markdown
subtitle:   掌握降价
date:       2020-02-12
author:     zm
header-img: img/mardown.png
catalog: true
tags:
    - markdown
---
# 结构化文档

有时使用不同级别的标题来结构化文档很有用。以“＃”开头的行以创建标题。连续多个“ ##”表示较小的标题尺寸。

### 这是一个第三层标题，

对于不同的标题大小，您可以一直使用一个`＃`直到`#######六个。

如果要引用某人，请在以下行之前使用>字符：

> Coffee。有史以来最好的有机悬架...我击败了博格。
>-珍妮威上尉
# 用Markdown使某些单**粗体**和*斜体*非常容易。您甚至可以[链接到Google！]（http://google.com）
### 对于粗体，你可以使用一个`** **`。对于斜体，你可以使用`**`。如果你要链接到某个网址，可以使用这样`[链接到Google！]（http://google.com）`的格式
# 有时您想要编号列表：

1. 一
2. 二
3. 三
# 有时您想要符号点：

* 以星号开始一行
* 利润！

# 另外，-破折号也一样工作

- 如果您有子点，则在破折号或星号前加两个空格：
  
  
  - 这样
  
  
  - 这样
  
  如果要嵌入图像，请按以下步骤操作：

`！[Yaktocat的图像]（https://octodex.github.com/images/yaktocat.png）`

！[Yaktocat的图像]（https://octodex.github.com/images/yaktocat.png）
###有多种使用GitHub的markdown设置代码样式的方法。如果您有内联代码块，请将其包装在反引号中：`var example = true`。如果您有更长的代码块，则可以缩进四个空格：

    if（isAwesome）{ 
      return true 
    } 

GitHub还支持一种称为代码围栏的代码，它允许多行而不缩进：三个反引号和三个反引号

``` 
if（isAwesome）{ 
  返回true 
} 
``` 

如果你想使用语法高亮，包括语言
`javascript`
：
```javascript
if (isAwesome){
  return true
}
```
GitHub在Markdown中支持许多其他功能，可帮助您参考并链接到其他人。如果您想对某人发表评论，则可以在他们的名字前面加上@符号：Hey @kneath - 爱您的毛衣！

但我必须承认，任务列表是我的最爱：

- [x] 这是一个完整的项目
- [ ] 这是一个不完整的项目

在“问题”的第一条注释中包含任务列表时，您会看到一个有用的进度栏在您的问题列表中。它也可以在拉取请求中使用！

而且，当然是表情符号！
# 标头
```
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag
```
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag
# 重点
```
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_
```
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_
# 清单
## 无序
```
* Item 1
* Item 2
  * Item 2a
  * Item 2b
  ```
* Item 1
* Item 2
  * Item 2a
  * Item 2b
## 有序
```
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
   ```
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
# 图片
```
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)
```
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)
# 链接
```
http://github.com - automatic!
[GitHub](http://github.com)
```
http://github.com - automatic!
[GitHub](http://github.com)
# 块引用
```
As Kanye West said:

> We're living the future so
> the present is our past.
```
As Kanye West said:

> We're living the future so
> the present is our past.
# 内联代码
```
I think you should use an
`<addr>` element here instead.
```
I think you should use an
`<addr>` element here instead.
# 表格
```
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
```
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
# 删除线
包裹有两个波浪号的任何单词（如~~this~~）将显示为划线。
# 自动链接网址
任何网址（如http://www.github.com/）都会自动转换为可点击的链接。
# 用户名@mentions
键入@符号，然后输入用户名，将通知该人前来查看评论。这就是所谓的“ @mention”，因为您提到的是个人。您也可以@提及组织内的团队。
# 在资源库中发布参考
引用“发布”或“拉取请求”的任何数字都将自动转换为链接。
```
#1
mojombo#1
mojombo/github-flavored-markdown#1
```
#1
mojombo#1
mojombo/github-flavored-markdown#1
# SHA参考
对提交的SHA-1哈希的任何引用将自动转换为GitHub上该提交的链接。
```
16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac
```
16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac
