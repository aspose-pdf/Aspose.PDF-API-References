---
title: "类 Heading"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Heading 类。表示标题"
type: docs
weight: 5590
url: /zh/net/aspose.pdf/heading/
---
## Heading class

表示标题。

```csharp
public sealed class Heading : TextFragment
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Heading](heading/)(int) | 初始化 Cell 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | 获取文本的位置，文本由 [`TextFragment`](../../aspose.pdf.text/textfragment/) 对象表示。Position 结构的 YIndent 表示文本片段的基线坐标。 |
| [DestinationPage](../../aspose.pdf/heading/destinationpage/) { get; set; } | 获取目标页面。 |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | 获取或设置段落结束注释。（仅用于 PDF 生成） |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | 获取或设置段落脚注。（仅用于 PDF 生成） |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | 获取包含 TextFragment 的表单对象 |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | 获取或设置文本片段的水平对齐方式。 |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | 设置片段超链接 |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence/) { get; set; } | 获取标题是否应自动编号。 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 获取或设置一个布尔值，指示此段落是否将在下一列。默认值为 false。（用于 pdf 生成） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 获取或设置段落是否为内联。默认值为 false。（用于 pdf 生成） |
| [IsInList](../../aspose.pdf/heading/isinlist/) { get; set; } | 获取标题是否应出现在目录列表中。 |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 获取或设置一个布尔值，强制此段落在新页面生成。默认值为 false。（用于 pdf 生成） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 获取或设置一个布尔值，指示当前段落是否与下一段落保持在同一页。默认值为 false。（用于 pdf 生成） |
| [Level](../../aspose.pdf/heading/level/) { get; set; } | 获取级别。 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 获取或设置段落的外边距（用于 pdf 生成） |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | 获取包含 TextFragment 的页面 |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | 获取或设置文本的位置，文本由 [`TextFragment`](../../aspose.pdf.text/textfragment/) 对象表示。 |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | 获取 TextFragment 的矩形 |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | 获取文本替换选项。该选项定义在将片段文本替换为更短或更长时的行为。 |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | 获取当前 [`TextFragment`](../../aspose.pdf.text/textfragment/) 的文本段。 |
| [StartNumber](../../aspose.pdf/heading/startnumber/) { get; set; } | 获取标题起始编号。 |
| [Style](../../aspose.pdf/heading/style/) { get; set; } | 获取或设置样式。 |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | 获取或设置 [`TextFragment`](../../aspose.pdf.text/textfragment/) 对象表示的字符串文本对象。 |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | 获取或设置文本编辑选项。该选项定义当请求的符号无法使用字体写入时的特殊行为。 |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | 获取或设置 [`TextFragment`](../../aspose.pdf.text/textfragment/) 对象表示的文本的文本状态。 |
| [TocPage](../../aspose.pdf/heading/tocpage/) { get; set; } | 获取包含此标题的页面。 |
| [Top](../../aspose.pdf/heading/top/) { get; set; } | 获取此标题的顶部 Y 坐标。 |
| [UserLabel](../../aspose.pdf/heading/userlabel/) { get; set; } | 获取或设置用户标签。 |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | 获取或设置文本片段的垂直对齐方式。 |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | 获取或设置此段落的换行行数（仅用于 PDF 生成） |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 获取或设置一个整数值，指示图形的 Z 顺序。ZIndex 较大的图形将位于 ZIndex 较小的图形之上。ZIndex 可以为负数。ZIndex 为负的图形将位于页面文本的后面。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone/)() | 克隆标题。 |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments/)() | 克隆包含所有段落的标题。 |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | 获取表示[`TextFragment`](../../aspose.pdf.text/textfragment/) 文本中指定部分的[`TextSegment`](../../aspose.pdf.text/textsegment/)(s)。 |

### 另请参见

* class [TextFragment](../../aspose.pdf.text/textfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


