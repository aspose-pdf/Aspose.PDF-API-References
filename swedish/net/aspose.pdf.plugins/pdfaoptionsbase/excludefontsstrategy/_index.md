---
title: PdfAOptionsBase.ExcludeFontsStrategy
second_title: Aspose.PDF for .NET API Reference
description: PdfAOptionsBase-egenskap. Hämtar eller ställer in strategin för att ta bort typsnitt för att minimera storleken på utdatafilen under PDF/A-konverteringsprocessen
type: docs
weight: 30
url: /sv/net/aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/
---
## PdfAOptionsBase.ExcludeFontsStrategy-egenskap

Hämtar eller ställer in strategin för att ta bort typsnitt för att minimera storleken på utdatafilen under PDF/A-konverteringsprocessen.

```csharp
public RemoveFontsStrategy ExcludeFontsStrategy { get; set; }
```

### Egenskapsvärde

Strategin för att ta bort typsnitt. Detta kan vara en av värdena från [`RemoveFontsStrategy`](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/) uppräkningen. Standard är kombinationen av SubsetFonts och RemoveDuplicatedFonts.

## Kommentarer

Denna egenskap gör att du kan kontrollera hur typsnitt hanteras under konverteringsprocessen. Du kan välja att ta bort duplicerade typsnitt, ta bort liknande typsnitt med olika bredder eller delmängd typsnitt.

### Se Även

* enum [RemoveFontsStrategy](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)