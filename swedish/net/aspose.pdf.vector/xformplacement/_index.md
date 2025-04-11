---
title: Class XFormPlacement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vector.XFormPlacement-klass. Representerar XForm-placering. Om XForm visas på sidan mer än 1 gång kommer alla XformPlacements som är kopplade till denna XForm att ha gemensamma grafiska element men olika grafiska tillstånd.
type: docs
weight: 11260
url: /sv/net/aspose.pdf.vector/xformplacement/
---
## XFormPlacement klass

Representerar XForm placering. Om XForm visas på sidan mer än 1 gång, kommer alla XformPlacements kopplade till denna XForm att ha gemensamma grafiska element, men olika grafiska tillstånd.

```csharp
public sealed class XFormPlacement : GraphicElement
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Elements](../../aspose.pdf.vector/xformplacement/elements/) { get; } | Hämtar grafiska element inuti denna XForm. |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Hämtar grafiskt elementmatris. Matrisen sätts när elementet skapas. Den ändras när SetPosition() anropas. |
| [Name](../../aspose.pdf.vector/xformplacement/name/) { get; } | Hämtar namnet på XForm. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Hämtar en samling av operatörer som representerar elementet. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Hämtar den aktuella `XFormPlacement` där elementet är beläget. |
| override [Position](../../aspose.pdf.vector/xformplacement/position/) { set; } |  |
| override [Rectangle](../../aspose.pdf.vector/xformplacement/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Hämtar sidan från vilken det grafiska elementet extraheras. |
| [XForm](../../aspose.pdf.vector/xformplacement/xform/) { get; } | Hämtar XForm kopplad till denna XFormPlacement. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [AddOnPage](../../aspose.pdf.vector/xformplacement/addonpage/)(Page) | Lägger till det aktuella elementet på sidan. Om det finns många element att lägga till är det bättre att använda [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Frigör alla resurser som används av [`GraphicElement`](../graphicelement/) klassen. |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Tar bort det aktuella elementet från sidan. Om det finns många element att ta bort är det bättre att använda [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Konverterar elementet till en enda SVG-bild. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Konverterar elementet till en enda SVG-bildfil. |

### Se Även

* klass [GraphicElement](../graphicelement/)
* namnrymd [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)