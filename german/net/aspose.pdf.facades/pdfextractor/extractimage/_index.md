---
title: PdfExtractor.ExtractImage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor-Methode. Bilder aus PDF-Dateien extrahieren
type: docs
weight: 120
url: /de/net/aspose.pdf.facades/pdfextractor/extractimage/
---
## PdfExtractor.ExtractImage-Methode

Bilder aus PDF-Dateien extrahieren.

```csharp
public void ExtractImage()
```

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