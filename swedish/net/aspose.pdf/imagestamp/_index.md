---
title: ImageStamp
second_title: Aspose.PDF för .NET API Referens
description: Återger grafisk stämpel.
type: docs
weight: 3790
url: /sv/net/aspose.pdf/imagestamp/
---
## ImageStamp class

Återger grafisk stämpel.

```csharp
public sealed class ImageStamp : Stamp
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [ImageStamp](imagestamp#constructor)(Stream) | Initierar en ny instans av[`ImageStamp`](../imagestamp) class. |
| [ImageStamp](imagestamp#constructor_1)(string) | Skapar bildstämpel för bild i den angivna filen. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background) { get; set; } | Ställer in eller får ett boolvärde som indikerar att innehållet är stämplat som bakgrund. Om värdet är sant, läggs stämpelinnehållet längst ner. Av defalt är värdet falskt, stämpelinnehållet läggs överst. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin) { get; set; } | Får eller ställer in bottenmarginalen på stämpeln. |
| [Height](../../aspose.pdf/imagestamp/height) { get; set; } | Hämtar eller ställer in bildhöjd. Om du ställer in den här bilden kan du skala bilden vertikalt. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment) { get; set; } | Hämtar eller ställer in horisontell justering av stämpeln på sidan. |
| [Image](../../aspose.pdf/imagestamp/image) { get; } | Får bildström som används för stämpling. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin) { get; set; } | Hämtar eller ställer in vänster marginal på stämpeln. |
| [Opacity](../../aspose.pdf/stamp/opacity) { get; set; } | Hämtar eller ställer in ett värde för att indikera stämpelns opacitet. Värdet är från 0.0 till 1.0. Som standard är värdet 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity) { get; set; } | Hämtar eller ställer in ett värde för att indikera stämpelkonturens opacitet. Värdet är från 0.0 till 1.0. Som standard är värdet 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth) { get; set; } | Hämtar eller ställer in ett värde för stämpelns konturbredd. Som standard är värdet 1.0. |
| [Quality](../../aspose.pdf/imagestamp/quality) { get; set; } | Får eller ställer in kvaliteten på bildstämpeln i procent. Giltiga värden är 0..100 %. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin) { get; set; } | Får eller ställer in höger marginal på stämpeln. |
| [Rotate](../../aspose.pdf/stamp/rotate) { get; set; } | Ställer in eller hämtar rotationen av stämpelinnehåll enligt[`Rotation`](../rotation) värden. Obs. Den här egenskapen är för inställda vinklar som är multiplar av 90 grader (0, 90, 180, 270 grader). Använd RotateAngle-egenskapen för att ställa in godtycklig vinkel. Om vinkeln inställd av ArbitraryAngle inte är multipel av 90 returnerar Rotate-egenskapen Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle) { get; set; } | Hämtar eller ställer in stämpelns rotationsvinkel i grader. Den här egenskapen gör det möjligt att ställa in godtycklig rotationsvinkel. |
| [TopMargin](../../aspose.pdf/stamp/topmargin) { get; set; } | Får eller ställer in den övre marginalen på stämpeln. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment) { get; set; } | Får eller ställer in vertikal justering av stämpeln på sidan. |
| [Width](../../aspose.pdf/imagestamp/width) { get; set; } | Hämtar eller ställer in bildbredd. Att ställa in den här egenskapen allos till skala bilden horisontellt. |
| [XIndent](../../aspose.pdf/stamp/xindent) { get; set; } | Horisontell stämpelkoordinat, med början från vänster. |
| [YIndent](../../aspose.pdf/stamp/yindent) { get; set; } | Vertikal stämpelkoordinat, från botten. |
| [Zoom](../../aspose.pdf/stamp/zoom) { get; set; } | Zoomningsfaktor för stämpeln. Tillåter att skala stämpel. Observera att par av egenskaper ZoomX och ZoomY tillåter att ställa in zoomfaktor för varje yxa separat. Inställning av denna egenskap ändrar både ZoomX- och ZoomY-egenskaper. Om ZoomX och ZoomY är olika returnerar Zoom-egenskapen ZoomX-värdet. |
| [ZoomX](../../aspose.pdf/stamp/zoomx) { get; set; } | Stämpelns horisontella zoomfaktor. Tillåter att skala stämpel horisontellt. |
| [ZoomY](../../aspose.pdf/stamp/zoomy) { get; set; } | Vertikal zoomfaktor för stämpeln. Tillåter att skala stämpel vertikalt. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid)() | Returnerar stämpel-ID. |
| override [Put](../../aspose.pdf/imagestamp/put)(Page) | Lägger till grafisk stämpel på sidan. |
| [setStampId](../../aspose.pdf/stamp/setstampid)(int) | Anger stämpel-ID. |

### Se även

* class [Stamp](../stamp)
* namnutrymme [Aspose.Pdf](../../aspose.pdf)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
