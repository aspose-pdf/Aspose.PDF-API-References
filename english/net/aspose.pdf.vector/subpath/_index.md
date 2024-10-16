---
title: Class SubPath
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vector.SubPath class. Represents vector graphics object on the page. Basically vector graphics objects are represented by two groups of SubPaths. One of them is represented by a set of lines and curves. Others are presented as rectangles and can sometimes be confused. Usually it is a rectangular area that has a color but very often this rectangle is placed at the beginning of the page and defines the entire space of the page in white. So you get the SubPath but visually you only see the text on the page
type: docs
weight: 8460
url: /net/aspose.pdf.vector/subpath/
---
## SubPath class

Represents vector graphics object on the page. Basically, vector graphics objects are represented by two groups of SubPaths. One of them is represented by a set of lines and curves. Others are presented as rectangles and can sometimes be confused. Usually it is a rectangular area that has a color, but very often this rectangle is placed at the beginning of the page and defines the entire space of the page in white. So you get the SubPath, but visually you only see the text on the page.

```csharp
public sealed class SubPath : GraphicElement
```

## Properties

| Name | Description |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Gets graphic element matrix. The matrix sets when element is created. It changes when SetPosition() is called. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Gets a collection of operators representing the element. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Gets the current [`XFormPlacement`](../xformplacement/) in which the element is located. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | Gets or sets the position in the current coordinate space. If [`Parent`](../graphicelement/parent/) is not !:null then the element have xForm coordinate space. |
| override [Rectangle](../../aspose.pdf.vector/subpath/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Gets the page from which the graphic element is extracted. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | Adds current element on the page. If there are many elements to add better use [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Releases all resources used by the [`GraphicElement`](../graphicelement/) class. |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Removes current element from the page. If there are many elements to remove better use [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Converts the element into a single SVG image. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Converts the element into a single SVG image file. |

### See Also

* class [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


