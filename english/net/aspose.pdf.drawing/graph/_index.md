---
title: "Graph Class"
linktitle: "Graph"
articleTitle: "Graph"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Drawing.Graph class. Represents graph - graphics generator paragraph."
type: docs
weight: 80
url: "/net/aspose.pdf.drawing/graph/"
keywords: "Graph, Aspose.Pdf.Drawing, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Graph class

Represents graph - graphics generator paragraph.

```csharp
public sealed class Graph : BaseParagraph
```

## Constructors

| Name | Description |
| --- | --- |
| [Graph](./graph/)(double, double) | Initializes a new instance of the [`Graph`](../../aspose.pdf.drawing/graph/) class. |

## Properties

| Name | Description |
| --- | --- |
| [Border](./border/) { get; set; } | Gets or sets the border. |
| [GraphInfo](./graphinfo/) { get; set; } | Gets or sets a `GraphInfo` object that indicates the graph info,such as color, line width,etc. |
| [Height](./height/) { get; set; } | Gets or sets a float value that indicates the graph height. The unit is point. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Gets or sets a horizontal alignment of paragraph |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Gets or sets the fragment hyperlink(for pdf generator). |
| [IsChangePosition](./ischangeposition/) { get; set; } | Gets or sets change curret position after process paragraph.(default true) |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Gets or sets a paragraph is inline. Default is false.(for pdf generation) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Gets or sets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Gets or sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [Left](./left/) { get; set; } | Gets or sets the table left coordinate. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Gets or sets a outer margin for paragraph (for pdf generation) |
| [Shapes](./shapes/) { get; set; } | Gets or sets a `Shapes` collection that indicates all shapes in the graph. |
| [Title](./title/) { get; set; } | Gets or sets a string value that indicates the title of the graph. |
| [Top](./top/) { get; set; } | Gets or sets the table top coordinate. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Gets or sets a vertical alignment of paragraph |
| [Width](./width/) { get; set; } | Gets or sets a float value that indicates the graph width. The unit is point. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Gets or sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](./clone/)() | Clone the graph. |

### See Also

* class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namespace [Aspose.Pdf.Drawing](../../aspose.pdf.drawing/)
* assembly [Aspose.PDF](../../)

