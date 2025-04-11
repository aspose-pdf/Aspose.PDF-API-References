---
title: Class TextFragment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextFragment 类。表示 Pdf 文本的片段
type: docs
weight: 10940
url: /zh/net/aspose.pdf.text/textfragment/
---
## TextFragment class

表示 Pdf 文本的片段。

```csharp
public class TextFragment : BaseParagraph
```

## Constructors

| Name | Description |
| --- | --- |
| [TextFragment](textfragment/#constructor)() | 初始化 `TextFragment` 对象的新实例。 |
| [TextFragment](textfragment/#constructor_2)(string) | 创建包含单个 [`TextSegment`](../textsegment/) 对象的 `TextFragment` 对象。指定段落内的文本字符串。 |
| [TextFragment](textfragment/#constructor_1)(TabStops) | 使用预定义的 [`TabStops`](../tabstops/) 位置初始化 `TextFragment` 对象的新实例。 |
| [TextFragment](textfragment/#constructor_3)(string, TabStops) | 创建包含单个 [`TextSegment`](../textsegment/) 对象的 `TextFragment` 对象，并使用预定义的 [`TabStops`](../tabstops/) 位置。 |

## Properties

| Name | Description |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | 获取表示 `TextFragment` 对象的文本位置。Position 结构的 YIndent 表示文本片段的基线坐标。 |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | 获取或设置段落结束注释。（仅用于 PDF 生成） |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | 获取或设置段落脚注。（仅用于 PDF 生成） |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | 获取包含 TextFragment 的表单对象 |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | 获取或设置文本片段的水平对齐方式。 |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | 设置片段超链接 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 获取或设置一个布尔值，指示该段落是否位于下一列。默认值为 false。（用于 PDF 生成） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 获取或设置段落是否为内联。默认值为 false。（用于 PDF 生成） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 获取或设置一个布尔值，强制该段落在新页面生成。默认值为 false。（用于 PDF 生成） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 获取或设置一个布尔值，指示当前段落是否与下一个段落保持在同一页面。默认值为 false。（用于 PDF 生成） |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 获取或设置段落的外边距（用于 PDF 生成） |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | 获取包含 TextFragment 的页面 |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | 获取或设置表示 `TextFragment` 对象的文本位置。 |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | 获取 TextFragment 的矩形 |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | 获取文本替换选项。选项定义在片段文本被替换为更短/更长文本时的行为。 |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | 获取当前 `TextFragment` 的文本片段。 |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | 获取或设置 `TextFragment` 对象表示的字符串文本对象。 |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | 获取或设置文本编辑选项。选项定义在请求的符号无法用字体书写时的特殊行为。 |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | 获取或设置 `TextFragment` 对象表示的文本状态。 |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | 获取或设置文本片段的垂直对齐方式。 |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | 获取或设置该段落的换行数（仅用于 PDF 生成） |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 获取或设置一个整数值，指示图形的 Z 顺序。具有较大 ZIndex 的图形将放置在具有较小 ZIndex 的图形上方。ZIndex 可以为负数。具有负 ZIndex 的图形将放置在页面文本后面。 |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone/)() | 克隆片段。 |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments/)() | 克隆包含所有片段的片段。 |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | 获取表示 `TextFragment` 文本指定部分的 [`TextSegment`](../textsegment/) 对象。 |

## Remarks

简单来说，`TextFragment` 对象包含 [`TextSegment`](../textsegment/) 对象的列表。详细来说：Pdf 文档中的文本由两个基本对象表示：`TextFragment` 和 [`TextSegment`](../textsegment/)。它们之间的区别主要依赖于上下文。让我们考虑以下场景。用户搜索文本 "hello world" 以进行操作，改变其属性，查看等。

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

Pdf 文本的物理表示非常复杂。文本 "hello world" 可能由几个物理上独立的文本片段组成。Aspose.Pdf 文本模型基本上建立了 `TextFragment` 对象提供对表示用户查询的物理 [`TextSegment`](../textsegment/) 对象集的单一逻辑操作集。在文本搜索场景中，`TextFragment` 是逻辑的 "hello world" 文本表示，而 [`TextSegment`](../textsegment/) 对象集合表示构成 "hello world" 文本对象的所有物理片段。因此，`TextFragment` 接近逻辑文本表示。而 [`TextSegment`](../textsegment/) 接近物理文本表示。显然，每个 [`TextSegment`](../textsegment/) 对象可能具有自己的字体、颜色、定位属性。`TextFragment` 提供了一种简单的方法来更改文本及其属性：设置字体、设置字体大小、设置字体颜色等。同时，[`TextSegment`](../textsegment/) 对象是可访问的，用户能够独立操作 [`TextSegment`](../textsegment/) 对象。请注意，改变 TextFragment 属性可能会改变内部 [`Segments`](./segments/) 集合，因为 TextFragment 是一个聚合对象，它可能会重新排列内部片段或将它们合并为单个片段。如果您的要求是保持 [`Segments`](./segments/) 集合不变，请单独更改内部片段。

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

* class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)