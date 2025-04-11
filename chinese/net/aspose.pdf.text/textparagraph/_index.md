---
title: Class TextParagraph
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextParagraph 类。表示多行文本对象的文本段落
type: docs
weight: 10990
url: /zh/net/aspose.pdf.text/textparagraph/
---
## TextParagraph 类

表示多行文本对象的文本段落。

```csharp
public sealed class TextParagraph
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TextParagraph](textparagraph/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [FirstLineIndent](../../aspose.pdf.text/textparagraph/firstlineindent/) { get; set; } | 获取或设置后续行的缩进值。如果设置为非零值，它比 FormattingOptions.SubsequentLinesIndent 值更具优势。 |
| [FormattingOptions](../../aspose.pdf.text/textparagraph/formattingoptions/) { get; set; } | 获取或设置格式化选项。 |
| [HorizontalAlignment](../../aspose.pdf.text/textparagraph/horizontalalignment/) { get; set; } | 获取或设置段落内文本的水平对齐方式 [`Rectangle`](./rectangle/)。 |
| [Justify](../../aspose.pdf.text/textparagraph/justify/) { get; set; } | 获取或设置文本是否被对齐的值。 |
| [Margin](../../aspose.pdf.text/textparagraph/margin/) { get; set; } | 获取或设置填充。 |
| [Position](../../aspose.pdf.text/textparagraph/position/) { get; set; } | 获取或设置段落的位置。 |
| [Rectangle](../../aspose.pdf.text/textparagraph/rectangle/) { get; set; } | 获取或设置段落的矩形。 |
| [Rotation](../../aspose.pdf.text/textparagraph/rotation/) { get; set; } | 获取或设置旋转角度（以度为单位）。 |
| [SubsequentLinesIndent](../../aspose.pdf.text/textparagraph/subsequentlinesindent/) { get; set; } | 获取或设置后续行的缩进值。如果设置为非零值，它比 FormattingOptions.SubsequentLinesIndent 值更具优势。 |
| [TextRectangle](../../aspose.pdf.text/textparagraph/textrectangle/) { get; } | 获取放置在段落中的文本的矩形。 |
| [VerticalAlignment](../../aspose.pdf.text/textparagraph/verticalalignment/) { get; set; } | 获取或设置段落内文本的垂直对齐方式 [`Rectangle`](./rectangle/)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_3)(string) | 添加文本行 |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline)(TextFragment) | 添加带有文本状态参数的文本行。 |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_6)(string, float) | 添加文本行。 |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_4)(string, TextState) | 添加带有文本状态参数的文本行。 |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_1)(TextFragment, TextState) | 添加带有文本状态参数的文本行。 |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_5)(string, TextState, float) | 添加带有文本状态参数的文本行 |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_2)(TextFragment, TextState, float) | 添加带有文本状态参数的文本行 |
| [BeginEdit](../../aspose.pdf.text/textparagraph/beginedit/)() | 开始编辑 TextParagraph。 |
| [EndEdit](../../aspose.pdf.text/textparagraph/endedit/)() | 结束编辑 TextParagraph。 |

## 示例

该示例演示如何创建文本段落对象并将其附加到 Pdf 页面。

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// create text paragraph
TextParagraph paragraph = new TextParagraph();
           
// set the paragraph rectangle
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// set word wrapping options
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// append string lines
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// append the paragraph to the Pdf page with the TextBuilder
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// save Pdf document
doc.Save(outFile);
```

### 另请参阅

* 命名空间 [Aspose.Pdf.Text](../../aspose.pdf.text/)
* 程序集 [Aspose.PDF](../../)