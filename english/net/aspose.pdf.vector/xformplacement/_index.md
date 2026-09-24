---
title: "XFormPlacement Class"
linktitle: "XFormPlacement"
articleTitle: "XFormPlacement"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Vector.XFormPlacement class. Represents XForm placement. If the XForm is displayed on the page more than 1 time, all XformPlacements associated wi..."
type: docs
weight: 100
url: "/net/aspose.pdf.vector/xformplacement/"
keywords: "XFormPlacement, Aspose.Pdf.Vector, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## XFormPlacement class

Represents XForm placement.
 If the XForm is displayed on the page more than 1 time,
 all XformPlacements associated with this XForm will have common graphical elements, but different graphical states.

```csharp
public sealed class XFormPlacement : GraphicElement
```

## Properties

| Name | Description |
| --- | --- |
| [Elements](./elements/) { get; } | Gets graphic elements inside this XForm. |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Gets graphic element matrix. The matrix sets when element is created. *(Inherited from GraphicElement)* |
| [Name](./name/) { get; } | Gets name of the XForm. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Gets a collection of operators representing the element. *(Inherited from GraphicElement)* |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; set; } | Gets the current [`XFormPlacement`](../../aspose.pdf.vector/xformplacement/) in which the element is located. *(Inherited from GraphicElement)* |
| [Position](./position/) { set; } |  |
| [Rectangle](./rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Gets the page from which the graphic element is extracted. *(Inherited from GraphicElement)* |
| [XForm](./xform/) { get; } | Gets XForm associated with this XFormPlacement. |

## Methods

| Name | Description |
| --- | --- |
| [AddOnPage](./addonpage/)(*Page*) | Adds current element on the page. |
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

