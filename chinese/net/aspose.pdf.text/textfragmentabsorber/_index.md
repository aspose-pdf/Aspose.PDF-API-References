---
title: Class TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextFragmentAbsorber class. 表示文本片段的吸收器对象。执行文本搜索并通过 TextFragments 集合提供对搜索结果的访问
type: docs
weight: 10950
url: /zh/net/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber class

表示文本片段的吸收器对象。执行文本搜索并通过 [`TextFragments`](./textfragments/) 集合提供对搜索结果的访问。

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## Constructors

| Name | Description |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor)() | 初始化一个新的 `TextFragmentAbsorber` 实例，该实例执行文档或页面的所有文本段的搜索。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_6)(Regex) | 为指定的 System.Text.RegularExpressions.Regex 类对象初始化一个新的 `TextFragmentAbsorber` 实例。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_2)(string) | 为指定的文本短语初始化一个新的 `TextFragmentAbsorber` 实例。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_1)(TextEditOptions) | 使用文本编辑选项初始化一个新的 `TextFragmentAbsorber` 实例，该实例执行文档或页面的所有文本段的搜索。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_7)(Regex, TextEditOptions) | 为指定的文本短语和文本编辑选项初始化一个新的 `TextFragmentAbsorber` 实例。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_8)(Regex, TextSearchOptions) | 为指定的文本短语和文本搜索选项初始化一个新的 `TextFragmentAbsorber` 实例。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_9)(Regex[], TextSearchOptions) | 为指定的文本短语和文本搜索选项初始化一个新的 `TextFragmentAbsorber` 实例。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_3)(string, TextEditOptions) | 为指定的文本短语和文本编辑选项初始化一个新的 `TextFragmentAbsorber` 实例。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_4)(string, TextSearchOptions) | 为指定的文本短语和文本搜索选项初始化一个新的 `TextFragmentAbsorber` 实例。 |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_5)(string, TextSearchOptions, TextEditOptions) | 为指定的文本短语、文本搜索选项和文本编辑选项初始化一个新的 `TextFragmentAbsorber` 实例。 |

## Properties

| Name | Description |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors/) { get; } | [`TextExtractionError`](../textextractionerror/) 对象的列表。它包含在文本提取过程中发现的错误的信息。仅当 TextSearchOptions.LogTextExtractionErrors = true 时才会搜索错误；这可能会降低性能。 |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions/) { get; set; } | 获取或设置文本提取选项。 |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors/) { get; } | 值指示在文本提取过程中是否发现错误。仅当 TextSearchOptions.LogTextExtractionErrors = true 时才会搜索错误；这可能会降低性能。 |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase/) { get; set; } | 获取或设置 `TextFragmentAbsorber` 在 PDF 文档或页面上搜索的短语。 |
| [RegexResults](../../aspose.pdf.text/textfragmentabsorber/regexresults/) { get; } | 获取以 System.Text.RegularExpressions.Regex 类作为键和 [`TextFragment`](../textfragment/) 作为值的搜索出现次数的字典。 |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text/) { get; } | 获取 [`TextAbsorber`](../textabsorber/) 在 PDF 文档或页面上提取的文本。 |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions/) { get; set; } | 获取或设置文本编辑选项。该选项定义在请求的符号无法用字体书写时的特殊行为。 |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments/) { get; set; } | 获取以 [`TextFragment`](../textfragment/) 对象表示的搜索出现次数的集合。 |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions/) { get; set; } | 获取或设置文本替换选项。该选项定义在片段文本被替换为更短/更长文本时的行为。 |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions/) { get; set; } | 获取或设置搜索选项。该选项启用使用正则表达式进行搜索。 |

## Methods

| Name | Description |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_2)(float) | 为所有被吸收的文本片段应用字体大小。如果所有页面上的所有片段都被吸收，它的速度比循环遍历片段更快。否则，它的工作方式与循环相似。 |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments)(Font) | 为所有被吸收的文本片段应用字体。如果所有页面上的所有片段都被吸收，它的速度比循环遍历片段更快。否则，它的工作方式与循环相似。 |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_1)(Font, float) | 为所有被吸收的文本片段应用字体和大小。如果所有页面上的所有片段都被吸收，它的速度比循环遍历片段更快。否则，它的工作方式与循环相似。 |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext)(Document) | 从文档中移除所有文本。 |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_1)(Page) | 从指定页面中移除所有文本。 |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_2)(Page, Rectangle) | 从指定页面中移除指定矩形内的文本。 |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset/)() | 清除此 `TextFragmentAbsorber` 对象的 TextFragments 集合。 |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit)(Document) | 在指定文档上执行搜索。 |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_1)(Page) | 在指定页面上执行搜索。 |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_2)(XForm) | 在指定表单对象上执行搜索。 |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/)(XForm) | 在指定的 XForm 上提取文本。 |

## Remarks

`TextFragmentAbsorber` 对象主要用于文本搜索场景。当搜索完成时，出现的次数用 [`TextFragment`](../textfragment/) 对象表示，这些对象包含在 [`TextFragments`](./textfragments/) 集合中。[`TextFragment`](../textfragment/) 对象提供对搜索出现文本、文本属性的访问，并允许编辑文本和更改文本状态（字体、字体大小、颜色等）。

## Examples

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

### See Also

* class [TextAbsorber](../textabsorber/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)