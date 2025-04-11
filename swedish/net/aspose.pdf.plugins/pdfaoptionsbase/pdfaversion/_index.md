---
title: PdfAOptionsBase.PdfAVersion
second_title: Aspose.PDF for .NET API Reference
description: PdfAOptionsBase-egenskap. Hämtar eller ställer in versionen av PDF/A-standarden som ska användas för validering eller konvertering
type: docs
weight: 110
url: /sv/net/aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/
---
## PdfAOptionsBase.PdfAVersion-egenskap

Hämtar eller ställer in versionen av PDF/A-standarden som ska användas för validering eller konvertering.

```csharp
public PdfAStandardVersion PdfAVersion { get; set; }
```

### Egenskapsvärde

Versionen av PDF/A-standarden. Detta kan vara en av värdena från [`PdfAStandardVersion`](../../pdfastandardversion/) uppräkningen.

## Kommentarer

PDF/A-standardversionen används för att bestämma efterlevnadsnivån för PDF/A-validering och konvertering. Om versionen är inställd på Auto kommer systemet automatiskt att bestämma den lämpliga PDF/A-standardversionen för validering baserat på dokumentmetadata. För PDF/A-konverteringsprocessen standardinställs Auto till PDF/A-1b standardversion.

### Se Även

* enum [PdfAStandardVersion](../../pdfastandardversion/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)