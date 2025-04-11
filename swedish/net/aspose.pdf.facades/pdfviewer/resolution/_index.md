---
title: PdfViewer.Resolution
second_title: Aspose.PDF for .NET API Reference
description: PdfViewer-egenskap. Hämtar eller ställer in upplösning under visning och utskrift. Ju högre upplösning, desto långsammare hastighet. Standardvärdet är 150
type: docs
weight: 160
url: /sv/net/aspose.pdf.facades/pdfviewer/resolution/
---
## PdfViewer.Resolution-egenskap

Hämtar eller ställer in upplösning under visning och utskrift. Ju högre upplösning, desto långsammare hastighet. Standardvärdet är 150.

```csharp
public int Resolution { get; set; }
```

## Kommentarer

Denna egenskap ändrar bildupplösningen i flöden för sid-till-bild-konvertering: när [`PrintAsImage`](../printasimage/) är inställt på `true`, eller när metoden [`DecodePage`](../decodepage/) eller [`DecodeAllPages`](../decodeallpages/) anropas. För att ställa in en skrivareupplösning för direkt utskrift till en skrivare, använd egenskapen [`PrinterResolution`](../../../aspose.pdf.printing/pagesettings/printerresolution/) i klassen [`PageSettings`](../../../aspose.pdf.printing/pagesettings/).

### Se Även

* klass [PdfViewer](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)