---
title: "Klass PdfPageStamp"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.PdfPageStamp-klass. Klassen representerar en stämpel som använder en PDF-sida som stämpel"
type: docs
weight: 8560
url: /sv/net/aspose.pdf/pdfpagestamp/
---
## PdfPageStamp class

Klassen representerar en stämpel som använder en PDF-sida som stämpel.

```csharp
public sealed class PdfPageStamp : Stamp
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfPageStamp](pdfpagestamp/#constructor)(Page) | Konstruktor för PdfPageStamp. |
| [PdfPageStamp](pdfpagestamp/#constructor_1)(Stream, int) | Skapar en PDF-sidstämpel från den angivna sidan i dokumentet från strömmen. |
| [PdfPageStamp](pdfpagestamp/#constructor_2)(string, int) | Skapar en PDF-sidstämpel från den angivna sidan i dokumentet i den specificerade filen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Ställer in eller hämtar ett booleskt värde som indikerar att innehållet är stämplat som bakgrund. Om värdet är true läggs stämpelns innehåll längst ner. Som standard är värdet false, och stämpelns innehåll läggs överst. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Hämtar eller anger nedre marginal för stämpeln. |
| virtual [Height](../../aspose.pdf/stamp/height/) { get; set; } | Önskad höjd på stämpeln på sidan. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Hämtar eller anger horisontell justering av stämpeln på sidan. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Hämtar eller anger vänster marginal för stämpeln. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Hämtar eller anger ett värde för att indikera stämpelns opacitet. Värdet är från 0.0 till 1.0. Som standard är värdet 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Hämtar eller anger ett värde för att indikera stämpelns konturopacitet. Värdet är från 0.0 till 1.0. Som standard är värdet 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Hämtar eller anger ett värde för stämpelns konturbredd. Som standard är värdet 1.0. |
| [PdfPage](../../aspose.pdf/pdfpagestamp/pdfpage/) { get; set; } | Hämtar eller anger sidan som ska användas som stämpel. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Hämtar eller anger högermarginalen för stämpeln. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Ställer in eller hämtar rotationen av stämpelns innehåll enligt [`Rotation`](../rotation/) värden. Obs! Denna egenskap är för att ange vinklar som är multiplar av 90 grader (0, 90, 180, 270 grader). För att ange en godtycklig vinkel, använd egenskapen RotateAngle. Om vinkeln som anges av ArbitraryAngle inte är en multipel av 90 så returnerar Rotate‑egenskapen Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Hämtar eller anger rotationsvinkeln för stämpeln i grader. Denna egenskap tillåter att ange en godtycklig rotationsvinkel. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Hämtar eller anger övre marginalen för stämpeln. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Hämtar eller anger vertikal justering av stämpeln på sidan. |
| virtual [Width](../../aspose.pdf/stamp/width/) { get; set; } | Önskad bredd på stämpeln på sidan. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | Horisontell stämpelkoordinat, räknat från vänster. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | Vertikal stämpelkoordinat, räknat från botten. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Zoomfaktor för stämpeln. Tillåter att skala stämpeln. Observera att paret av egenskaper ZoomX och ZoomY tillåter att ange zoomfaktor för varje axel separat. Inställning av denna egenskap ändrar både ZoomX- och ZoomY-egenskaperna. Om ZoomX och ZoomY är olika returnerar Zoom‑egenskapen ZoomX‑värdet. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Horisontell zoomfaktor för stämpeln. Tillåter att skala stämpeln horisontellt. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Vertikal zoomfaktor för stämpeln. Tillåter att skala stämpeln vertikalt. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Returnerar stämpelns ID. |
| override [Put](../../aspose.pdf/pdfpagestamp/put/)(Page) | Placera stämpeln på den angivna sidan. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Anger stämpelns ID. |

### Se även

* class [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


