# Markdown 区块

Markdown 区块引用是在段落开头使用 > 号，然后后面紧跟一个**空格**符号

1 简单示例

````markdown
> 中国
> 江苏
> 南京
````

2 区块嵌套

```markdown
> 中国
> > 江苏
> > > 南京
```

3 区块中使用列表

```markdown
> 中国
> 1. 江苏
> 2. 广东
> + 山东
> + 河南
> + 浙江
```

4 列表中使用区块

如果要在列表项目内放进区块，那么就需要在 **>** 前添加四个空格的缩进。

```markdown
* 江苏
    > 南京
    > 徐州
* 广东
```

[Demo](https://github.com/Molln/Markdown/blob/master/Demo/MarkdownBlock.md)