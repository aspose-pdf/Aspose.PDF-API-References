---
title: Class GraphicElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vector.GraphicElement klass. Representerar basklass för grafiska objekt på sidan
type: docs
weight: 11180
url: /sv/net/aspose.pdf.vector/graphicelement/
---
## GraphicElement klass

Representerar basklass för grafiska objekt på sidan.

```csharp
public abstract class GraphicElement : IDisposable
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Hämtar grafikelementets matris. Matrisen sätts när elementet skapas. Den ändras när SetPosition() anropas. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Hämtar en samling av operatörer som representerar elementet. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Hämtar den aktuella [`XFormPlacement`](../xformplacement/) där elementet är beläget. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | Hämtar eller sätter positionen i det aktuella koordinatsystemet. Om [`Parent`](./parent/) inte är !:null så har elementet xForm-koordinatsystem. |
| abstract [Rectangle](../../aspose.pdf.vector/graphicelement/rectangle/) { get; } | Hämtar den begränsande rektangeln av `GraphicElement`. |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Hämtar sidan från vilken grafikelementet extraheras. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | Lägger till det aktuella elementet på sidan. Om det finns många element att lägga till är det bättre att använda [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Frigör alla resurser som används av `GraphicElement` klassen. |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Tar bort det aktuella elementet från sidan. Om det finns många element att ta bort är det bättre att använda [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg)() | Konverterar elementet till en enda SVG-bild. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg_1)(string) | Konverterar elementet till en enda SVG-bildfil. |

### Se Även

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)