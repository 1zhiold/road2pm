

# Markdown使用说明

## Markdown简介
Markdown是一种非常简单好用的本文标记语言，对于新手来说，简单理解为一种格式，基础的语法内容在下方都有展示。再简单点理解，在你写字的时候，想打一个标题，在对应文字前加一个`#`就可以了。

为什么要使用Markdown，网上一搜有无数的答案，这里仅列出和课程相关的内容
* Github支持Markdown，无论是仓库中的文档还是Issue中，如果感兴趣，可以关注 [Mastering Markdown · GitHub Guides](https://guides.github.com/features/mastering-markdown/)
* 基于Markdown，我们在Github的每一次版本记录可以清晰的看到变化记录，这一点使用Word或者其他的所见即所得的文档工具无法实现
* 足够简单
* 作为产品，你需要了解，大部分的开发者（没做过调研，直觉如此）知道Markdown

关于Markdown的语法，可以参考的地方太多了，这里简单列出一些，一下的语法说明主要来自[MarkEditor](https://www.markeditor.com/)自带的说明内容，简单做了删减。顺带安利 MardEditor，MacOs 下的好用的Makrdown书写工具（付费）。

## Markdown基本语法
>  Markdown是非常棒以及流行的写作语法，平文本，「易读易写」，一般只需几分钟就能学会Markdown的基本用法。

### 标题:
```
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```
分别对应HTML中的`<h1>一级标题</h1>`，以此类推。

```
**用两个星号标记起来，表示加粗**，*一个星号，表示斜体*，~~这样子表示删除~~，这些就是最基本的语法了。
```

### 插入链接
**插入链接:**
```
这是一个 [链接](http://url.com/)
```

### 列表
**无序列表:**
```
- Red
- Green
- Blue
```


**有序列表则使用数字接着一个英文句点：**
```
1.  Bird
2.  McHale
3.  Parish
```


**也可以混合在一起使用:**
```
- Bird
    - blue bird
- McHale
    1. a man
    2. HoustonRockets
- Parish
```



### 分割线
**`-`加上空格组成，三个以上:**
```
- - - - - -
```


### 内容引用
用`>`放在段首，之后是空格，输入文字:

```
> 你
> 一会看我
> 一会看云

>  我觉得
>  你看我时很远
>  你看云时很近
```


### 插入图片

**插图语法:**
```
![图片的alt信息，可空](图片的url)
```

## 其他
可参考的 Markdown 使用教程：
* https://www.runoob.com/markdown/md-tutorial.html

