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
| [Matrix](./matrix/) { get; } | Gets graphic element matrix. The matrix sets when element is created. |
| [Operators](./operators/) { get; } | Gets a collection of operators representing the element. |
| [Parent](./parent/) { get; set; } | Gets the current [`XFormPlacement`](../../aspose.pdf.vector/xformplacement/) in which the element is located. |
| [Position](./position/) { get; set; } | Gets or sets the position in the current coordinate space. |
| [Rectangle](./rectangle/) { get; } | Gets the bounding rectangle of the [`GraphicElement`](../../aspose.pdf.vector/graphicelement/). |
| [SourcePage](./sourcepage/) { get; } | Gets the page from which the graphic element is extracted. |

## Methods

| Name | Description |
| --- | --- |
| [AddOnPage](./addonpage/)(*Page*) | Adds current element on the page. |
| [Dispose](./dispose/) | Releases all resources used by the [`GraphicElement`](../../aspose.pdf.vector/graphicelement/) class. |
| [Dispose](./dispose/)(*bool*) | Releases all resources used by the [`GraphicElement`](../../aspose.pdf.vector/graphicelement/) class. |
| [FindDelta](./finddelta/)(*Point*) |  |
| [GetInitialPoint](./getinitialpoint/)(*double, double*) |  |
| [Remove](./remove/) | Removes current element from the page. |
| [SaveToSvg](./savetosvg/) | Converts the element into a single SVG image. |
| [SaveToSvg](./savetosvg/)(*string*) | Converts the element into a single SVG image file. |
| [SetPosition](./setposition/)(*Point*) |  |

## Fields

| Name | Description |
| --- | --- |
| readonly [_currentContent](./_currentcontent/) |  |
| [_graphicState](./_graphicstate/) |  |
| [_matrix](./_matrix/) |  |
| [_operators](./_operators/) |  |
| [_page](./_page/) |  |

### See Also

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)

