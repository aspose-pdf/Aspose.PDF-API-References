---
title: "MarkupParagraph Class"
linktitle: "MarkupParagraph"
articleTitle: "MarkupParagraph"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Text.MarkupParagraph class. Represents a paragraph."
type: docs
weight: 240
url: "/net/aspose.pdf.text/markupparagraph/"
keywords: "MarkupParagraph, Aspose.Pdf.Text, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## MarkupParagraph class

Represents a paragraph.

```csharp
public sealed class MarkupParagraph
```

## Properties

| Name | Description |
| --- | --- |
| [ContinuationPageNumbers](./continuationpagenumbers/) { get; } | List of page numbers on which the paragraph is continued. It will match with page where the paragraph started if it is continuing in the next column on the same page. |
| [Fragments](./fragments/) { get; } | Collection of not empty [`TextFragment`](../../aspose.pdf.text/textfragment/) objects of the paragraph. |
| [Lines](./lines/) { get; } | Lines of paragraph. Each line represented by list of text fragments. |
| [Points](./points/) { get; } | Points of polygon that describes paragraph. Starting point is lower left corner of the paragraph. And next points are in anti-clockwise sequence. |
| [SecondaryPoints](./secondarypoints/) { get; } | Points of secondary polygon describes paragraph continuation. It will not be null if the paragraph is continued in the next column or page. Starting point is lower left corner of the paragraph. And next points are in anti-clockwise sequence. |
| [Text](./text/) { get; set; } | Gets or sets the paragraph text. |

### See Also

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)

