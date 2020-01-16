# Markdown 段落格式

Markdown 段落没有特殊的格式，直接编写文字就好

## 一 换行

1 使用两个以上空格加回车

2 使用一个空行来表示重新开始一个段落

## 二 字体

1 斜体

```markdown
*斜体文本*
_斜体文本_
```

2 粗体

```markdown
**粗体文本**
__粗体文本__
```

3 粗斜体

```markdown
***粗斜体文本***
___粗斜体文本___
```

## 三 分隔线

使用三个以上的星号、减号、下划线来建立一个分隔线，行内不能有其他东西，可以加入空格

````markdown
***
* * *
---
- - -
___
_ _ _
````

## 四 删除线

如果段落上的文字要添加删除线，只需要在文字的两端加上两个波浪线 **~~** 即可

````markdown
~~Molln~~
````

## 五 下划线

下划线可以通过 HTML 的<u></u>标签来实现

````markdown
<u>Molln</u>
````

~~经测试，在 Github 无效~~

## 六 脚注

格式

[^要注明的文本]



示例

```markdown
Markdown [^MARKDOWN]

[^MARKDOWN]:Markdown 是一种轻量级标记语言，它允许人们使用易读易写的纯文本格式编写文档。
```



效果如下

Markdown [^MARKDOWN]

[^MARKDOWN]: Markdown 是一种轻量级标记语言，它允许人们使用易读易写的纯文本格式编写文档。



~~经测试，在Github 无效~~



[Demo](https://github.com/Molln/Markdown/blob/master/Demo/MarkdownParagraph.md)