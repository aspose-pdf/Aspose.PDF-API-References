---
title: Class PdfPageStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfPageStamp klass. Klassen representerar stämpel som använder PDF-sidan som stämpel
type: docs
weight: 8420
url: /sv/net/aspose.pdf/pdfpagestamp/
---
## PdfPageStamp klass

Klassen representerar stämpel som använder PDF-sidan som stämpel.

```csharp
public sealed class PdfPageStamp : Stamp
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfPageStamp](pdfpagestamp/#constructor)(Page) | Konstruktör för PdfPageStamp. |
| [PdfPageStamp](pdfpagestamp/#constructor_1)(Stream, int) | Skapar PDF-sidestämpel från angiven sida i dokumentet från strömmen. |
| [PdfPageStamp](pdfpagestamp/#constructor_2)(string, int) | Skapar PDF-sidestämpel från angiven sida av dokumentet i angiven fil. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Sätter eller hämtar ett bool-värde som indikerar att innehållet stämplas som bakgrund. Om värdet är sant, läggs stämpelinnehållet längst ner. Som standard är värdet falskt, stämpelinnehållet läggs överst. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Hämtar eller sätter nedre marginal för stämpel. |
| virtual [Height](../../aspose.pdf/stamp/height/) { get; set; } | Önskad höjd på stämpeln på sidan. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Hämtar eller sätter horisontell justering av stämpeln på sidan. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Hämtar eller sätter vänster marginal för stämpel. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Hämtar eller sätter ett värde för att indikera stämpelns opacitet. Värdet är från 0.0 till 1.0. Som standard är värdet 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Hämtar eller sätter ett värde för att indikera stämpelns konturopacitet. Värdet är från 0.0 till 1.0. Som standard är värdet 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Hämtar eller sätter ett värde för stämpelns konturbredd. Som standard är värdet 1.0. |
| [PdfPage](../../aspose.pdf/pdfpagestamp/pdfpage/) { get; set; } | Hämtar eller sätter sidan som kommer att användas som stämpel. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Hämtar eller sätter höger marginal för stämpel. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Sätter eller hämtar rotationen av stämpelinnehållet enligt [`Rotation`](../rotation/) värden. Obs. Denna egenskap är för att ställa in vinklar som är multiplar av 90 grader (0, 90, 180, 270 grader). För att ställa in godtycklig vinkel, använd RotateAngle-egenskapen. Om vinkeln som ställs in av ArbitraryAngle inte är en multipel av 90, returnerar Rotate-egenskapen Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Hämtar eller sätter rotationsvinkeln för stämpeln i grader. Denna egenskap tillåter att ställa in godtycklig rotationsvinkel. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Hämtar eller sätter övre marginal för stämpel. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Hämtar eller sätter vertikal justering av stämpeln på sidan. |
| virtual [Width](../../aspose.pdf/stamp/width/) { get; set; } | Önskad bredd på stämpeln på sidan. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Horisontell stämpelkoordinat, som börjar från vänster. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Vertikal stämpelkoordinat, som börjar från botten. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Zoomfaktor för stämpeln. Möjliggör skalning av stämpeln. Observera att paret av egenskaper ZoomX och ZoomY tillåter att ställa in zoomfaktor för varje axel separat. Inställning av denna egenskap ändrar både ZoomX och ZoomY egenskaper. Om ZoomX och ZoomY är olika, returnerar Zoom-egenskapen värdet av ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Horisontell zoomfaktor för stämpeln. Möjliggör skalning av stämpeln horisontellt. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Vertikal zoomfaktor för stämpeln. Möjliggör skalning av stämpeln vertikalt. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Returnerar stämpel-ID. |
| override [Put](../../aspose.pdf/pdfpagestamp/put/)(Page) | Sätter stämpeln på den angivna sidan. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Sätter stämpel-ID. |

### Se Även

* klass [Stamp](../stamp/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)