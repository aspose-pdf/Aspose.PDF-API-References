---
title: TextFragmentAbsorber
second_title: Aspose.PDF for .NET API 参考
description: 初始化TextFragmentAbsorberaspose.pdf.text/textfragmentabsorber的新实例该实例执行文档或页面的所有文本段的搜索.
type: docs
weight: 10
url: /zh/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

初始化[`TextFragmentAbsorber`](../../textfragmentabsorber)的新实例，该实例执行文档或页面的所有文本段的搜索.

```csharp
public TextFragmentAbsorber()
```

### 评论

执行文本搜索并通过TextFragments集合。

### 例子

该示例演示如何在第一个 PDF 文档页面上查找文本并替换该文本。

```csharp
// 打开文档
cument doc = new Document(@"D:\Tests\input.pdf");

// 查找将用于更改文档文本的字体 font
pose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// 创建TextFragmentAbsorber object
xtFragmentAbsorber absorber = new TextFragmentAbsorber();

// 使吸收器搜索所有“hello world”文本出现
sorber.Phrase = "hello world";

// 接受第一页的吸收器
c.Pages[1].Accept(absorber);

// 更改第一个文本出现的文本
sorber.TextFragments[1].Text = "hi world";

// 保存文档
c.Save(@"D:\Tests\output.pdf");  
```

### 也可以看看

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* 命名空间 [Aspose.Pdf.Text](../../textfragmentabsorber)
* 部件 [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

使用文本编辑选项初始化[`TextFragmentAbsorber`](../../textfragmentabsorber)的新实例，执行搜索所有文本段文档或页面。

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| textEditOptions | TextEditOptions | 文本编辑选项（允许打开一些编辑功能）。 |

### 评论

执行文本搜索并通过TextFragments集合。

### 例子

该示例演示了如何在第一个 PDF 文档页面上查找所有文本片段并为其替换字体.

```csharp
// 打开文档
cument doc = new Document(@"D:\Tests\input.pdf");

// 创建TextFragmentAbsorber object
xtFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));

// 接受第一页的吸收器
c.Pages[1].Accept(absorber);

// 查找快递 font
f.Text.Font font = FontRepository.FindFont("Courier");

// 设置所有文本片段的字体
reach (TextFragment textFragment in absorber.TextFragments)

  textFragment.TextState.Font = font;


// 保存文档
c.Save(@"D:\Tests\output.pdf");
```

### 也可以看看

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* 命名空间 [Aspose.Pdf.Text](../../textfragmentabsorber)
* 部件 [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

为指定的文本短语初始化[`TextFragmentAbsorber`](../../textfragmentabsorber)类的新实例。

```csharp
public TextFragmentAbsorber(string phrase)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| phrase | String | [`TextFragmentAbsorber`](../../textfragmentabsorber)搜索的短语 |

### 评论

执行指定短语的文本搜索并通过P提供对搜索结果的访问:Aspose.Pdf.Text.TextFragmentAbsorber.TextFragments集合。

### 例子

该示例演示如何在第一个 PDF 文档页面上查找文本并替换文本及其字体.

```csharp
// 打开文档
cument doc = new Document(@"D:\Tests\input.pdf");

// 查找将用于更改文档文本的字体 font
pose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// 创建 TextFragmentAbsorber 对象以查找所有“hello world”文本出现
xtFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
c.Pages[1].Accept(absorber);

// 更改第一个文本出现的文本和字体
sorber.TextFragments[1].Text = "hi world";
sorber.TextFragments[1].TextState.Font = font;

// 保存文档
c.Save(@"D:\Tests\output.pdf");  
```

### 也可以看看

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* 命名空间 [Aspose.Pdf.Text](../../textfragmentabsorber)
* 部件 [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

为指定的 System.Text.RegularExpressions.Regex 类初始化[`TextFragmentAbsorber`](../../textfragmentabsorber)类的新实例目的。

```csharp
public TextFragmentAbsorber(Regex regex)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex 类对象，即[`TextFragmentAbsorber`](../../textfragmentabsorber)搜索 |

### 评论

执行指定短语的文本搜索并通过P提供对搜索结果的访问:Aspose.Pdf.Text.TextFragmentAbsorber.TextFragments集合。

### 例子

该示例演示如何在第一个 PDF 文档页面上查找文本并替换文本及其字体.

```csharp
// 打开文档
cument doc = new Document(@"D:\Tests\input.pdf");

// 查找将用于更改文档文本的字体 font
pose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// 创建 TextAbsorber 对象以查找输入 regex

xtFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"));

// 接受第一页的吸收器
c.Pages[1].Accept(absorber);

// 我们应该找到 "hello" 单词并将其替换为 "Hi"
c.Pages[1].Accept(absorber);
sorber.TextFragments[1].Text = "Hi";

// 保存文档
c.Save(@"D:\Tests\output.pdf");
```

### 也可以看看

* class [TextFragmentAbsorber](../../textfragmentabsorber)
* 命名空间 [Aspose.Pdf.Text](../../textfragmentabsorber)
* 部件 [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

为指定的文本短语和文本搜索选项初始化[`TextFragmentAbsorber`](../../textfragmentabsorber)类的新实例。

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| phrase | String | [`TextFragmentAbsorber`](../../textfragmentabsorber)搜索的短语 |
| textSearchOptions | TextSearchOptions | 文本搜索选项（允许打开某些搜索功能。例如，使用正则表达式搜索） |

### 评论

执行指定短语的文本搜索并通过P提供对搜索结果的访问:Aspose.Pdf.Text.TextFragmentAbsorber.TextFragments集合。

### 例子

该示例演示了如何在第一个 PDF 文档页面上查找带有正则表达式的文本并替换该文本.

```csharp
// 打开文档
cument doc = new Document(@"D:\Tests\input.pdf");

 创建 TextFragmentAbsorber 对象，该对象使用正则表达式搜索所有以 'h' 开头和以 'o' 结尾的单词。
xtFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// 我们应该找到 "hello" 单词并将其替换为 "Hi"
c.Pages[1].Accept(absorber);
sorber.TextFragments[1].Text = "Hi"; 

// 保存文档
c.Save(@"D:\Tests\output.pdf");  
```

### 也可以看看

* class [TextSearchOptions](../../textsearchoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* 命名空间 [Aspose.Pdf.Text](../../textfragmentabsorber)
* 部件 [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

为指定的文本短语和文本搜索选项初始化[`TextFragmentAbsorber`](../../textfragmentabsorber)类的新实例。

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex 类对象，即[`TextFragmentAbsorber`](../../textfragmentabsorber)搜索 |
| textSearchOptions | TextSearchOptions | 文本搜索选项（允许打开某些搜索功能。） |

### 评论

执行指定短语的文本搜索并通过P提供对搜索结果的访问:Aspose.Pdf.Text.TextFragmentAbsorber.TextFragments集合。

### 例子

该示例演示了如何在第一个 PDF 文档页面上查找带有正则表达式的文本并替换该文本.

```csharp
// 打开文档
cument doc = new Document(@"D:\Tests\input.pdf");

 创建 TextFragmentAbsorber 对象，该对象使用正则表达式搜索所有以 'h' 开头和以 'o' 结尾的单词。
xtFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"), new TextSearchOptions(true));

// 我们应该找到 "hello" 单词并将其替换为 "Hi"
c.Pages[1].Accept(absorber);
sorber.TextFragments[1].Text = "Hi";

// 保存文档
c.Save(@"D:\Tests\output.pdf");
```

### 也可以看看

* class [TextSearchOptions](../../textsearchoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* 命名空间 [Aspose.Pdf.Text](../../textfragmentabsorber)
* 部件 [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

为指定的文本短语、文本搜索选项和文本初始化[`TextFragmentAbsorber`](../../textfragmentabsorber)类的新实例编辑选项。

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| phrase | String | [`TextFragmentAbsorber`](../../textfragmentabsorber)搜索的短语 |
| textSearchOptions | TextSearchOptions | 文本搜索选项（允许打开某些搜索功能。例如，使用正则表达式搜索） |
| textEditOptions | TextEditOptions | 文本编辑选项（允许打开一些编辑功能）。 |

### 评论

执行指定短语的文本搜索并通过P提供对搜索结果的访问:Aspose.Pdf.Text.TextFragmentAbsorber.TextFragments集合。

### 例子

该示例演示了如何在第一个 PDF 文档页面上查找带有正则表达式的文本并替换该文本.

```csharp
// 打开文档
cument doc = new Document(@"D:\Tests\input.pdf");

 创建 TextFragmentAbsorber 对象，该对象使用正则表达式搜索所有以 'h' 开头和以 'o' 结尾的单词。
xtFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// 我们应该找到 "hello" 单词并将其替换为 "Hi"
c.Pages[1].Accept(absorber);
sorber.TextFragments[1].Text = "Hi"; 

// 保存文档
c.Save(@"D:\Tests\output.pdf");  
```

### 也可以看看

* class [TextSearchOptions](../../textsearchoptions)
* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* 命名空间 [Aspose.Pdf.Text](../../textfragmentabsorber)
* 部件 [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

为指定的文本短语和文本编辑选项初始化[`TextFragmentAbsorber`](../../textfragmentabsorber)类的新实例。

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| phrase | String | 短语[`TextFragmentAbsorber`](../../textfragmentabsorber)搜索 |
| textEditOptions | TextEditOptions | 文本编辑选项（允许打开一些编辑功能）。 |

### 评论

执行指定短语的文本搜索并通过P提供对搜索结果的访问:Aspose.Pdf.Text.TextFragmentAbsorber.TextFragments集合。

### 也可以看看

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* 命名空间 [Aspose.Pdf.Text](../../textfragmentabsorber)
* 部件 [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

为指定的文本短语和文本编辑选项初始化[`TextFragmentAbsorber`](../../textfragmentabsorber)类的新实例。

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| regex | Regex | System.Text.RegularExpressions.Regex 类对象[`TextFragmentAbsorber`](../../textfragmentabsorber)搜索 |
| textEditOptions | TextEditOptions | 文本编辑选项（允许打开一些编辑功能）。 |

### 评论

执行指定短语的文本搜索并通过P提供对搜索结果的访问:Aspose.Pdf.Text.TextFragmentAbsorber.TextFragments集合。

### 也可以看看

* class [TextEditOptions](../../texteditoptions)
* class [TextFragmentAbsorber](../../textfragmentabsorber)
* 命名空间 [Aspose.Pdf.Text](../../textfragmentabsorber)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
