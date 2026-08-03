---
title: "Klass SubPath"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Vector.SubPath-klass. Representerar ett vektorgrafikobjekt på sidan. I grund och botten representeras vektorgrafikobjekt av två grupper av SubPaths. En av dem representeras av en samling linjer och kurvor. De andra visas som rektanglar och kan ibland förväxlas. Vanligtvis är det ett rektangulärt område som har en färg, men mycket ofta placeras denna rektangel i början av sidan och definierar hela sidans utrymme i vitt. Så du får SubPath men visuellt ser du bara texten på sidan."
type: docs
weight: 11410
url: /sv/net/aspose.pdf.vector/subpath/
---
## SubPath class

Representerar ett vektorgrafikobjekt på sidan. I grund och botten representeras vektorgrafikobjekt av två grupper av SubPaths. En av dem representeras av en uppsättning linjer och kurvor. De andra visas som rektanglar och kan ibland förväxlas. Vanligtvis är det ett rektangulärt område som har en färg, men mycket ofta placeras denna rektangel i början av sidan och definierar hela sidans utrymme i vitt. Så du får SubPath, men visuellt ser du bara texten på sidan.

```csharp
public sealed class SubPath : GraphicElement
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Hämtar grafiskt elementmatris. Matrisen sätts när elementet skapas. Den ändras när SetPosition() anropas. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Hämtar en samling av operatorer som representerar elementet. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Hämtar den aktuella [`XFormPlacement`](../xformplacement/) där elementet är placerat. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | Hämtar eller anger positionen i det aktuella koordinatrymmet. Om [`Parent`](../graphicelement/parent/) inte är !:null har elementet xForm-koordinatrymd. |
| override [Rectangle](../../aspose.pdf.vector/subpath/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Hämtar sidan som det grafiska elementet extraheras från. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | Lägger till det aktuella elementet på sidan. Om det finns många element att lägga till är det bättre att använda [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Frigör alla resurser som används av klassen [`GraphicElement`](../graphicelement/). |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Tar bort det aktuella elementet från sidan. Om det finns många element att ta bort är det bättre att använda [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Konverterar elementet till en enda SVG-bild. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Konverterar elementet till en enda SVG-bildfil. |

### Se även

* class [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


