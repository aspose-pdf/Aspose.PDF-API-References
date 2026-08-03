---
title: "Klass ImagesDifference"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Comparison.ImagesDifference-klass. Representerar resultatklassen för jämförelse av två PDF-sidor"
type: docs
weight: 3340
url: /sv/net/aspose.pdf.comparison/imagesdifference/
---
## ImagesDifference class

Representerar resultatsklassen för jämförelse av två PDF-sidor.

```csharp
public sealed class ImagesDifference : IDisposable
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Difference](../../aspose.pdf.comparison/imagesdifference/difference/) { get; } | Hämtar differensarrayen. Denna array liknar den ursprungliga bilddataarrayen som erhålls som resultat av LockBits-metoden. |
| [Height](../../aspose.pdf.comparison/imagesdifference/height/) { get; } | Höjden på differensen. |
| [SourceImage](../../aspose.pdf.comparison/imagesdifference/sourceimage/) { get; } | Hämtar bilden av den första jämförda sidan. Bilden har ett pixelformat på 24bpp. |
| [Stride](../../aspose.pdf.comparison/imagesdifference/stride/) { get; } | Radsteget för differensbilddata. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [DifferenceToImage](../../aspose.pdf.comparison/imagesdifference/differencetoimage/)(Color, Color) | Konverterar differensarrayen till en bitmap-bild med de angivna färgerna. |
| [Dispose](../../aspose.pdf.comparison/imagesdifference/dispose/)() | Utför eventuella nödvändiga städåtgärder innan objektet förstörs. |
| [GetDestinationImage](../../aspose.pdf.comparison/imagesdifference/getdestinationimage/)() | Returnerar en ny bitmap som representerar destinationsbilden genom att applicera differensarrayen på källbilden. |

### Se även

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


