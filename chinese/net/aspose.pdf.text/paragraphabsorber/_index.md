---
title: Class ParagraphAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.ParagraphAbsorber class. 表示页面结构对象（如节和段落）的吸收器对象。执行文本节和段落的搜索，并提供对描述其在文本坐标空间中的矩形和多边形的访问。还执行文本段落搜索，并通过按结构元素分组的 TextFragments 集合提供对搜索结果的访问。
type: docs
weight: 10670
url: /zh/net/aspose.pdf.text/paragraphabsorber/
---
## ParagraphAbsorber class

表示页面结构对象（如节和段落）的吸收器对象。执行文本节和段落的搜索，并提供对描述其在文本坐标空间中的矩形和多边形的访问。还执行文本段落搜索，并通过 !:TextFragments 集合提供对搜索结果的访问，这些集合按结构元素分组。

```csharp
public class ParagraphAbsorber
```

## Constructors

| Name | Description |
| --- | --- |
| [ParagraphAbsorber](paragraphabsorber/#constructor)() | 初始化一个新的 `ParagraphAbsorber` 实例，该实例执行对文档或页面的节/段落的搜索。 |
| [ParagraphAbsorber](paragraphabsorber/#constructor_2)(int) | 初始化一个新的 `ParagraphAbsorber` 实例，该实例执行对文档或页面的节/段落的搜索。 |
| [ParagraphAbsorber](paragraphabsorber/#constructor_1)(ParagraphAbsorberOptions) | 初始化一个新的 `ParagraphAbsorber` 实例，该实例使用指定的参数执行对文档或页面的节/段落的搜索。 |
| [ParagraphAbsorber](paragraphabsorber/#constructor_3)(int, ParagraphAbsorberOptions) | 初始化一个新的 `ParagraphAbsorber` 实例，该实例使用指定的参数执行对文档或页面的节/段落的搜索。 |

## Properties

| Name | Description |
| --- | --- |
| [IsMulticolumnParagraphsAllowed](../../aspose.pdf.text/paragraphabsorber/ismulticolumnparagraphsallowed/) { get; set; } | 获取或设置一个值，该值指示下一个节的起始文本行是否可以视为前一个节最后一个段落的延续。 |
| [PageMarkups](../../aspose.pdf.text/paragraphabsorber/pagemarkups/) { get; } | 获取已吸收的 [`PageMarkup`](../pagemarkup/) 集合。 |
| [ParagraphAbsorberOptions](../../aspose.pdf.text/paragraphabsorber/paragraphabsorberoptions/) { get; set; } | 获取或设置 ParagraphAbsorberOptions。 |
| [SectionsSearchDepth](../../aspose.pdf.text/paragraphabsorber/sectionssearchdepth/) { get; set; } | 获取或设置一个值，该值指示将执行多少次对结构更细元素的顺序搜索。默认搜索深度为 3。这意味着对水平划分的节（标题、段落等）进行三次搜索，对垂直划分的节（列）进行三次搜索。 |
| [TextReplaceOptions](../../aspose.pdf.text/paragraphabsorber/textreplaceoptions/) { get; set; } | 获取或设置 TextReplaceOptions。 |

## Methods

| Name | Description |
| --- | --- |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit)(Document) | 在指定的 [`Document`](../../aspose.pdf/document/) 上执行节和段落的搜索。 |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit_1)(Page) | 在指定的 [`Page`](../../aspose.pdf/page/) 上执行搜索。 |

## Remarks

当搜索完成时，[`PageMarkups`](./pagemarkups/) 集合将包含表示页面结构的 [`PageMarkup`](../pagemarkup/) 对象，这些对象由 [`MarkupSection`](../markupsection/) 和 [`MarkupParagraph`](../markupparagraph/) 的集合组成。[`TextFragment`](../textfragment/) 对象提供对搜索出现文本、文本属性的访问，并允许编辑文本和更改文本状态（字体、字体大小、颜色等）。

## Examples

该示例演示如何找到每个段落在第一个 PDF 文档页面上的第一个文本段并突出显示它。

```csharp
// Open document
Document doc = new Document("input.pdf");

// Create ParagraphAbsorber object
ParagraphAbsorber absorber = new ParagraphAbsorber();

// Accept the absorber for first page
absorber.Visit(doc.Pages[1]);

// Get markup object of first page
PageMarkup markup = absorber.PageMarkups[0];

// Loop through structure elements of the page text to find first text fragment of each paragraph
foreach (MarkupSection section in markup.Sections)
{
    foreach (MarkupParagraph paragraph in section.Paragraphs)
    {
        TextFragment fragment = paragraph.Fragments[0];
        // Update text properties
        fragment.TextState.BackgroundColor = Color.LightBlue;
    }
}

// Save document
doc.Save(GetOutputPath("output.pdf"));
```

### See Also

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)