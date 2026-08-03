---
title: "Klass ImageCompressionOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Optimization.ImageCompressionOptions-klass. Klassen innehåller en uppsättning alternativ för bildkomprimering"
type: docs
weight: 8090
url: /sv/net/aspose.pdf.optimization/imagecompressionoptions/
---
## ImageCompressionOptions class

Klassen innehåller en uppsättning alternativ för bildkomprimering.

```csharp
public class ImageCompressionOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ImageCompressionOptions](imagecompressionoptions/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CompressImages](../../aspose.pdf.optimization/imagecompressionoptions/compressimages/) { get; set; } | Om den här flaggan är satt till true komprimeras bilder i dokumentet. Komprimeringsnivån anges med egenskapen ImageQuality. |
| [Encoding](../../aspose.pdf.optimization/imagecompressionoptions/encoding/) { get; set; } | Hämtar eller anger kodning som används för att lagra bilder. |
| [ImageQuality](../../aspose.pdf.optimization/imagecompressionoptions/imagequality/) { get; set; } | Anger nivå för bildkomprimering när flaggan CompressImages används. |
| [MaxResolution](../../aspose.pdf.optimization/imagecompressionoptions/maxresolution/) { get; set; } | Anger maximal upplösning för bilder. Om en bild har högre upplösning kommer den att skalas. |
| [ResizeImages](../../aspose.pdf.optimization/imagecompressionoptions/resizeimages/) { get; set; } | Om den här flaggan är satt till true och CompressImages är true kommer bilder att ändras i storlek om bildens upplösning är större än den angivna MaxResolution‑parametern. |
| [Version](../../aspose.pdf.optimization/imagecompressionoptions/version/) { get; set; } | Version av komprimeringsalgoritmen. Möjliga värden är: 1. standardkomprimering, 2. fast (förbättrad komprimering som är snabbare än standard men kan vara otillämplig för vissa bilder), 3. blandad (standardkomprimering tillämpas på bilder som inte kan komprimeras av den snabbare algoritmen, detta kan ge bästa komprimering men är långsammare än \"fast\"-algoritmen. Versionen \"Fast\" är inte tillämplig för att ändra bildstorlek (standardmetoden kommer att användas). Standard är \"Standard\". |

### Se även

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)


