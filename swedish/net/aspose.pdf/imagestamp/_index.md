---
title: "Klass ImageStamp"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.ImageStamp-klass. Representerar en grafisk stämpel"
type: docs
weight: 6060
url: /sv/net/aspose.pdf/imagestamp/
---
## ImageStamp class

Representerar en grafisk stämpel.

```csharp
public sealed class ImageStamp : Stamp
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ImageStamp](imagestamp/#constructor)(Stream) | Initierar en ny instans av klassen `ImageStamp`. |
| [ImageStamp](imagestamp/#constructor_1)(string) | Skapar bildstämpel från bild i den angivna filen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AlternativeText](../../aspose.pdf/imagestamp/alternativetext/) { get; set; } | Hämtar eller anger alternativ text för bildstämpel. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | Ställer in eller hämtar ett booleskt värde som indikerar att innehållet är stämplat som bakgrund. Om värdet är true läggs stämpelns innehåll längst ner. Som standard är värdet false, och stämpelns innehåll läggs överst. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | Hämtar eller anger nedre marginal för stämpeln. |
| override [Height](../../aspose.pdf/imagestamp/height/) { get; set; } | Hämtar eller anger bildhöjd. Att ställa in denna bild möjliggör vertikal skalning av bilden. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | Hämtar eller anger horisontell justering av stämpeln på sidan. |
| [Image](../../aspose.pdf/imagestamp/image/) { get; } | Hämtar bildström som används för stämpling. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | Hämtar eller anger vänster marginal för stämpeln. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | Hämtar eller anger ett värde för att indikera stämpelns opacitet. Värdet är från 0.0 till 1.0. Som standard är värdet 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | Hämtar eller anger ett värde för att indikera stämpelns konturopacitet. Värdet är från 0.0 till 1.0. Som standard är värdet 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | Hämtar eller anger ett värde för stämpelns konturbredd. Som standard är värdet 1.0. |
| [Quality](../../aspose.pdf/imagestamp/quality/) { get; set; } | Hämtar eller anger kvalitet för bildstämpel i procent. Giltiga värden är 0..100%. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | Hämtar eller anger högermarginalen för stämpeln. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | Ställer in eller hämtar rotationen av stämpelns innehåll enligt [`Rotation`](../rotation/) värden. Obs! Denna egenskap är för att ange vinklar som är multiplar av 90 grader (0, 90, 180, 270 grader). För att ange en godtycklig vinkel, använd egenskapen RotateAngle. Om vinkeln som anges av ArbitraryAngle inte är en multipel av 90 så returnerar Rotate‑egenskapen Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | Hämtar eller anger rotationsvinkeln för stämpeln i grader. Denna egenskap tillåter att ange en godtycklig rotationsvinkel. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | Hämtar eller anger övre marginalen för stämpeln. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | Hämtar eller anger vertikal justering av stämpeln på sidan. |
| override [Width](../../aspose.pdf/imagestamp/width/) { get; set; } | Hämtar eller anger bildbredd. Att ställa in denna egenskap möjliggör horisontell skalning av bilden. |
| override [XIndent](../../aspose.pdf/imagestamp/xindent/) { get; set; } | Hämtar och anger horisontell stämpelkoordinat, räknat från vänster. |
| override [YIndent](../../aspose.pdf/imagestamp/yindent/) { get; set; } | Hämtar och anger vertikal stämpelkoordinat, räknat från botten. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | Zoomfaktor för stämpeln. Tillåter att skala stämpeln. Observera att paret av egenskaper ZoomX och ZoomY tillåter att ange zoomfaktor för varje axel separat. Inställning av denna egenskap ändrar både ZoomX- och ZoomY-egenskaperna. Om ZoomX och ZoomY är olika returnerar Zoom‑egenskapen ZoomX‑värdet. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | Horisontell zoomfaktor för stämpeln. Tillåter att skala stämpeln horisontellt. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | Vertikal zoomfaktor för stämpeln. Tillåter att skala stämpeln vertikalt. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | Returnerar stämpelns ID. |
| override [Put](../../aspose.pdf/imagestamp/put/)(Page) | Lägger till grafisk stämpel på page. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | Anger stämpelns ID. |

### Se även

* class [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


