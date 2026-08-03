---
title: "PdfAOptionsBase.ExcludeFontsStrategy"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfAOptionsBase egenskap. Hämtar eller anger strategin för att ta bort teckensnitt för att minimera storleken på utdatafilen under PDF/A‑konverteringsprocessen."
type: docs
weight: 30
url: /sv/net/aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/
---
## PdfAOptionsBase.ExcludeFontsStrategy property

Hämtar eller anger strategin för att ta bort teckensnitt för att minimera utdatafilens storlek under PDF/A‑konverteringsprocessen.

```csharp
public RemoveFontsStrategy ExcludeFontsStrategy { get; set; }
```

### Property Value

Strategin för att ta bort teckensnitt. Detta kan vara ett av värdena från [`RemoveFontsStrategy`](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/) enumeration. Standardvärdet är kombinationen av SubsetFonts och RemoveDuplicatedFonts.

## Anmärkningar

Denna egenskap låter dig kontrollera hur teckensnitt hanteras under konverteringsprocessen. Du kan välja att ta bort duplicerade teckensnitt, ta bort liknande teckensnitt med olika bredd, eller skapa delmängder av teckensnitt.

### Se även

* enum [RemoveFontsStrategy](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)


