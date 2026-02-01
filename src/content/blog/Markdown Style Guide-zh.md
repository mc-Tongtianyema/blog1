---
title: "Markdown Style Guide中文人工乱翻译版"
description: "语法教学."
pubDate: "Jan 31 2026"
heroImage: "/blog-placeholder-1.jpg"
---

这里是一个可以在 Astro 中编写 Markdown 内容时使用的一些基本 Markdown 语法示例。

## 标题

以下 HTML `<h1>` — `<h6>` 元素代表六个章节标题层级。`<h1>` 是最高区段，而 `<h6>` 是最低层。

# H1

## H2

### H3

#### H4

##### H5

###### H6

## 段落

Xerum, quo qui aut unt expliquam qui dolut labo. Aque venitatiusda cum, voluptionse latur sitiae dolessi aut parist aut dollo enim qui voluptate ma dolestendit peritin re plis aut quas inctum laceat est volestemque commosa as cus endigna tectur, offic to cor sequas etum rerum idem sintibus eiur? Quianimin porecus evelectur, cum que nis nust voloribus ratem aut omnimi, sitatur? Quiatem. Nam, omnis sum am facea corem alique molestrunt et eos evelece arcillit ut aut eos eos nus, sin conecerem erum fuga. Ri oditatquam, ad quibus unda veliamenimin cusam et facea ipsamus es exerum sitate dolores editium rerore eost, temped molorro ratiae volorro te reribus dolorer sperchicium faceata tiustia prat.

Itatur? Quiatae cullecum rem ent aut odis in re eossequodi nonsequ idebis ne sapicia is sinveli squiatum, core et que aut hariosam ex eat.</br>
纳尼？你确定这玩意我会翻译????

## 图片

### 语法

```markdown
![Alt text](你的图片地址)
```

### 结果

![blog placeholder](/blog-placeholder-about.jpg)

## 引用块

块引元素表示引用自其他来源的内容，可选择性地引用必须在`页脚`或`引用`元素内，也可以选择内嵌更改，如注释和缩写。

### 无署名的引用

#### 语法

```markdown
> Tiam, ad mint andaepu dandae nostion secatur sequo quae.  我也不会
> **注意** 你可以在块引号中使用 _Markdown_ 语法.
```

#### 输出

> Tiam, ad mint andaepu dandae nostion secatur sequo quae.  我也不会</br>
> **注意** 你可以在块引号中使用 _Markdown_ 语法.

### 有署名的引用

#### 语法

```markdown
> 不要通过分享记忆来沟通，要通过交流来分享记忆。<br>
> — <cite>罗布·派克[^1]</cite>

[^1]: 意思/出处
```

#### 输出

> 不要通过分享记忆来沟通，要通过交流来分享记忆。<br>
> — <cite>罗布·派克[^1]</cite>

[^1]: 以上引述摘自 Rob Pike 于 2015 年 11 月 18 日 Gopherfest 期间的 [演讲](https://www.youtube.com/watch?v=PAAkCSZUG1c) 。

## 表格

### 语法

```markdown
| 斜体   | 加粗     | 代码   |
| --------- | -------- | ------ |
| _斜体_ | **加粗** | `代码` |
```

### 输出

| 斜体   | 加粗     | 代码   |
| --------- | -------- | ------ |
| _斜体_ | **加粗** | `代码` |

## 代码块

### 语法
我们可以在新行中使用 3 个` ``` `,并在新行写 3 个回溯引号写 Snippet 和 Close，为了突出语言特定的句法，在前 3 个回溯引号后写一个语言名称的单词，例如：HTML、JAVASCRIPT、CSS、MARKDOWN、TYPESCRIPT、TXT、BASH。

````markdown
```html
<!doctype html>
<html lang="en">
	<head>
		<meta charset="utf-8" />
		<title>这是html代码演示</title>
	</head>
	<body>
		<p>测试</p>
	</body>
</html>
```
````

### Output

```html
<!doctype html>
<html lang="en">
	<head>
		<meta charset="utf-8" />
		<title>这是html代码演示</title>
	</head>
	<body>
		<p>测试</p>
	</body>
</html>
```

## 列表

### 有序列表

#### 语法

```markdown
1. 第一行
2. 第二行
3. 第三行
```

#### Output

1. 第一行
2. 第二行
3. 第三行

### 无序列表

#### 语法

```markdown
- 列表项
- 又一个项
- 另一个项
```

#### 输出

- 列表项
- 又一个项
- 另一个项

### 无序子列表项

#### 语法
```markdown
- 能吃的
  - 苹果
  - 香蕉
  - 橘子
- 不能吃的
  - 石头
  - 木头
```

#### 输出

- 能吃的
  - 苹果
  - 香蕉
  - 橘子
- 不能吃的
  - 石头
  - 木头

## 其他元素 — 缩写、sub、sup、kbd、mark

### 语法

```markdown
<abbr title="Graphics Interchange Format">GIF</abbr>是一种位图图像格式。

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

按 <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>Esc</kbd> 键打开任务管理器。

大多数<mark>蝾螈</mark>是夜行性，捕食昆虫、蠕虫和其他小型生物。
```

### 输出

<abbr title="Graphics Interchange Format">GIF</abbr>是一种位图图像格式。

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

按 <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>Esc</kbd> 键打开任务管理器。

大多数<mark>蝾螈</mark>是夜行性，捕食昆虫、蠕虫和其他小型生物。
