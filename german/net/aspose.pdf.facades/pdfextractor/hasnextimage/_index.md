---
title: PdfExtractor.HasNextImage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor-Methode. Überprüft, ob weitere Bilder im PDF-Dokument verfügbar sind. Hinweis ExtractImage muss vor der Verwendung dieser Methode aufgerufen werden.
type: docs
weight: 200
url: /de/net/aspose.pdf.facades/pdfextractor/hasnextimage/
---
## PdfExtractor.HasNextImage-Methode

Überprüft, ob weitere Bilder im PDF-Dokument verfügbar sind. Hinweis: ExtractImage muss vor der Verwendung dieser Methode aufgerufen werden.

```csharp
public bool HasNextImage()
```

### Rückgabewert

Wahr, wenn weitere Bilder verfügbar sind

## Beispiele

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf("sample.pdf");
extractor.ExtractImage();
int i = 1;
while (extractor.HasNextImage())
{
    extractor.GetNextImage("image-" + i +".pdf");
}
```

### Siehe auch

* Klasse [PdfExtractor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)