---
title: "Klass XFormPlacement"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Vector.XFormPlacement-klass. Representerar XForm-placering. Om XForm visas på sidan mer än en gång kommer alla XformPlacements som är associerade med detta XForm att ha gemensamma grafiska element men olika grafiska tillstånd."
type: docs
weight: 11450
url: /sv/net/aspose.pdf.vector/xformplacement/
---
## XFormPlacement class

Representerar XForm-placering. Om XForm visas på sidan mer än en gång, kommer alla XformPlacements som är associerade med detta XForm att ha gemensamma grafiska element, men olika grafiska tillstånd.

```csharp
public sealed class XFormPlacement : GraphicElement
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Elements](../../aspose.pdf.vector/xformplacement/elements/) { get; } | Hämtar grafiska element inuti detta XForm. |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | Hämtar grafiskt elementmatris. Matrisen sätts när elementet skapas. Den ändras när SetPosition() anropas. |
| [Name](../../aspose.pdf.vector/xformplacement/name/) { get; } | Hämtar namnet på XForm. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | Hämtar en samling av operatorer som representerar elementet. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | Hämtar den aktuella `XFormPlacement` där elementet är placerat. |
| override [Position](../../aspose.pdf.vector/xformplacement/position/) { set; } |  |
| override [Rectangle](../../aspose.pdf.vector/xformplacement/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | Hämtar sidan som det grafiska elementet extraheras från. |
| [XForm](../../aspose.pdf.vector/xformplacement/xform/) { get; } | Hämtar XForm som är associerad med denna XFormPlacement. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [AddOnPage](../../aspose.pdf.vector/xformplacement/addonpage/)(Page) | Lägger till det aktuella elementet på sidan. Om det finns många element att lägga till är det bättre att använda [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | Frigör alla resurser som används av klassen [`GraphicElement`](../graphicelement/). |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | Tar bort det aktuella elementet från sidan. Om det finns många element att ta bort är det bättre att använda [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | Konverterar elementet till en enda SVG-bild. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | Konverterar elementet till en enda SVG-bildfil. |

### Se även

* class [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


