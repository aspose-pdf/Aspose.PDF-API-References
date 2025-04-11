---
title: Class TextAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextAbsorber 类。表示文本的吸收器对象。执行文本提取并通过 Text 对象提供对结果的访问
type: docs
weight: 10800
url: /zh/net/aspose.pdf.text/textabsorber/
---
## TextAbsorber 类

表示文本的吸收器对象。执行文本提取并通过 [`Text`](./text/) 对象提供对结果的访问。

```csharp
public class TextAbsorber
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TextAbsorber](textabsorber/#constructor)() | 初始化 `TextAbsorber` 的新实例。 |
| [TextAbsorber](textabsorber/#constructor_1)(TextExtractionOptions) | 使用提取选项初始化 `TextAbsorber` 的新实例。 |
| [TextAbsorber](textabsorber/#constructor_3)(TextSearchOptions) | 使用文本搜索选项初始化 `TextAbsorber` 的新实例。 |
| [TextAbsorber](textabsorber/#constructor_2)(TextExtractionOptions, TextSearchOptions) | 使用提取和文本搜索选项初始化 `TextAbsorber` 的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Errors](../../aspose.pdf.text/textabsorber/errors/) { get; } | [`TextExtractionError`](../textextractionerror/) 对象的列表。它包含在文本提取过程中发现的错误的信息。仅当 TextSearchOptions.LogTextExtractionErrors = true 时才会搜索错误；这可能会降低性能。 |
| virtual [ExtractionOptions](../../aspose.pdf.text/textabsorber/extractionoptions/) { get; set; } | 获取或设置文本提取选项。 |
| [HasErrors](../../aspose.pdf.text/textabsorber/haserrors/) { get; } | 值指示在文本提取过程中是否发现错误。仅当 TextSearchOptions.LogTextExtractionErrors = true 时才会搜索错误；这可能会降低性能。 |
| virtual [Text](../../aspose.pdf.text/textabsorber/text/) { get; } | 获取 `TextAbsorber` 在 PDF 文档或页面上提取的文本。 |
| virtual [TextSearchOptions](../../aspose.pdf.text/textabsorber/textsearchoptions/) { get; set; } | 获取或设置文本搜索选项。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit)(Document) | 提取指定文档上的文本 |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_1)(Page) | 提取指定页面上的文本 |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_2)(XForm) | 提取指定 XForm 上的文本。 |

## 备注

`TextAbsorber` 对象用于从 Pdf 文档或文档的页面中提取文本。

## 示例

该示例演示如何提取第一个 PDF 文档页面上的文本。

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for first page
doc.Pages[1].Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### 另请参阅

* 命名空间 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../)