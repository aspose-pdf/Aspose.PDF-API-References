---
title: PdfExtractor.ExtractImage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor metod. Extrahera bilder från PDF-fil
type: docs
weight: 120
url: /sv/net/aspose.pdf.facades/pdfextractor/extractimage/
---
## PdfExtractor.ExtractImage metod

Extrahera bilder från PDF-fil.

```csharp
public void ExtractImage()
```

## Exempel

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

### Se Även

* klass [PdfExtractor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)