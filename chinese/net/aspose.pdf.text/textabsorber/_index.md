---
title: "类 TextAbsorber"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Text.TextAbsorber 类。表示文本的吸收器对象。执行文本提取并通过 Text 对象提供对结果的访问。"
type: docs
weight: 10980
url: /zh/net/aspose.pdf.text/textabsorber/
---
## TextAbsorber class

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
| [Errors](../../aspose.pdf.text/textabsorber/errors/) { get; } | [`TextExtractionError`](../textextractionerror/) 对象的列表。它包含在文本提取期间发现的错误信息。仅当 TextSearchOptions.LogTextExtractionErrors = true 时才会执行错误搜索；这可能会降低性能。 |
| virtual [ExtractionOptions](../../aspose.pdf.text/textabsorber/extractionoptions/) { get; set; } | 获取或设置文本提取选项。 |
| [HasErrors](../../aspose.pdf.text/textabsorber/haserrors/) { get; } | 该值指示在文本提取期间是否发现错误。仅当 TextSearchOptions.LogTextExtractionErrors = true 时才会执行错误搜索；这可能会降低性能。 |
| virtual [Text](../../aspose.pdf.text/textabsorber/text/) { get; } | 获取 `TextAbsorber` 在 PDF 文档或页面上提取的文本。 |
| virtual [TextSearchOptions](../../aspose.pdf.text/textabsorber/textsearchoptions/) { get; set; } | 获取或设置文本搜索选项。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit)(Document) | 在指定的文档上提取文本 |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_1)(Page) | 在指定的页面上提取文本 |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_2)(XForm) | 在指定的 XForm 上提取文本。 |

## 备注

`TextAbsorber` 对象用于从 PDF 文档或文档的页面中提取文本。

## 示例

此示例演示如何在第一个 PDF 文档页面上提取文本。

```csharp
// 打开文档
Document doc = new Document(inFile);

// 创建 TextAbsorber 对象以提取文本
TextAbsorber absorber = new TextAbsorber();

// 为第一页接受吸收器
doc.Pages[1].Accept(absorber);

// 获取提取的文本
string extractedText = absorber.Text;

```

### 另请参见

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


