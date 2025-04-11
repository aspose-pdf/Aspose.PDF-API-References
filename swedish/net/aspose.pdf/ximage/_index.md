---
title: Class XImage
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XImage klass. Klass som representerar bild XObject
type: docs
weight: 11350
url: /sv/net/aspose.pdf/ximage/
---
## XImage klass

Klass som representerar bild X-Objekt.

```csharp
public sealed class XImage
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ContainsTransparency](../../aspose.pdf/ximage/containstransparency/) { get; } | Om bilden innehåller transparens returnera true; annars false. |
| [FilterType](../../aspose.pdf/ximage/filtertype/) { get; } | Hämtar bildfiltertyp. |
| [Grayscaled](../../aspose.pdf/ximage/grayscaled/) { get; } | Hämtar gråskalig version av bilden. |
| [Height](../../aspose.pdf/ximage/height/) { get; } | Hämtar höjden på bilden. |
| [ImageMask](../../aspose.pdf/ximage/imagemask/) { get; } | Hämtar en flagga som indikerar om bilden ska behandlas som en bildmask (se 8.9.6, "Maskerade bilder"). Om denna flagga är true, ska värdet av BitsPerComponent vara 1 och Mask och ColorSpace får inte specificeras; omaskerade områden ska målas med den aktuella icke-stroke färgen. Standardvärde: false. |
| [Metadata](../../aspose.pdf/ximage/metadata/) { get; } | Metadata för bilden. |
| [Name](../../aspose.pdf/ximage/name/) { get; set; } | Hämtar eller sätter bildens namn. Observera att om du ändrar namnet på bilden som har referenser i sidinnehållet, kan dokumentet bli felaktigt. Använd XImage.Rename-metoden i detta fall. |
| [Width](../../aspose.pdf/ximage/width/) { get; } | Hämtar bredden på bilden. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddStencilMask](../../aspose.pdf/ximage/addstencilmask/)(Stream) | Lägger till en stencilmask till XImage. |
| [GetColorType](../../aspose.pdf/ximage/getcolortype/)() | Returnerar färgtyp för bilden. |
| [GetNameInCollection](../../aspose.pdf/ximage/getnameincollection/)() | Returnerar namnet på bilden i dess samling. |
| [GetRawImageData](../../aspose.pdf/ximage/getrawimagedata/)() | Hämtar de råa bilddata från källbilden. |
| [IsTheSameObject](../../aspose.pdf/ximage/isthesameobject/)(XImage) | Returnerar true om båda bilder refererar till samma objekt. |
| [Rename](../../aspose.pdf/ximage/rename/)(string) | Byter namn på bilden och ersätter alla referenser till bilden med det nya namnet |
| [Save](../../aspose.pdf/ximage/save/#save)(Stream) | Sparar bilddata i ström som JPEG-bild. |
| [Save](../../aspose.pdf/ximage/save/#save_2)(Stream, ImageFormat) | Sparar bilden i ström med begärt format. |
| [Save](../../aspose.pdf/ximage/save/#save_1)(Stream, int) | Sparar bilddata i ström som JPEG-bild med angiven upplösning. |
| [Save](../../aspose.pdf/ximage/save/#save_3)(Stream, ImageFormat, int) | Sparar bilden i ström med begärt format med angiven upplösning. |
| [ToStream](../../aspose.pdf/ximage/tostream/)() | Returnerar den ursprungliga bildströmmen. |
| static [DetectColorType](../../aspose.pdf/ximage/detectcolortype/)(Bitmap) |  |

### Se Även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)