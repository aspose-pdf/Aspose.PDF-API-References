---
title: Class Stamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Stamp klass. En abstrakt klass för olika typer av stämplar som kommer som ättlingar
type: docs
weight: 10130
url: /sv/net/aspose.pdf/stamp/
---
## Stämpel klass

En abstrakt klass för olika typer av stämplar som kommer som ättlingar.

```csharp
public abstract class Stamp
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Bakgrund](../../aspose.pdf/stamp/background/) { get; set; } | Sätter eller hämtar ett bool-värde som indikerar att innehållet stämplas som bakgrund. Om värdet är sant, läggs stämpelinnehållet längst ner. Som standard är värdet falskt, stämpelinnehållet läggs överst. |
| [Bottenmarginal](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Hämtar eller sätter bottenmarginalen för stämpeln. |
| virtual [Höjd](../../aspose.pdf/stamp/height/) { get; set; } | Önskad höjd på stämpeln på sidan. |
| [HorisontellJustering](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Hämtar eller sätter horisontell justering av stämpeln på sidan. |
| [Vänstermarginal](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Hämtar eller sätter vänstermarginalen för stämpeln. |
| [Opacitet](../../aspose.pdf/stamp/opacity/) { get; set; } | Hämtar eller sätter ett värde för att indikera stämpelns opacitet. Värdet är från 0.0 till 1.0. Som standard är värdet 1.0. |
| [KonturOpacitet](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Hämtar eller sätter ett värde för att indikera stämpelns konturopacitet. Värdet är från 0.0 till 1.0. Som standard är värdet 1.0. |
| [KonturBredd](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Hämtar eller sätter ett värde för stämpelns konturbredd. Som standard är värdet 1.0. |
| [Högermarginal](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Hämtar eller sätter högermarginalen för stämpeln. |
| [Rotera](../../aspose.pdf/stamp/rotate/) { get; set; } | Sätter eller hämtar rotationen av stämpelinnehållet enligt [`Rotation`](../rotation/) värden. Observera. Denna egenskap är för att ställa in vinklar som är multiplar av 90 grader (0, 90, 180, 270 grader). För att ställa in godtycklig vinkel, använd egenskapen RotateAngle. Om vinkeln som ställs in av ArbitraryAngle inte är en multipel av 90, returnerar Rotate-egenskapen Rotation.None. |
| [RoteraVinkel](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Hämtar eller sätter rotationsvinkeln för stämpeln i grader. Denna egenskap tillåter att ställa in godtycklig rotationsvinkel. |
| [ToppMarginal](../../aspose.pdf/stamp/topmargin/) { get; set; } | Hämtar eller sätter toppmarginalen för stämpeln. |
| [VertikalJustering](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Hämtar eller sätter vertikal justering av stämpeln på sidan. |
| virtual [Bredd](../../aspose.pdf/stamp/width/) { get; set; } | Önskad bredd på stämpeln på sidan. |
| virtual [XIndentering](../../aspose.pdf/stamp/xindent/) { get; set; } | Horisontell stämpelkoordinat, som börjar från vänster. |
| virtual [YIndentering](../../aspose.pdf/stamp/yindent/) { get; set; } | Vertikal stämpelkoordinat, som börjar från botten. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Zoomfaktor för stämpeln. Möjliggör skalning av stämpeln. Observera att paret av egenskaperna ZoomX och ZoomY tillåter att ställa in zoomfaktor för varje axel separat. Inställning av denna egenskap ändrar både ZoomX och ZoomY egenskaper. Om ZoomX och ZoomY är olika, returnerar Zoom-egenskapen värdet av ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Horisontell zoomfaktor för stämpeln. Möjliggör skalning av stämpeln horisontellt. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Vertikal zoomfaktor för stämpeln. Möjliggör skalning av stämpeln vertikalt. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Returnerar stämpel-ID. |
| abstract [Put](../../aspose.pdf/stamp/put/)(Page) | Lägger till stämpeln på sidan. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Sätter stämpel-ID. |

### Se Även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)