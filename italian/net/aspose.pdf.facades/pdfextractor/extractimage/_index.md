---
title: "PdfExtractor.ExtractImage"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "PdfExtractor method. Estrae immagini dal file PDF"
type: docs
weight: 120
url: /it/net/aspose.pdf.facades/pdfextractor/extractimage/
---
## PdfExtractor.ExtractImage method

Estrai le immagini dal file PDF.

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

### Vedi anche

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


