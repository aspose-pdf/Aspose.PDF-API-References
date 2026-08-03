---
title: "PdfViewer.Resolution"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfViewer‑egenskap. Hämtar eller sätter upplösning under visning och utskrift. Ju högre upplösning, desto långsammare hastighet. Standardvärdet är 150."
type: docs
weight: 160
url: /sv/net/aspose.pdf.facades/pdfviewer/resolution/
---
## PdfViewer.Resolution property

Hämtar eller anger upplösning vid visning och utskrift. Högre upplösning ger lägre hastighet. Standardvärdet är 150.

```csharp
public int Resolution { get; set; }
```

## Anmärkningar

Denna egenskap ändrar bildens upplösning i konverteringsflöden från sida till bild: när [`PrintAsImage`](../printasimage/) är satt till `true`, eller när metoden [`DecodePage`](../decodepage/) eller [`DecodeAllPages`](../decodeallpages/) anropas. För att ställa in en skrivarupplösning för direktutskrift till en skrivare, använd egenskapen [`PrinterResolution`](../../../aspose.pdf.printing/pagesettings/printerresolution/) i klassen [`PageSettings`](../../../aspose.pdf.printing/pagesettings/).

### Se även

* class [PdfViewer](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


