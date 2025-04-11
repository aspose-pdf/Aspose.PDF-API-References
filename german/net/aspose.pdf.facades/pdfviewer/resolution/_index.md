---
title: PdfViewer.Resolution
second_title: Aspose.PDF for .NET API Reference
description: PdfViewer-Eigenschaft. Ruft die Auflösung während der Anzeige und des Drucks ab oder legt sie fest. Je höher die Auflösung, desto langsamer die Geschwindigkeit. Der Standardwert ist 150.
type: docs
weight: 160
url: /de/net/aspose.pdf.facades/pdfviewer/resolution/
---
## PdfViewer.Resolution-Eigenschaft

Ruft die Auflösung während der Anzeige und des Drucks ab oder legt sie fest. Je höher die Auflösung, desto langsamer die Geschwindigkeit. Der Standardwert ist 150.

```csharp
public int Resolution { get; set; }
```

## Bemerkungen

Diese Eigenschaft ändert die Bildauflösung in den Abläufen zur Umwandlung von Seiten in Bilder: wenn [`PrintAsImage`](../printasimage/) auf `true` gesetzt ist oder wenn die Methoden [`DecodePage`](../decodepage/) oder [`DecodeAllPages`](../decodeallpages/) aufgerufen werden. Um eine Druckerauflösung für den direkten Druck an einen Drucker festzulegen, verwenden Sie die Eigenschaft [`PrinterResolution`](../../../aspose.pdf.printing/pagesettings/printerresolution/) in der Klasse [`PageSettings`](../../../aspose.pdf.printing/pagesettings/).

### Siehe auch

* Klasse [PdfViewer](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)