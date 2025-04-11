---
title: Class ImagesDifference
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.ImagesDifference klass. Representerar resultatklassen av att jämföra två PDF-sidor
type: docs
weight: 3230
url: /sv/net/aspose.pdf.comparison/imagesdifference/
---
## ImagesDifference klass

Representerar resultatklassen av att jämföra två PDF-sidor.

```csharp
public sealed class ImagesDifference : IDisposable
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Difference](../../aspose.pdf.comparison/imagesdifference/difference/) { get; } | Hämtar differensarrayen. Denna array liknar den ursprungliga bilddataarrayen som erhållits som ett resultat av LockBits-metoden. |
| [Height](../../aspose.pdf.comparison/imagesdifference/height/) { get; } | Höjden på differensen. |
| [SourceImage](../../aspose.pdf.comparison/imagesdifference/sourceimage/) { get; } | Hämtar bilden av den första jämförda sidan. Bilden har ett pixelformat på 24bpp. |
| [Stride](../../aspose.pdf.comparison/imagesdifference/stride/) { get; } | Steget av differensbilddata. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [DifferenceToImage](../../aspose.pdf.comparison/imagesdifference/differencetoimage/)(Color, Color) | Konverterar differensarrayen till en bitmapbild med hjälp av de angivna färgerna. |
| [Dispose](../../aspose.pdf.comparison/imagesdifference/dispose/)() | Utför nödvändiga städoperationer innan objektet förstörs. |
| [GetDestinationImage](../../aspose.pdf.comparison/imagesdifference/getdestinationimage/)() | Returnerar en ny bitmap som representerar destinationsbilden genom att tillämpa differensarrayen på källbilden. |

### Se Även

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)