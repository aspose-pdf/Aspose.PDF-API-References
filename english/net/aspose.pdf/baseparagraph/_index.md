---
title: "BaseParagraph Class"
linktitle: "BaseParagraph"
articleTitle: "BaseParagraph"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.BaseParagraph class. Represents a abstract base object can be added to the page(doc.Paragraphs.Add())."
type: docs
weight: 130
url: "/net/aspose.pdf/baseparagraph/"
keywords: "BaseParagraph, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## BaseParagraph class

Represents a abstract base object can be added to the page(doc.[Paragraphs](../paragraphs/).Add()).

```csharp
public abstract class BaseParagraph : ICloneable
```

## Properties

| Name | Description |
| --- | --- |
| virtual [HorizontalAlignment](./horizontalalignment/) { get; set; } | Gets or sets a horizontal alignment of paragraph |
| virtual [Hyperlink](./hyperlink/) { get; set; } | Gets or sets the fragment hyperlink(for pdf generator). |
| [IsFirstParagraphInColumn](./isfirstparagraphincolumn/) { get; set; } | Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [IsInLineParagraph](./isinlineparagraph/) { get; set; } | Gets or sets a paragraph is inline. Default is false.(for pdf generation) |
| [IsInNewPage](./isinnewpage/) { get; set; } | Gets or sets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [IsKeptWithNext](./iskeptwithnext/) { get; set; } | Gets or sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [Margin](./margin/) { get; set; } | Gets or sets a outer margin for paragraph (for pdf generation) |
| virtual [VerticalAlignment](./verticalalignment/) { get; set; } | Gets or sets a vertical alignment of paragraph |
| [ZIndex](./zindex/) { get; set; } | Gets or sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |

## Methods

| Name | Description |
| --- | --- |
| virtual [Clone](./clone/)() | Clones this instance. Virtual method. Always return null. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

