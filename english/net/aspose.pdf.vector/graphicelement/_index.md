---
title: "GraphicElement Class"
linktitle: "GraphicElement"
articleTitle: "GraphicElement"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Vector.GraphicElement class. Represents base class for graphics object on the page."
type: docs
weight: 20
url: "/net/aspose.pdf.vector/graphicelement/"
keywords: "GraphicElement, Aspose.Pdf.Vector, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## GraphicElement class

Represents base class for graphics object on the page.

```csharp
public abstract class GraphicElement : IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [Matrix](./matrix/) { get; } | Gets graphic element matrix. The matrix sets when element is created. It changes when SetPosition() is called. |
| [Operators](./operators/) { get; } | Gets a collection of operators representing the element. |
| [Parent](./parent/) { get; set; } | Gets the current [`XFormPlacement`](../../aspose.pdf.vector/xformplacement/) in which the element is located. |
| virtual [Position](./position/) { get; set; } | Gets or sets the position in the current coordinate space. If `Parent` is not `!:null` then the element have xForm coordinate space. |
| abstract [Rectangle](./rectangle/) { get; } | Gets the bounding rectangle of the [`GraphicElement`](../../aspose.pdf.vector/graphicelement/). |
| [SourcePage](./sourcepage/) { get; } | Gets the page from which the graphic element is extracted. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddOnPage](./addonpage/)(Page) | Adds current element on the page. If there are many elements to add better use `AddGraphics`. |
| [Dispose](./dispose/)() | Releases all resources used by the [`GraphicElement`](../../aspose.pdf.vector/graphicelement/) class. |
| [Remove](./remove/)() | Removes current element from the page. If there are many elements to remove better use `DeleteGraphics`. |
| [SaveToSvg](./savetosvg/)() | Converts the element into a single SVG image. |
| [SaveToSvg](./savetosvg/)(string) | Converts the element into a single SVG image file. |

### See Also

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)

