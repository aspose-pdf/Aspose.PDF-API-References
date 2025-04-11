---
title: PdfExtractor.ExtractImage
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfExtractor. Estrai immagini da un file PDF
type: docs
weight: 120
url: /it/net/aspose.pdf.facades/pdfextractor/extractimage/
---
## Metodo PdfExtractor.ExtractImage

Estrai immagini da un file PDF.

```csharp
public void ExtractImage()
```

## Esempi

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

### Vedi Anche

* classe [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)