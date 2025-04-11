---
title: Class SubPath
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vector.SubPath klass. Representerar vektorgrafikobjekt på sidan. I grund och botten representeras vektorgrafikobjekt av två grupper av SubPaths. En av dem representeras av en uppsättning linjer och kurvor. Andra presenteras som rektanglar och kan ibland förväxlas. Vanligtvis är det ett rektangulärt område som har en färg, men mycket ofta placeras denna rektangel i början av sidan och definierar hela sidans utrymme i vitt. Så du får SubPath, men visuellt ser du bara texten på sidan.
type: docs
weight: 11220
url: /sv/net/aspose.pdf.vector/subpath/
---
## SubPath klass

Representerar vektorgrafikobjekt på sidan. I grund och botten representeras vektorgrafikobjekt av två grupper av SubPaths. En av dem representeras av en uppsättning linjer och kurvor. Andra presenteras som rektanglar och kan ibland förväxlas. Vanligtvis är det ett rektangulärt område som har en färg, men mycket ofta placeras denna rektangel i början av sidan och definierar hela sidans utrymme i vitt. Så du får SubPath, men visuellt ser du bara texten på sidan.

```csharp
public sealed class SubPath : GraphicElement
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Hämtar grafikelementets matris. Matrisen sätts när elementet skapas. Den ändras när SetPosition() anropas. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Hämtar en samling av operatörer som representerar elementet. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Hämtar den aktuella [`XFormPlacement`](../xformplacement/) där elementet är beläget. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | Hämtar eller sätter positionen i det aktuella koordinatsystemet. Om [`Parent`](../graphicelement/parent/) inte är !:null så har elementet xForm-koordinatsystem. |
| override [Rectangle](../../aspose.pdf.vector/subpath/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Hämtar sidan från vilken grafikelementet extraheras. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | Lägger till det aktuella elementet på sidan. Om det finns många element att lägga till är det bättre att använda [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Frigör alla resurser som används av [`GraphicElement`](../graphicelement/) klassen. |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Tar bort det aktuella elementet från sidan. Om det finns många element att ta bort är det bättre att använda [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Konverterar elementet till en enda SVG-bild. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Konverterar elementet till en enda SVG-bildfil. |

### Se Även

* klass [GraphicElement](../graphicelement/)
* namnrum [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)