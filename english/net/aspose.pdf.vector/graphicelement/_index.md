---
title: Class GraphicElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vector.GraphicElement class. Represents base class for graphics object on the page
type: docs
weight: 11330
url: /net/aspose.pdf.vector/graphicelement/
---
## GraphicElement class

Represents base class for graphics object on the page.

```csharp
public abstract class GraphicElement : IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Gets graphic element matrix. The matrix sets when element is created. It changes when SetPosition() is called. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Gets a collection of operators representing the element. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Gets the current [`XFormPlacement`](../xformplacement/) in which the element is located. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | Gets or sets the position in the current coordinate space. If [`Parent`](./parent/) is not !:null then the element have xForm coordinate space. |
| abstract [Rectangle](../../aspose.pdf.vector/graphicelement/rectangle/) { get; } | Gets the bounding rectangle of the `GraphicElement`. |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Gets the page from which the graphic element is extracted. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | Adds current element on the page. If there are many elements to add better use [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Releases all resources used by the `GraphicElement` class. |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Removes current element from the page. If there are many elements to remove better use [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg)() | Converts the element into a single SVG image. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg_1)(string) | Converts the element into a single SVG image file. |

### See Also

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


