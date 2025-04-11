---
title: Class MarkupParagraph
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.MarkupParagraph 类。表示一个段落
type: docs
weight: 10630
url: /zh/net/aspose.pdf.text/markupparagraph/
---
## MarkupParagraph class

表示一个段落。

```csharp
public sealed class MarkupParagraph
```

## Properties

| Name | Description |
| --- | --- |
| [ContinuationPageNumbers](../../aspose.pdf.text/markupparagraph/continuationpagenumbers/) { get; } | 段落继续的页面编号列表。如果段落在同一页面的下一列继续，它将与段落开始的页面匹配。 |
| [Fragments](../../aspose.pdf.text/markupparagraph/fragments/) { get; } | 段落中非空的 [`TextFragment`](../textfragment/) 对象的集合。 |
| [Lines](../../aspose.pdf.text/markupparagraph/lines/) { get; } | 段落的行。每一行由文本片段的列表表示。 |
| [Points](../../aspose.pdf.text/markupparagraph/points/) { get; } | 描述段落的多边形的点。起始点是段落的左下角。接下来的点按逆时针顺序排列。 |
| [SecondaryPoints](../../aspose.pdf.text/markupparagraph/secondarypoints/) { get; } | 描述段落继续的次级多边形的点。如果段落在下一列或页面继续，它将不为 null。起始点是段落的左下角。接下来的点按逆时针顺序排列。 |
| [Text](../../aspose.pdf.text/markupparagraph/text/) { get; set; } | 获取或设置段落文本。 |

### See Also

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)