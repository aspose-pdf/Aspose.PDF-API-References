---
title: Class ImageCompressionOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Optimization.ImageCompressionOptions klass. Klassen innehåller inställningar för bildkomprimering
type: docs
weight: 7950
url: /sv/net/aspose.pdf.optimization/imagecompressionoptions/
---
## ImageCompressionOptions klass

Klassen innehåller inställningar för bildkomprimering.

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
| [CompressImages](../../aspose.pdf.optimization/imagecompressionoptions/compressimages/) { get; set; } | Om denna flagga är inställd på true kommer bilder att komprimeras i dokumentet. komprimeringsnivån anges med egenskapen ImageQuality. |
| [Encoding](../../aspose.pdf.optimization/imagecompressionoptions/encoding/) { get; set; } | Hämtar eller ställer in kodningen som används för att lagra bilder. |
| [ImageQuality](../../aspose.pdf.optimization/imagecompressionoptions/imagequality/) { get; set; } | Anger nivån av bildkomprimering när flaggan CompressImages används. |
| [MaxResolution](../../aspose.pdf.optimization/imagecompressionoptions/maxresolution/) { get; set; } | Anger den maximala upplösningen för bilder. Om bilden har högre upplösning kommer den att skalas. |
| [ResizeImages](../../aspose.pdf.optimization/imagecompressionoptions/resizeimages/) { get; set; } | Om denna flagga är inställd på true och CompressImages är true kommer bilder att ändras i storlek om bildens upplösning är större än den angivna MaxResolution-parametern. |
| [Version](../../aspose.pdf.optimization/imagecompressionoptions/version/) { get; set; } | Version av komprimeringsalgoritm. Möjliga värden är: 1. standardkomprimering, 2. snabb (förbättrad komprimering som är snabbare än standard men kanske inte är tillämplig för alla bilder), 3. blandad (standardkomprimering tillämpas på bilder som inte kan komprimeras av snabbare algoritm, detta kan ge bästa komprimering men är långsammare än "snabb" algoritm. Version "Snabb" är inte tillämplig för att ändra storlek på bilder (standardmetod kommer att användas). Standard är "Standard". |

### Se Även

* namnrymd [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* sammansättning [Aspose.PDF](../../)