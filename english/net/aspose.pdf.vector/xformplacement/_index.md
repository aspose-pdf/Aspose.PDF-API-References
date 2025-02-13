---
title: Class XFormPlacement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vector.XFormPlacement class. Represents XForm placement. If the XForm is displayed on the page more than 1 time all XformPlacements associated with this XForm will have common graphical elements but different graphical states
type: docs
weight: 10210
url: /net/aspose.pdf.vector/xformplacement/
---
## XFormPlacement class

Represents XForm placement. If the XForm is displayed on the page more than 1 time, all XformPlacements associated with this XForm will have common graphical elements, but different graphical states.

```csharp
public sealed class XFormPlacement : GraphicElement
```

## Properties

| Name | Description |
| --- | --- |
| [Elements](../../aspose.pdf.vector/xformplacement/elements/) { get; } | Gets graphic elements inside this XForm. |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Gets graphic element matrix. The matrix sets when element is created. It changes when SetPosition() is called. |
| [Name](../../aspose.pdf.vector/xformplacement/name/) { get; } | Gets name of the XForm. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Gets a collection of operators representing the element. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Gets the current `XFormPlacement` in which the element is located. |
| override [Position](../../aspose.pdf.vector/xformplacement/position/) { set; } |  |
| override [Rectangle](../../aspose.pdf.vector/xformplacement/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Gets the page from which the graphic element is extracted. |
| [XForm](../../aspose.pdf.vector/xformplacement/xform/) { get; } | Gets XForm associated with this XFormPlacement. |

## Methods

| Name | Description |
| --- | --- |
| override [AddOnPage](../../aspose.pdf.vector/xformplacement/addonpage/)(Page) | Adds current element on the page. If there are many elements to add better use [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Releases all resources used by the [`GraphicElement`](../graphicelement/) class. |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Removes current element from the page. If there are many elements to remove better use [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Converts the element into a single SVG image. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Converts the element into a single SVG image file. |

### See Also

* class [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


