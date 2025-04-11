---
title: Class ImageStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImageStamp klass. Representerar en grafisk stämpel
type: docs
weight: 5930
url: /sv/net/aspose.pdf/imagestamp/
---
## ImageStamp klass

Representerar en grafisk stämpel.

```csharp
public sealed class ImageStamp : Stamp
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ImageStamp](imagestamp/#constructor)(Stream) | Initierar en ny instans av `ImageStamp` klassen. |
| [ImageStamp](imagestamp/#constructor_1)(string) | Skapar en bildstämpel från bilden i den angivna filen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AlternativeText](../../aspose.pdf/imagestamp/alternativetext/) { get; set; } | Hämtar eller ställer in alternativ text för bildstämpel. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Ställer in eller hämtar ett bool-värde som indikerar att innehållet stämplas som bakgrund. Om värdet är sant, läggs stämpelinnehållet längst ner. Som standard är värdet falskt, stämpelinnehållet läggs överst. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Hämtar eller ställer in nedre marginal för stämpel. |
| override [Height](../../aspose.pdf/imagestamp/height/) { get; set; } | Hämtar eller ställer in bildens höjd. Att ställa in denna bild möjliggör vertikal skalning av bilden. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Hämtar eller ställer in horisontell justering av stämpel på sidan. |
| [Image](../../aspose.pdf/imagestamp/image/) { get; } | Hämtar bildströmmen som används för stämpling. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Hämtar eller ställer in vänster marginal för stämpel. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Hämtar eller ställer in ett värde för att indikera stämpelns opacitet. Värdet är från 0.0 till 1.0. Som standard är värdet 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Hämtar eller ställer in ett värde för att indikera stämpelns konturopacitet. Värdet är från 0.0 till 1.0. Som standard är värdet 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Hämtar eller ställer in ett värde för stämpelns konturbredd. Som standard är värdet 1.0. |
| [Quality](../../aspose.pdf/imagestamp/quality/) { get; set; } | Hämtar eller ställer in kvaliteten på bildstämpeln i procent. Giltiga värden är 0..100%. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Hämtar eller ställer in höger marginal för stämpel. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Ställer in eller hämtar rotationen av stämpelinnehållet enligt [`Rotation`](../rotation/) värden. Observera. Denna egenskap är för att ställa in vinklar som är multiplar av 90 grader (0, 90, 180, 270 grader). För att ställa in godtycklig vinkel, använd RotateAngle-egenskapen. Om vinkeln som ställs in av ArbitraryAngle inte är en multipel av 90, returnerar Rotate-egenskapen Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Hämtar eller ställer in rotationsvinkeln för stämpel i grader. Denna egenskap möjliggör att ställa in godtycklig rotationsvinkel. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Hämtar eller ställer in övre marginal för stämpel. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Hämtar eller ställer in vertikal justering av stämpel på sidan. |
| override [Width](../../aspose.pdf/imagestamp/width/) { get; set; } | Hämtar eller ställer in bildens bredd. Att ställa in denna egenskap möjliggör horisontell skalning av bilden. |
| override [XIndent](../../aspose.pdf/imagestamp/xindent/) { get; set; } | Hämtar och ställer in den horisontella stämpelkoordinaten, som börjar från vänster. |
| override [YIndent](../../aspose.pdf/imagestamp/yindent/) { get; set; } | Hämtar och ställer in den vertikala stämpelkoordinaten, som börjar från botten. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Zoomfaktor för stämpeln. Möjliggör skalning av stämpeln. Observera att paret av egenskaperna ZoomX och ZoomY möjliggör att ställa in zoomfaktor för varje axel separat. Att ställa in denna egenskap ändrar både ZoomX och ZoomY egenskaper. Om ZoomX och ZoomY är olika, returnerar Zoom-egenskapen värdet av ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Horisontell zoomfaktor för stämpeln. Möjliggör skalning av stämpeln horisontellt. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Vertikal zoomfaktor för stämpeln. Möjliggör skalning av stämpeln vertikalt. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Returnerar stämpel-ID. |
| override [Put](../../aspose.pdf/imagestamp/put/)(Page) | Lägger till grafisk stämpel på sidan. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Ställer in stämpel-ID. |

### Se Även

* klass [Stamp](../stamp/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* samling [Aspose.PDF](../../)