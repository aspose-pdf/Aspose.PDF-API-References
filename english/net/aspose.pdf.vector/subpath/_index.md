---
title: "SubPath Class"
linktitle: "SubPath"
articleTitle: "SubPath"
second_title: "Aspose.PDF for .NET"
description: "Represents vector graphics object on the page. Basically, vector graphics objects are represented by two groups of SubPaths. One of them is represented by a ..."
type: docs
weight: 60
url: "/net/aspose.pdf.vector/subpath/"
keywords: "SubPath, Aspose.Pdf.Vector, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## SubPath class

Represents vector graphics object on the page.
 Basically, vector graphics objects are represented by two groups of SubPaths.
 One of them is represented by a set of lines and curves.
 Others are presented as rectangles and can sometimes be confused.
 Usually it is a rectangular area that has a color, but very often this rectangle
 is placed at the beginning of the page and defines the entire space of the page in white.
 So you get the SubPath, but visually you only see the text on the page.

```csharp
public sealed class SubPath : GraphicElement
```

## Properties

| Name | Description |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Gets graphic element matrix. The matrix sets when element is created. *(Inherited from GraphicElement)* |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Gets a collection of operators representing the element. *(Inherited from GraphicElement)* |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; set; } | Gets the current [`XFormPlacement`](../../aspose.pdf.vector/xformplacement/) in which the element is located. *(Inherited from GraphicElement)* |
| [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | Gets or sets the position in the current coordinate space. *(Inherited from GraphicElement)* |
| [Rectangle](./rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Gets the page from which the graphic element is extracted. *(Inherited from GraphicElement)* |

## Methods

| Name | Description |
| --- | --- |
| [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(*Page*) | Adds current element on the page. *(Inherited from GraphicElement)* |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/) | Releases all resources used by the [`GraphicElement`](../../aspose.pdf.vector/graphicelement/) class. *(Inherited from GraphicElement)* |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)(*bool*) | Releases all resources used by the [`GraphicElement`](../../aspose.pdf.vector/graphicelement/) class. *(Inherited from GraphicElement)* |
| [FindDelta](../../aspose.pdf.vector/graphicelement/finddelta/)(*Point*) | *(Inherited from GraphicElement)* |
| [GetInitialPoint](./getinitialpoint/)(*double, double*) |  |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/) | Removes current element from the page. *(Inherited from GraphicElement)* |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/) | Converts the element into a single SVG image. *(Inherited from GraphicElement)* |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(*string*) | Converts the element into a single SVG image file. *(Inherited from GraphicElement)* |
| [SetPosition](../../aspose.pdf.vector/graphicelement/setposition/)(*Point*) | *(Inherited from GraphicElement)* |

## Fields

| Name | Description |
| --- | --- |
| readonly [_currentContent](../../aspose.pdf.vector/graphicelement/_currentcontent/) | *(Inherited from GraphicElement)* |
| [_graphicState](../../aspose.pdf.vector/graphicelement/_graphicstate/) | *(Inherited from GraphicElement)* |
| [_matrix](../../aspose.pdf.vector/graphicelement/_matrix/) | *(Inherited from GraphicElement)* |
| [_operators](../../aspose.pdf.vector/graphicelement/_operators/) | *(Inherited from GraphicElement)* |
| [_page](../../aspose.pdf.vector/graphicelement/_page/) | *(Inherited from GraphicElement)* |

### See Also

* class [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)

