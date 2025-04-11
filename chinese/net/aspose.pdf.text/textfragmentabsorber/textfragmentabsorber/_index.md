---
title: TextFragmentAbsorber.TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: TextFragmentAbsorber 构造函数。初始化一个新的 TextFragmentAbsorber 实例，该实例执行文档或页面的所有文本段落的搜索
type: docs
weight: 10
url: /zh/net/aspose.pdf.text/textfragmentabsorber/textfragmentabsorber/
---
## TextFragmentAbsorber() {#constructor}

初始化一个新的 [`TextFragmentAbsorber`](../) 实例，该实例执行文档或页面的所有文本段落的搜索。

```csharp
public TextFragmentAbsorber()
```

## 备注

执行文本搜索，并通过 [`TextFragments`](../textfragments/) 集合提供对搜索结果的访问。

## 示例

该示例演示如何在第一个 PDF 文档页面上查找文本并替换文本。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// Make the absorber to search all "hello world" text occurrences
absorber.Phrase = "hello world";

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 另请参阅

* 类 [TextFragmentAbsorber](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(TextEditOptions) {#constructor_1}

初始化一个新的 [`TextFragmentAbsorber`](../) 实例，带有文本编辑选项，该实例执行文档或页面的所有文本段落的搜索。

```csharp
public TextFragmentAbsorber(TextEditOptions textEditOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| textEditOptions | TextEditOptions | 文本编辑选项（允许启用某些编辑功能）。 |

## 备注

执行文本搜索，并通过 [`TextFragments`](../textfragments/) 集合提供对搜索结果的访问。

## 示例

该示例演示如何在第一个 PDF 文档页面上查找所有文本片段并替换它们的字体。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new TextEditOptions(TextEditOptions.FontReplace.RemoveUnusedFonts));

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Find Courier font
Pdf.Text.Font font = FontRepository.FindFont("Courier");

// Set the font for all the text fragments
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.TextState.Font = font;
}

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

### 另请参阅

* 类 [TextEditOptions](../../texteditoptions/)
* 类 [TextFragmentAbsorber](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)

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

该示例演示如何在第一个 PDF 文档页面上查找文本并替换文本及其字体。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 另请参阅

* 类 [TextFragmentAbsorber](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex) {#constructor_6}

初始化一个新的 [`TextFragmentAbsorber`](../) 类实例，用于指定的 System.Text.RegularExpressions.Regex 类对象。

```csharp
public TextFragmentAbsorber(Regex regex)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| regex | Regex | [`TextFragmentAbsorber`](../) 搜索的 System.Text.RegularExpressions.Regex 类对象 |

## 备注

执行指定短语的文本搜索，并通过 [`TextFragments`](../textfragments/) 集合提供对搜索结果的访问。

## 示例

该示例演示如何在第一个 PDF 文档页面上查找文本并替换文本及其字体。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextAbsorber object to find all instances of the input regex
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"));

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

### 另请参阅

* 类 [TextFragmentAbsorber](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions) {#constructor_4}

初始化一个新的 [`TextFragmentAbsorber`](../) 类实例，用于指定的文本短语和文本搜索选项。

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| phrase | String | [`TextFragmentAbsorber`](../) 搜索的短语 |
| textSearchOptions | TextSearchOptions | 文本搜索选项（允许启用某些搜索功能。例如，使用正则表达式搜索） |

## 备注

执行指定短语的文本搜索，并通过 [`TextFragments`](../textfragments/) 集合提供对搜索结果的访问。

## 示例

该示例演示如何在第一个 PDF 文档页面上使用正则表达式查找文本并替换文本。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 
 
// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 另请参阅

* 类 [TextSearchOptions](../../textsearchoptions/)
* 类 [TextFragmentAbsorber](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextSearchOptions) {#constructor_8}

初始化一个新的 [`TextFragmentAbsorber`](../) 类实例，用于指定的文本短语和文本搜索选项。

```csharp
public TextFragmentAbsorber(Regex regex, TextSearchOptions textSearchOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| regex | Regex | [`TextFragmentAbsorber`](../) 搜索的 System.Text.RegularExpressions.Regex 类对象 |
| textSearchOptions | TextSearchOptions | 文本搜索选项（允许启用某些搜索功能。） |

## 备注

执行指定短语的文本搜索，并通过 [`TextFragments`](../textfragments/) 集合提供对搜索结果的访问。

## 示例

该示例演示如何在第一个 PDF 文档页面上使用正则表达式查找文本并替换文本。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(new System.Text.RegularExpressions.Regex(@"h\w*?o"), new TextSearchOptions(true));

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

### 另请参阅

* 类 [TextSearchOptions](../../textsearchoptions/)
* 类 [TextFragmentAbsorber](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex[], TextSearchOptions) {#constructor_9}

初始化一个新的 [`TextFragmentAbsorber`](../) 类实例，用于指定的文本短语和文本搜索选项。

```csharp
public TextFragmentAbsorber(Regex[] regexes, TextSearchOptions textSearchOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| regexes | Regex[] | [`TextFragmentAbsorber`](../) 搜索的 System.Text.RegularExpressions.Regex 类对象数组。 |
| textSearchOptions | TextSearchOptions | 文本搜索选项（允许启用某些搜索功能）。 |

## 备注

执行指定短语数组的文本搜索，并通过 [`RegexResults`](../regexresults/) 字典提供对搜索结果的访问。

## 示例

该示例演示如何在第一个 PDF 文档页面上使用正则表达式数组查找文本。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

var regexes = new Regex[]
{
new Regex( @"expression1", RegexOptions.IgnoreCase),
new Regex( @"expression2", RegexOptions.IgnoreCase),
};
// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true));
doc.Pages[1].Accept(absorber);
// Get results of 
var results = absorber.RegexResults;
```

### 另请参阅

* 类 [TextSearchOptions](../../textsearchoptions/)
* 类 [TextFragmentAbsorber](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextSearchOptions, TextEditOptions) {#constructor_5}

初始化一个新的 [`TextFragmentAbsorber`](../) 类实例，用于指定的文本短语、文本搜索选项和文本编辑选项。

```csharp
public TextFragmentAbsorber(string phrase, TextSearchOptions textSearchOptions, 
    TextEditOptions textEditOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| phrase | String | [`TextFragmentAbsorber`](../) 搜索的短语 |
| textSearchOptions | TextSearchOptions | 文本搜索选项（允许启用某些搜索功能。例如，使用正则表达式搜索） |
| textEditOptions | TextEditOptions | 文本编辑选项（允许启用某些编辑功能）。 |

## 备注

执行指定短语的文本搜索，并通过 [`TextFragments`](../textfragments/) 集合提供对搜索结果的访问。

## 示例

该示例演示如何在第一个 PDF 文档页面上使用正则表达式查找文本并替换文本。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression.
TextFragmentAbsorber absorber = new TextFragmentAbsorber(@"h\w*?o", new TextSearchOptions(true));

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 另请参阅

* 类 [TextSearchOptions](../../textsearchoptions/)
* 类 [TextEditOptions](../../texteditoptions/)
* 类 [TextFragmentAbsorber](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(string, TextEditOptions) {#constructor_3}

初始化一个新的 [`TextFragmentAbsorber`](../) 类实例，用于指定的文本短语和文本编辑选项。

```csharp
public TextFragmentAbsorber(string phrase, TextEditOptions textEditOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| phrase | String | [`TextFragmentAbsorber`](../) 搜索的短语 |
| textEditOptions | TextEditOptions | 文本编辑选项（允许启用某些编辑功能）。 |

## 备注

执行指定短语的文本搜索，并通过 [`TextFragments`](../textfragments/) 集合提供对搜索结果的访问。

### 另请参阅

* 类 [TextEditOptions](../../texteditoptions/)
* 类 [TextFragmentAbsorber](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)

---

## TextFragmentAbsorber(Regex, TextEditOptions) {#constructor_7}

初始化一个新的 [`TextFragmentAbsorber`](../) 类实例，用于指定的文本短语和文本编辑选项。

```csharp
public TextFragmentAbsorber(Regex regex, TextEditOptions textEditOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| regex | Regex | [`TextFragmentAbsorber`](../) 搜索的 System.Text.RegularExpressions.Regex 类对象 |
| textEditOptions | TextEditOptions | 文本编辑选项（允许启用某些编辑功能）。 |

## 备注

执行指定短语的文本搜索，并通过 [`TextFragments`](../textfragments/) 集合提供对搜索结果的访问。

### 另请参阅

* 类 [TextEditOptions](../../texteditoptions/)
* 类 [TextFragmentAbsorber](../)
* 命名空间 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../../)