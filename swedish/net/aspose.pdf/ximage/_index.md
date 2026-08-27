---
title: "Class XImage"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.XImage klass. Klass som representerar bild‑XObject."
type: docs
weight: 11540
url: /sv/net/aspose.pdf/ximage/
---
## XImage class

Klassen representerar bild‑X‑Object.

```csharp
public sealed class XImage
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ContainsTransparency](../../aspose.pdf/ximage/containstransparency/) { get; } | Om bilden innehåller transparens returneras true; annars false. |
| [FilterType](../../aspose.pdf/ximage/filtertype/) { get; } | Hämtar bildfiltertyp. |
| [Grayscaled](../../aspose.pdf/ximage/grayscaled/) { get; } | Hämtar gråskalig version av bilden. |
| [Height](../../aspose.pdf/ximage/height/) { get; } | Hämtar bildens höjd. |
| [ImageMask](../../aspose.pdf/ximage/imagemask/) { get; } | Hämtar en flagga som indikerar om bilden ska behandlas som en bildmask (se 8.9.6, "Masked Images"). Om denna flagga är true ska värdet för BitsPerComponent vara 1 och Mask och ColorSpace får inte specificeras; omaskade områden ska målas med den aktuella icke‑strokande färgen. Standardvärde: false. |
| [Metadata](../../aspose.pdf/ximage/metadata/) { get; } | Metadata för bilden. |
| [Name](../../aspose.pdf/ximage/name/) { get; set; } | Hämtar eller anger bildens namn. Observera att om du ändrar namnet på bilden som har referenser i Page‑innehållet kan document bli felaktigt. Använd XImage.Rename‑metoden i så fall. |
| [Width](../../aspose.pdf/ximage/width/) { get; } | Hämtar bildens bredd. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddStencilMask](../../aspose.pdf/ximage/addstencilmask/)(Stream) | Lägger till en stencilmask till XImage. |
| [GetAlternativeText](../../aspose.pdf/ximage/getalternativetext/)(Page) | Returnerar en lista med strängar med alternativ text för en XImage. |
| [GetColorType](../../aspose.pdf/ximage/getcolortype/)() | Returnerar bildens färgtyp. |
| [GetNameInCollection](../../aspose.pdf/ximage/getnameincollection/)() | Returnerar bildens namn i dess samling. |
| [GetRawImageData](../../aspose.pdf/ximage/getrawimagedata/)() | Hämtar den råa bilddatan från källbilden. |
| [IsTheSameObject](../../aspose.pdf/ximage/isthesameobject/)(XImage) | Returnerar true om båda bilderna refererar till samma objekt. |
| [Rename](../../aspose.pdf/ximage/rename/)(string) | Byter namn på bilden och ersätter alla referenser till bilden med det nya namnet. |
| [Save](../../aspose.pdf/ximage/save/#save)(Stream) | Sparar bilddata till ström som JPEG‑bild. |
| [Save](../../aspose.pdf/ximage/save/#save_2)(Stream, ImageFormat) | Sparar bilden till ström i önskat format. |
| [Save](../../aspose.pdf/ximage/save/#save_1)(Stream, int) | Sparar bilddata till ström som JPEG‑bild med angiven upplösning. |
| [Save](../../aspose.pdf/ximage/save/#save_3)(Stream, ImageFormat, int) | Sparar bilden i en ström med begärt format och specificerad upplösning. |
| [ToStream](../../aspose.pdf/ximage/tostream/)() | Returnerar den ursprungliga bildströmmen. |
| [TrySetAlternativeText](../../aspose.pdf/ximage/trysetalternativetext/)(string, Page) | Ställer in alternativ text för en XImage på sidan. |
| static [DetectColorType](../../aspose.pdf/ximage/detectcolortype/)(Bitmap) |  |

### Se även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


