---
title: "类 TextParagraph"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Text.TextParagraph 类。将文本段落表示为多行文本对象"
type: docs
weight: 11170
url: /zh/net/aspose.pdf.text/textparagraph/
---
## TextParagraph class

表示文本段落作为多行文本对象。

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
| [FirstLineIndent](../../aspose.pdf.text/textparagraph/firstlineindent/) { get; set; } | 获取或设置后续行缩进值。如果设置为非零值，则优于 FormattingOptions.SubsequentLinesIndent 值。 |
| [FormattingOptions](../../aspose.pdf.text/textparagraph/formattingoptions/) { get; set; } | 获取或设置格式选项。 |
| [HorizontalAlignment](../../aspose.pdf.text/textparagraph/horizontalalignment/) { get; set; } | 获取或设置段落内部文本的水平对齐方式，使用 [`Rectangle`](./rectangle/)。 |
| [Justify](../../aspose.pdf.text/textparagraph/justify/) { get; set; } | 获取或设置文本是否两端对齐的值。 |
| [Margin](../../aspose.pdf.text/textparagraph/margin/) { get; set; } | 获取或设置填充。 |
| [Position](../../aspose.pdf.text/textparagraph/position/) { get; set; } | 获取或设置段落的位置。 |
| [Rectangle](../../aspose.pdf.text/textparagraph/rectangle/) { get; set; } | 获取或设置段落的矩形。 |
| [Rotation](../../aspose.pdf.text/textparagraph/rotation/) { get; set; } | 获取或设置以度为单位的旋转角度。 |
| [SubsequentLinesIndent](../../aspose.pdf.text/textparagraph/subsequentlinesindent/) { get; set; } | 获取或设置后续行缩进值。如果设置为非零值，则优于 FormattingOptions.SubsequentLinesIndent 值。 |
| [TextRectangle](../../aspose.pdf.text/textparagraph/textrectangle/) { get; } | 获取放置在段落中的文本的矩形。 |
| [VerticalAlignment](../../aspose.pdf.text/textparagraph/verticalalignment/) { get; set; } | 获取或设置段落的[`Rectangle`](./rectangle/)内文本的垂直对齐方式。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_3)(string) | 追加文本行 |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline)(TextFragment) | 使用文本状态参数追加文本行。 |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_6)(string, float) | 追加文本行。 |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_4)(string, TextState) | 使用文本状态参数追加文本行。 |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_1)(TextFragment, TextState) | 使用文本状态参数追加文本行。 |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_5)(string, TextState, float) | 使用文本状态参数追加文本行 |
| [AppendLine](../../aspose.pdf.text/textparagraph/appendline/#appendline_2)(TextFragment, TextState, float) | 使用文本状态参数追加文本行 |
| [BeginEdit](../../aspose.pdf.text/textparagraph/beginedit/)() | 开始编辑 TextParagraph。 |
| [EndEdit](../../aspose.pdf.text/textparagraph/endedit/)() | 结束编辑 TextParagraph。 |

## 示例

此示例演示如何创建文本段落对象并将其追加到 Pdf 页面。

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// 创建文本段落
TextParagraph paragraph = new TextParagraph();
           
// 设置段落矩形
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// 设置自动换行选项
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// 追加字符串行
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// 使用 TextBuilder 将段落追加到 Pdf 页面
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// 保存 Pdf 文档
doc.Save(outFile);
```

### 另请参见

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


