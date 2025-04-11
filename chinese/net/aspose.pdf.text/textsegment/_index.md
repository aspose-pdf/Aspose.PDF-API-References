---
title: Class TextSegment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextSegment class. 表示Pdf文本的片段
type: docs
weight: 11050
url: /zh/net/aspose.pdf.text/textsegment/
---
## TextSegment class

表示Pdf文本的片段。

```csharp
public sealed class TextSegment
```

## Constructors

| Name | Description |
| --- | --- |
| [TextSegment](textsegment/#constructor)() | 创建TextSegment对象。 |
| [TextSegment](textsegment/#constructor_1)(string) | 创建TextSegment对象。 |

## Properties

| Name | Description |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition/) { get; set; } | 获取文本的位置，由`TextSegment`对象表示。Position结构的YIndent表示文本片段的基线坐标。 |
| [Characters](../../aspose.pdf.text/textsegment/characters/) { get; } | 获取表示文本片段中字符信息的CharInfo对象集合。 |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex/) { get; } | 获取当前片段在显示文本操作符（Tj, TJ）片段中的结束字符索引。 |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink/) { get; set; } | 获取或设置片段超链接（用于pdf生成器）。 |
| [Position](../../aspose.pdf.text/textsegment/position/) { get; set; } | 获取文本的位置，由`TextSegment`对象表示。 |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle/) { get; } | 获取TextSegment的矩形 |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex/) { get; } | 获取当前片段在显示文本操作符（Tj, TJ）片段中的起始字符索引。 |
| [Text](../../aspose.pdf.text/textsegment/text/) { get; set; } | 获取或设置`TextSegment`对象表示的字符串文本对象。 |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions/) { get; set; } | 获取或设置文本编辑选项。选项定义在请求的符号无法用字体书写时的特殊行为。 |
| [TextState](../../aspose.pdf.text/textsegment/textstate/) { get; set; } | 获取或设置`TextSegment`对象表示的文本状态。 |

## Methods

| Name | Description |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode/)(string) | 将字符串编码为html。 |

## Remarks

简而言之，`TextSegment`对象是[`TextFragment`](../textfragment/)对象的子对象。详细来说：Pdf文档中的文本由两个基本对象表示：[`TextFragment`](../textfragment/)和`TextSegment`。它们之间的区别主要依赖于上下文。让我们考虑以下场景。用户搜索文本“hello world”以进行操作，改变其属性，查看等。

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

Pdf文本的物理表示非常复杂。文本“hello world”可能由几个物理上独立的文本片段组成。Aspose.Pdf文本模型基本上建立了[`TextFragment`](../textfragment/)对象提供对表示用户查询的物理`TextSegment`对象集的单一逻辑操作集。在文本搜索场景中，[`TextFragment`](../textfragment/)是逻辑“hello world”文本表示，而`TextSegment`对象集合表示构成“hello world”文本对象的所有物理片段。因此，[`TextFragment`](../textfragment/)接近逻辑文本表示。而`TextSegment`接近物理文本表示。显然，每个`TextSegment`对象可能具有自己的字体、颜色、定位属性。[`TextFragment`](../textfragment/)提供了一种简单的方法来更改文本及其属性：设置字体、设置字体大小、设置字体颜色等。与此同时，`TextSegment`对象是可访问的，用户能够独立操作`TextSegment`对象。

## Examples

该示例演示如何使用`TextSegment`对象的[`TextState`](./textstate/)对象更改文本的颜色和字体大小。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text segment of the first text occurrence
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text segment of the first text occurrence
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)