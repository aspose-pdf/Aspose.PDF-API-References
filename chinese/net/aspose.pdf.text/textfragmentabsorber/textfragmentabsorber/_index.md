---
title: "TextFragmentAbsorber.TextFragmentAbsorber"
second_title: "Aspose.PDF for .NET API 参考"
description: "TextFragmentAbsorber 构造函数。初始化一个新的 TextFragmentAbsorber 实例，用于搜索文档或页面的所有文本段落。"
type: docs
weight: 10
url: /zh/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

初始化一个新的 [`TextFragmentAbsorber`](../) 实例，用于搜索文档或页面的所有文本段落。

```csharp
public TextFragmentAbsorber()
```

## 备注

执行文本搜索并通过 [`TextFragments`](../textfragments/) 集合提供对搜索结果的访问。

## 示例

示例演示了如何在 PDF 文档的第一页查找文本并替换该文本。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 查找用于更改文档文本字体的字体
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// 创建 TextFragmentAbsorber 对象
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// 让吸收器搜索所有 \"hello world\" 文本出现。
absorber.Phrase = "hello world";

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 更改第一次文本出现的内容。
absorber.TextFragments[1].Text = "hi world";

// 保存文档
doc.Save(@"D:\Tests\output.pdf");  
```

### 另请参见

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

初始化一个新的 [`TextFragmentAbsorber`](../) 实例，带有文本编辑选项，用于搜索文档或页面的所有文本段落。

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| textEditOptions | TextEditOptions | 文本编辑选项（允许开启某些编辑功能）。 |

## 备注

执行文本搜索并通过 [`TextFragments`](../textfragments/) 集合提供对搜索结果的访问。

## 示例

示例演示了如何在 PDF 文档的第一页查找所有文本片段并替换它们的字体。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 查找 Courier 字体
Pdf.Text.Font font = FontRepository.FindFont("Courier");

// 为所有文本片段设置字体。
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.TextState.Font = font;
}

// 保存文档
doc.Save(@"D:\Tests\output.pdf");
```

### 另请参见

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string) {#constructor_2}

初始化一个新的 [`TextFragmentAbsorber`](../) 类实例，用于指定的文本短语。

```csharp
public TextFragmentAbsorber(string phrase)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| phrase | String | [`TextFragmentAbsorber`](../) 搜索的短语 |

## 备注

执行指定短语的文本搜索，并通过 [`TextFragments`](../textfragments/) 集合提供对搜索结果的访问。

## 示例

示例演示了如何在第一个 PDF 文档页上查找文本并替换该文本及其字体。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 查找用于更改文档文本字体的字体
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 更改首次文本出现的文本和字体
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// 保存文档
doc.Save(@"D:\Tests\output.pdf");  
```

### 另请参见

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

为指定的 System.Text.RegularExpressions.Regex 类对象初始化一个新的 [`TextFragmentAbsorber`](../) 类实例。

```csharp
public TextFragmentAbsorber(Regex regex)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| regex | Regex | [`TextFragmentAbsorber`](../) 搜索的 System.Text.RegularExpressions.Regex 类对象。 |

## 备注

执行指定短语的文本搜索，并通过 [`TextFragments`](../textfragments/) 集合提供对搜索结果的访问。

## 示例

示例演示了如何在第一个 PDF 文档页上查找文本并替换该文本及其字体。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 查找用于更改文档文本字体的字体
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// 创建 TextAbsorber 对象以查找输入正则表达式的所有实例。
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"));

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 我们应该找到 "hello" 单词并将其替换为 "Hi"。
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// 保存文档
doc.Save(@"D:\Tests\output.pdf");
```

### 另请参见

* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

为指定的文本短语和文本搜索选项初始化一个新的 [`TextFragmentAbsorber`](../) 类实例。

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| phrase | String | [`TextFragmentAbsorber`](../) 搜索的短语 |
| textSearchOptions | TextSearchOptions | 文本搜索选项（允许开启某些搜索功能。例如，使用正则表达式搜索） |

## 备注

执行指定短语的文本搜索，并通过 [`TextFragments`](../textfragments/) 集合提供对搜索结果的访问。

## 示例

示例演示了如何在第一页 PDF 文档上使用正则表达式查找文本并替换该文本。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象，使用正则表达式搜索所有以 'h' 开头并以 'o' 结尾的单词。
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// 我们应该找到 "hello" 单词并将其替换为 "Hi"。
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 
 
// 保存文档
doc.Save(@"D:\Tests\output.pdf");  
```

### 另请参见

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

为指定的文本短语和文本搜索选项初始化一个新的 [`TextFragmentAbsorber`](../) 类实例。

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| regex | Regex | [`TextFragmentAbsorber`](../) 搜索的 System.Text.RegularExpressions.Regex 类对象。 |
| textSearchOptions | TextSearchOptions | 文本搜索选项（允许开启某些搜索功能。） |

## 备注

执行指定短语的文本搜索，并通过 [`TextFragments`](../textfragments/) 集合提供对搜索结果的访问。

## 示例

示例演示了如何在第一页 PDF 文档上使用正则表达式查找文本并替换该文本。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象，使用正则表达式搜索所有以 'h' 开头并以 'o' 结尾的单词。
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"), new TextSearchOptions(true));

// 我们应该找到 "hello" 单词并将其替换为 "Hi"。
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// 保存文档
doc.Save(@"D:\Tests\output.pdf");
```

### 另请参见

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex[], TextSearchOptions) {#constructor_9}

为指定的文本短语和文本搜索选项初始化一个新的 [`TextFragmentAbsorber`](../) 类实例。

```csharp
public TextFragmentAbsorber(Regex[] regexes, TextSearchOptions textSearchOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| regexes | Regex[] | [`TextFragmentAbsorber`](../) 搜索的 System.Text.RegularExpressions.Regex 类对象数组。 |
| textSearchOptions | TextSearchOptions | 文本搜索选项（允许开启某些搜索功能）。 |

## 备注

对指定的短语数组执行文本搜索，并通过 [`RegexResults`](../regexresults/) 字典提供对搜索结果的访问。

## 示例

示例演示了如何在第一页 PDF 文档上使用正则表达式数组查找文本。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// 创建 TextFragmentAbsorber 对象，使用正则表达式搜索所有以 'h' 开头并以 'o' 结尾的单词。
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// 获取结果
var results = absorber.RegexResults;
```

### 另请参见

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

为指定的文本短语、文本搜索选项和文本编辑选项初始化一个新的 [`TextFragmentAbsorber`](../) 类实例。

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| phrase | String | [`TextFragmentAbsorber`](../) 搜索的短语 |
| textSearchOptions | TextSearchOptions | 文本搜索选项（允许开启某些搜索功能。例如，使用正则表达式搜索） |
| textEditOptions | TextEditOptions | 文本编辑选项（允许开启某些编辑功能）。 |

## 备注

执行指定短语的文本搜索，并通过 [`TextFragments`](../textfragments/) 集合提供对搜索结果的访问。

## 示例

示例演示了如何在第一页 PDF 文档上使用正则表达式查找文本并替换该文本。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象，使用正则表达式搜索所有以 'h' 开头并以 'o' 结尾的单词。
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// 我们应该找到 "hello" 单词并将其替换为 "Hi"。
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// 保存文档
doc.Save(@"D:\Tests\output.pdf");  
```

### 另请参见

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

为指定的文本短语和文本编辑选项初始化一个新的 [`TextFragmentAbsorber`](../) 类实例。

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| phrase | String | [`TextFragmentAbsorber`](../) 搜索的短语 |
| textEditOptions | TextEditOptions | 文本编辑选项（允许开启某些编辑功能）。 |

## 备注

执行指定短语的文本搜索，并通过 [`TextFragments`](../textfragments/) 集合提供对搜索结果的访问。

### 另请参见

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

为指定的文本短语和文本编辑选项初始化一个新的 [`TextFragmentAbsorber`](../) 类实例。

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| regex | Regex | [`TextFragmentAbsorber`](../) 搜索的 System.Text.RegularExpressions.Regex 类对象。 |
| textEditOptions | TextEditOptions | 文本编辑选项（允许开启某些编辑功能）。 |

## 备注

执行指定短语的文本搜索，并通过 [`TextFragments`](../textfragments/) 集合提供对搜索结果的访问。

### 另请参见

* class [TextEditOptions](../../texteditoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


